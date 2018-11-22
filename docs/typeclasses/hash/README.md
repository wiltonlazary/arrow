---
layout: docs
title: Hash
permalink: /docs/typeclasses/hash/
---

## Hash

{:.beginner}
beginner

The `Hash` typeclass abstracts the ability to compute the hash of any object.  
It can be considered the typeclass equivalent of Java's `Object#hashcode` and Kotlin's `Any#hashCode`.  

A hash function is a mapping of arbitrary data (`F`) to an output set of fixed size (`Int`). The result, a hash value, is most commonly used in collections like HashTable as a lookup value.

{: data-executable='true'}
```kotlin
import arrow.instances.*

fun main(args: Array<String>) {
  //sampleStart
  // Enable the extension functions inside Hash using run
  val result = String.hash().run { "1".hash() }
  //sampleEnd
  println(result)
}
```

### Main Combinators

#### F.hash

Computes a hash of an instance of `F`.

`fun F.hash(): Int`

{: data-executable='true'}
```kotlin
import arrow.instances.*

fun main(args: Array<String>) {
  //sampleStart
  // Enable the extension functions inside Hash using run
  val result = String.hash().run { "MyString".hash() }
  //sampleEnd
  println(result)
}
```

### Laws

Arrow provides [`HashLaws`][hash_laws_source]{:target="_blank"} in the form of test cases for internal verification of lawful instances and third party apps creating their own `Hash` instances.

#### Creating your own `Hash` instances

Hash contains a special instance that delegates to Kotlin's `Any?.hashCode()` function in all cases. This may be sufficient for most use cases, but will fail for data types that contain functions, typeclasses or non-data classes.
It also might make more sense to provide your own instance in for some cases, for example when there is already a unique property on an object.
Hash has a constructor to create a `Hash` instance from any function `(F) -> Int`.

{: data-executable='true'}
```kotlin
import arrow.typeclasses.Hash

data class User(val id: String, val name: String)
val user = User("MyId", "MyName")

fun main(args: Array<String>) {
  //sampleStart
  // This is fine
  val result = Hash.any().run { user.hash() }
  //sampleEnd
  println(result)
}
```

{: data-executable='true'}
```kotlin
import arrow.typeclasses.Hash

data class User(val id: String, val name: String)
val user = User("MyId", "MyName")

fun main(args: Array<String>) {
  //sampleStart  
  // This might be better because id usually is a unique value in itself
  val userHash = Hash<User> { u -> u.id.hashCode() }
  val result = userHash.run { user.hash() }
  //sampleEnd
  println(result)
}
```

{: data-executable='true'}
```kotlin
import arrow.core.*
import arrow.typeclasses.Hash

fun main(args: Array<String>) {
  //sampleStart
  // This will return false because it's not evaluated for hashing
  val result = Hash.any().run { Eval.later { 1 }.hash() == Eval.later { 1 }.hash() }
  //sampleEnd
  println(result)
}
```

{: data-executable='true'}
```kotlin
import arrow.typeclasses.Hash

fun main(args: Array<String>) {
  //sampleStart
  // using invoke constructor
  val stringHash = Hash<String> { a -> a.hashCode() }
  val result = stringHash.run { "MyString".hash() }
  //sampleEnd
  println(result)
}
```

See [Deriving and creating custom typeclass]({{ '/docs/patterns/glossary' | relative_url }}) to provide your own `Hash` instances for custom datatypes.

### Data types

| Module | Data types |
|__arrow.core__|[Either]({{ '/docs/arrow/core/either' | relative_url }}), [Id]({{ '/docs/arrow/core/id' | relative_url }}), [Option]({{ '/docs/arrow/core/option' | relative_url }}), [Try]({{ '/docs/arrow/core/try' | relative_url }}), [Tuple10]({{ '/docs/arrow/core/tuple10' | relative_url }}), [Tuple2]({{ '/docs/arrow/core/tuple2' | relative_url }}), [Tuple3]({{ '/docs/arrow/core/tuple3' | relative_url }}), [Tuple4]({{ '/docs/arrow/core/tuple4' | relative_url }}), [Tuple5]({{ '/docs/arrow/core/tuple5' | relative_url }}), [Tuple6]({{ '/docs/arrow/core/tuple6' | relative_url }}), [Tuple7]({{ '/docs/arrow/core/tuple7' | relative_url }}), [Tuple8]({{ '/docs/arrow/core/tuple8' | relative_url }}), [Tuple9]({{ '/docs/arrow/core/tuple9' | relative_url }})|
|__arrow.data__|[Coproduct]({{ '/docs/arrow/data/coproduct' | relative_url }}), [Sum]({{ '/docs/arrow/data/sum' | relative_url }}), [Ior]({{ '/docs/arrow/data/ior' | relative_url }}), [ListK]({{ '/docs/arrow/data/listk' | relative_url }}), [MapK]({{ '/docs/arrow/data/mapk' | relative_url }}), [NonEmptyList]({{ '/docs/arrow/data/nonemptylist' | relative_url }}), [SequenceK]({{ '/docs/arrow/data/sequencek' | relative_url }}), [SetK]({{ '/docs/arrow/data/setk' | relative_url }}), [Validated]({{ '/docs/arrow/data/validated' | relative_url }})|
|__arrow.typeclasses__|[Const]({{ '/docs/arrow/typeclasses/const' | relative_url }})|

### Hierarchy

<canvas id="hierarchy-diagram"></canvas>
<script>
  drawNomNomlDiagram('hierarchy-diagram', 'diagram.nomnol')
</script>



[hash_laws_source]: https://github.com/arrow-kt/arrow/blob/master/modules/core/arrow-test/src/main/kotlin/arrow/test/laws/HashLaws.kt