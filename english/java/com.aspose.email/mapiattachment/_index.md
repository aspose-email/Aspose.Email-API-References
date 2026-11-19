---
title: MapiAttachment
second_title: Aspose.Email for Java API Reference
description: Represents an attachment of an Outlook item.
type: docs
weight: 405
url: /java/com.aspose.email/mapiattachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiAttachment extends MapiPropertyContainer
```

Represents an attachment of an Outlook item.

An attachment is either a file, whose content is in \#getBinaryData().getBinaryData(), or an embedded object, such as an attached Outlook message, which is in \#getObjectData().getObjectData(). Like the message itself, the attachment is a set of MAPI properties: use the inherited property methods for data that has no dedicated member.

Add attachments through the [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) returned by [MapiMessageItemBase.getAttachments()](../../com.aspose.email/mapimessageitembase\#getAttachments--).

This example saves the attachments of a message: an embedded message is loaded as a [MapiMessage](../../com.aspose.email/mapimessage), any other attachment is saved to a file.

```

 MapiMessage msg = MapiMessage.load("source.msg");

 for (MapiAttachment attachment : msg.getAttachments()) {
     if (attachment.isInline()) {
         // an image or object shown in the message body
         System.out.println("Inline: " + attachment.getDisplayName());
     } else if (attachment.getObjectData() != null && attachment.getObjectData().isOutlookMessage()) {
         // an attached Outlook message
         MapiMessage embedded = attachment.getObjectData().toMapiMessage();
         System.out.println("Embedded message: " + embedded.getSubject());
     } else {
         attachment.save(Paths.get("output", attachment.getLongFileName()).toString());
     }
 }
 
