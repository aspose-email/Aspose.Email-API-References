---
title: DeleteMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Contrassegna un messaggio con il numero di sequenza specificato come eliminato
type: docs
weight: 560
url: /it/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(string uniqueId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Numero di sequenza di un messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
