---
title: CreateFolder
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea la nueva carpeta con el nombre especificado en la carpeta principal especificada.
type: docs
weight: 500
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Crea la nueva carpeta con el nombre especificado en la carpeta principal especificada.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | Un uri de la carpeta principal. |
| name | String | Un nombre de la carpeta que se creará. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*o*name* es`nulo`o`vacío`. |

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Crea la nueva carpeta

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | El URI de la carpeta principal |
| name | String | El nombre de la nueva carpeta. |
| permissions | ExchangeFolderPermissionCollection | Un permiso en la nueva carpeta |

### Valor_devuelto

Devuelve información de la carpeta

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Crea la nueva carpeta

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | El URI de la carpeta principal |
| name | String | El nombre de la nueva carpeta. |
| permissions | ExchangeFolderPermissionCollection | Un permiso en la nueva carpeta |
| folderClass | String | La clase de nueva carpeta. |

### Valor_devuelto

Devuelve información de la carpeta

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Crea una nueva carpeta en la carpeta raíz.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | El nombre de la nueva carpeta. |
| folderType | ExchangeFolderType | tipo de carpeta |

### Valor_devuelto

Devuelve información de la carpeta

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Crea la nueva carpeta

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | El URI de la carpeta principal |
| name | String | El nombre de la nueva carpeta. |
| folderType | ExchangeFolderType | tipo de carpeta |

### Valor_devuelto

Devuelve información de la carpeta

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Crea una nueva carpeta en la carpeta raíz.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | El nombre de la nueva carpeta. |

### Valor_devuelto

Devuelve información de la carpeta

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
