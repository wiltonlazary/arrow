---
layout: docs
title: MonadFilter
permalink: /docs/typeclasses/monadfilter/
---

## MonadFilter

{:.advanced}
advanced

`MonadFilter` is a type class that abstracts away the option of interrupting computation if a given predicate is not satisfied.

All instances of `MonadFilter` provide syntax over their respective data types to comprehend monadically over their computation:

## continueWith

Binding over `MonadFilter` instances with `bindingFilter` brings into scope the `continueIf` guard that requires a `Boolean` predicate as value. If the predicate is `true` the computation will continue and if the predicate returns `false` the computation is short-circuited returning monad filter instance `empty()` value.

In the example below we demonstrate monadic comprehension over the `MonadFilter` instances for both `Option` and `ListK` since both data types can provide a safe `empty` value.

When `continueIf` is satisfied the computation continues

```kotlin
import arrow.*
import arrow.core.*
import arrow.mtl.typeclasses.*
import arrow.mtl.instances.*
import arrow.mtl.instances.option.monadFilter.*

ForOption extensions { 
  bindingFilter {
     val a = Option(1).bind()
     val b = Option(1).bind()
     val c = a + b
     continueIf(c > 0)
     c
  }
}
// Some(2)
```

```kotlin
import arrow.data.*
import arrow.mtl.instances.listk.monadFilter.*

ForListK extensions { 
 bindingFilter {
     val a = listOf(1).k().bind()
     val b = listOf(1).k().bind()
     val c = a + b
     continueIf(c > 0)
     c
 }
}
// ListK(list=[2])
```

When `continueIf` returns `false` the computation is interrupted and the `empty()` value is returned

```kotlin
ForOption extensions {
  bindingFilter {
     val a = Option(1).bind()
     val b = Option(1).bind()
     val c = a + b
     continueIf(c < 0)
     c
  }
}
// None
```

```kotlin
ForListK extensions {
 bindingFilter {
     val a = listOf(1).k().bind()
     val b = listOf(1).k().bind()
     val c = a + b
     continueIf(c < 0)
     c
 }
}
// ListK(list=[])
```

##bindWithFilter

Binding over `MonadFilter` instances with `bindingFilter` brings into scope the `bindWithFilter` guard that requires a `Boolean` predicate as value getting matched on the monad capturing inner value. If the predicate is `true` the computation will continue and if the predicate returns `false` the computation is short-circuited returning the monad filter instance `empty()` value.

When `bindWithFilter` is satisfied the computation continues

```kotlin
ForOption extensions { 
 bindingFilter {
     val a = Option(1).bind()
     val b = Option(1).bindWithFilter { it == a } //continues
     a + b
 }
}
// Some(2)
```

```kotlin
bindingFilter {
 val a = listOf(1).k().bind()
 val b = listOf(1).k().bindWithFilter { it == a } //continues
 a + b
}
// ListK(list=[2])
```

When `bindWithFilter` returns `false` the computation short circuits yielding the monad's empty value

```kotlin
import arrow.mtl.instances.option.monadFilter.*

bindingFilter {
 val a = Option(0).bind()
 val b = Option(1).bindWithFilter { it == a } //short circuits because a is 0
 a + b
}
// None
```

```kotlin
import arrow.mtl.instances.listk.monadFilter.*

bindingFilter {
 val a = listOf(0).k().bind()
 val b = listOf(1).k().bindWithFilter { it == a } //short circuits because a is 0
 a + b
}
// ListK(list=[])
```

### Data types

| Module | Data types |
|__arrow.core__|[Option]({{ '/docs/arrow/core/option' | relative_url }})|
|__arrow.data__|[ListK]({{ '/docs/arrow/data/listk' | relative_url }}), [SequenceK]({{ '/docs/arrow/data/sequencek' | relative_url }}), [WriterT]({{ '/docs/arrow/data/writert' | relative_url }})|




## Type Class Hierarchy

<canvas id="arrow.mtl.typeclasses-hierarchy-diagram"></canvas>
<script>
  drawNomNomlDiagram('arrow.mtl.typeclasses-hierarchy-diagram', 'arrow.mtl.typeclasses-diagram.nomnol')
</script>
