---
title: ListMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: الحصول على قائمة الرسائل في المجلد الحالي.
type: docs
weight: 880
url: /ar/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* سلبي. |

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
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

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| modificationSequence | Int64 | تسلسل التعديل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| modificationSequence | Int64 | تسلسل التعديل |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
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

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
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

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
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

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
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

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
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

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
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

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

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

## ListMessagesAsync(int) {#listmessagesasync_27}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* سلبي. |

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| modificationSequence | Int64 | تسلسل التعديل |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| modificationSequence | Int64 | تسلسل التعديل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

الحصول على قائمة الرسائل في المجلد الحالي

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

الحصول على قائمة الرسائل في المجلد المحدد

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | مجلد لاسترداد الرسائل. |
| retrieveRecursively | Boolean | يشير إلى ما إذا كان يجب استرداد الرسائل بشكل متكرر. |
| messageExtraFields | IEnumerable`1 | قائمة المعلمات الإضافية للرسالة التي سيتم طلبها. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| modificationSequence | Int64 | تسلسل التعديل |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| folderName | String | موقع الرسائل |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

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

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

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

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

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

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folderName | String | موقع الرسائل |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل استعلام البحث. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

مجموعة من كائنات ImapMessageInfo.

### أنظر أيضا

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../imapclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

الحصول على قائمة الرسائل في المجلد الحالي.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IConnection | الاتصال بالخادم |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
