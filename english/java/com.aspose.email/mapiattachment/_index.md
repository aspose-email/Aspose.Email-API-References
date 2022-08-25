---
title: MapiAttachment
second_title: Aspose.Email for Java API Reference
description:  Represents the attachment in the E-mail message.
type: docs
weight: 384
url: /java/com.aspose.email/mapiattachment/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiAttachment extends MapiPropertyContainer
```

Represents the attachment in the E-mail message.
## Methods

| Method | Description |
| --- | --- |
| [getItemId()](#getItemId--) | The item id, uses with a server |
| [getExtension()](#getExtension--) | Gets a filename extension that indicates the document type of an attachment. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getFileName()](#getFileName--) | Gets an attachment's base filename and extension, excluding path. |
| [getLongFileName()](#getLongFileName--) | Gets an attachment's long filename and extension, excluding path. |
| [getDisplayName()](#getDisplayName--) | Gets the display name of the ole object in an attachment. |
| [getMimeTag()](#getMimeTag--) | Gets formatting information about a Multipurpose Internet Mail Extensions (MIME) attachment. |
| [getBinaryData()](#getBinaryData--) | Gets or sets binary attachment data. |
| [setBinaryData(byte[] value)](#setBinaryData-byte---) | Gets or sets binary attachment data. |
| [getContent()](#getContent--) | Gets the content. |
| [getObjectData()](#getObjectData--) | Gets an attachment object typically accessed through the OLE IStorage interface. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [save(String filename)](#save-java.lang.String-) | Save attachment content. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Save attachment content. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [removeProperty(long tag)](#removeProperty-long-) | Provides correctly removing property from all collections. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
### getItemId() {#getItemId--}
```
public String getItemId()
```


The item id, uses with a server

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gets a filename extension that indicates the document type of an attachment.

Value: The extension.

**Returns:**
java.lang.String
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets an attachment's base filename and extension, excluding path.

Value: The file name.

**Returns:**
java.lang.String
### getLongFileName() {#getLongFileName--}
```
public final String getLongFileName()
```


Gets an attachment's long filename and extension, excluding path.

Value: The long file name.

**Returns:**
java.lang.String
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of the ole object in an attachment.

Value: The display name.

**Returns:**
java.lang.String
### getMimeTag() {#getMimeTag--}
```
public final String getMimeTag()
```


Gets formatting information about a Multipurpose Internet Mail Extensions (MIME) attachment.

Value: The mime tag.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Gets or sets binary attachment data.

Value: The binary data.

**Returns:**
byte[]
### setBinaryData(byte[] value) {#setBinaryData-byte---}
```
public final void setBinaryData(byte[] value)
```


Gets or sets binary attachment data.

Value: The binary data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content.

Value: The content.

**Returns:**
java.lang.Object
### getObjectData() {#getObjectData--}
```
public final MapiObjectProperty getObjectData()
```


Gets an attachment object typically accessed through the OLE IStorage interface.

Value: The object data.

**Returns:**
[MapiObjectProperty](../../com.aspose.email/mapiobjectproperty)
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### save(String filename) {#save-java.lang.String-}
```
public final void save(String filename)
```


Save attachment content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name to save. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Save attachment content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save. |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Provides correctly removing property from all collections.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of MapiProperty. |

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets MAPI property by property descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor for looked property |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The property descriptor. |
| value | java.lang.Object | The property data. |

