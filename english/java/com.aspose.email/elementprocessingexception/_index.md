---
title: ElementProcessingException
second_title: Aspose.Email for Java API Reference
description:  The exception that is thrown when one of many elements failed with exception.
type: docs
weight: 164
url: /java/com.aspose.email/elementprocessingexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class ElementProcessingException extends AsposeException
```

The exception that is thrown when one of many elements failed with exception.
## Constructors

| Constructor | Description |
| --- | --- |
| [ElementProcessingException(int elementIndex, Throwable innerException)](#ElementProcessingException-int-java.lang.Throwable-) | Initializes a new instance of the [ElementProcessingException](../../com.aspose.email/elementprocessingexception) class with a specified element index. |
## Methods

| Method | Description |
| --- | --- |
| [getElementIndex()](#getElementIndex--) | The index of the processed element. |
### ElementProcessingException(int elementIndex, Throwable innerException) {#ElementProcessingException-int-java.lang.Throwable-}
```
public ElementProcessingException(int elementIndex, Throwable innerException)
```


Initializes a new instance of the [ElementProcessingException](../../com.aspose.email/elementprocessingexception) class with a specified element index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elementIndex | int | The index of the processed element. |
| innerException | java.lang.Throwable | The exception that is the cause of the current exception. |

### getElementIndex() {#getElementIndex--}
```
public final int getElementIndex()
```


The index of the processed element.

**Returns:**
int
