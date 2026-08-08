---
title: MapiTask
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Outlook 任务对象。
type: docs
weight: 284
url: /zh/androidjava/com.aspose.email/mapitask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public class MapiTask extends MapiMessageItemBase
```

表示 Outlook 任务对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiTask()](#MapiTask--) | 初始化 [MapiTask](../../com.aspose.email/mapitask) 类的新实例。 |
| [MapiTask(String subject, String body, Date startDate, Date dueDate)](#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | 初始化 [MapiTask](../../com.aspose.email/mapitask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | 创建 mapi 节点。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVTodo(InputStream stream)](#fromVTodo-java.io.InputStream-) | 从指定的流创建 MapiTask 的实例。 |
| [fromVTodo(InputStream stream, boolean detectEncoding)](#fromVTodo-java.io.InputStream-boolean-) | 从指定的流创建 MapiTask 的实例。 |
| [fromVTodo(String filePath)](#fromVTodo-java.lang.String-) | 从指定的 .ics 文件创建一个 MapiTask 实例。 |
| [fromVTodo(String filePath, boolean detectEncoding)](#fromVTodo-java.lang.String-boolean-) | 从指定的 .ics 文件创建一个 MapiTask 实例。 |
| [getAcceptanceState()](#getAcceptanceState--) | 获取或设置任务的接受状态。 |
| [getActualEffort()](#getActualEffort--) | 获取或设置用户实际在任务上花费的分钟数。 |
| [getAttachments()](#getAttachments--) | 获取消息中的附件。 |
| [getBilling()](#getBilling--) | 包含与项目关联的计费信息。 |
| [getBody()](#getBody--) | 获取消息文本。 |
| [getBodyHtml()](#getBodyHtml--) | 获取消息的 BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) 并转换为 HTML，如果存在，否则返回空字符串。 |
| [getBodyRtf()](#getBodyRtf--) | 获取或设置 RTF 格式的消息文本。 |
| [getBodyType()](#getBodyType--) | 获取正文的类型。 |
| [getCategories()](#getCategories--) | 包含消息对象的关键字或类别。 |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | 获取代码页。 |
| [getCompanies()](#getCompanies--) | 包含与项目关联的公司名称。 |
| [getDateCompleted()](#getDateCompleted--) | 获取或设置用户完成任务工作的日期。 |
| [getDueDate()](#getDueDate--) | 获取或设置用户期望完成任务工作的日期。 |
| [getEstimatedEffort()](#getEstimatedEffort--) | 获取或设置用户期望在任务上工作的分钟数。 |
| [getFlags()](#getFlags--) | 获取 Task 对象的指示标志。 |
| [getHistory()](#getHistory--) | 获取或设置对 Task 对象最近一次所做更改的类型。 |
| [getItemId()](#getItemId--) | 项目 ID，供服务器使用。 |
| [getLastUpdate()](#getLastUpdate--) | 获取或设置对 Task 对象最近一次更改的日期和时间。 |
| [getMessageClass()](#getMessageClass--) | 获取区分大小写的字符串，以标识发送者定义的消息类，例如 IPM.Note。 |
| [getMileage()](#getMileage--) | 包含与项目关联的里程信息。 |
| [getMode()](#getMode--) | 获取或设置 Task 对象的分配状态。 |
| [getNamedProperties()](#getNamedProperties--) | 获取消息的命名属性。 |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | 获取命名属性映射。 |
| [getPercentComplete()](#getPercentComplete--) | 获取或设置用户在任务上取得的进度。 |
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
| [getRecipients()](#getRecipients--) | 获取消息的收件人。 |
| [getRecurrence()](#getRecurrence--) | 获取或设置重复属性。 |
| [getReminderFileParameter()](#getReminderFileParameter--) | 指定当提醒逾期时客户端应播放的声音的完整路径。 |
| [getReminderSet()](#getReminderSet--) | 获取或设置一个值，指示对象上是否设置了提醒。 |
| [getReminderTime()](#getReminderTime--) | 获取或设置提醒的初始触发时间。 |
| [getSensitivity()](#getSensitivity--) | 获取敏感度。 |
| [getStartDate()](#getStartDate--) | 获取或设置用户期望任务开始工作的日期。 |
| [getState()](#getState--) | 获取或设置 Task 对象的当前分配状态。 |
| [getStatus()](#getStatus--) | 获取或设置用户在任务上的进度状态。 |
| [getSubStorages()](#getSubStorages--) | 获取子存储。 |
| [getSubject()](#getSubject--) | 获取或设置消息的主题。 |
| [getSubjectPrefix()](#getSubjectPrefix--) | 获取主题前缀，通常指示对消息的某种操作，例如转发时的 "FW: "。 |
| [getUsers()](#getUsers--) | 获取或设置任务用户的信息。 |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | 确定字符串属性是否为 Unicode 编码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | 正确地从所有集合中移除属性。 |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | 使用指定的格式将此 [MapiTask](../../com.aspose.email/mapitask) 保存到给定的流中。 |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | 使用指定的格式将此 [MapiTask](../../com.aspose.email/mapitask) 保存到文件中。 |
| [setAcceptanceState(int value)](#setAcceptanceState-int-) | 获取或设置任务的接受状态。 |
| [setActualEffort(int value)](#setActualEffort-int-) | 获取或设置用户实际在任务上花费的分钟数。 |
| [setBilling(String value)](#setBilling-java.lang.String-) | 包含与项目关联的计费信息。 |
| [setBody(String value)](#setBody-java.lang.String-) | 获取消息文本。 |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | 设置正文的内容。 |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | 设置正文的内容。 |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | 获取或设置 RTF 格式的消息文本。 |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | 获取或设置 RTF 格式的消息文本。 |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | 包含消息对象的关键字或类别。 |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | 包含与项目关联的公司名称。 |
| [setDateCompleted(Date value)](#setDateCompleted-java.util.Date-) | 获取或设置用户完成任务工作的日期。 |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | 获取或设置用户期望完成任务工作的日期。 |
| [setEstimatedEffort(int value)](#setEstimatedEffort-int-) | 获取或设置用户期望在任务上工作的分钟数。 |
| [setHistory(int value)](#setHistory-int-) | 获取或设置对 Task 对象最近一次所做更改的类型。 |
| [setLastUpdate(Date value)](#setLastUpdate-java.util.Date-) | 获取或设置对 Task 对象最近一次更改的日期和时间。 |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | 获取区分大小写的字符串，以标识发送者定义的消息类，例如 IPM.Note。 |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | 设置消息标志。 |
| [setMileage(String value)](#setMileage-java.lang.String-) | 包含与项目关联的里程信息。 |
| [setMode(int value)](#setMode-int-) | 获取或设置 Task 对象的分配状态。 |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | 设置已命名属性的映射。 |
| [setPercentComplete(int value)](#setPercentComplete-int-) | 获取或设置用户在任务上取得的进度。 |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | 设置属性。 |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | 设置 MAPI 属性。 |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | 获取消息的收件人。 |
| [setRecurrence(MapiCalendarRecurrencePattern value)](#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-) | 获取或设置重复属性。 |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | 指定当提醒逾期时客户端应播放的声音的完整路径。 |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | 获取或设置一个值，指示对象上是否设置了提醒。 |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | 获取或设置提醒的初始触发时间。 |
| [setSensitivity(int value)](#setSensitivity-int-) | 获取敏感度。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 获取或设置用户期望任务开始工作的日期。 |
| [setState(int value)](#setState-int-) | 获取或设置 Task 对象的当前分配状态。 |
| [setStatus(int value)](#setStatus-int-) | 获取或设置用户在任务上的进度状态。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 获取或设置消息的主题。 |
| [setUsers(MapiTaskUsers value)](#setUsers-com.aspose.email.MapiTaskUsers-) | 获取或设置任务用户的信息。 |
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
### MapiTask() {#MapiTask--}
```
public MapiTask()
```


初始化 [MapiTask](../../com.aspose.email/mapitask) 类的新实例。

### MapiTask(String subject, String body, Date startDate, Date dueDate) {#MapiTask-java.lang.String-java.lang.String-java.util.Date-java.util.Date-}
```
public MapiTask(String subject, String body, Date startDate, Date dueDate)
```


初始化 [MapiTask](../../com.aspose.email/mapitask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 主题 | java.lang.String | 主题。 |
| 正文 | java.lang.String | 消息正文。 |
| startDate | java.util.Date | 开始日期。 |
| dueDate | java.util.Date | 截止日期。 |

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
### fromVTodo(InputStream stream) {#fromVTodo-java.io.InputStream-}
```
public static MapiTask fromVTodo(InputStream stream)
```


从指定的流创建 MapiTask 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加载的流。 |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified stream.
### fromVTodo(InputStream stream, boolean detectEncoding) {#fromVTodo-java.io.InputStream-boolean-}
```
public static MapiTask fromVTodo(InputStream stream, boolean detectEncoding)
```


从指定的流创建 MapiTask 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加载的流。 |
| detectEncoding | boolean | 通过分析其字节顺序标记 (BOM) 来确定数据编码 |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified stream.
### fromVTodo(String filePath) {#fromVTodo-java.lang.String-}
```
public static MapiTask fromVTodo(String filePath)
```


从指定的 .ics 文件创建一个 MapiTask 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要加载的文件路径。 |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified file.
### fromVTodo(String filePath, boolean detectEncoding) {#fromVTodo-java.lang.String-boolean-}
```
public static MapiTask fromVTodo(String filePath, boolean detectEncoding)
```


从指定的 .ics 文件创建一个 MapiTask 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要加载的文件路径。 |
| detectEncoding | boolean | 通过分析其字节顺序标记 (BOM) 来确定数据编码 |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - Returns a MapiTask instance which is loaded from the specified file.
### getAcceptanceState() {#getAcceptanceState--}
```
public final int getAcceptanceState()
```


获取或设置任务的接受状态。

**Returns:**
int
### getActualEffort() {#getActualEffort--}
```
public final int getActualEffort()
```


获取或设置用户实际在任务上花费的分钟数。

**Returns:**
int
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
public String getBody()
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
### getDateCompleted() {#getDateCompleted--}
```
public final Date getDateCompleted()
```


获取或设置用户完成任务工作的日期。

**Returns:**
java.util.Date
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


获取或设置用户期望完成任务工作的日期。

**Returns:**
java.util.Date
### getEstimatedEffort() {#getEstimatedEffort--}
```
public final int getEstimatedEffort()
```


获取或设置用户期望在任务上工作的分钟数。

**Returns:**
int
### getFlags() {#getFlags--}
```
public final int getFlags()
```


获取 Task 对象的指示标志。

**Returns:**
int
### getHistory() {#getHistory--}
```
public final int getHistory()
```


获取或设置对 Task 对象最近一次所做更改的类型。

**Returns:**
int
### getItemId() {#getItemId--}
```
public String getItemId()
```


项目 ID，供服务器使用。

**Returns:**
java.lang.String
### getLastUpdate() {#getLastUpdate--}
```
public final Date getLastUpdate()
```


获取或设置对 Task 对象最近一次更改的日期和时间。

**Returns:**
java.util.Date
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


获取区分大小写的字符串，用于标识发送者自定义的消息类，例如 IPM.Note。消息类指定消息的类型、目的或内容。

值：表示消息类的字符串。

**Returns:**
java.lang.String
### getMileage() {#getMileage--}
```
public final String getMileage()
```


包含与项目关联的里程信息。

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public final int getMode()
```


