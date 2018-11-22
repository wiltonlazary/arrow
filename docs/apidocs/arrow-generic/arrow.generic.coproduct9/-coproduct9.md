---
title: Coproduct9 - arrow-generic
---

[arrow-generic](../index.html) / [arrow.generic.coproduct9](index.html) / [Coproduct9](./-coproduct9.html)

# Coproduct9

`sealed class Coproduct9<A, B, C, D, E, F, G, H, I>`

### Extension Functions

| [fold](fold.html) | `fun <A, B, C, D, E, F, G, H, I, RESULT> `[`Coproduct9`](./-coproduct9.html)`<`[`A`](fold.html#A)`, `[`B`](fold.html#B)`, `[`C`](fold.html#C)`, `[`D`](fold.html#D)`, `[`E`](fold.html#E)`, `[`F`](fold.html#F)`, `[`G`](fold.html#G)`, `[`H`](fold.html#H)`, `[`I`](fold.html#I)`>.fold(a: (`[`A`](fold.html#A)`) -> `[`RESULT`](fold.html#RESULT)`, b: (`[`B`](fold.html#B)`) -> `[`RESULT`](fold.html#RESULT)`, c: (`[`C`](fold.html#C)`) -> `[`RESULT`](fold.html#RESULT)`, d: (`[`D`](fold.html#D)`) -> `[`RESULT`](fold.html#RESULT)`, e: (`[`E`](fold.html#E)`) -> `[`RESULT`](fold.html#RESULT)`, f: (`[`F`](fold.html#F)`) -> `[`RESULT`](fold.html#RESULT)`, g: (`[`G`](fold.html#G)`) -> `[`RESULT`](fold.html#RESULT)`, h: (`[`H`](fold.html#H)`) -> `[`RESULT`](fold.html#RESULT)`, i: (`[`I`](fold.html#I)`) -> `[`RESULT`](fold.html#RESULT)`): `[`RESULT`](fold.html#RESULT) |
| [select](select.html) | `fun <A> `[`Coproduct9`](./-coproduct9.html)`<`[`A`](select.html#A)`, *, *, *, *, *, *, *, *>.select(): Option<`[`A`](select.html#A)`>`<br>`fun <B> `[`Coproduct9`](./-coproduct9.html)`<*, `[`B`](select.html#B)`, *, *, *, *, *, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`B`](select.html#B)`>`<br>`fun <C> `[`Coproduct9`](./-coproduct9.html)`<*, *, `[`C`](select.html#C)`, *, *, *, *, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`C`](select.html#C)`>`<br>`fun <D> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, `[`D`](select.html#D)`, *, *, *, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`D`](select.html#D)`>`<br>`fun <E> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, *, `[`E`](select.html#E)`, *, *, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`E`](select.html#E)`>`<br>`fun <F> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, *, *, `[`F`](select.html#F)`, *, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`F`](select.html#F)`>`<br>`fun <G> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, *, *, *, `[`G`](select.html#G)`, *, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`G`](select.html#G)`>`<br>`fun <H> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, *, *, *, *, `[`H`](select.html#H)`, *>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy6: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`H`](select.html#H)`>`<br>`fun <I> `[`Coproduct9`](./-coproduct9.html)`<*, *, *, *, *, *, *, *, `[`I`](select.html#I)`>.select(dummy0: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy1: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy6: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummy7: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Option<`[`I`](select.html#I)`>` |
