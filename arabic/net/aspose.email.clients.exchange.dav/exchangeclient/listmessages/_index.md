---
title: ListMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسرد الرسائل .
type: docs
weight: 280
url: /ar/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| messageClass | String | فئة الرسالة. |
| recursive | Boolean | إذا تم التعيين على`حقيقي` [العودية]. |

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

سرد الرسائل في المجلد المحدد

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد Uri |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا. |

### قيمة الإرجاع

مجموعة من معلومات الرسالة

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | الملف. |
| query | String | الاستعلام. |

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

يسرد الرسائل .

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | Uri للمجلد الذي يحتوي على الرسائل. |
| query | MailQuery | ال[`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث. |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا. |

### قيمة الإرجاع

جمع معلومات الرسالة.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

يسرد رسالة البريد في المجلد المحدد.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | عنوان URL للمجلد |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

أ[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) مجموعة.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

سرد الرسائل في المجلد المحدد

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد Uri |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل |
| options | ExchangeListMessagesOptions | يحدد إعدادات القائمة |

### قيمة الإرجاع

مجموعة من معلومات الرسالة

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
