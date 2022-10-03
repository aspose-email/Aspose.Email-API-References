---
title: AutodiscoverResponseCollection
second_title: Aspose.Email for Java API Reference
description: Represents a collection of responses to a call to the Autodiscover service.
type: docs
weight: 72
url: /java/com.aspose.email/autodiscoverresponsecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AutodiscoverResponse](../../com.aspose.email/autodiscoverresponse)

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public abstract class AutodiscoverResponseCollection<TResponse> extends AutodiscoverResponse implements System.Collections.Generic.IGenericEnumerable<TResponse>
```

Represents a collection of responses to a call to the Autodiscover service.

 TResponse : The type of the responses in the collection.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of responses in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the response at the specified index. |
| [iterator()](#iterator--) | Gets an enumerator that iterates through the elements of the collection. |
| [iterator_()](#iterator---) | Gets an enumerator that iterates through the elements of the collection. |
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of responses in the collection.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final TResponse get_Item(int index)
```


Gets the response at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index. |

**Returns:**
TResponse
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<TResponse> iterator()
```


Gets an enumerator that iterates through the elements of the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<TResponse> - An IEnumerator for the collection.
### iterator_() {#iterator---}
```
public final System.Collections.IEnumerator iterator_()
```


Gets an enumerator that iterates through the elements of the collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - An IEnumerator for the collection.
