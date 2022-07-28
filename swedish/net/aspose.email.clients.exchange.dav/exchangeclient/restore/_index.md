---
title: Restore
second_title: Aspose.Email för .NET API-referens
description: Återställer utbytesmappar från den angivna personliga lagringsfilen.
type: docs
weight: 350
url: /sv/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Återställer utbytesmappar från den angivna personliga lagringsfilen.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | En sökväg till personlig lagringsfil. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* är inte specificerad. |

### Se även

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Återställer utbytesmappar från den givna personliga lagringen.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En stream som innehåller personlig lagring. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| NotSupportedException | De*stream* stöder inte läsning. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* är`null`. |

### Se även

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Återställer utbytesmappar från den givna personliga lagringen.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pst | PersonalStorage | En personlig lagring som innehåller de säkerhetskopierade imap-mapparna. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* är`null`. |

### Se även

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Återställer de angivna utbytesmapparna från den angivna personliga lagringsfilen.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | En sökväg till personlig lagringsfil. |
| folders | ExchangeFolderInfoCollection | En mappar som ska återställas. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* är inte specificerad. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* är`null`. |

### Se även

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Återställer de angivna utbytesmapparna från den givna personliga lagringen.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En stream som innehåller personlig lagring. |
| folders | ExchangeFolderInfoCollection | En mappar som ska återställas. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| NotSupportedException | De*stream* stöder inte läsning. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*eller*folders* är`null`. |

### Se även

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Återställer de angivna utbytesmapparna från den givna personliga lagringen.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pst | PersonalStorage | En personlig lagring som innehåller de säkerhetskopierade utbytesmapparna. |
| folders | ExchangeFolderInfoCollection | En mappar som ska återställas. |
| options | RestoreOptions | Återställ alternativ. |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*eller*folders* är`null`. |

### Se även

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
