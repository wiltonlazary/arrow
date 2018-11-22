---
title: ObservableK - arrow-effects-rx2
---

[arrow-effects-rx2](../../index.html) / [arrow.effects](../index.html) / [ObservableK](./index.html)

# ObservableK

`@higherkind data class ObservableK<A> : `[`ObservableKOf`](../-observable-k-of.html)`<`[`A`](index.html#A)`>, `[`ObservableKKindedJ`](../-observable-k-kinded-j.html)`<`[`A`](index.html#A)`>`

### Constructors

| [&lt;init&gt;](-init-.html) | `ObservableK(observable: Observable<`[`A`](index.html#A)`>)` |

### Properties

| [observable](observable.html) | `val observable: Observable<`[`A`](index.html#A)`>` |

### Functions

| [ap](ap.html) | `fun <B> ap(fa: `[`ObservableKOf`](../-observable-k-of.html)`<(`[`A`](index.html#A)`) -> `[`B`](ap.html#B)`>): `[`ObservableK`](./index.html)`<`[`B`](ap.html#B)`>` |
| [bracketCase](bracket-case.html) | `fun <B> bracketCase(use: (`[`A`](index.html#A)`) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`B`](bracket-case.html#B)`>, release: (`[`A`](index.html#A)`, ExitCase<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`>) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>): `[`ObservableK`](./index.html)`<`[`B`](bracket-case.html#B)`>` |
| [concatMap](concat-map.html) | `fun <B> concatMap(f: (`[`A`](index.html#A)`) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`B`](concat-map.html#B)`>): `[`ObservableK`](./index.html)`<`[`B`](concat-map.html#B)`>` |
| [continueOn](continue-on.html) | `fun continueOn(ctx: `[`CoroutineContext`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html)`): `[`ObservableK`](./index.html)`<`[`A`](index.html#A)`>` |
| [equals](equals.html) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [flatMap](flat-map.html) | `fun <B> flatMap(f: (`[`A`](index.html#A)`) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`B`](flat-map.html#B)`>): `[`ObservableK`](./index.html)`<`[`B`](flat-map.html#B)`>` |
| [foldLeft](fold-left.html) | `fun <B> foldLeft(b: `[`B`](fold-left.html#B)`, f: (`[`B`](fold-left.html#B)`, `[`A`](index.html#A)`) -> `[`B`](fold-left.html#B)`): `[`B`](fold-left.html#B) |
| [foldRight](fold-right.html) | `fun <B> foldRight(lb: Eval<`[`B`](fold-right.html#B)`>, f: (`[`A`](index.html#A)`, Eval<`[`B`](fold-right.html#B)`>) -> Eval<`[`B`](fold-right.html#B)`>): Eval<`[`B`](fold-right.html#B)`>` |
| [handleErrorWith](handle-error-with.html) | `fun handleErrorWith(function: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`ObservableK`](./index.html)`<`[`A`](index.html#A)`>): `[`ObservableK`](./index.html)`<`[`A`](index.html#A)`>` |
| [hashCode](hash-code.html) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [map](map.html) | `fun <B> map(f: (`[`A`](index.html#A)`) -> `[`B`](map.html#B)`): `[`ObservableK`](./index.html)`<`[`B`](map.html#B)`>` |
| [runAsync](run-async.html) | `fun runAsync(cb: (Either<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`, `[`A`](index.html#A)`>) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>): `[`ObservableK`](./index.html)`<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [runAsyncCancellable](run-async-cancellable.html) | `fun runAsyncCancellable(cb: (Either<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`, `[`A`](index.html#A)`>) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>): `[`ObservableK`](./index.html)`<Disposable>` |
| [switchMap](switch-map.html) | `fun <B> switchMap(f: (`[`A`](index.html#A)`) -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`B`](switch-map.html#B)`>): `[`ObservableK`](./index.html)`<`[`B`](switch-map.html#B)`>` |
| [traverse](traverse.html) | `fun <G, B> traverse(GA: Applicative<`[`G`](traverse.html#G)`>, f: (`[`A`](index.html#A)`) -> Kind<`[`G`](traverse.html#G)`, `[`B`](traverse.html#B)`>): Kind<`[`G`](traverse.html#G)`, `[`ObservableK`](./index.html)`<`[`B`](traverse.html#B)`>>` |

### Companion Object Functions

| [defer](defer.html) | `fun <A> defer(fa: () -> `[`ObservableKOf`](../-observable-k-of.html)`<`[`A`](defer.html#A)`>): `[`ObservableK`](./index.html)`<`[`A`](defer.html#A)`>` |
| [invoke](invoke.html) | `operator fun <A> invoke(fa: () -> `[`A`](invoke.html#A)`): `[`ObservableK`](./index.html)`<`[`A`](invoke.html#A)`>` |
| [just](just.html) | `fun <A> just(a: `[`A`](just.html#A)`): `[`ObservableK`](./index.html)`<`[`A`](just.html#A)`>` |
| [raiseError](raise-error.html) | `fun <A> raiseError(t: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`ObservableK`](./index.html)`<`[`A`](raise-error.html#A)`>` |
| [runAsync](run-async.html) | `fun <A> runAsync(fa: Proc<`[`A`](run-async.html#A)`>): `[`ObservableK`](./index.html)`<`[`A`](run-async.html#A)`>` |
| [tailRecM](tail-rec-m.html) | `tailrec fun <A, B> tailRecM(a: `[`A`](tail-rec-m.html#A)`, f: (`[`A`](tail-rec-m.html#A)`) -> `[`ObservableKOf`](../-observable-k-of.html)`<Either<`[`A`](tail-rec-m.html#A)`, `[`B`](tail-rec-m.html#B)`>>): `[`ObservableK`](./index.html)`<`[`B`](tail-rec-m.html#B)`>` |
