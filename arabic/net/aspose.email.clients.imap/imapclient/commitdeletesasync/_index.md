---
title: CommitDeletesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تنفيذ عمليات الحذف
type: docs
weight: 470
url: /ar/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync()
```

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(int sleep)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف الرسالة |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

تنفيذ عمليات الحذف

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف الرسالة |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
