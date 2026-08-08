---
title: MessageStore
second_title: Aspose.Email for Android via Java API 参考
description: Message store 是 PST 的根，它大致相当于邮箱的顶部。
type: docs
weight: 318
url: /zh/androidjava/com.aspose.email/messagestore/
---

**Inheritance:**
java.lang.Object
```
public class MessageStore
```

Message store 是 PST 的根，它大致相当于邮箱的顶部。
## 方法

| 方法 | 描述 |
| --- | --- |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | 更改 pst 显示名称。 |
| [changePassword(String password)](#changePassword-java.lang.String-) | 设置密码。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | 获取 PST 的显示名称。 |
| [getProperties()](#getProperties--) | 获取消息存储对象的 MAPI 属性。 |
| [hashCode()](#hashCode--) |  |
| [isPasswordProtected()](#isPasswordProtected--) | 获取一个值，指示存储是否受密码保护。 |
| [isPasswordValid(String password)](#isPasswordValid-java.lang.String-) | 确定指定的字符串是否是存储的有效密码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty property)](#setProperty-com.aspose.email.MapiProperty-) | 设置属性。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


更改 pst 显示名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newName | java.lang.String | 消息存储的新显示名称。 |

### changePassword(String password) {#changePassword-java.lang.String-}
```
public final void changePassword(String password)
```


设置密码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 表示密码的字符串。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取 PST 的显示名称。

值：表示显示名称的字符串。

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


获取消息存储对象的 MAPI 属性。消息存储包含访问和管理 PST 内容所需的顶层 PST 设置和元数据。

值： [MapiProperty](../../com.aspose.email/mapiproperty) 集合。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


获取一个值，指示存储是否受密码保护。

值：如果存储受密码保护，则为 true；否则为 false。

**Returns:**
boolean
### isPasswordValid(String password) {#isPasswordValid-java.lang.String-}
```
public final boolean isPasswordValid(String password)
```


确定指定的字符串是否是存储的有效密码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 密码字符串。 |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setProperty(MapiProperty property) {#setProperty-com.aspose.email.MapiProperty-}
```
public final void setProperty(MapiProperty property)
```


设置属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性。 |

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

