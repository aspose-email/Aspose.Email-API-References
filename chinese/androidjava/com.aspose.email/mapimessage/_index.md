---
title: MapiMessage
second_title: Aspose.Email for Android via Java API 参考
description: 表示可解析的 Outlook 消息格式文档。
type: docs
weight: 260
url: /zh/androidjava/com.aspose.email/mapimessage/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiMessage extends MapiMessageItemBase
```

表示可解析的 Outlook 消息格式文档。

--------------------

> The following exmaple demonstrates how to read Outlook Message files.
> 
> [Java]
> 
> ```
> //Open Outlook Message files
>   MapiMessage msg = MapiMessage.fromFile("outlookmessage.msg");
> 
>   //read subject
>   System.out.print("Subject:" + msg.getSubject());
> 
>   //sender name
>   System.out.print("From:" + msg.getSenderName());
> 
>   //message body
>   System.out.print("Body:" + msg.getBody());
> 
>   //Attachments
>   for(MapiAttachment att : msg.getAttachments())
>   {
>       System.out.print("Attachment Name:"+att.getFileName());
>       att.save(att.getFileName());
>   }
> ```

--------------------

MapiMessage 类的实例用于表示由 MapiMessageReader 类解析的 Microsoft Outlook 消息文档文件。要访问电子邮件的发件人、收件人和内容，请使用 MapiMessage 类的相应属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiMessage()](#MapiMessage--) | 初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。 |
| [MapiMessage(int format)](#MapiMessage-int-) | 初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。 |
| [MapiMessage(String from, String to, String subject, String body, int format)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-) | 初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。 |
| [MapiMessage(String from, String to, String subject, String body)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addCustomProperty(MapiProperty property, String stringNameId)](#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-) | 添加自定义属性。 |
| [addCustomProperty(int type, byte[] data, String stringNameId)](#addCustomProperty-int-byte---java.lang.String-) | 添加自定义属性。 |
| [checkBounced()](#checkBounced--) | 检查此消息是否可以视为退回消息。 |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | 创建 mapi 节点。 |
| [deepClone()](#deepClone--) | 创建当前实例的副本对象。 |
| [destroyAttachments(String path)](#destroyAttachments-java.lang.String-) | 销毁指定 Outlook 消息文件中的附件。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromFile(String path)](#fromFile-java.lang.String-) | 从指定文件创建 MapiMessage 实例。 |
| [fromMailMessage(MailMessage message)](#fromMailMessage-com.aspose.email.MailMessage-) | 从 MailMessage 创建 MapiMessage 实例。 |
| [fromMailMessage(MailMessage message, MapiConversionOptions options)](#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-) | 从 MailMessage 创建 MapiMessage 实例。 |
| [fromMailMessage(String fileName)](#fromMailMessage-java.lang.String-) | 从 MailMessage 创建 MapiMessage 实例。 |
| [fromProperties(MapiPropertyCollection properties)](#fromProperties-com.aspose.email.MapiPropertyCollection-) | 从 Mapi 属性集合创建 MapiMessage 实例。 |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 从指定流创建 MapiMessage 实例。 |
| [getAttachments()](#getAttachments--) | 获取消息中的附件。 |
| [getBilling()](#getBilling--) | 包含与项目关联的计费信息。 |
| [getBody()](#getBody--) | 获取消息文本。 |
| [getBodyHtml()](#getBodyHtml--) | 获取消息的 BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) 并转换为 HTML，如果存在，否则返回空字符串。 |
| [getBodyRtf()](#getBodyRtf--) | 获取或设置 RTF 格式的消息文本。 |
| [getBodyType()](#getBodyType--) | 获取正文的类型。 |
| [getCategories()](#getCategories--) | 包含消息对象的关键字或类别。 |
| [getClass()](#getClass--) |  |
| [getClientSubmitTime()](#getClientSubmitTime--) | 获取或设置消息发送者提交消息的日期和时间。 |
| [getCodePage()](#getCodePage--) | 获取代码页。 |
| [getCompanies()](#getCompanies--) | 包含与项目关联的公司名称。 |
| [getConversationTopic()](#getConversationTopic--) | 获取会话线程中第一条消息的主题。 |
| [getCustomProperties()](#getCustomProperties--) | 获取自定义 MapiProperties 的集合。 |
| [getDeliveryTime()](#getDeliveryTime--) | 获取或设置消息的投递日期和时间。 |
| [getDisplayBcc()](#getDisplayBcc--) | 获取盲目抄送 (BCC) 消息收件人的显示名称列表，使用分号 (;) 分隔。 |
| [getDisplayCc()](#getDisplayCc--) | 获取抄送 (CC) 消息收件人的显示名称列表，使用分号 (;) 分隔。 |
| [getDisplayName()](#getDisplayName--) | 获取消息的显示名称。 |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | 获取显示名称的前缀。 |
| [getDisplayTo()](#getDisplayTo--) | 获取主要 (To) 消息收件人的显示名称列表，使用分号 (;) 分隔。 |
| [getFlags()](#getFlags--) | 获取消息标志。 |
| [getHeaders()](#getHeaders--) | 获取传输消息头。 |
| [getInternetMessageId()](#getInternetMessageId--) | 获取消息的消息 ID。 |
| [getItemId()](#getItemId--) | 项目 ID，供服务器使用。 |
| [getMessageClass()](#getMessageClass--) | 获取区分大小写的字符串，以标识发送者定义的消息类，例如 IPM.Note。 |
| [getMessageFormat()](#getMessageFormat--) | 获取 Outlook 消息格式。 |
| [getMileage()](#getMileage--) | 包含与项目关联的里程信息。 |
| [getNamedProperties()](#getNamedProperties--) | 获取消息的命名属性。 |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | 获取命名属性映射。 |
| [getNormalizedSubject()](#getNormalizedSubject--) | 获取消息的规范化主题。 |
| [getProperties()](#getProperties--) | 获取属性的集合。 |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | 通过属性描述符获取 MAPI 属性。 |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | 获取由标签指定的属性值，类型为 Boolean。 |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | 获取由标签指定的属性值，类型为 DateTime。 |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | 获取由标签指定的属性的 int32 值。 |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | 获取由标签指定的属性值，类型为 Long（int64）。 |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | 获取由标签指定的属性值，类型为 Short。 |
| [getPropertyStream()](#getPropertyStream--) | 获取属性流。 |
| [getPropertyString(long tag)](#getPropertyString-long-) | 获取由标签指定的属性的字符串值。 |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | 获取由标签指定的属性的字符串值。 |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | 获取或设置指示是否请求已读回执的值。 |
| [getRecipients()](#getRecipients--) | 获取消息的收件人。 |
| [getReplyTo()](#getReplyTo--) | 获取或设置回复收件人名称。 |
| [getSenderAddressType()](#getSenderAddressType--) | 获取消息发送者的电子邮件地址类型。 |
| [getSenderEmailAddress()](#getSenderEmailAddress--) | 获取或设置消息发送者的电子邮件地址。 |
| [getSenderName()](#getSenderName--) | 获取或设置消息发送者的显示名称。 |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | 获取或设置消息发送者的电子邮件地址。 |
| [getSensitivity()](#getSensitivity--) | 获取敏感度。 |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | 获取由发送者代表的消息用户的地址类型。 |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | 获取或设置由发送者代表的消息用户的电子邮件地址。 |
| [getSentRepresentingName()](#getSentRepresentingName--) | 获取或设置由发送者代表的消息用户的显示名称。 |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | 获取或设置由发送者代表的消息用户的电子邮件地址。 |
| [getSubStorages()](#getSubStorages--) | 获取子存储。 |
| [getSubject()](#getSubject--) | 获取或设置消息的主题。 |
| [getSubjectPrefix()](#getSubjectPrefix--) | 获取主题前缀，通常指示对消息的某种操作，例如转发时的 "FW: "。 |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | 获取特定传输的消息信封信息。 |
| [hashCode()](#hashCode--) |  |
| [isMsgFormat(InputStream stream)](#isMsgFormat-java.io.InputStream-) | 确定指定的流是否为 MSG 格式。 |
| [isMsgFormat(String fileName)](#isMsgFormat-java.lang.String-) | 确定指定的文件是否为 MSG 格式。 |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | 确定字符串属性是否为 Unicode 编码。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从流加载消息。 |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | 使用附加选项从流加载消息。 |
| [load(String fileName)](#load-java.lang.String-) | 从文件加载消息。 |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | 从文件加载消息并使用附加选项。 |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | 从传输中立封装格式 (TNEF) 数据结构加载消息 |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | 从传输中立封装格式 (TNEF) 数据结构加载消息 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAttachments(String path)](#removeAttachments-java.lang.String-) | 从指定的 Outlook 消息文件中删除所有附件。 |
| [removeProperty(long tag)](#removeProperty-long-) | 正确地从所有集合中移除属性。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将消息保存为 Msg 到指定的流。 |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | 将消息保存为流并使用附加选项。 |
| [save(String fileName)](#save-java.lang.String-) | 将消息保存为 Msg 到指定的文件。 |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | 将消息保存为文件并使用附加选项。 |
| [saveAsTemplate(OutputStream stream)](#saveAsTemplate-java.io.OutputStream-) | 将 Outlook 文件模板 (OFT 格式) 保存到指定的流。 |
| [saveAsTemplate(String fileName)](#saveAsTemplate-java.lang.String-) | 将 Outlook 文件模板 (OFT 格式) 保存到指定的文件。 |
| [saveAsTnef(OutputStream stream)](#saveAsTnef-java.io.OutputStream-) | 以 TNEF 格式保存消息。 |
| [saveAsTnef(String fileName)](#saveAsTnef-java.lang.String-) | 以 TNEF 格式保存消息。 |
| [setBilling(String value)](#setBilling-java.lang.String-) | 包含与项目关联的计费信息。 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取消息文本。 |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | 设置正文的内容。 |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | 设置正文的内容。 |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | 获取或设置 RTF 格式的消息文本。 |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | 获取或设置 RTF 格式的消息文本。 |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | 包含消息对象的关键字或类别。 |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | 获取或设置消息发送者提交消息的日期和时间。 |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | 包含与项目关联的公司名称。 |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | 获取或设置消息的投递日期和时间。 |
| [setHeaders(HeaderCollection value)](#setHeaders-com.aspose.email.HeaderCollection-) | 获取传输消息头。 |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | 获取区分大小写的字符串，以标识发送者定义的消息类，例如 IPM.Note。 |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | 设置消息标志。 |
| [setMileage(String value)](#setMileage-java.lang.String-) | 包含与项目关联的里程信息。 |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | 设置已命名属性的映射。 |
| [setProperty(MapiAttachment value, long signed, long key)](#setProperty-com.aspose.email.MapiAttachment-long-long-) | 设置附件。 |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | 设置属性。 |
| [setProperty(MapiRecipient value, long signed, long key)](#setProperty-com.aspose.email.MapiRecipient-long-long-) | 设置收件人。 |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | 设置 MAPI 属性。 |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | 获取或设置指示是否请求已读回执的值。 |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | 获取消息的收件人。 |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | 获取或设置回复收件人名称。 |
| [setSenderEmailAddress(String value)](#setSenderEmailAddress-java.lang.String-) | 获取或设置消息发送者的电子邮件地址。 |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | 获取或设置消息发送者的显示名称。 |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | 获取或设置消息发送者的电子邮件地址。 |
| [setSensitivity(int value)](#setSensitivity-int-) | 获取敏感度。 |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | 获取或设置由发送者代表的消息用户的电子邮件地址。 |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | 获取或设置由发送者代表的消息用户的显示名称。 |
| [setStringPropertyValue(long tag, String value)](#setStringPropertyValue-long-java.lang.String-) | 设置字符串属性值。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置消息的主题。 |
| [toMailMessage(MailConversionOptions options)](#toMailMessage-com.aspose.email.MailConversionOptions-) | 从此 MapiMessage 创建 MailMessage 实例。 |
| [toMapiMessageItem()](#toMapiMessageItem--) | 根据 MessageClass 将 MapiMessage 转换为 IMapiMessageItem 对象。 |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | 尝试使用指定的标签键获取属性数据。 |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | 获取指定属性的值，类型为 DateTime。 |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | 获取指定属性的值，类型为 Int32。 |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | 获取指定属性的值，类型为 Long。 |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | 尝试使用指定的标签获取属性数据为字符串。 |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | 尝试使用指定的标签和代码页获取属性数据为字符串。 |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | 获取指定属性的值，类型为 String。 |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | 获取指定属性的值，类型为 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessage() {#MapiMessage--}
```
public MapiMessage()
```


初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。

### MapiMessage(int format) {#MapiMessage-int-}
```
public MapiMessage(int format)
```


初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | int | 定义是否对该消息使用 Unicode 或 ASCII 编码。 |

### MapiMessage(String from, String to, String subject, String body, int format) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-}
```
public MapiMessage(String from, String to, String subject, String body, int format)
```


初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| from | java.lang.String | 发件人地址。 |
| 至 | java.lang.String | 收件人地址。注意，地址之间用分号分隔。 |
| 主题 | java.lang.String | 消息主题。 |
| 正文 | java.lang.String | 消息正文。 |
| 格式 | int | 定义是否对该消息使用 Unicode 或 ASCII 编码。 |

### MapiMessage(String from, String to, String subject, String body) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiMessage(String from, String to, String subject, String body)
```


