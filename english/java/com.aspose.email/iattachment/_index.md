---
title: IAttachment
second_title: Aspose.Email for Java API Reference
description: The common interface of attachments.
type: docs
weight: 785
url: /java/com.aspose.email/iattachment/
---
```
public interface IAttachment
```

The common interface of attachments.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the name of the attachment. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the attachment to a stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the attachment to a file. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of the attachment. |
### getName() {#getName--}
```
public abstract String getName()
```


Gets the name of the attachment.

**Returns:**
java.lang.String
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Saves the attachment to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Saves the attachment to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Sets the name of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

