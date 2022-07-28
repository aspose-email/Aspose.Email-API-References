---
title: CreateFolder
second_title: Aspose.Email för .NET API-referens
description: Skapar den nya mappen med det angivna namnet i den angivna överordnade mappen.
type: docs
weight: 500
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Skapar den nya mappen med det angivna namnet i den angivna överordnade mappen.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentFolderUri | String | En uri för överordnad mapp. |
| name | String | Ett namn på mappen som ska skapas. |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*eller*name* är`null`eller`tömma`. |

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Skapar den nya mappen

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentFolderUri | String | URI:n för den överordnade mappen |
| name | String | Namnet på den nya mappen |
| permissions | ExchangeFolderPermissionCollection | En behörighet för ny mapp |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Skapar den nya mappen

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentFolderUri | String | URI:n för den överordnade mappen |
| name | String | Namnet på den nya mappen |
| permissions | ExchangeFolderPermissionCollection | En behörighet för ny mapp |
| folderClass | String | Klassen av ny mapp |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Skapar ny mapp i rotmappen.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namnet på den nya mappen |
| folderType | ExchangeFolderType | Typ av mapp |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Skapar den nya mappen

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentFolderUri | String | URI:n för den överordnade mappen |
| name | String | Namnet på den nya mappen |
| folderType | ExchangeFolderType | Typ av mapp |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Skapar ny mapp i rotmappen.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namnet på den nya mappen |

### Returvärde

Returnerar mappinformation

### Se även

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
