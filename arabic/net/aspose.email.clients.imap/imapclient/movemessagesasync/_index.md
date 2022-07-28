---
title: MoveMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: نقل الرسالة
type: docs
weight: 960
url: /ar/net/aspose.email.clients.imap/imapclient/movemessagesasync/
---
## MoveMessagesAsync(IConnection, int, int, string, bool) {#movemessagesasync_1}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool) {#movemessagesasync_21}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string) {#movemessagesasync}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string) {#movemessagesasync_20}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_9}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_29}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#movemessagesasync_8}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string) {#movemessagesasync_28}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool) {#movemessagesasync_17}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool) {#movemessagesasync_37}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string) {#movemessagesasync_16}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string) {#movemessagesasync_36}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_13}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_33}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#movemessagesasync_12}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string) {#movemessagesasync_32}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_5}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_25}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_4}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_24}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, bool, CancellationToken) {#movemessagesasync_2}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool, CancellationToken) {#movemessagesasync_22}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, CancellationToken) {#movemessagesasync_3}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, CancellationToken) {#movemessagesasync_23}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_10}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_30}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_11}

نقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_31}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool, CancellationToken) {#movemessagesasync_18}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool, CancellationToken) {#movemessagesasync_38}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, CancellationToken) {#movemessagesasync_19}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, CancellationToken) {#movemessagesasync_39}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_14}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_34}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_15}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_35}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_6}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_26}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_7}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_27}

لنقل الرسالة

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
