---
title: PageInfo
second_title: Aspose.Email for Java API Reference
description:  Contains information about retrieved page when paging methods are used.
type: docs
weight: 547
url: /java/com.aspose.email/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

Contains information about retrieved page when paging methods are used.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageInfo(int itemsPerPage)](#PageInfo-int-) | Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class |
| [PageInfo(int itemsPerPage, int offset)](#PageInfo-int-int-) | Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class |
| [PageInfo(int totalCount, int itemsPerPage, int offset, boolean lastPage)](#PageInfo-int-int-int-boolean-) | Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class |
| [PageInfo(int totalCount, int itemsPerPage, int offset, int absoluteOffset, boolean lastPage)](#PageInfo-int-int-int-int-boolean-) | Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class |
## Methods

| Method | Description |
| --- | --- |
| [getPageOffset()](#getPageOffset--) | Gets offset of a page |
| [setPageOffset(int value)](#setPageOffset-int-) | Gets offset of a page |
| [getAbsoluteOffset()](#getAbsoluteOffset--) | Gets additinal offset added to start index of a page |
| [setAbsoluteOffset(int value)](#setAbsoluteOffset-int-) | Gets additinal offset added to start index of a page |
| [getLastPage()](#getLastPage--) | Indicates whether current page is last page in view. |
| [setLastPage(boolean value)](#setLastPage-boolean-) | Indicates whether current page is last page in view. |
| [getTotalCount()](#getTotalCount--) | Gets total count of items in view |
| [setTotalCount(int value)](#setTotalCount-int-) | Gets total count of items in view |
| [getItemsPerPage()](#getItemsPerPage--) | A number of items in page |
| [setItemsPerPage(int value)](#setItemsPerPage-int-) | A number of items in page |
| [getNextPage()](#getNextPage--) | Information of the next page or null if current page is last |
### PageInfo(int itemsPerPage) {#PageInfo-int-}
```
public PageInfo(int itemsPerPage)
```


Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int | A number of items in page |

### PageInfo(int itemsPerPage, int offset) {#PageInfo-int-int-}
```
public PageInfo(int itemsPerPage, int offset)
```


Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int | A number of items in page |
| offset | int | offset in view of a page |

### PageInfo(int totalCount, int itemsPerPage, int offset, boolean lastPage) {#PageInfo-int-int-int-boolean-}
```
public PageInfo(int totalCount, int itemsPerPage, int offset, boolean lastPage)
```


Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| totalCount | int | total count of items in view |
| itemsPerPage | int | A number of items in page |
| offset | int | offset in view of a page |
| lastPage | boolean | Indicates whether current page is last page in view |

### PageInfo(int totalCount, int itemsPerPage, int offset, int absoluteOffset, boolean lastPage) {#PageInfo-int-int-int-int-boolean-}
```
public PageInfo(int totalCount, int itemsPerPage, int offset, int absoluteOffset, boolean lastPage)
```


Initializes a new instance of the [PageInfo](../../com.aspose.email/pageinfo) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| totalCount | int | total count of items in view |
| itemsPerPage | int |  |
| offset | int | offset in view of a page |
| absoluteOffset | int |  |
| lastPage | boolean |  |

### getPageOffset() {#getPageOffset--}
```
public final int getPageOffset()
```


Gets offset of a page

**Returns:**
int
### setPageOffset(int value) {#setPageOffset-int-}
```
public final void setPageOffset(int value)
```


Gets offset of a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAbsoluteOffset() {#getAbsoluteOffset--}
```
public final int getAbsoluteOffset()
```


Gets additinal offset added to start index of a page

**Returns:**
int
### setAbsoluteOffset(int value) {#setAbsoluteOffset-int-}
```
public final void setAbsoluteOffset(int value)
```


Gets additinal offset added to start index of a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLastPage() {#getLastPage--}
```
public final boolean getLastPage()
```


Indicates whether current page is last page in view.

**Returns:**
boolean
### setLastPage(boolean value) {#setLastPage-boolean-}
```
public final void setLastPage(boolean value)
```


Indicates whether current page is last page in view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTotalCount() {#getTotalCount--}
```
public final int getTotalCount()
```


Gets total count of items in view

**Returns:**
int
### setTotalCount(int value) {#setTotalCount-int-}
```
public final void setTotalCount(int value)
```


Gets total count of items in view

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getItemsPerPage() {#getItemsPerPage--}
```
public final int getItemsPerPage()
```


A number of items in page

**Returns:**
int
### setItemsPerPage(int value) {#setItemsPerPage-int-}
```
public final void setItemsPerPage(int value)
```


A number of items in page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNextPage() {#getNextPage--}
```
public PageInfo getNextPage()
```


Information of the next page or null if current page is last

**Returns:**
[PageInfo](../../com.aspose.email/pageinfo)
