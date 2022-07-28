---
title: Restore
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt Austauschordner aus der angegebenen persönlichen Speicherdatei wieder her.
type: docs
weight: 350
url: /de/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Stellt Austauschordner aus der angegebenen persönlichen Speicherdatei wieder her.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Ein Pfad zur persönlichen Speicherdatei. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* ist nicht angegeben. |

### Siehe auch

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Stellt Austauschordner aus dem angegebenen persönlichen Speicher wieder her.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream mit persönlichem Speicher. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Das*stream* unterstützt das Lesen nicht. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* ist`Null`. |

### Siehe auch

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Stellt Austauschordner aus dem angegebenen persönlichen Speicher wieder her.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pst | PersonalStorage | Ein persönlicher Speicher, der die gesicherten imap-Ordner enthält. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* ist`Null`. |

### Siehe auch

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Stellt die angegebenen Austauschordner aus der angegebenen persönlichen Speicherdatei wieder her.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Ein Pfad zur persönlichen Speicherdatei. |
| folders | ExchangeFolderInfoCollection | Ein wiederherzustellender Ordner. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* ist nicht angegeben. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* ist`Null`. |

### Siehe auch

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Stellt die angegebenen Austauschordner aus dem angegebenen persönlichen Speicher wieder her.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream mit persönlichem Speicher. |
| folders | ExchangeFolderInfoCollection | Ein wiederherzustellender Ordner. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Das*stream* unterstützt das Lesen nicht. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*oder*folders* ist`Null`. |

### Siehe auch

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Stellt die angegebenen Austauschordner aus dem angegebenen persönlichen Speicher wieder her.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pst | PersonalStorage | Ein persönlicher Speicher, der die gesicherten Austauschordner enthält. |
| folders | ExchangeFolderInfoCollection | Ein wiederherzustellender Ordner. |
| options | RestoreOptions | Wiederherstellungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*oder*folders* ist`Null`. |

### Siehe auch

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* namensraum [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
