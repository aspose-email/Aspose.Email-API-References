---
title: MapiMessageItemBase
second_title: Aspose.Email for Java API Reference
description:  Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties attachments recipients.
type: docs
weight: 445
url: /java/com.aspose.email/mapimessageitembase/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)

**All Implemented Interfaces:**
[com.aspose.email.IMapiMessageItem](../../com.aspose.email/imapimessageitem), com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class MapiMessageItemBase extends MapiPropertyContainer implements IMapiMessageItem, System.IDisposable, Closeable
```

Represents the base class for all MapiMessageItem classes and keeps common collections of mapi properties, attachments, recipients.
## Methods

| Method | Description |
| --- | --- |
| [getItemId()](#getItemId--) | The item id, uses with a server |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
| [getAttachments()](#getAttachments--) | Gets the attachments in the message. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the message. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Gets the recipients of the message. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the named property mapping. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getBodyRtf()](#getBodyRtf--) | Gets or sets the RTF formatted message text. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Gets or sets the RTF formatted message text. |
| [getBodyHtml()](#getBodyHtml--) | Gets the \`\`\` BodyRtf \`\`\`(\#getBodyRtf/\#setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string. |
| [getCompanies()](#getCompanies--) | Contains the names of the companies that are associated with an item. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Contains the names of the companies that are associated with an item. |
| [getCategories()](#getCategories--) | Contains keywords or categories for the message object. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Contains keywords or categories for the message object. |
| [getMileage()](#getMileage--) | Contains the mileage information that is associated with an item. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Contains the mileage information that is associated with an item. |
| [getBilling()](#getBilling--) | Contains the billing information associated with an item. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Contains the billing information associated with an item. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [getBody()](#getBody--) | Gets the message text. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets the message text. |
| [getSubject()](#getSubject--) | Gets or sets the subject of the message. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject of the message. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Gets or sets the RTF formatted message text. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the content of the body. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the content of the body. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the message flags. |
| [removeProperty(long tag)](#removeProperty-long-) | Provides correctly removing property from all collections. |
### getItemId() {#getItemId--}
```
public String getItemId()
```


The item id, uses with a server

**Returns:**
java.lang.String
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

### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments in the message.

Value: The attachment collection.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the message.

Value: The collection of recipients.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Gets the recipients of the message.

Value: The collection of recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the named property mapping.

Value: The named property mapping.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.

Value: The string that represents subject prefix.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the body.

Value: The type of the body.

**Returns:**
int
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Returns:**
java.lang.String
### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the \`\`\` BodyRtf \`\`\`(\#getBodyRtf/\#setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string.

**Returns:**
java.lang.String
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Contains the names of the companies that are associated with an item.

**Returns:**
java.lang.String[]
### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Contains the names of the companies that are associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Contains keywords or categories for the message object.

**Returns:**
java.lang.String[]
### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Contains keywords or categories for the message object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMileage() {#getMileage--}
```
public final String getMileage()
```


Contains the mileage information that is associated with an item.

**Returns:**
java.lang.String
### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Contains the mileage information that is associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBilling() {#getBilling--}
```
public final String getBilling()
```


Contains the billing information associated with an item.

**Returns:**
java.lang.String
### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Contains the billing information associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Value: The sensitivity.

**Returns:**
int
### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Value: The sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Returns:**
java.lang.String
### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBody() {#getBody--}
```
public String getBody()
```


Gets the message text.

Value: The string that represents message body.

**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Gets the message text.

Value: The string that represents message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Specify that the content should be compressed. |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content. |
| compression | boolean | Specify that the content should be compressed.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the message flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The message flags. |

### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Provides correctly removing property from all collections.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of MapiProperty. |

