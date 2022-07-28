---
title: Create
second_title: Aspose.Email per riferimento all'API .NET
description: Crea il nuovo file PST con il nome file specificato.
type: docs
weight: 20
url: /it/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Crea il nuovo file PST con il nome file specificato.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome completo del file. |
| version | FileFormatVersion | La versione del file PST. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il nome del file è nullo o vuoto |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Crea il PST in un flusso.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui viene creato il PST. |
| version | FileFormatVersion | La versione del file PST. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il nome del file è nullo o vuoto |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Crea il PST in un flusso.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui viene creato il PST. |
| version | FileFormatVersion | La versione del file PST. |
| leaveStreamOpen | Boolean | Lascia lo stream aperto quando PersonalStorage viene eliminato. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il nome del file è nullo o vuoto |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Crea il nuovo file PST con il nome file specificato.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome completo del file. |
| version | FileFormatVersion | La versione del file PST. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il nome del file è nullo o vuoto |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Crea il PST in un flusso.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui viene creato il PST. |
| version | FileFormatVersion | La versione del file PST. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il flusso è nullo |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Crea il PST in un flusso.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui viene creato il PST. |
| version | FileFormatVersion | La versione del file PST. |
| leaveStreamOpen | Boolean | Lascia lo stream aperto quando PersonalStorage viene eliminato. |

### Valore di ritorno

Un oggetto PersonalStorage che rappresenta il nuovo PST.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | genera se viene creata la versione del file ANSI |
| ArgumentNullException | genera se il flusso è nullo |

### Osservazioni

Nota, ora è supportata solo la creazione di versioni di file Unicode.

### Guarda anche

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
