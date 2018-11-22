---
title: Applicative.tupled - arrow-typeclasses
---

[arrow-typeclasses](../../index.html) / [arrow.typeclasses](../index.html) / [Applicative](index.html) / [tupled](./tupled.html)

# tupled

`open fun <A, B> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>): Kind<`[`F`](index.html#F)`, Tuple2<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`>>`
`open fun <A, B, C> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>): Kind<`[`F`](index.html#F)`, Tuple3<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`>>`
`open fun <A, B, C, D> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>): Kind<`[`F`](index.html#F)`, Tuple4<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`>>`
`open fun <A, B, C, D, E> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>): Kind<`[`F`](index.html#F)`, Tuple5<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`>>`
`open fun <A, B, C, D, E, FF> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>, f: Kind<`[`F`](index.html#F)`, `[`FF`](tupled.html#FF)`>): Kind<`[`F`](index.html#F)`, Tuple6<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`>>`
`open fun <A, B, C, D, E, FF, G> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>, f: Kind<`[`F`](index.html#F)`, `[`FF`](tupled.html#FF)`>, g: Kind<`[`F`](index.html#F)`, `[`G`](tupled.html#G)`>): Kind<`[`F`](index.html#F)`, Tuple7<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`>>`
`open fun <A, B, C, D, E, FF, G, H> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>, f: Kind<`[`F`](index.html#F)`, `[`FF`](tupled.html#FF)`>, g: Kind<`[`F`](index.html#F)`, `[`G`](tupled.html#G)`>, h: Kind<`[`F`](index.html#F)`, `[`H`](tupled.html#H)`>): Kind<`[`F`](index.html#F)`, Tuple8<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`>>`
`open fun <A, B, C, D, E, FF, G, H, I> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>, f: Kind<`[`F`](index.html#F)`, `[`FF`](tupled.html#FF)`>, g: Kind<`[`F`](index.html#F)`, `[`G`](tupled.html#G)`>, h: Kind<`[`F`](index.html#F)`, `[`H`](tupled.html#H)`>, i: Kind<`[`F`](index.html#F)`, `[`I`](tupled.html#I)`>): Kind<`[`F`](index.html#F)`, Tuple9<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`, `[`I`](tupled.html#I)`>>`
`open fun <A, B, C, D, E, FF, G, H, I, J> tupled(a: Kind<`[`F`](index.html#F)`, `[`A`](tupled.html#A)`>, b: Kind<`[`F`](index.html#F)`, `[`B`](tupled.html#B)`>, c: Kind<`[`F`](index.html#F)`, `[`C`](tupled.html#C)`>, d: Kind<`[`F`](index.html#F)`, `[`D`](tupled.html#D)`>, e: Kind<`[`F`](index.html#F)`, `[`E`](tupled.html#E)`>, f: Kind<`[`F`](index.html#F)`, `[`FF`](tupled.html#FF)`>, g: Kind<`[`F`](index.html#F)`, `[`G`](tupled.html#G)`>, h: Kind<`[`F`](index.html#F)`, `[`H`](tupled.html#H)`>, i: Kind<`[`F`](index.html#F)`, `[`I`](tupled.html#I)`>, j: Kind<`[`F`](index.html#F)`, `[`J`](tupled.html#J)`>): Kind<`[`F`](index.html#F)`, Tuple10<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`, `[`I`](tupled.html#I)`, `[`J`](tupled.html#J)`>>`