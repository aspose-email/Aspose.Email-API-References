---
title: CreateFolder
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée le nouveau dossier avec le nom spécifié dans le dossier parent spécifié.
type: docs
weight: 500
url: /fr/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Crée le nouveau dossier avec le nom spécifié dans le dossier parent spécifié.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| parentFolderUri | String | Un uri du dossier parent. |
| name | String | Un nom de dossier à créer. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*ou*name* est`nul`ou`vide`. |

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Crée le nouveau dossier

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| parentFolderUri | String | L'URI du dossier parent |
| name | String | Le nom du nouveau dossier |
| permissions | ExchangeFolderPermissionCollection | Une autorisation sur un nouveau dossier |

### Return_Value

Renvoie les informations du dossier

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Crée le nouveau dossier

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| parentFolderUri | String | L'URI du dossier parent |
| name | String | Le nom du nouveau dossier |
| permissions | ExchangeFolderPermissionCollection | Une autorisation sur un nouveau dossier |
| folderClass | String | La classe du nouveau dossier |

### Return_Value

Renvoie les informations du dossier

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Crée un nouveau dossier dans le dossier racine.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Le nom du nouveau dossier |
| folderType | ExchangeFolderType | Type de dossier |

### Return_Value

Renvoie les informations du dossier

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Crée le nouveau dossier

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| parentFolderUri | String | L'URI du dossier parent |
| name | String | Le nom du nouveau dossier |
| folderType | ExchangeFolderType | Type de dossier |

### Return_Value

Renvoie les informations du dossier

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Crée un nouveau dossier dans le dossier racine.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Le nom du nouveau dossier |

### Return_Value

Renvoie les informations du dossier

### Voir également

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
