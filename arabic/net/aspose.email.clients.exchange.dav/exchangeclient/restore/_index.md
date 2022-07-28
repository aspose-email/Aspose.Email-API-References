---
title: Restore
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يستعيد مجلدات التبادل من ملف التخزين الشخصي المحدد.
type: docs
weight: 350
url: /ar/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

يستعيد مجلدات التبادل من ملف التخزين الشخصي المحدد.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileName | String | مسار إلى ملف التخزين الشخصي. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* غير محدد. |

### أنظر أيضا

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

يستعيد مجلدات التبادل من وحدة التخزين الشخصية المحددة.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على تخزين شخصي. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotSupportedException | ال*stream* لا يدعم القراءة. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* هو`لا شيء`. |

### أنظر أيضا

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

يستعيد مجلدات التبادل من وحدة التخزين الشخصية المحددة.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pst | PersonalStorage | تخزين شخصي يحتوي على مجلدات imap التي تم نسخها احتياطيًا. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* هو`لا شيء`. |

### أنظر أيضا

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

يستعيد مجلدات التبادل المحددة من ملف التخزين الشخصي المحدد.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileName | String | مسار إلى ملف التخزين الشخصي. |
| folders | ExchangeFolderInfoCollection | المجلدات المراد استعادتها. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* غير محدد. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* هو`لا شيء`. |

### أنظر أيضا

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

يستعيد مجلدات التبادل المحددة من التخزين الشخصي المحدد.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على تخزين شخصي. |
| folders | ExchangeFolderInfoCollection | المجلدات المراد استعادتها. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotSupportedException | ال*stream* لا يدعم القراءة. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*أو*folders* هو`لا شيء`. |

### أنظر أيضا

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

يستعيد مجلدات التبادل المحددة من التخزين الشخصي المحدد.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pst | PersonalStorage | تخزين شخصي يحتوي على مجلدات التبادل التي تم نسخها احتياطيًا. |
| folders | ExchangeFolderInfoCollection | المجلدات المراد استعادتها. |
| options | RestoreOptions | استعادة الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*أو*folders* هو`لا شيء`. |

### أنظر أيضا

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
