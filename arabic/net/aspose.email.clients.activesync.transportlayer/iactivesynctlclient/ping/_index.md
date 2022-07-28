---
title: Ping
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.
type: docs
weight: 140
url: /ar/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| serverId | String | عنصر المعرف هو عنصر فرعي مطلوب لعنصر المجلد في طلبات الأمر Ping التي تحدد معرف الخادم للمجلد المراد مراقبته. |
| fClass | FolderClass | عنصر الفئة هو عنصر فرعي مطلوب لعنصر المجلد في طلبات الأمر Ping التي تحدد فئة المحتوى للمجلد المراد مراقبته. |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| heartbeatInterval | Int32 | يحدد HeartbeatInterval طول الوقت ، بالثواني ، الذي يجب أن ينتظره الخادم قبل إرسال استجابة إذا لم تتم إضافة عناصر جديدة إلى مجموعة المجلدات المحددة. |
| serverId | String | عنصر المعرف هو عنصر فرعي مطلوب لعنصر المجلد في طلبات الأمر Ping التي تحدد معرف الخادم للمجلد المراد مراقبته. |
| fClass | FolderClass | عنصر الفئة هو عنصر فرعي مطلوب لعنصر المجلد في طلبات الأمر Ping التي تحدد فئة المحتوى للمجلد المراد مراقبته. |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pingParameters | PingParameter[] | معلمات بينغ |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| heartbeatInterval | Int32 | يحدد HeartbeatInterval طول الوقت ، بالثواني ، الذي يجب أن ينتظره الخادم قبل إرسال استجابة إذا لم تتم إضافة عناصر جديدة إلى مجموعة المجلدات المحددة. |
| pingParameters | PingParameter[] | معلمات بينغ |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | معلمات بينغ |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| heartbeatInterval | Int32 | يحدد HeartbeatInterval طول الوقت ، بالثواني ، الذي يجب أن ينتظره الخادم قبل إرسال استجابة إذا لم تتم إضافة عناصر جديدة إلى مجموعة المجلدات المحددة. |
| pingParameters | IEnumerable`1 | معلمات بينغ |

### قيمة الإرجاع

صفيف من المجلدات حيث تم اكتشاف التغييرات

### أنظر أيضا

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
