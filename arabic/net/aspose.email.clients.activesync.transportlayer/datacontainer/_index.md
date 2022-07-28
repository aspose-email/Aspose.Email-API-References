---
title: DataContainer
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحتوي على بيانات لكائن معين  مثل جهة اتصال أو رسالة بريد إلكتروني أو موعد تقويم أو عنصر مهمة. يمكن استخدام DataContainer لتغيير العناصر أو إضافة عناصر أو جلب العناصر على جهاز العميل أو الخادم.
type: docs
weight: 1150
url: /ar/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

يحتوي على بيانات لكائن معين ، مثل جهة اتصال أو رسالة بريد إلكتروني أو موعد تقويم أو عنصر مهمة. يمكن استخدام DataContainer لتغيير العناصر أو إضافة عناصر أو جلب العناصر على جهاز العميل أو الخادم.

```csharp
public class DataContainer : IEnumerable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | تهيئة مثيل جديد لفئة DataContainer. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | تهيئة مثيل جديد لفئة DataContainer. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | تهيئة مثيل جديد لفئة DataContainer. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | تهيئة مثيل جديد لفئة DataContainer. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | تحديد ما إذا كانت البيانات ثنائية. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | اسم العنصر ، الذي توجد بياناته في حاوية البيانات. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | يحصل على DataContainer للعنصر المحدد إذا كانت كمية DataContainers أكثر من واحدة ، يرتفع AsposeException . (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | مساحة الاسم للعنصر ، التي ترد بياناتها في حاوية البيانات. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | حاوية البيانات الأصل |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | بادئة في عقدة xml للعنصر |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | نسخ العناصر الفرعية لبيانات التطبيق إلى قائمة جديدة. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | قيمة العنصر |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | يضيف بيانات عنصر بتنسيق xml إلى DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | يضيف بيانات عنصر بتنسيق xml إلى DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | يضيف DataContainer فارغًا للعنصر. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | إضافة بيانات عنصر إلى DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | إضافة بيانات عنصر إلى DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | يحصل على قائمة بحاويات البيانات للعنصر المحدد |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
