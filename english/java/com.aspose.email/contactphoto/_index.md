---
title: ContactPhoto
second_title: Aspose.Email for Java API Reference
description:  Represents contact photo.
type: docs
weight: 121
url: /java/com.aspose.email/contactphoto/
---
**Inheritance:**
java.lang.Object
```
public class ContactPhoto
```

Represents contact photo.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContactPhoto(byte[] data, int photoImageFormat)](#ContactPhoto-byte---int-) | Initializes a new instance of the [ContactPhoto](../../com.aspose.email/contactphoto) class |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets object identification information |
| [getPhotoImageFormat()](#getPhotoImageFormat--) | Gets a photo type. |
| [getData()](#getData--) | Gets an image data. |
### ContactPhoto(byte[] data, int photoImageFormat) {#ContactPhoto-byte---int-}
```
public ContactPhoto(byte[] data, int photoImageFormat)
```


Initializes a new instance of the [ContactPhoto](../../com.aspose.email/contactphoto) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Image data of photo. |
| photoImageFormat | int | Image format of photo [MapiContactPhotoImageFormat](../../com.aspose.email/mapicontactphotoimageformat). |

### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets object identification information

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
### getPhotoImageFormat() {#getPhotoImageFormat--}
```
public final int getPhotoImageFormat()
```


Gets a photo type.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Gets an image data.

**Returns:**
byte[]
