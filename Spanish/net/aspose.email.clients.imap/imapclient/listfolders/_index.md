---
title: ListFolders
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene la lista de carpetas en el buzón
type: docs
weight: 830
url: /es/net/aspose.email.clients.imap/imapclient/listfolders/
---
## ListFolders(IConnection) {#listfolders_1}

Obtiene la lista de carpetas en el buzón

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(IConnection, string) {#listfolders_3}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| parentFolder | String | Nombre de la carpeta |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(IConnection, bool) {#listfolders_2}

Obtiene la lista de carpetas en el buzón

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, bool loadFullInfo)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperarán los nombres de las carpetas. |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders() {#listfolders}

Obtiene la lista de carpetas en el buzón

```csharp
public ImapFolderInfoCollection ListFolders()
```

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(string) {#listfolders_7}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolder | String | Nombre de la carpeta |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(bool) {#listfolders_6}

Obtiene la lista de carpetas en el buzón

```csharp
public ImapFolderInfoCollection ListFolders(bool loadFullInfo)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperarán los nombres de las carpetas. |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(string, bool) {#listfolders_8}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolder | String | Nombre de la carpeta |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperarán los nombres de las carpetas. |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(IConnection, string, bool) {#listfolders_4}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| parentFolder | String | Nombre de la carpeta |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperarán los nombres de las carpetas. |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfolders_9}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo, 
    ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolder | String | Nombre de la carpeta |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperan los nombres de las carpetas. |
| options | ListFoldersOptions | Opciones de funcionamiento |
| returnOptions | ListFoldersReturnOptions | Opciones de devolución para la operación |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## ListFolders(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfolders_5}

Obtiene la lista de subcarpetas en la carpeta especificada

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| parentFolder | String | Nombre de la carpeta |
| loadFullInfo | Boolean | Si es verdadero, indica que la información de la carpeta debe recuperarse completamente de un servidor; de lo contrario, solo se recuperan los nombres de las carpetas. |
| options | ListFoldersOptions | Opciones de funcionamiento |
| returnOptions | ListFoldersReturnOptions | Opciones de devolución para la operación |

### Valor_devuelto

Colección de objetos ImapFolderInfo

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
