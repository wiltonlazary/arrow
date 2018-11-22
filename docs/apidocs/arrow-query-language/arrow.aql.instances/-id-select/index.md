---
title: IdSelect - arrow-query-language
---

[arrow-query-language](../../index.html) / [arrow.aql.instances](../index.html) / [IdSelect](./index.html)

# IdSelect

`@extension interface IdSelect : `[`Select`](../../arrow.aql/-select/index.html)`<ForId>`

### Functions

| [functor](functor.html) | `open fun functor(): Functor<ForId>` |

### Inherited Functions

| [query](../../arrow.aql/-select/query.html) | `open infix fun <A, Z> `[`Source`](../../arrow.aql/-source.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/query.html#A)`>.query(f: `[`Source`](../../arrow.aql/-source.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/query.html#A)`>.() -> `[`Z`](../../arrow.aql/-select/query.html#Z)`): `[`Z`](../../arrow.aql/-select/query.html#Z) |
| [select](../../arrow.aql/-select/select.html) | `open infix fun <A, Z> `[`Source`](../../arrow.aql/-source.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/select.html#A)`>.select(f: `[`Selection`](../../arrow.aql/-selection.html)`<`[`A`](../../arrow.aql/-select/select.html#A)`, `[`Z`](../../arrow.aql/-select/select.html#Z)`>): `[`Query`](../../arrow.aql/-query/index.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/select.html#A)`, `[`Z`](../../arrow.aql/-select/select.html#Z)`>`<br>Commented method or class |
| [selectAll](../../arrow.aql/-select/select-all.html) | `open fun <A> `[`Source`](../../arrow.aql/-source.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/select-all.html#A)`>.selectAll(): `[`Query`](../../arrow.aql/-query/index.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/select-all.html#A)`, `[`A`](../../arrow.aql/-select/select-all.html#A)`>` |
| [value](../../arrow.aql/-select/value.html) | `open fun <A, Z> `[`Query`](../../arrow.aql/-query/index.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`A`](../../arrow.aql/-select/value.html#A)`, `[`Z`](../../arrow.aql/-select/value.html#Z)`>.value(): `[`Source`](../../arrow.aql/-source.html)`<`[`F`](../../arrow.aql/-select/index.html#F)`, `[`Z`](../../arrow.aql/-select/value.html#Z)`>` |
