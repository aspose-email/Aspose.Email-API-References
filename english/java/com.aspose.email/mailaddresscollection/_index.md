---
title: MailAddressCollection
second_title: Aspose.Email for Java API Reference
description: Represents a collection of  objects.
type: docs
weight: 365
url: /java/com.aspose.email/mailaddresscollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class MailAddressCollection extends System.Collections.ObjectModel.Collection<MailAddress>
```

Represents a collection of [MailAddress](../../com.aspose.email/mailaddress) objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailAddressCollection()](#MailAddressCollection--) |  |
## Methods

| Method | Description |
| --- | --- |
| [to_MailAddressCollection(MailAddress address)](#to-MailAddressCollection-com.aspose.email.MailAddress-) | Performs an implicit conversion from [MailAddress](../../com.aspose.email/mailaddress) to [MailAddressCollection](../../com.aspose.email/mailaddresscollection). |
| [to_MailAddressCollection(String addresses)](#to-MailAddressCollection-java.lang.String-) | Performs an implicit conversion from String to [MailAddressCollection](../../com.aspose.email/mailaddresscollection). |
| [copy()](#copy--) | Copies this instance. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [addMailAddress(MailAddress address)](#addMailAddress-com.aspose.email.MailAddress-) | Add a [MailAddress](../../com.aspose.email/mailaddress) to the collection. |
| [add(String addresses)](#add-java.lang.String-) | Add a list of e-mail addresses to the collection. |
| [addRange(MailAddressCollection addresses)](#addRange-com.aspose.email.MailAddressCollection-) | Adds addresses to collection |
| [addRange(Iterable<MailAddress> addresses)](#addRange-java.lang.Iterable-com.aspose.email.MailAddress--) | Adds addresses to collection |
| [insertItem(int index, MailAddress item)](#insertItem-int-com.aspose.email.MailAddress-) | Inserts an element into the  System.Collections.ObjectModel.Collection1  at the specified index. |
| [clear()](#clear--) | Removes all elements from the Collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the Collection. |
### MailAddressCollection() {#MailAddressCollection--}
```
public MailAddressCollection()
```


### to_MailAddressCollection(MailAddress address) {#to-MailAddressCollection-com.aspose.email.MailAddress-}
```
public static MailAddressCollection to_MailAddressCollection(MailAddress address)
```


Performs an implicit conversion from [MailAddress](../../com.aspose.email/mailaddress) to [MailAddressCollection](../../com.aspose.email/mailaddresscollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | [MailAddress](../../com.aspose.email/mailaddress) | The address. |

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - The result of the conversion.
### to_MailAddressCollection(String addresses) {#to-MailAddressCollection-java.lang.String-}
```
public static MailAddressCollection to_MailAddressCollection(String addresses)
```


Performs an implicit conversion from String to [MailAddressCollection](../../com.aspose.email/mailaddresscollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addresses | java.lang.String | The address list. |

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - The result of the conversion.
### copy() {#copy--}
```
public final MailAddressCollection copy()
```


Copies this instance.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - 
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### addMailAddress(MailAddress address) {#addMailAddress-com.aspose.email.MailAddress-}
```
public final void addMailAddress(MailAddress address)
```


Add a [MailAddress](../../com.aspose.email/mailaddress) to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | [MailAddress](../../com.aspose.email/mailaddress) | The [MailAddress](../../com.aspose.email/mailaddress) |

### add(String addresses) {#add-java.lang.String-}
```
public final void add(String addresses)
```


Add a list of e-mail addresses to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addresses | java.lang.String | An address list. Addresses must be separated with a comma character. |

### addRange(MailAddressCollection addresses) {#addRange-com.aspose.email.MailAddressCollection-}
```
public final void addRange(MailAddressCollection addresses)
```


Adds addresses to collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Collection of mail addresses |

### addRange(Iterable<MailAddress> addresses) {#addRange-java.lang.Iterable-com.aspose.email.MailAddress--}
```
public final void addRange(Iterable<MailAddress> addresses)
```


Adds addresses to collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addresses | java.lang.Iterable<com.aspose.email.MailAddress> | Enumeration of mail addresses |

### insertItem(int index, MailAddress item) {#insertItem-int-com.aspose.email.MailAddress-}
```
public void insertItem(int index, MailAddress item)
```


Inserts an element into the  System.Collections.ObjectModel.Collection1  at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which  item  should be inserted. |
| item | [MailAddress](../../com.aspose.email/mailaddress) | The object to insert. The value can be null for reference types. |

### clear() {#clear--}
```
public void clear()
```


Removes all elements from the Collection.

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Removes the element at the specified index of the Collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

