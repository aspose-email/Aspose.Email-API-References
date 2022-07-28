---
title: FetchMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupère les messages de manière asynchrone
type: docs
weight: 140
url: /fr/net/aspose.email.clients.pop3/pop3client/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;) {#fetchmessagesasync_4}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Les numéros de séquence des messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;) {#fetchmessagesasync_6}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uids | IEnumerable`1 | Les numéros de séquence des messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#fetchmessagesasync}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumbers | IEnumerable`1 | Les numéros de séquence des messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#fetchmessagesasync_2}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, IEnumerable<string> uids)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uids | IEnumerable`1 | Les numéros de séquence des messages |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_5}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Les numéros de séquence des messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_7}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uids | IEnumerable`1 | Les numéros de séquence des messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_1}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumbers | IEnumerable`1 | Les numéros de séquence des messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_3}

Récupère les messages de manière asynchrone

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<string> uids, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uids | IEnumerable`1 | Les numéros de séquence des messages |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* espace de noms [Aspose.Email.Clients.Pop3](../../pop3client)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