```
## Methods

| Method | Description |
| --- | --- |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBinaryData()](#getBinaryData--) | Gets the content of a file attachment. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getContent()](#getContent--) | Gets the content of the attachment. |
| [getContentLength()](#getContentLength--) | Gets the length of the attachment content in bytes. |
| [getDisplayName()](#getDisplayName--) | Gets the name of the attachment shown to the user. |
| [getExtension()](#getExtension--) | Gets the file name extension of the attachment, such as  .docx . |
| [getFileName()](#getFileName--) | Gets the short (8.3) file name of the attachment, without a path. |
| [getItemId()](#getItemId--) | Gets the identifier of the attachment on the mail server, for attachments obtained from a server;  null  otherwise. |
| [getLongFileName()](#getLongFileName--) | Gets the full file name of the attachment, without a path. |
| [getMimeTag()](#getMimeTag--) | Gets the MIME content type of the attachment, such as  image/png . |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of the attachment. |
| [getObjectData()](#getObjectData--) | Gets the embedded object of the attachment, such as an attached Outlook message or an OLE document. |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property of the attachment by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream of the attachment. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [getSubStorages()](#getSubStorages--) | Gets the sub-storages of the attachment. |
| [hashCode()](#hashCode--) |  |
| [isInline()](#isInline--) | Gets a value indicating whether the attachment is shown inside the message body (an inline image, for example) rather than as a regular attachment. |
| [isReference()](#isReference--) | Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email. |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | Loads an attachment from a stream in TNEF format. |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | Loads an attachment from a file in TNEF format. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openRead()](#openRead--) | Opens the attachment content for reading. |
| [removeProperty(long tag)](#removeProperty-long-) | Removes a property from the attachment, including its named-property mapping. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the content of the attachment to a stream. |
| [save(String filename)](#save-java.lang.String-) | Saves the content of the attachment to a file. |
| [saveToTnef(OutputStream stream)](#saveToTnef-java.io.OutputStream-) | Saves the attachment to a stream in TNEF format. |
| [saveToTnef(String filename)](#saveToTnef-java.lang.String-) | Saves the attachment to a file in TNEF format. |
| [setBinaryData(byte[] value)](#setBinaryData-byte---) | Sets the content of a file attachment. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Sets the name of the attachment shown to the user. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property to the attachment, or replaces the property with the same tag. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property of the attachment. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Gets the value of a property as bytes. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of a property as a date and time, if the property exists. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Gets the value of a property as a string. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of a property as a string, if the property exists. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Gets the content of a file attachment.

**Returns:**
byte[] - The content of the file, or  null  if the attachment is an embedded object.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page of the ANSI strings of the object.

**Returns:**
int - The code page.
### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content of the attachment.

**Returns:**
java.lang.Object - The content: the file data for a file attachment, or the object for an embedded attachment.
### getContentLength() {#getContentLength--}
```
public final long getContentLength()
```


Gets the length of the attachment content in bytes.

For attachments added from a stream this does not materialise the content. For embedded message attachments ( getObjectData().isOutlookMessage()  is  true ), this property returns the size of the embedded message content.

**Returns:**
long
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the name of the attachment shown to the user.

**Returns:**
java.lang.String - The display name.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gets the file name extension of the attachment, such as  .docx .

**Returns:**
java.lang.String - The extension, including the leading period.
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the short (8.3) file name of the attachment, without a path. Use \#getLongFileName().getLongFileName() for the full name.

**Returns:**
java.lang.String - The short file name.
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets the identifier of the attachment on the mail server, for attachments obtained from a server;  null  otherwise.

**Returns:**
java.lang.String
### getLongFileName() {#getLongFileName--}
```
public final String getLongFileName()
```


Gets the full file name of the attachment, without a path.

**Returns:**
java.lang.String - The long file name.
### getMimeTag() {#getMimeTag--}
```
public final String getMimeTag()
```


Gets the MIME content type of the attachment, such as  image/png .

**Returns:**
java.lang.String - The MIME type.
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of the attachment.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The collection of named properties.
### getObjectData() {#getObjectData--}
```
public final MapiObjectProperty getObjectData()
```


Gets the embedded object of the attachment, such as an attached Outlook message or an OLE document.

**Returns:**
[MapiObjectProperty](../../com.aspose.email/mapiobjectproperty) - The embedded object, or  null  for a file attachment.
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets all properties of the object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets a MAPI property of the attachment by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the attachment does not have it.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of a property as a Boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Boolean - The value, or  null  if the property does not exist.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of a property as a date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property. |

**Returns:**
java.util.Date - The value, or  null  if the property does not exist.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the value of a property as a 32-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Integer - The value, or  null  if the property does not exist.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of a property as a 64-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Long - The value, or  null  if the property does not exist.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of a property as a 16-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Short - The value, or  null  if the property does not exist.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream of the attachment.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream) - The property stream.
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub-storages of the attachment.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The sub-storages.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInline() {#isInline--}
```
public boolean isInline()
```


Gets a value indicating whether the attachment is shown inside the message body (an inline image, for example) rather than as a regular attachment.

**Returns:**
boolean
### isReference() {#isReference--}
```
public final boolean isReference()
```


Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email.

This property determines if the attachment is referenced by its file path or a web link based on the  PidTagAttachMethod  MAPI property. The following values indicate a reference-based attachment:

 *   0x00000002  -  afByReference : The attachment is identified by a fully qualified file path, accessible to recipients with shared access to the file server.
 *   0x00000004  -  afByReferenceOnly : The attachment is identified solely by its fully qualified file path.
 *   0x00000007  -  afByWebReference : The attachment is identified by a web link, with the  PidNameAttachmentProviderType  specifying the web service API handling the attachment.

If the attachment does not match these criteria, this property returns  false .

**Returns:**
boolean -  true  if the attachment is stored as a reference; otherwise,  false .
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines whether the string properties of the object are stored in Unicode.

**Returns:**
boolean -  true  if the strings are Unicode;  false  if they are ANSI.
### loadFromTnef(InputStream stream) {#loadFromTnef-java.io.InputStream-}
```
public static MapiAttachment loadFromTnef(InputStream stream)
```


Loads an attachment from a stream in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The loaded attachment.
### loadFromTnef(String fileName) {#loadFromTnef-java.lang.String-}
```
public static MapiAttachment loadFromTnef(String fileName)
```


Loads an attachment from a file in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file. |

**Returns:**
[MapiAttachment](../../com.aspose.email/mapiattachment) - The loaded attachment.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### openRead() {#openRead--}
```
public final InputStream openRead()
```


Opens the attachment content for reading.

For attachments added from a stream the content is read from the source on demand and is not copied into memory. Each call returns an independent reader, so several readers may be used at the same time.

**Returns:**
java.io.InputStream - An independent, read-only, seekable stream over the attachment content.
### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Removes a property from the attachment, including its named-property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property to remove. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the content of the attachment to a stream. An embedded message is saved in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(String filename) {#save-java.lang.String-}
```
public final void save(String filename)
```


Saves the content of the attachment to a file. An embedded message is saved in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The path of the file to write. |

### saveToTnef(OutputStream stream) {#saveToTnef-java.io.OutputStream-}
```
public final void saveToTnef(OutputStream stream)
```


Saves the attachment to a stream in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### saveToTnef(String filename) {#saveToTnef-java.lang.String-}
```
public final void saveToTnef(String filename)
```


Saves the attachment to a file in TNEF format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The path of the file to write. |

### setBinaryData(byte[] value) {#setBinaryData-byte---}
```
public final void setBinaryData(byte[] value)
```


Sets the content of a file attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The content of the file, or  null  if the attachment is an embedded object. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Sets the name of the attachment shown to the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name. |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Adds the property to the attachment, or replaces the property with the same tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets the value of a MAPI property of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of a property as a date and time, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.util.Date[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of a property as a 32-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | int[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of a property as a 64-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | long[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of a property as a string, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
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