获取或设置 Task 对象的分配状态。

**Returns:**
int
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
### getPercentComplete() {#getPercentComplete--}
```
public final int getPercentComplete()
```


获取或设置用户在任务上取得的进度。

**Returns:**
int
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
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


获取消息的收件人。

值：收件人集合。

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarRecurrencePattern getRecurrence()
```


获取或设置重复属性。

**Returns:**
[MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


指定当提醒逾期时客户端应播放的声音的完整路径。

**Returns:**
java.lang.String
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


获取或设置一个值，指示对象上是否设置了提醒。

**Returns:**
boolean
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


获取或设置提醒的初始触发时间。

**Returns:**
java.util.Date
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


获取敏感度。

值：敏感度。

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


获取或设置用户期望任务开始工作的日期。

**Returns:**
java.util.Date
### getState() {#getState--}
```
public final int getState()
```


获取或设置 Task 对象的当前分配状态。

**Returns:**
int
### getStatus() {#getStatus--}
```
public final int getStatus()
```


获取或设置用户在任务上的进度状态。

**Returns:**
int
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
### getUsers() {#getUsers--}
```
public final MapiTaskUsers getUsers()
```


获取或设置任务用户的信息。

**Returns:**
[MapiTaskUsers](../../com.aspose.email/mapitaskusers)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


确定字符串属性是否为 Unicode 编码。

**Returns:**
布尔型 - 如果字符串属性为 Unicode 编码，则为 True。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


正确地从所有集合中移除属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tag | long | MapiProperty 的标签。 |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


使用指定的格式将此 [MapiTask](../../com.aspose.email/mapitask) 保存到给定的流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveFormat | int |  |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


使用指定的格式将此 [MapiTask](../../com.aspose.email/mapitask) 保存到文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveFormat | int |  |

### setAcceptanceState(int value) {#setAcceptanceState-int-}
```
public final void setAcceptanceState(int value)
```


获取或设置任务的接受状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setActualEffort(int value) {#setActualEffort-int-}
```
public final void setActualEffort(int value)
```


获取或设置用户实际在任务上花费的分钟数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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
public void setBody(String value)
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

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


包含与项目关联的公司名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDateCompleted(Date value) {#setDateCompleted-java.util.Date-}
```
public final void setDateCompleted(Date value)
```


获取或设置用户完成任务工作的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


获取或设置用户期望完成任务工作的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setEstimatedEffort(int value) {#setEstimatedEffort-int-}
```
public final void setEstimatedEffort(int value)
```


获取或设置用户期望在任务上工作的分钟数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setHistory(int value) {#setHistory-int-}
```
public final void setHistory(int value)
```


获取或设置对 Task 对象最近一次所做更改的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setLastUpdate(Date value) {#setLastUpdate-java.util.Date-}
```
public final void setLastUpdate(Date value)
```


获取或设置对 Task 对象最近一次更改的日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

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

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


获取或设置 Task 对象的分配状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


设置已命名属性的映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | 该 MapiNamedPropertyMappingStorage。 |

### setPercentComplete(int value) {#setPercentComplete-int-}
```
public final void setPercentComplete(int value)
```


获取或设置用户在任务上取得的进度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


设置属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | 属性。 |

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

### setRecurrence(MapiCalendarRecurrencePattern value) {#setRecurrence-com.aspose.email.MapiCalendarRecurrencePattern-}
```
public final void setRecurrence(MapiCalendarRecurrencePattern value)
```


获取或设置重复属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern) |  |

### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


指定当提醒逾期时客户端应播放的声音的完整路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


获取或设置一个值，指示对象上是否设置了提醒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


获取或设置提醒的初始触发时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

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

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


获取或设置用户期望任务开始工作的日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setState(int value) {#setState-int-}
```
public final void setState(int value)
```


获取或设置 Task 对象的当前分配状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


获取或设置用户在任务上的进度状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

### setUsers(MapiTaskUsers value) {#setUsers-com.aspose.email.MapiTaskUsers-}
```
public final void setUsers(MapiTaskUsers value)
```


获取或设置任务用户的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MapiTaskUsers](../../com.aspose.email/mapitaskusers) |  |

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

