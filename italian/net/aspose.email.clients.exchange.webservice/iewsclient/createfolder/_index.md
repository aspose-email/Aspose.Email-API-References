---
title: CreateFolder
second_title: Aspose.Email per riferimento all'API .NET
description: Crea la nuova cartella con il nome specificato nella cartella principale specificata.
type: docs
weight: 500
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Crea la nuova cartella con il nome specificato nella cartella principale specificata.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentFolderUri | String | Un uri della cartella principale. |
| name | String | Un nome della cartella da creare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*o*name* è`nullo`o`vuoto`. |

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Crea la nuova cartella

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentFolderUri | String | L'URI della cartella principale |
| name | String | Il nome della nuova cartella |
| permissions | ExchangeFolderPermissionCollection | Un'autorizzazione sulla nuova cartella |

### Valore di ritorno

Restituisce le informazioni sulla cartella

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Crea la nuova cartella

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentFolderUri | String | L'URI della cartella principale |
| name | String | Il nome della nuova cartella |
| permissions | ExchangeFolderPermissionCollection | Un'autorizzazione sulla nuova cartella |
| folderClass | String | La classe della nuova cartella |

### Valore di ritorno

Restituisce le informazioni sulla cartella

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Crea una nuova cartella nella cartella principale.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il nome della nuova cartella |
| folderType | ExchangeFolderType | Tipo di cartella |

### Valore di ritorno

Restituisce le informazioni sulla cartella

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Crea la nuova cartella

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentFolderUri | String | L'URI della cartella principale |
| name | String | Il nome della nuova cartella |
| folderType | ExchangeFolderType | Tipo di cartella |

### Valore di ritorno

Restituisce le informazioni sulla cartella

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Crea una nuova cartella nella cartella principale.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il nome della nuova cartella |

### Valore di ritorno

Restituisce le informazioni sulla cartella

### Guarda anche

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
