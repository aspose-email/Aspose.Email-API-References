---
title: IAttachment
second_title: Aspose.Email for Java API Reference
description:  Represents a common attachment interface
type: docs
weight: 731
url: /java/com.aspose.email/iattachment/
---```
public interface IAttachment
```

Represents a common attachment interface
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets or sets an attachment name |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets an attachment name |
| [save(String fileName)](#save-java.lang.String-) | Saves attachment to file |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves an attachment to stream |
### getName() {#getName--}
```
public abstract String getName()
```


Gets or sets an attachment name

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Gets or sets an attachment name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Saves attachment to file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A file name |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Saves an attachment to stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

