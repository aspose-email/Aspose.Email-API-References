---
title: Лицензия
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет методы лицензирования компонента.
type: docs
weight: 176
url: /ru/androidjava/com.aspose.email/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы лицензирования компонента.

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
## Constructors

| Constructor | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Инициализирует новый экземпляр этого класса.

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
| Parameter | Type | Описание |
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


Лицензирует компонент.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| licenseFile | java.io.File | Файл licenseFileInfo. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Лицензирует компонент.

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
| Parameter | Type | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток, содержащий лицензию. |

--------------------



Используйте этот метод для загрузки лицензии из потока.



void setLicense(java.io.InputStream stream)  |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


Лицензирует компонент.

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
| Parameter | Type | Описание |
| --- | --- | --- |
|  | licenseName | java.lang.String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

--------------------



Пытается найти лицензию в следующих местах:

 

1. Явный путь.

 

2. Папка сборки компонента.

3. Папка вызывающей сборки клиента.

4. Папка входной сборки.

5. Встроенный ресурс в вызывающей сборке клиента.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

 

2. Папка jar‑файла компонента.

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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

