---
title: 许可证
second_title: Aspose.Email for Android via Java API 参考
description: 提供对组件进行授权的方法。
type: docs
weight: 176
url: /zh/androidjava/com.aspose.email/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件进行授权的方法。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As license = New license
>  	License.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | 为组件授权。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 为组件授权。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 为组件授权。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


初始化此类的新实例。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As license = New license
>  	License.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```

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




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public final void setLicense(File licenseFile)
```


为组件授权。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseFile | java.io.File | licenseFileInfo 的文件。 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


为组件授权。

--------------------

> ```
> ```
> 
>  [C#]
>  License license = new License();
>  license.SetLicense(myStream);
>  [Visual Basic]
>  Dim license as License = new License
>  license.SetLicense(myStream)
>  
> ```
>  ```
> 
>  License license = new License();
>  license.setLicense(myStream);
>  
> ```
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 包含许可证的流。 |

--------------------



使用此方法从流中加载许可证。



void setLicense(java.io.InputStream stream)  |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


为组件授权。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As License = New License
>  	license.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseName | java.lang.String | 可以是完整或简短的文件名或嵌入资源的名称。使用空字符串切换到评估模式。 |

--------------------



尝试在以下位置查找许可证：

 

1. 显式路径。

 

2. 组件程序集的文件夹。

3. 客户端调用程序集的文件夹。

4. 入口程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 显式路径。

2. 客户端调用程序集中的嵌入资源。

 

2. 组件 JAR 文件的文件夹。

|

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