初始化 [MapiMessage](../../com.aspose.email/mapimessage) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| from | java.lang.String | 发件人地址。 |
| 至 | java.lang.String | 收件人地址。注意，地址之间用分号分隔。 |
| 主题 | java.lang.String | 消息主题。 |
| 正文 | java.lang.String | 消息正文。 |

### addCustomProperty(MapiProperty property, String stringNameId) {#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-}
```
public final void addCustomProperty(MapiProperty property, String stringNameId)
```


添加自定义属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性[MapiProperty](../../com.aspose.email/mapiproperty)。 |
| stringNameId | java.lang.String | propertyString 的名称。 |

### addCustomProperty(int type, byte[] data, String stringNameId) {#addCustomProperty-int-byte---java.lang.String-}
```
public final void addCustomProperty(int type, byte[] data, String stringNameId)
```


添加自定义属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | MapiProperty[MapiPropertyType](../../com.aspose.email/mapipropertytype) 的类型 |
| 数据 | byte[] | MapiProperty data.byte |
| stringNameId | java.lang.String | propertyString 的名称。 |

### checkBounced() {#checkBounced--}
```
public final BounceResult checkBounced()
```


检查此消息是否可以视为退回消息。

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### close() {#close--}
```
public void close()
```




### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


创建 mapi 节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 节点键。 |

