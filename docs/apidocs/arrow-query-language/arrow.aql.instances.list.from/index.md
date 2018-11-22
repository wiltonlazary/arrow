---
title: arrow.aql.instances.list.from - arrow-query-language
---

[arrow-query-language](../index.html) / [arrow.aql.instances.list.from](./index.html)

## Package arrow.aql.instances.list.from

### Types

| [List](-list/index.html) | `object List` |

### Extensions for External Classes

| [kotlin.collections.List](kotlin.collections.-list/index.html) |  |

### Functions

| [applicative](applicative.html) | `fun applicative(): Applicative<ForListK>` |
| [join](join.html) | `infix fun <A, B, Z, X> `[`Query`](../arrow.aql/-query/index.html)`<ForListK, `[`A`](join.html#A)`, `[`Z`](join.html#Z)`>.join(query: `[`Query`](../arrow.aql/-query/index.html)`<ForListK, `[`B`](join.html#B)`, `[`X`](join.html#X)`>): `[`Query`](../arrow.aql/-query/index.html)`<ForListK, Tuple2<`[`A`](join.html#A)`, `[`B`](join.html#B)`>, Tuple2<`[`Z`](join.html#Z)`, `[`X`](join.html#X)`>>` |
