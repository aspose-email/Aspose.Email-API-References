---
title: BuildResult
second_title: Aspose.Email for Java API Reference
description: Represents the outcome of a single  run.
type: docs
weight: 87
url: /java/com.aspose.email/buildresult/
---

**Inheritance:**
java.lang.Object
```
public final class BuildResult
```

Represents the outcome of a single [TgzBackupBuilder.build(String,String,String)](../../com.aspose.email/tgzbackupbuilder\#build-String-String-String-) run.
## Constructors

| Constructor | Description |
| --- | --- |
| [BuildResult()](#BuildResult--) | Initialises a new instance of [BuildResult](../../com.aspose.email/buildresult) with an empty error list. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | Gets the list of errors encountered during the build. |
| [getMessagesWritten()](#getMessagesWritten--) | Gets or sets the total number of EML messages successfully written to the archive. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMessagesWritten(int value)](#setMessagesWritten-int-) | Gets or sets the total number of EML messages successfully written to the archive. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BuildResult() {#BuildResult--}
```
public BuildResult()
```


Initialises a new instance of [BuildResult](../../com.aspose.email/buildresult) with an empty error list.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrors() {#getErrors--}
```
public final System.Collections.Generic.IGenericList<String> getErrors()
```


Gets the list of errors encountered during the build. Each entry contains the source file path and the exception message, separated by " - ". Files that appear here were skipped and are not present in the archive.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String>
### getMessagesWritten() {#getMessagesWritten--}
```
public final int getMessagesWritten()
```


Gets or sets the total number of EML messages successfully written to the archive.

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




### setMessagesWritten(int value) {#setMessagesWritten-int-}
```
public final void setMessagesWritten(int value)
```


Gets or sets the total number of EML messages successfully written to the archive.

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