**Returns:**
com.aspose.email.IMapiNode - IMapiNode 接口。
### deepClone() {#deepClone--}
```
public final MapiMessage deepClone()
```


创建当前实例的副本对象。

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A new object that is a copy of this instance.
### destroyAttachments(String path) {#destroyAttachments-java.lang.String-}
```
public static void destroyAttachments(String path)
```


销毁指定 Outlook 邮件文件中的附件。DestroyAttachments 将忽略附件解析。

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Destroy attachments from Outlook Message files
>      MapiMessage.destroyAttachment("outlookmessage.msg");
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | Outlook 邮件文件的名称。 |

### dispose() {#dispose--}
```
public void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

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
### fromFile(String path) {#fromFile-java.lang.String-}
```
public static MapiMessage fromFile(String path)
```


从指定文件创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 要加载的文件的名称。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified file.
### fromMailMessage(MailMessage message) {#fromMailMessage-com.aspose.email.MailMessage-}
```
public static MapiMessage fromMailMessage(MailMessage message)
```


从 MailMessage 创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | MailMessage。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromMailMessage(MailMessage message, MapiConversionOptions options) {#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-}
```
public static MapiMessage fromMailMessage(MailMessage message, MapiConversionOptions options)
```


从 MailMessage 创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | MailMessage。 |
| options | [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) | MapiFromMailMessageOptions [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - [MapiMessage](../../com.aspose.email/mapimessage) that represents Outlook message.
### fromMailMessage(String fileName) {#fromMailMessage-java.lang.String-}
```
public static MapiMessage fromMailMessage(String fileName)
```


从 MailMessage 创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | MailMessage 的文件名。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromProperties(MapiPropertyCollection properties) {#fromProperties-com.aspose.email.MapiPropertyCollection-}
```
public static MapiMessage fromProperties(MapiPropertyCollection properties)
```


从 Mapi 属性集合创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | MapiProperty 的集合。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified properties.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static MapiMessage fromStream(InputStream stream)
```


