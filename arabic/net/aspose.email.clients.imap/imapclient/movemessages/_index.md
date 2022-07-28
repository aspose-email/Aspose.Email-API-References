---
title: MoveMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: لنقل الرسالة
type: docs
weight: 950
url: /ar/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(string, string, string) {#movemessages_18}

لنقل الرسالة

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة UID للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | مجموعة ImapMessageInfo |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

نقل الرسالة

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

لنقل الرسالة

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

نقل الرسالة

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(int, int, string) {#movemessages_10}

لنقل الرسالة

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startSequence | Int32 | رقم تسلسل البداية لقائمة الرسائل |
| endSequence | Int32 | رقم تسلسل النهاية لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

نقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

نقل الرسالة

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

لنقل الرسالة

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | مجموعة أرقام التسلسل للرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

لنقل الرسالة

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

لنقل الرسالة

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |
| folderName | String | اسم المجلد حيث سيتم نقل الرسالة |
| commitDeletions | Boolean | يحدد ما إذا كان يجب تنفيذ عمليات الحذف أم لا. |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
