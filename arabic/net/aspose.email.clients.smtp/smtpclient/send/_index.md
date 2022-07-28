---
title: Send
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إنشاء الرسالة المحددة وإرسالها.
type: docs
weight: 170
url: /ar/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |

### أنظر أيضا

* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

أرسل الرسالة المحددة.

```csharp
public void Send(MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

أرسل الرسالة المحددة.

```csharp
public void Send(params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

أرسل مجموعة الرسائل المحددة.

```csharp
public void Send(MailMessageCollection messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | MailMessageCollection | مجموعة الرسائل. |

### أنظر أيضا

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

أرسل الرسائل المحددة .

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

إنشاء الرسالة المحددة وإرسالها.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| from | String | سلسلة تحتوي على عنوان مرسل الرسالة. |
| recipients | String | سلسلة تحتوي على عنوان المستلمين. |
| subject | String | موضوع الرسالة. |
| body | String | نص الرسالة. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

أرسل الرسالة المحددة.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| message | MailMessage | MailMessage الذي يمثل رسالة بريد إلكتروني. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

أرسل الرسالة المحددة.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | MailMessage[] | صفيف MailMessage الذي يمثل رسائل بريد إلكتروني لإرسالها. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

أرسل مجموعة الرسائل المحددة.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | MailMessageCollection | مجموعة الرسائل. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

أرسل الرسائل المحددة .

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| messages | IEnumerable`1 | IEnumerator الذي يدعم تكرار الرسالة. |

### أنظر أيضا

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* مساحة الاسم [Aspose.Email.Clients.Smtp](../../smtpclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