从指定流创建 MapiMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加载的流。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified stream.
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


获取消息中的附件。

值：附件集合。

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


包含与项目关联的计费信息。

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public final String getBody()
```


获取消息文本。

值：表示邮件正文的字符串。

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


获取消息的 BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) 并转换为 HTML，如果存在，否则返回空字符串。

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


获取或设置 RTF 格式的消息文本。

值：表示邮件正文 RTF 的字符串。

--------------------

设置值时，PR\_RTF\_COMPRESSED、PR\_RTF\_DECOMPRESSES、PR\_BODY 属性的值会被更新。被设置的字符串值必须为 RTF 格式。因此，如果需要以 HTML 格式设置值，则必须先根据 RTF 扩展规范将该值编码为 RTF。要快速以 HTML 或纯文本格式设置邮件正文内容，请使用 SetBodyContent 方法。设置 null 值或空字符串时，BodyRtf 和 Body 属性的值将被设为 null。

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


获取正文的类型。

值：正文的类型。

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


包含消息对象的关键字或类别。

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientSubmitTime() {#getClientSubmitTime--}
```
public final Date getClientSubmitTime()
```


获取或设置消息发送者提交消息的日期和时间。

值：表示客户端提交时间的 DateTime。

--------------------

如果属性不可用，将返回 DateTime.MinValue。

**Returns:**
java.util.Date
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


获取代码页。

值：代码页。

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


包含与项目关联的公司名称。

**Returns:**
java.lang.String[]
### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


获取会话线程中第一条消息的主题。

值：表示会话主题的字符串。

**Returns:**
java.lang.String
### getCustomProperties() {#getCustomProperties--}
```
public final MapiPropertyCollection getCustomProperties()
```


获取自定义 MapiProperties 的集合。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - Collection of custom MapiProperties[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection).
### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


获取或设置消息的投递日期和时间。

值：表示投递时间的 DateTime。

--------------------

如果属性不可用，将返回 DateTime.MinValue。

**Returns:**
java.util.Date
### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


获取盲目抄送 (BCC) 消息收件人的显示名称列表，使用分号 (;) 分隔。

值：表示显示密送（bcc）的字符串。

**Returns:**
java.lang.String
### getDisplayCc() {#getDisplayCc--}
```
public final String getDisplayCc()
```


获取抄送 (CC) 消息收件人的显示名称列表，使用分号 (;) 分隔。

值：表示显示抄送（cc）的字符串。

**Returns:**
java.lang.String
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取消息的显示名称。

值：表示显示名称的字符串。

**Returns:**
java.lang.String
### getDisplayNamePrefix() {#getDisplayNamePrefix--}
```
public final String getDisplayNamePrefix()
```


获取显示名称的前缀。

值：表示显示名称前缀的字符串。

**Returns:**
java.lang.String
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


获取主要 (To) 消息收件人的显示名称列表，使用分号 (;) 分隔。

值：表示显示收件人的字符串。

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final long getFlags()
```


