---
title: PageInfo
second_title: Aspose.Email for Java API Reference
description: Contains information about retrieved page when paging methods are used.
type: docs
weight: 558
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAbsoluteOffset()](#getAbsoluteOffset--) | Gets additinal offset added to start index of a page |
| [getClass()](#getClass--) |  |
| [getItemsPerPage()](#getItemsPerPage--) | A number of items in page |
| [getLastPage()](#getLastPage--) | Indicates whether current page is last page in view. |
| [getNextPage()](#getNextPage--) | Information of the next page or null if current page is last |
| [getPageOffset()](#getPageOffset--) | Gets offset of a page |
| [getTotalCount()](#getTotalCount--) | Gets total count of items in view |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAbsoluteOffset(int value)](#setAbsoluteOffset-int-) | Gets additinal offset added to start index of a page |
| [setItemsPerPage(int value)](#setItemsPerPage-int-) | A number of items in page |
| [setLastPage(boolean value)](#setLastPage-boolean-) | Indicates whether current page is last page in view. |
| [setPageOffset(int value)](#setPageOffset-int-) | Gets offset of a page |
| [setTotalCount(int value)](#setTotalCount-int-) | Gets total count of items in view |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAbsoluteOffset() {#getAbsoluteOffset--}
```
public final int getAbsoluteOffset()
```


Gets additinal offset added to start index of a page

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItemsPerPage() {#getItemsPerPage--}
```
public final int getItemsPerPage()
```


A number of items in page

**Returns:**
int
### getLastPage() {#getLastPage--}
```
public final boolean getLastPage()
```


Indicates whether current page is last page in view.

**Returns:**
boolean
### getNextPage() {#getNextPage--}
```
public PageInfo getNextPage()
```


Information of the next page or null if current page is last

**Returns:**
[PageInfo](../../com.aspose.email/pageinfo)
### getPageOffset() {#getPageOffset--}
```
public final int getPageOffset()
```


Gets offset of a page

**Returns:**
int
### getTotalCount() {#getTotalCount--}
```
public final int getTotalCount()
```


Gets total count of items in view

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAbsoluteOffset(int value) {#setAbsoluteOffset-int-}
```
public final void setAbsoluteOffset(int value)
```


Gets additinal offset added to start index of a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setItemsPerPage(int value) {#setItemsPerPage-int-}
```
public final void setItemsPerPage(int value)
```


A number of items in page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLastPage(boolean value) {#setLastPage-boolean-}
```
public final void setLastPage(boolean value)
```


Indicates whether current page is last page in view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPageOffset(int value) {#setPageOffset-int-}
```
public final void setPageOffset(int value)
```


Gets offset of a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTotalCount(int value) {#setTotalCount-int-}
```
public final void setTotalCount(int value)
```


Gets total count of items in view

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

