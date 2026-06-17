---
title: ContentDisposition
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Content-Disposition 头部。
type: docs
weight: 85
url: /zh/androidjava/com.aspose.email/contentdisposition/
---

**Inheritance:**
java.lang.Object
```
public class ContentDisposition
```

表示 Content-Disposition 头部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentDisposition()](#ContentDisposition--) | 初始化一个新的 [ContentDisposition](../../com.aspose.email/contentdisposition) 类的实例。 |
| [ContentDisposition(String disposition)](#ContentDisposition-java.lang.String-) | 初始化一个新的 [ContentDisposition](../../com.aspose.email/contentdisposition) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | 获取或设置创建日期。 |
| [getDispositionType()](#getDispositionType--) | 获取或设置 disposition 的类型。 |
| [getFileName()](#getFileName--) | 获取或设置附件的文件名。 |
| [getInline()](#getInline--) | 获取或设置决定 disposition 类型的值。 |
| [getModificationDate()](#getModificationDate--) | 获取或设置修改日期。 |
| [getParameters()](#getParameters--) | 获取参数。 |
| [getReadDate()](#getReadDate--) | 获取或设置读取日期。 |
| [getSize()](#getSize--) | 获取或设置文件附件的大小。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | 获取或设置创建日期。 |
| [setDispositionType(String value)](#setDispositionType-java.lang.String-) | 获取或设置 disposition 的类型。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 获取或设置附件的文件名。 |
| [setInline(boolean value)](#setInline-boolean-) | 获取或设置决定 disposition 类型的值。 |
| [setModificationDate(Date value)](#setModificationDate-java.util.Date-) | 获取或设置修改日期。 |
| [setReadDate(Date value)](#setReadDate-java.util.Date-) | 获取或设置读取日期。 |
| [setSize(long value)](#setSize-long-) | 获取或设置文件附件的大小。 |
| [toString()](#toString--) | 返回表示此实例的 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentDisposition() {#ContentDisposition--}
```
public ContentDisposition()
```


初始化一个新的 [ContentDisposition](../../com.aspose.email/contentdisposition) 类的实例。

### ContentDisposition(String disposition) {#ContentDisposition-java.lang.String-}
```
public ContentDisposition(String disposition)
```


初始化一个新的 [ContentDisposition](../../com.aspose.email/contentdisposition) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| disposition | java.lang.String | 包含 disposition 的值。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例则为 true；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


获取或设置创建日期。

值：指示文件创建日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Returns:**
java.util.Date
### getDispositionType() {#getDispositionType--}
```
public final String getDispositionType()
```


获取或设置 disposition 的类型。

值：包含 disposition 类型的 String。

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


获取或设置附件的文件名。

值：文件的名称。

**Returns:**
java.lang.String
### getInline() {#getInline--}
```
public final boolean getInline()
```


获取或设置决定 disposition 类型的值。

值：如果附件中的内容以内联方式呈现则为 true；否则为 false。

**Returns:**
boolean
### getModificationDate() {#getModificationDate--}
```
public final Date getModificationDate()
```


获取或设置修改日期。

值：指示文件修改日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Returns:**
java.util.Date
### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


获取参数。

值：包含参数名称/值对的 StringDictionary。

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary)
### getReadDate() {#getReadDate--}
```
public final Date getReadDate()
```


获取或设置读取日期。

值：指示文件读取日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Returns:**
java.util.Date
### getSize() {#getSize--}
```
public final long getSize()
```


获取或设置文件附件的大小。

值：指定文件附件中字节数的 Int32。

**Returns:**
long
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


获取或设置创建日期。

值：指示文件创建日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDispositionType(String value) {#setDispositionType-java.lang.String-}
```
public final void setDispositionType(String value)
```


获取或设置 disposition 的类型。

值：包含 disposition 类型的 String。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


获取或设置附件的文件名。

值：文件的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setInline(boolean value) {#setInline-boolean-}
```
public final void setInline(boolean value)
```


获取或设置决定 disposition 类型的值。

值：如果附件中的内容以内联方式呈现则为 true；否则为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setModificationDate(Date value) {#setModificationDate-java.util.Date-}
```
public final void setModificationDate(Date value)
```


获取或设置修改日期。

值：指示文件修改日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setReadDate(Date value) {#setReadDate-java.util.Date-}
```
public final void setReadDate(Date value)
```


获取或设置读取日期。

值：指示文件读取日期的 DateTime 值；如果未指定日期，则为 MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


获取或设置文件附件的大小。

值：指定文件附件中字节数的 Int32。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 String。

**Returns:**
java.lang.String - 表示此实例的 String。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

