---
title: arrow.instances.try.applicative.arrow.Kind - arrow-instances-core
---

[arrow-instances-core](../../index.html) / [arrow.instances.try.applicative](../index.html) / [arrow.Kind](./index.html)

### Extensions for arrow.Kind

| [ap](ap.html) | `fun <A, B> Kind<ForTry, `[`A`](ap.html#A)`>.ap(arg1: Kind<ForTry, (`[`A`](ap.html#A)`) -> `[`B`](ap.html#B)`>): Try<`[`B`](ap.html#B)`>` |
| [map](map.html) | `fun <A, B> Kind<ForTry, `[`A`](map.html#A)`>.map(arg1: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`): Try<`[`B`](map.html#B)`>` |
| [map2](map2.html) | `fun <A, B, Z> Kind<ForTry, `[`A`](map2.html#A)`>.map2(arg1: Kind<ForTry, `[`B`](map2.html#B)`>, arg2: (Tuple2<`[`A`](map2.html#A)`, `[`B`](map2.html#B)`>) -> `[`Z`](map2.html#Z)`): Try<`[`Z`](map2.html#Z)`>` |
| [map2Eval](map2-eval.html) | `fun <A, B, Z> Kind<ForTry, `[`A`](map2-eval.html#A)`>.map2Eval(arg1: Eval<Kind<ForTry, `[`B`](map2-eval.html#B)`>>, arg2: (Tuple2<`[`A`](map2-eval.html#A)`, `[`B`](map2-eval.html#B)`>) -> `[`Z`](map2-eval.html#Z)`): Eval<Kind<ForTry, `[`Z`](map2-eval.html#Z)`>>` |
| [plus](plus.html) | `operator fun Kind<ForTry, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>.plus(arg1: Kind<ForTry, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>): Try<`[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [product](product.html) | `fun <A, B> Kind<ForTry, `[`A`](product.html#A)`>.product(arg1: Kind<ForTry, `[`B`](product.html#B)`>): Try<Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>`<br>`fun <A, B, Z> Kind<ForTry, Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, Z> Kind<ForTry, Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, Z> Kind<ForTry, Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, Z> Kind<ForTry, Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, Z> Kind<ForTry, Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, Z> Kind<ForTry, Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, H, Z> Kind<ForTry, Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, H, I, Z> Kind<ForTry, Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`>>.product(arg1: Kind<ForTry, `[`Z`](product.html#Z)`>): Try<Tuple10<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`, `[`Z`](product.html#Z)`>>` |
