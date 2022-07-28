---
title: MeetingResponse
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم.
type: docs
weight: 110
url: /ar/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| userResponse | UserResponse | يشير إلى ما إذا كان الاجتماع قد تم قبوله أو قبوله مبدئيًا أو رفضه. |
| collectionId | String | يحدد المجلد الذي يحتوي على طلب الاجتماع. اختياري إذا تم تضمين LongId . يمكن أن يصل طول قيمة CollectionId إلى 64 حرفًا . |
| requestId | String | يحدد معرف الخادم لعنصر رسالة طلب الاجتماع. اختياري إذا تم تضمين LongId . يمكن أن تصل قيمة معرف الطلب إلى 64 حرفًا . |

### قيمة الإرجاع

إرجاع كائن MeetingResponseResult.

### أنظر أيضا

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| userResponse | UserResponse | يشير إلى ما إذا كان الاجتماع قد تم قبوله أو قبوله مبدئيًا أو رفضه. |
| collectionId | String | يحدد المجلد الذي يحتوي على طلب الاجتماع. اختياري إذا تم تضمين LongId . يمكن أن يصل طول قيمة CollectionId إلى 64 حرفًا . |
| requestId | String | يحدد معرف الخادم لعنصر رسالة طلب الاجتماع. اختياري إذا تم تضمين LongId . يمكن أن تصل قيمة معرف الطلب إلى 64 حرفًا . |
| longId | String | يحدد المعرف الطويل لطلب الاجتماع المصدر ، والذي يتم إرجاعه في رسالة استجابة أمر البحث. إذا كان LongId موجودًا ، فلن يكون CollectionId و InstanceId و RequestId موجودًا. يمكن أن يصل طول قيمة LongId إلى 256 حرفًا . |
| instanceId | String | يحدد مثيل الاجتماع المتكرر المراد تعديله. لا يتم دعم InstanceId عندما يكون إصدار البروتوكول هو 12.1 أو 14.0. يتم إرجاع قيمة الحالة 2 إذا تم تضمين عنصر InstanceId في الطلبات التي يكون فيها إصدار البروتوكول هو 12.1 أو 14.0. يحتوي InstanceId على وقت بدء الموعد أو مثيل الاجتماع المطلوب تعديله. إذا لم يتم تضمين InstanceId في طلب MeetingResponse ، فيجب اتخاذ الإجراء على كل مثيل للعنصر المتكرر. يمكن لـ InstanceId تحديد وقت بدء استثناء لموعد أو اجتماع متكرر. يمكن استخدام InstanceId مع LongId لتحديد عنصر تقويم ، أو يمكن استخدامه مع CollectionId و RequestId لتحديد عنصر تقويم. مثال ، 2010-04-08T18: 16: 00.000Z. إذا كانت قيمة InstanceId المحددة ليست بالتنسيق الصحيح ، يستجيب الخادم بقيمة عنصر الحالة 104. إذا كانت قيمة InstanceId تحدد اجتماعًا غير متكرر ، يستجيب الخادم بقيمة عنصر الحالة 146. |

### قيمة الإرجاع

إرجاع كائن MeetingResponseResult.

### أنظر أيضا

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| request | MeetingResponseRequest[] | صفيف من كائنات MeetingResponseRequest |

### قيمة الإرجاع

إرجاع صفيف من كائنات MeetingResponseResult.

### أنظر أيضا

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| request | IEnumerable`1 | تعداد كائنات MeetingResponseRequest |

### قيمة الإرجاع

إرجاع صفيف من كائنات MeetingResponseResult.

### أنظر أيضا

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
