---
title: CommitDeletes
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تنفيذ عمليات الحذف
type: docs
weight: 460
url: /ar/net/aspose.email.clients.imap/imapclient/commitdeletes/
---
## CommitDeletes() {#commitdeletes}

تنفيذ عمليات الحذف

```csharp
public void CommitDeletes()
```

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(int) {#commitdeletes_6}

تنفيذ عمليات الحذف

```csharp
public void CommitDeletes(int sleep)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IEnumerable&lt;string&gt;) {#commitdeletes_7}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(string) {#commitdeletes_8}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uniqueId | String | معرّف الرسالة |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(string, string) {#commitdeletes_9}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string startUid, string endUid)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |

### أنظر أيضا

* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, IEnumerable&lt;string&gt;) {#commitdeletes_3}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, IEnumerable<string> uidSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uidSet | IEnumerable`1 | مجموعة من المعرفات الفريدة للرسائل |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string) {#commitdeletes_4}

تنفيذ عمليات الحذف

```csharp
public void CommitDeletes(IConnection connection, string uniqueId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| uniqueId | String | معرّف الرسالة |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string, string) {#commitdeletes_5}

قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, string startUid, string endUid)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| startUid | String | UID البداية لقائمة الرسائل |
| endUid | String | UID النهائي لقائمة الرسائل |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IConnection) {#commitdeletes_1}

تنفيذ عمليات الحذف

```csharp
public void CommitDeletes(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, int) {#commitdeletes_2}

تنفيذ عمليات الحذف

```csharp
public void CommitDeletes(IConnection connection, int sleep)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| sleep | Int32 | وقت الانتظار يكمل العملية بالمللي ثانية |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
