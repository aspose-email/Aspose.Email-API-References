---
title: ListMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسرد الرسائل. يحصل على معلومات لرسالة البحث
type: docs
weight: 870
url: /ar/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| fieldsList | ImapListFields | الحقول التي يمكن استرجاعها من الخادم. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| fieldsList | ImapListFields | الحقول التي يمكن استرجاعها من الخادم. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| uniqueIdLst | IEnumerable`1 | قائمة UniqueId لـ[`ImapMessageInfo`](../../imapmessageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| sequenceNumberLst | IEnumerable`1 | التسلسل قائمة أرقام[`ImapMessageInfo`](../../imapmessageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| uniqueIdLst | IEnumerable`1 | قائمة UniqueId لـ[`ImapMessageInfo`](../../imapmessageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

يسرد الرسائل. يحصل على معلومات لرسالة البحث

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| sequenceNumberLst | IEnumerable`1 | التسلسل قائمة أرقام[`ImapMessageInfo`](../../imapmessageinfo) للاسترداد من الخادم. |

### قيمة الإرجاع

ImapMessageInfoCollection

### ملاحظات

لاحظ أن الرسائل التي تم وضع علامة عليها على أنها محذوفة غير مدرجة

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| modificationSequence | Int64 | تسلسل التعديل |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| modificationSequence | Int64 | تسلسل التعديل |

### قيمة الإرجاع

مجموعة من[`ImapMessageInfo`](../../imapmessageinfo) تمثل معلومات الرسائل.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public ImapMessageInfoCollection ListMessages()
```

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| modificationSequence | Int64 | تسلسل التعديل |

### قيمة الإرجاع

مجموعة من[`ImapMessageInfo`](../../imapmessageinfo) تمثل معلومات الرسائل.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | موقع الرسائل |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_2}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_14}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, int) {#listmessages_22}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | موقع الرسائل |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(MailQuery, int) {#listmessages_15}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(IConnection, int) {#listmessages_5}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من[`ImapMessageInfo`](../../imapmessageinfo) تمثل معلومات الرسائل.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* سلبي. |

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessages(int) {#listmessages_17}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

مجموعة من[`ImapMessageInfo`](../../imapmessageinfo) تمثل معلومات الرسائل.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* سلبي. |

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
