---
title: arrow.instances.day.applicative.arrow.Kind - arrow-instances-data
---

[arrow-instances-data](../../index.html) / [arrow.instances.day.applicative](../index.html) / [arrow.Kind](./index.html)

### Extensions for arrow.Kind

| [ap](ap.html) | `fun <F, G, A, B> Kind<Kind<Kind<ForDay, `[`F`](ap.html#F)`>, `[`G`](ap.html#G)`>, `[`A`](ap.html#A)`>.ap(arg1: Kind<Kind<Kind<ForDay, `[`F`](ap.html#F)`>, `[`G`](ap.html#G)`>, (`[`A`](ap.html#A)`) -> `[`B`](ap.html#B)`>, AF: Applicative<`[`F`](ap.html#F)`>, AG: Applicative<`[`G`](ap.html#G)`>): Kind<`[`G`](ap.html#G)`, `[`B`](ap.html#B)`>` |
| [map](map.html) | `fun <F, G, A, B> Kind<Kind<Kind<ForDay, `[`F`](map.html#F)`>, `[`G`](map.html#G)`>, `[`A`](map.html#A)`>.map(arg1: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`, AF: Applicative<`[`F`](map.html#F)`>, AG: Applicative<`[`G`](map.html#G)`>): Kind<`[`G`](map.html#G)`, `[`B`](map.html#B)`>` |
| [map2](map2.html) | `fun <F, G, A, B, Z> Kind<Kind<Kind<ForDay, `[`F`](map2.html#F)`>, `[`G`](map2.html#G)`>, `[`A`](map2.html#A)`>.map2(arg1: Kind<Kind<Kind<ForDay, `[`F`](map2.html#F)`>, `[`G`](map2.html#G)`>, `[`B`](map2.html#B)`>, arg2: (Tuple2<`[`A`](map2.html#A)`, `[`B`](map2.html#B)`>) -> `[`Z`](map2.html#Z)`, AF: Applicative<`[`F`](map2.html#F)`>, AG: Applicative<`[`G`](map2.html#G)`>): Kind<`[`G`](map2.html#G)`, `[`Z`](map2.html#Z)`>` |
| [map2Eval](map2-eval.html) | `fun <F, G, A, B, Z> Kind<Kind<Kind<ForDay, `[`F`](map2-eval.html#F)`>, `[`G`](map2-eval.html#G)`>, `[`A`](map2-eval.html#A)`>.map2Eval(arg1: Eval<Kind<Kind<Kind<ForDay, `[`F`](map2-eval.html#F)`>, `[`G`](map2-eval.html#G)`>, `[`B`](map2-eval.html#B)`>>, arg2: (Tuple2<`[`A`](map2-eval.html#A)`, `[`B`](map2-eval.html#B)`>) -> `[`Z`](map2-eval.html#Z)`, AF: Applicative<`[`F`](map2-eval.html#F)`>, AG: Applicative<`[`G`](map2-eval.html#G)`>): Eval<Kind<Kind<Kind<ForDay, `[`F`](map2-eval.html#F)`>, `[`G`](map2-eval.html#G)`>, `[`Z`](map2-eval.html#Z)`>>` |
| [plus](plus.html) | `fun <F, G> Kind<Kind<Kind<ForDay, `[`F`](plus.html#F)`>, `[`G`](plus.html#G)`>, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>.plus(arg1: Kind<Kind<Kind<ForDay, `[`F`](plus.html#F)`>, `[`G`](plus.html#G)`>, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>, AF: Applicative<`[`F`](plus.html#F)`>, AG: Applicative<`[`G`](plus.html#G)`>): Kind<`[`G`](plus.html#G)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [product](product.html) | `fun <F, G, A, B> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`A`](product.html#A)`>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`B`](product.html#B)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>`<br>`fun <F, G, A, B, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, E, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, E, FF, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, E, FF, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, E, FF, H, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`Z`](product.html#Z)`>>`<br>`fun <F, G, A, B, C, D, E, FF, H, I, Z> Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`>>.product(arg1: Kind<Kind<Kind<ForDay, `[`F`](product.html#F)`>, `[`G`](product.html#G)`>, `[`Z`](product.html#Z)`>, AF: Applicative<`[`F`](product.html#F)`>, AG: Applicative<`[`G`](product.html#G)`>): Kind<`[`G`](product.html#G)`, Tuple10<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`, `[`Z`](product.html#Z)`>>` |
