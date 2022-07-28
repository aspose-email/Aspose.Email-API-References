---
title: SaveMessageAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni
type: docs
weight: 1100
url: /fr/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| resultStream | Stream | Flux qui recevra le message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| resultStream | Stream | Flux qui recevra le message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| resultStream | Stream | Flux qui recevra le message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| resultStream | Stream | Flux qui recevra le message |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| resultStream | Stream | Flux qui recevra le message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| resultStream | Stream | Flux qui recevra le message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| uniqueId | String | L'identifiant unique du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| resultStream | Stream | Flux qui recevra le message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un flux fourni

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| resultStream | Stream | Flux qui recevra le message |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| uniqueId | String | L'identifiant unique du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Télécharge le message avec le numéro de séquence spécifié et écrit ses données dans un fichier local

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sequenceNumber | Int32 | Le numéro de séquence du message |
| fileName | String | Le chemin du fichier local. Cela ne peut pas être un répertoire |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Objet de tâche, avec délégué pour cette opération

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
