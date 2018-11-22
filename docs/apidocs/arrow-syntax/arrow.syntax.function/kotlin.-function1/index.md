---
title: arrow.syntax.function.kotlin.Function1 - arrow-syntax
---

[arrow-syntax](../../index.html) / [arrow.syntax.function](../index.html) / [kotlin.Function1](./index.html)

### Extensions for kotlin.Function1

| [andThen](and-then.html) | `infix fun <P1, IP, R> ((`[`P1`](and-then.html#P1)`) -> `[`IP`](and-then.html#IP)`).andThen(f: (`[`IP`](and-then.html#IP)`) -> `[`R`](and-then.html#R)`): (`[`P1`](and-then.html#P1)`) -> `[`R`](and-then.html#R) |
| [bind](bind.html) | `fun <P1, R> ((`[`P1`](bind.html#P1)`) -> `[`R`](bind.html#R)`).bind(p1: `[`P1`](bind.html#P1)`): () -> `[`R`](bind.html#R) |
| [complement](complement.html) | `fun <P1> ((`[`P1`](complement.html#P1)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`).complement(): (`[`P1`](complement.html#P1)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [compose](compose.html) | `infix fun <IP, R, P1> ((`[`IP`](compose.html#IP)`) -> `[`R`](compose.html#R)`).compose(f: (`[`P1`](compose.html#P1)`) -> `[`IP`](compose.html#IP)`): (`[`P1`](compose.html#P1)`) -> `[`R`](compose.html#R) |
| [forwardCompose](forward-compose.html) | `infix fun <P1, IP, R> ((`[`P1`](forward-compose.html#P1)`) -> `[`IP`](forward-compose.html#IP)`).forwardCompose(f: (`[`IP`](forward-compose.html#IP)`) -> `[`R`](forward-compose.html#R)`): (`[`P1`](forward-compose.html#P1)`) -> `[`R`](forward-compose.html#R) |
| [memoize](memoize.html) | `fun <P1, R> ((`[`P1`](memoize.html#P1)`) -> `[`R`](memoize.html#R)`).memoize(): (`[`P1`](memoize.html#P1)`) -> `[`R`](memoize.html#R) |
| [optionLift](option-lift.html) | `fun <P1, R> ((`[`P1`](option-lift.html#P1)`) -> `[`R`](option-lift.html#R)`).optionLift(): (Option<`[`P1`](option-lift.html#P1)`>) -> Option<`[`R`](option-lift.html#R)`>` |
| [partially1](partially1.html) | `fun <P1, R> ((`[`P1`](partially1.html#P1)`) -> `[`R`](partially1.html#R)`).partially1(p1: `[`P1`](partially1.html#P1)`): () -> `[`R`](partially1.html#R) |
| [uncurried](uncurried.html) | `fun <P1, P2, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> (`[`P18`](uncurried.html#P18)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`, `[`P18`](uncurried.html#P18)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> (`[`P18`](uncurried.html#P18)`) -> (`[`P19`](uncurried.html#P19)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`, `[`P18`](uncurried.html#P18)`, `[`P19`](uncurried.html#P19)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19, P20, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> (`[`P18`](uncurried.html#P18)`) -> (`[`P19`](uncurried.html#P19)`) -> (`[`P20`](uncurried.html#P20)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`, `[`P18`](uncurried.html#P18)`, `[`P19`](uncurried.html#P19)`, `[`P20`](uncurried.html#P20)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19, P20, P21, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> (`[`P18`](uncurried.html#P18)`) -> (`[`P19`](uncurried.html#P19)`) -> (`[`P20`](uncurried.html#P20)`) -> (`[`P21`](uncurried.html#P21)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`, `[`P18`](uncurried.html#P18)`, `[`P19`](uncurried.html#P19)`, `[`P20`](uncurried.html#P20)`, `[`P21`](uncurried.html#P21)`) -> `[`R`](uncurried.html#R)<br>`fun <P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19, P20, P21, P22, R> ((`[`P1`](uncurried.html#P1)`) -> (`[`P2`](uncurried.html#P2)`) -> (`[`P3`](uncurried.html#P3)`) -> (`[`P4`](uncurried.html#P4)`) -> (`[`P5`](uncurried.html#P5)`) -> (`[`P6`](uncurried.html#P6)`) -> (`[`P7`](uncurried.html#P7)`) -> (`[`P8`](uncurried.html#P8)`) -> (`[`P9`](uncurried.html#P9)`) -> (`[`P10`](uncurried.html#P10)`) -> (`[`P11`](uncurried.html#P11)`) -> (`[`P12`](uncurried.html#P12)`) -> (`[`P13`](uncurried.html#P13)`) -> (`[`P14`](uncurried.html#P14)`) -> (`[`P15`](uncurried.html#P15)`) -> (`[`P16`](uncurried.html#P16)`) -> (`[`P17`](uncurried.html#P17)`) -> (`[`P18`](uncurried.html#P18)`) -> (`[`P19`](uncurried.html#P19)`) -> (`[`P20`](uncurried.html#P20)`) -> (`[`P21`](uncurried.html#P21)`) -> (`[`P22`](uncurried.html#P22)`) -> `[`R`](uncurried.html#R)`).uncurried(): (`[`P1`](uncurried.html#P1)`, `[`P2`](uncurried.html#P2)`, `[`P3`](uncurried.html#P3)`, `[`P4`](uncurried.html#P4)`, `[`P5`](uncurried.html#P5)`, `[`P6`](uncurried.html#P6)`, `[`P7`](uncurried.html#P7)`, `[`P8`](uncurried.html#P8)`, `[`P9`](uncurried.html#P9)`, `[`P10`](uncurried.html#P10)`, `[`P11`](uncurried.html#P11)`, `[`P12`](uncurried.html#P12)`, `[`P13`](uncurried.html#P13)`, `[`P14`](uncurried.html#P14)`, `[`P15`](uncurried.html#P15)`, `[`P16`](uncurried.html#P16)`, `[`P17`](uncurried.html#P17)`, `[`P18`](uncurried.html#P18)`, `[`P19`](uncurried.html#P19)`, `[`P20`](uncurried.html#P20)`, `[`P21`](uncurried.html#P21)`, `[`P22`](uncurried.html#P22)`) -> `[`R`](uncurried.html#R) |
| [unpaired](unpaired.html) | `fun <P1, P2, R> ((`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`P1`](unpaired.html#P1)`, `[`P2`](unpaired.html#P2)`>) -> `[`R`](unpaired.html#R)`).unpaired(): (`[`P1`](unpaired.html#P1)`, `[`P2`](unpaired.html#P2)`) -> `[`R`](unpaired.html#R) |
| [untripled](untripled.html) | `fun <P1, P2, P3, R> ((`[`Triple`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-triple/index.html)`<`[`P1`](untripled.html#P1)`, `[`P2`](untripled.html#P2)`, `[`P3`](untripled.html#P3)`>) -> `[`R`](untripled.html#R)`).untripled(): (`[`P1`](untripled.html#P1)`, `[`P2`](untripled.html#P2)`, `[`P3`](untripled.html#P3)`) -> `[`R`](untripled.html#R) |
