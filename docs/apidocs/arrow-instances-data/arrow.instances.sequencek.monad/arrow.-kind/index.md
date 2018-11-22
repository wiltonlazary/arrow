---
title: arrow.instances.sequencek.monad.arrow.Kind - arrow-instances-data
---

[arrow-instances-data](../../index.html) / [arrow.instances.sequencek.monad](../index.html) / [arrow.Kind](./index.html)

### Extensions for arrow.Kind

| [ap](ap.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](ap.html#A)`>.ap(arg1: Kind<ForSequenceK, (`[`A`](ap.html#A)`) -> `[`B`](ap.html#B)`>): SequenceK<`[`B`](ap.html#B)`>` |
| [effectM](effect-m.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](effect-m.html#A)`>.effectM(arg1: (`[`A`](effect-m.html#A)`) -> Kind<ForSequenceK, `[`B`](effect-m.html#B)`>): SequenceK<`[`A`](effect-m.html#A)`>` |
| [flatMap](flat-map.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](flat-map.html#A)`>.flatMap(arg1: (`[`A`](flat-map.html#A)`) -> Kind<ForSequenceK, `[`B`](flat-map.html#B)`>): SequenceK<`[`B`](flat-map.html#B)`>` |
| [flatten](flatten.html) | `fun <A> Kind<ForSequenceK, Kind<ForSequenceK, `[`A`](flatten.html#A)`>>.flatten(): SequenceK<`[`A`](flatten.html#A)`>` |
| [followedBy](followed-by.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](followed-by.html#A)`>.followedBy(arg1: Kind<ForSequenceK, `[`B`](followed-by.html#B)`>): SequenceK<`[`B`](followed-by.html#B)`>` |
| [followedByEval](followed-by-eval.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](followed-by-eval.html#A)`>.followedByEval(arg1: Eval<Kind<ForSequenceK, `[`B`](followed-by-eval.html#B)`>>): SequenceK<`[`B`](followed-by-eval.html#B)`>` |
| [forEffect](for-effect.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](for-effect.html#A)`>.forEffect(arg1: Kind<ForSequenceK, `[`B`](for-effect.html#B)`>): SequenceK<`[`A`](for-effect.html#A)`>` |
| [forEffectEval](for-effect-eval.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](for-effect-eval.html#A)`>.forEffectEval(arg1: Eval<Kind<ForSequenceK, `[`B`](for-effect-eval.html#B)`>>): SequenceK<`[`A`](for-effect-eval.html#A)`>` |
| [ifM](if-m.html) | `fun <B> Kind<ForSequenceK, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>.ifM(arg1: () -> Kind<ForSequenceK, `[`B`](if-m.html#B)`>, arg2: () -> Kind<ForSequenceK, `[`B`](if-m.html#B)`>): SequenceK<`[`B`](if-m.html#B)`>` |
| [map](map.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](map.html#A)`>.map(arg1: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`): SequenceK<`[`B`](map.html#B)`>` |
| [mproduct](mproduct.html) | `fun <A, B> Kind<ForSequenceK, `[`A`](mproduct.html#A)`>.mproduct(arg1: (`[`A`](mproduct.html#A)`) -> Kind<ForSequenceK, `[`B`](mproduct.html#B)`>): SequenceK<Tuple2<`[`A`](mproduct.html#A)`, `[`B`](mproduct.html#B)`>>` |