获取消息标志。

值：消息标志。

**Returns:**
long
### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


获取传输消息头。

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


获取消息的消息 ID。

值：表示互联网消息 ID 的字符串。

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public String getItemId()
```


项目 ID，供服务器使用。

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


获取区分大小写的字符串，用于标识发送者自定义的消息类，例如 IPM.Note。消息类指定消息的类型、目的或内容。

值：表示消息类的字符串。

**Returns:**
java.lang.String
### getMessageFormat() {#getMessageFormat--}
```
public final int getMessageFormat()
```


获取 Outlook 消息格式。

值：Outlook 消息格式。

**Returns:**
int
### getMileage() {#getMileage--}
```
public final String getMileage()
```


包含与项目关联的里程信息。

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


获取消息的命名属性。

值：已命名属性的集合。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


获取命名属性映射。

值：已命名属性的映射。

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


获取消息的规范化主题。

值：表示规范化主题的字符串。

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


获取属性的集合。

值：属性。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


通过属性描述符获取 MAPI 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 已查找属性的属性描述符 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


获取由标签指定的属性值，类型为 Boolean。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Boolean - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
byte[] - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


获取由标签指定的属性值，类型为 DateTime。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | long | MAPI 属性标签。 |

**Returns:**
java.util.Date - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


获取由标签指定的属性的 int32 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Integer - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


获取由标签指定的属性值，类型为 Long（int64）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Long - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


获取由标签指定的属性值，类型为 Short。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.Short - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


获取属性流。

值：属性流。

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |

**Returns:**
java.lang.String - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


获取由标签指定的属性的字符串值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| 代码页 | int | 用于获取字符串值的指定代码页。 |

**Returns:**
java.lang.String - 属性的值。如果属性不存在，返回 NULL；否则返回该值。
### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


获取或设置指示是否请求已读回执的值。

值：如果请求已读回执，则为 true；否则为 false。

**Returns:**
boolean
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


获取消息的收件人。

值：收件人集合。

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


获取或设置回复收件人名称。

**Returns:**
java.lang.String
### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


获取消息发送者的电子邮件地址类型。

值：表示发件人地址类型的字符串。

**Returns:**
java.lang.String
### getSenderEmailAddress() {#getSenderEmailAddress--}
```
public final String getSenderEmailAddress()
```


获取或设置消息发送者的电子邮件地址。

**Returns:**
java.lang.String
### getSenderName() {#getSenderName--}
```
public final String getSenderName()
```


获取或设置消息发送者的显示名称。

值：表示发件人名称的字符串。

--------------------

当设置为 null 值或空字符串时，属性的值将等于 SenderEmailAddress。

**Returns:**
java.lang.String
### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


获取或设置消息发送者的电子邮件地址。

**Returns:**
java.lang.String
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


获取敏感度。

值：敏感度。

**Returns:**
int
### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


获取由发送者代表的消息用户的地址类型。

值：表示已发送地址类型的字符串。

**Returns:**
java.lang.String
### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


获取或设置由发送者代表的消息用户的电子邮件地址。

**Returns:**
java.lang.String
### getSentRepresentingName() {#getSentRepresentingName--}
```
public final String getSentRepresentingName()
```


获取或设置由发送者代表的消息用户的显示名称。

Value: 表示发送的名称的字符串。

--------------------

当设置为 null 值或空字符串时，属性的值会在 SentRepresentingEmailAddress 中设置。

**Returns:**
java.lang.String
### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


获取或设置由发送者代表的消息用户的电子邮件地址。

Value: 表示发送的电子邮件地址的字符串。

**Returns:**
java.lang.String
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


获取子存储。

值：子存储。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


获取或设置消息的主题。

值：表示邮件主题的字符串。

--------------------

设置值时，SubjectPrefix(PR\_SUBJECT\_PREFIX) 和 NormalizedSubject(PR\_NORMALIZED\_SUBJECT) 属性的值也会被更新。如果 Subject 没有前缀，则 SubjectPrefix 属性的值设为 null。设置 null 值或空字符串时，Subject、SubjectPrefix、NormalizedSubject 属性的值均设为 null。

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


获取主题前缀，通常指示对消息的某种操作，例如转发时的 "FW: "。

值：表示主题前缀的字符串。

**Returns:**
java.lang.String
### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


获取特定传输的消息信封信息。

Value: 表示传输消息标头的字符串。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMsgFormat(InputStream stream) {#isMsgFormat-java.io.InputStream-}
```
public static boolean isMsgFormat(InputStream stream)
```


确定指定的流是否为 MSG 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 消息流。 |

**Returns:**
boolean -  true  如果流以 MSG 格式表示]; 否则为 false 。
### isMsgFormat(String fileName) {#isMsgFormat-java.lang.String-}
```
public static boolean isMsgFormat(String fileName)
```


确定指定的文件是否为 MSG 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

**Returns:**
boolean -  true  如果文件以 MSG 格式表示; 否则为 false 。
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


确定字符串属性是否为 Unicode 编码。

**Returns:**
布尔型 - 如果字符串属性为 Unicode 编码，则为 True。
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiMessage load(InputStream stream)
```


