---
title: DeleteMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة
type: docs
weight: 590
url: /ar/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
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

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
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

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
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

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
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

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo للحذف |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | يحدد ما إذا كان يجب الالتزام بالرسالة الآن. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| modificationSequence | Int64 | تسلسل التعديل. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc7162 |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
