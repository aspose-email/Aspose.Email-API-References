---
title: Restore
second_title: Aspose.Email for .NET API Reference
description: Restores exchange folders from the specified personal storage file.
type: docs
weight: 350
url: /net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Restores exchange folders from the specified personal storage file.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | A path to personal storage file. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* is not specified. |

### See Also

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Restores exchange folders from the given personal storage.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream containing personal storage. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | The *stream* does not support reading. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* is `null`. |

### See Also

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Restores exchange folders from the given personal storage.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pst | PersonalStorage | A personal storage containing the backuped imap folders. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* is `null`. |

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Restores the specified exchange folders from the specified personal storage file.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | A path to personal storage file. |
| folders | ExchangeFolderInfoCollection | A folders to be restored. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* is not specified. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* is `null`. |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Restores the specified exchange folders from the given personal storage.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream containing personal storage. |
| folders | ExchangeFolderInfoCollection | A folders to be restored. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | The *stream* does not support reading. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* or *folders* is `null`. |

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Restores the specified exchange folders from the given personal storage.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pst | PersonalStorage | A personal storage containing the backuped exchange folders. |
| folders | ExchangeFolderInfoCollection | A folders to be restored. |
| options | RestoreOptions | Restore options. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* or *folders* is `null`. |

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