从流加载消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流 java.io.InputStream。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(InputStream stream, LoadOptions options)
```


使用附加选项从流加载消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流 java.io.InputStream。 |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | 附加选项 [LoadOptions](../../com.aspose.email/loadoptions)。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(String fileName) {#load-java.lang.String-}
```
public static MapiMessage load(String fileName)
```


从文件加载消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 源文件路径字符串。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(String fileName, LoadOptions options)
```


从文件加载消息并使用附加选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 源文件路径字符串。 |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | 附加选项 [LoadOptions](../../com.aspose.email/loadoptions)。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### loadFromTnef(InputStream stream) {#loadFromTnef-java.io.InputStream-}
```
public static MapiMessage loadFromTnef(InputStream stream)
```


从传输中立封装格式 (TNEF) 数据结构加载消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 以 TNEF 格式表示消息数据的流 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### loadFromTnef(String fileName) {#loadFromTnef-java.lang.String-}
```
public static MapiMessage loadFromTnef(String fileName)
```


从传输中立封装格式 (TNEF) 数据结构加载消息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 包含 TNEF 格式消息数据的文件名 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAttachments(String path) {#removeAttachments-java.lang.String-}
```
public static MapiAttachmentCollection removeAttachments(String path)
```


从指定的 Outlook 消息文件中删除所有附件。

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Remove attachments from Outlook Message files
>      MapiAttachmentCollection attachments = MapiMessage.removeAttachments("outlookmessage.msg");
> 
>      //Attachments
>      for(MapiAttachment att : attachments)
>      {
>         System.out.print("Attachment Name:"+att.getFileName());
>         att.save(att.getFileName());
>      }
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | Outlook 邮件文件的名称。 |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments collection.
### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


正确地从所有集合中移除属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MapiProperty 的标签。 |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


将消息保存为 Msg 到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 流。 |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public final void save(OutputStream stream, SaveOptions options)
```


将消息保存为流并使用附加选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 保存消息的流。 |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | 用于保存的附加选项[SaveOptions](../../com.aspose.email/saveoptions)。 |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


将消息保存为 Msg 到指定的文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public final void save(String fileName, SaveOptions options)
```


将消息保存为文件并使用附加选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 保存消息的流。 |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | 用于保存的附加选项[SaveOptions](../../com.aspose.email/saveoptions)。 |

### saveAsTemplate(OutputStream stream) {#saveAsTemplate-java.io.OutputStream-}
```
public final void saveAsTemplate(OutputStream stream)
```


将 Outlook 文件模板 (OFT 格式) 保存到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 流。 |

### saveAsTemplate(String fileName) {#saveAsTemplate-java.lang.String-}
```
public final void saveAsTemplate(String fileName)
```


将 Outlook 文件模板 (OFT 格式) 保存到指定的文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### saveAsTnef(OutputStream stream) {#saveAsTnef-java.io.OutputStream-}
```
public final void saveAsTnef(OutputStream stream)
```


以 TNEF 格式保存消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 消息将被保存到的流。 |

### saveAsTnef(String fileName) {#saveAsTnef-java.lang.String-}
```
public final void saveAsTnef(String fileName)
```


以 TNEF 格式保存消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 消息将被保存到的文件名。 |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


包含与项目关联的计费信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


获取消息文本。

值：表示邮件正文的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


设置正文的内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 内容。 |
|  | contentType | int | 内容的类型。 |

--------------------

用于在 RTF、HTML 或纯文本格式下设置正文消息的内容。设置值时，PR\_RTF\_COMPRESSED、PR\_RTF\_DECOMPRESSES、PR\_BODY 属性的值也会被更新。注意，在设置 HTML 格式的值后，BodyRtf 属性返回的是在 RTF 中编码的值。 |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


设置正文的内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | java.lang.String | 内容。 |
| contentType | int | 内容的类型。 |
|  | compression | boolean | 指定内容应被压缩。 |

--------------------

用于在 RTF、HTML 或纯文本格式下设置正文消息的内容。设置值时，PR\_RTF\_COMPRESSED、PR\_RTF\_DECOMPRESSES、PR\_BODY 属性的值也会被更新。注意，在设置 HTML 格式的值后，BodyRtf 属性返回的是在 RTF 中编码的值。 |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


获取或设置 RTF 格式的消息文本。

值：表示邮件正文 RTF 的字符串。

--------------------

设置值时，PR\_RTF\_COMPRESSED、PR\_RTF\_DECOMPRESSES、PR\_BODY 属性的值会被更新。被设置的字符串值必须为 RTF 格式。因此，如果需要以 HTML 格式设置值，则必须先根据 RTF 扩展规范将该值编码为 RTF。要快速以 HTML 或纯文本格式设置邮件正文内容，请使用 SetBodyContent 方法。设置 null 值或空字符串时，BodyRtf 和 Body 属性的值将被设为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


获取或设置 RTF 格式的消息文本。

值：表示邮件正文 RTF 的字符串。

--------------------

设置值时，PR\_RTF\_COMPRESSED、PR\_RTF\_DECOMPRESSES、PR\_BODY 属性的值会被更新。被设置的字符串值必须为 RTF 格式。因此，如果需要以 HTML 格式设置值，则必须先根据 RTF 扩展规范将该值编码为 RTF。要快速以 HTML 或纯文本格式设置邮件正文内容，请使用 SetBodyContent 方法。设置 null 值或空字符串时，BodyRtf 和 Body 属性的值将被设为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | 指定内容应被压缩。 |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


包含消息对象的关键字或类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setClientSubmitTime(Date value) {#setClientSubmitTime-java.util.Date-}
```
public final void setClientSubmitTime(Date value)
```


获取或设置消息发送者提交消息的日期和时间。

值：表示客户端提交时间的 DateTime。

--------------------

如果属性不可用，将返回 DateTime.MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


包含与项目关联的公司名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDeliveryTime(Date value) {#setDeliveryTime-java.util.Date-}
```
public final void setDeliveryTime(Date value)
```


获取或设置消息的投递日期和时间。

值：表示投递时间的 DateTime。

--------------------

如果属性不可用，将返回 DateTime.MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setHeaders(HeaderCollection value) {#setHeaders-com.aspose.email.HeaderCollection-}
```
public final void setHeaders(HeaderCollection value)
```


获取传输消息头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HeaderCollection](../../com.aspose.email/headercollection) |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


获取区分大小写的字符串，用于标识发送者自定义的消息类，例如 IPM.Note。消息类指定消息的类型、目的或内容。

值：表示消息类的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


设置消息标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flags | long | 消息标志。 |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


包含与项目关联的里程信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


设置已命名属性的映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | 该 MapiNamedPropertyMappingStorage。 |

### setProperty(MapiAttachment value, long signed, long key) {#setProperty-com.aspose.email.MapiAttachment-long-long-}
```
public void setProperty(MapiAttachment value, long signed, long key)
```


设置附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiAttachment](../../com.aspose.email/mapiattachment) | 属性值。 |
| 已签名 | long | 指示属性已签名的值。 |
| 键 | long | 属性标签。 |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


设置属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性。 |

### setProperty(MapiRecipient value, long signed, long key) {#setProperty-com.aspose.email.MapiRecipient-long-long-}
```
public void setProperty(MapiRecipient value, long signed, long key)
```


设置收件人。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiRecipient](../../com.aspose.email/mapirecipient) | 属性值。 |
| 已签名 | long | 指示属性已签名的值。 |
| 键 | long | 属性标签。 |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


设置 MAPI 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | 属性描述符。 |
| value | java.lang.Object | 属性数据。 |

### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


获取或设置指示是否请求已读回执的值。

值：如果请求已读回执，则为 true；否则为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


获取消息的收件人。

值：收件人集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


获取或设置回复收件人名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderEmailAddress(String value) {#setSenderEmailAddress-java.lang.String-}
```
public final void setSenderEmailAddress(String value)
```


获取或设置消息发送者的电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderName(String value) {#setSenderName-java.lang.String-}
```
public final void setSenderName(String value)
```


获取或设置消息发送者的显示名称。

值：表示发件人名称的字符串。

--------------------

当设置为 null 值或空字符串时，属性的值将等于 SenderEmailAddress。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


获取或设置消息发送者的电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


获取敏感度。

值：敏感度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


获取或设置由发送者代表的消息用户的电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSentRepresentingName(String value) {#setSentRepresentingName-java.lang.String-}
```
public final void setSentRepresentingName(String value)
```


获取或设置由发送者代表的消息用户的显示名称。

Value: 表示发送的名称的字符串。

--------------------

当设置为 null 值或空字符串时，属性的值会在 SentRepresentingEmailAddress 中设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setStringPropertyValue(long tag, String value) {#setStringPropertyValue-long-java.lang.String-}
```
public final void setStringPropertyValue(long tag, String value)
```


设置字符串属性值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签。 |
| value | java.lang.String | 属性值。 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


获取或设置消息的主题。

值：表示邮件主题的字符串。

--------------------

设置值时，SubjectPrefix(PR\_SUBJECT\_PREFIX) 和 NormalizedSubject(PR\_NORMALIZED\_SUBJECT) 属性的值也会被更新。如果 Subject 没有前缀，则 SubjectPrefix 属性的值设为 null。设置 null 值或空字符串时，Subject、SubjectPrefix、NormalizedSubject 属性的值均设为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toMailMessage(MailConversionOptions options) {#toMailMessage-com.aspose.email.MailConversionOptions-}
```
public final MailMessage toMailMessage(MailConversionOptions options)
```


从此 MapiMessage 创建 MailMessage 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [MailConversionOptions](../../com.aspose.email/mailconversionoptions) | 在从 MapiMessage 转换为 MailMessage 时允许指定其他选项。 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Returns a MailMessage instance which is loaded from this MapiMessage.
### toMapiMessageItem() {#toMapiMessageItem--}
```
public final IMapiMessageItem toMapiMessageItem()
```


根据 MessageClass 将 MapiMessage 转换为 IMapiMessageItem 对象。

**Returns:**
[IMapiMessageItem](../../com.aspose.email/imapimessageitem) - The IMapiMessageItem interface.
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


尝试使用指定的标签键获取属性数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 标签键。 |

**Returns:**
byte[] - 属性数据。
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


获取指定属性的值，类型为 DateTime。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.util.Date[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


获取指定属性的值，类型为 Int32。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | int[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


获取指定属性的值，类型为 Long。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | long[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


尝试使用指定的标签获取属性数据为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签键。 |

**Returns:**
java.lang.String - 包含属性数据内容的字符串。
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


尝试使用指定的标签和代码页获取属性数据为字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | 属性标签键。 |
| 代码页 | int | 代码页。 |

**Returns:**
java.lang.String - 包含属性数据内容的字符串。
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


获取指定属性的值，类型为 String。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.lang.String[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


获取指定属性的值，类型为 String。返回值指示操作是否成功。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MAPI 属性标签。 |
| value | java.lang.String[] | 当此方法返回时，如果属性存在，则包含指定属性的值。此参数以未初始化的形式传递。 |
| 代码页 | int | 用于获取字符串值的指定代码页。 |

**Returns:**
boolean - 如果 s 转换成功则为 true；否则为 false。
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

