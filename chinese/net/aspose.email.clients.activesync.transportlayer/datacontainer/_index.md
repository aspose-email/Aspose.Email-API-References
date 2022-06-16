---
title: DataContainer
second_title: Aspose.Email for .NET API 参考
description: 包含特定对象的数据例如联系人电子邮件日历约会或任务项 DataContainer 可用于在客户端设备或服务器上更改项目添加项目或获取项目
type: docs
weight: 1150
url: /zh/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

包含特定对象的数据，例如联系人、电子邮件、日历约会或任务项。 DataContainer 可用于在客户端设备或服务器上更改项目、添加项目或获取项目。

```csharp
public class DataContainer : IEnumerable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | 初始化 DataContainer 类的新实例。 |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | 初始化 DataContainer 类的新实例。 |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | 初始化 DataContainer 类的新实例。 |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | 初始化 DataContainer 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | 指定数据是否为二进制。 |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | 元素的名称，其数据包含在数据容器中。 |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | 获取所选元素的 DataContainer 如果 DataContainers 的数量多于一个，则 AsposeException 上升。 (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | 元素的命名空间，其数据包含在数据容器中。 |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | 父数据容器 |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | xml 节点中元素 |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | 将 ApplicationData 的子元素复制到新列表。 |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | 元素的值 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | 将xml格式的元素数据添加到DataContainer。 |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | 将xml格式的元素数据添加到DataContainer。 |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | 为元素添加空 DataContainer。 |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | 将元素的数据添加到 DataContainer。 |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | 将元素的数据添加到 DataContainer。 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | 获取选定元素的 DataContainers 列表 |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | 获取选定元素的 DataContainers 列表 |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | 返回一个遍历集合的枚举器。 |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | 返回代表当前对象的字符串。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
