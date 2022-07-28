---
title: AddMessageFlagsAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يضيف أعلام الرسالة
type: docs
weight: 350
url: /ar/net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## AddMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_35}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_27}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_7}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_54}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_34}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_26}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_6}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_47}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_43}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_19}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_15}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_46}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_42}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_18}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_14}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_39}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_11}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_38}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_10}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#addmessageflagsasync}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#addmessageflagsasync_20}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags) {#addmessageflagsasync_28}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags) {#addmessageflagsasync_48}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#addmessageflagsasync_1}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#addmessageflagsasync_21}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long) {#addmessageflagsasync_29}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long) {#addmessageflagsasync_49}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags) {#addmessageflagsasync_52}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags) {#addmessageflagsasync_32}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#addmessageflagsasync_24}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#addmessageflagsasync_4}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long) {#addmessageflagsasync_53}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long) {#addmessageflagsasync_33}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#addmessageflagsasync_25}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#addmessageflagsasync_5}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_44}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_40}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_16}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_12}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_45}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_41}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_17}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_13}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| flags | ImapMessageFlags | الأعلام المراد إزالتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_36}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_8}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_37}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_9}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_3}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_23}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_31}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_51}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_2}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_22}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_30}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceNumber | Int32 | الرقم التسلسلي للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_50}

يضيف الإشارات إلى الرسالة

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف فريد للرسالة |
| flags | ImapMessageFlags | الأعلام المراد إضافتها |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_55}

يضيف أعلام الرسالة

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| flags | ImapMessageFlags | الأعلام المراد تغييرها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
