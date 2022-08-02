---
title: Restore
second_title: Referencia de la API de Aspose.Email para .NET
description: Restaura carpetas de intercambio desde el archivo de almacenamiento personal especificado.
type: docs
weight: 350
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/restore/
---
## Restore(string, RestoreOptions) {#restore_5}

Restaura carpetas de intercambio desde el archivo de almacenamiento personal especificado.

```csharp
public void Restore(string fileName, RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | Una ruta al archivo de almacenamiento personal. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* no se especifica |

### Ver también

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## Restore(Stream, RestoreOptions) {#restore_3}

Restaura carpetas de intercambio del almacenamiento personal dado.

```csharp
public void Restore(Stream stream, RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo que contiene almacenamiento personal. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | los*stream* no admite la lectura. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream* es`nulo`. |

### Ver también

* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## Restore(PersonalStorage, RestoreOptions) {#restore_1}

Restaura carpetas de intercambio del almacenamiento personal dado.

```csharp
public void Restore(PersonalStorage pst, RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pst | PersonalStorage | Un almacenamiento personal que contiene las carpetas imap respaldadas. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst* es`nulo`. |

### Ver también

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## Restore(string, ExchangeFolderInfoCollection, RestoreOptions) {#restore_4}

Restaura las carpetas de intercambio especificadas del archivo de almacenamiento personal especificado.

```csharp
public void Restore(string fileName, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | Una ruta al archivo de almacenamiento personal. |
| folders | ExchangeFolderInfoCollection | Una carpeta para ser restaurada. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *fileName* no se especifica |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* es`nulo`. |

### Ver también

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## Restore(Stream, ExchangeFolderInfoCollection, RestoreOptions) {#restore_2}

Restaura las carpetas de intercambio especificadas del almacenamiento personal dado.

```csharp
public void Restore(Stream stream, ExchangeFolderInfoCollection folders, RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo que contiene almacenamiento personal. |
| folders | ExchangeFolderInfoCollection | Una carpeta para ser restaurada. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | los*stream* no admite la lectura. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *stream*o*folders* es`nulo`. |

### Ver también

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## Restore(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) {#restore}

Restaura las carpetas de intercambio especificadas del almacenamiento personal dado.

```csharp
public void Restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, 
    RestoreOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pst | PersonalStorage | Un almacenamiento personal que contiene las carpetas de intercambio respaldadas. |
| folders | ExchangeFolderInfoCollection | Una carpeta para ser restaurada. |
| options | RestoreOptions | Restaurar opciones. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *pst*o*folders* es`nulo`. |

### Ver también

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [RestoreOptions](../../../aspose.email.storage.pst/restoreoptions)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
