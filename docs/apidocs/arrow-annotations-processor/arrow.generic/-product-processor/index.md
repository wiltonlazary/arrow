---
title: ProductProcessor - arrow-annotations-processor
---

[arrow-annotations-processor](../../index.html) / [arrow.generic](../index.html) / [ProductProcessor](./index.html)

# ProductProcessor

`@AutoService([Processor]) class ProductProcessor : `[`AbstractProcessor`](../../arrow.common.utils/-abstract-processor/index.html)

### Constructors

| [&lt;init&gt;](-init-.html) | `ProductProcessor()` |

### Functions

| [getSupportedAnnotationTypes](get-supported-annotation-types.html) | `fun getSupportedAnnotationTypes(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [getSupportedSourceVersion](get-supported-source-version.html) | `fun getSupportedSourceVersion(): `[`SourceVersion`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/SourceVersion.html) |
| [onProcess](on-process.html) | `fun onProcess(annotations: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`TypeElement`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/TypeElement.html)`>, roundEnv: `[`RoundEnvironment`](http://docs.oracle.com/javase/6/docs/api/javax/annotation/processing/RoundEnvironment.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| [process](../../arrow.common.utils/-abstract-processor/process.html) | `fun process(annotations: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`TypeElement`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/TypeElement.html)`>, roundEnv: `[`RoundEnvironment`](http://docs.oracle.com/javase/6/docs/api/javax/annotation/processing/RoundEnvironment.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| [log](../../arrow.common.messager/me.eugeniomarletti.kotlin.processing.-kotlin-processing-environment/log.html) | `fun KotlinProcessingEnvironment.log(message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, element: `[`Element`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/Element.html)`? = null, annotationMirror: `[`AnnotationMirror`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationMirror.html)`? = null, annotationValue: `[`AnnotationValue`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationValue.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [logE](../../arrow.common.messager/me.eugeniomarletti.kotlin.processing.-kotlin-processing-environment/log-e.html) | `fun KotlinProcessingEnvironment.logE(message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, element: `[`Element`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/Element.html)`? = null, annotationMirror: `[`AnnotationMirror`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationMirror.html)`? = null, annotationValue: `[`AnnotationValue`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationValue.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [logMW](../../arrow.common.messager/me.eugeniomarletti.kotlin.processing.-kotlin-processing-environment/log-m-w.html) | `fun KotlinProcessingEnvironment.logMW(message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, element: `[`Element`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/Element.html)`? = null, annotationMirror: `[`AnnotationMirror`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationMirror.html)`? = null, annotationValue: `[`AnnotationValue`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationValue.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [logW](../../arrow.common.messager/me.eugeniomarletti.kotlin.processing.-kotlin-processing-environment/log-w.html) | `fun KotlinProcessingEnvironment.logW(message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, element: `[`Element`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/Element.html)`? = null, annotationMirror: `[`AnnotationMirror`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationMirror.html)`? = null, annotationValue: `[`AnnotationValue`](http://docs.oracle.com/javase/6/docs/api/javax/lang/model/element/AnnotationValue.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
