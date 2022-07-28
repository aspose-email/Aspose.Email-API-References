---
title: Restore
second_title: Aspose.Email per riferimento all'API .NET
description: Ripristina le cartelle di scambio dal file di archiviazione personale specificato.
type: docs
weight: 350
url: /it/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Ripristina le cartelle di scambio dal file di archiviazione personale specificato.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Un percorso al file di archiviazione personale. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* non è specificato. |

### Guarda anche

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Ripristina le cartelle di scambio dalla memoria personale specificata.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso contenente memoria personale. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotSupportedException | Il*stream* non supporta la lettura. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* è`nullo`. |

### Guarda anche

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Ripristina le cartelle di scambio dalla memoria personale specificata.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pst | PersonalStorage | Una memoria personale contenente le cartelle imap di cui è stato eseguito il backup. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* è`nullo`. |

### Guarda anche

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Ripristina le cartelle di scambio specificate dal file di archiviazione personale specificato.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Un percorso al file di archiviazione personale. |
| folders | ExchangeFolderInfoCollection | A cartelle da ripristinare. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* non è specificato. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* è`nullo`. |

### Guarda anche

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Ripristina le cartelle di scambio specificate dalla memoria personale specificata.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso contenente memoria personale. |
| folders | ExchangeFolderInfoCollection | A cartelle da ripristinare. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotSupportedException | Il*stream* non supporta la lettura. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*o*folders* è`nullo`. |

### Guarda anche

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Ripristina le cartelle di scambio specificate dalla memoria personale specificata.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pst | PersonalStorage | Una memoria personale contenente le cartelle di scambio di cui è stato eseguito il backup. |
| folders | ExchangeFolderInfoCollection | A cartelle da ripristinare. |
| options | RestoreOptions | Opzioni di ripristino. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*o*folders* è`nullo`. |

### Guarda anche

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
