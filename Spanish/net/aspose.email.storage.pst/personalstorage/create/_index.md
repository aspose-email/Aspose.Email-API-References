---
title: Create
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea el nuevo archivo PST con el nombre de archivo especificado.
type: docs
weight: 20
url: /es/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

Crea el nuevo archivo PST con el nombre de archivo especificado.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | El nombre completo del archivo. |
| version | FileFormatVersion | La versión del archivo PST. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si el nombre del archivo es nulo o está vacío |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

Crea el PST en un stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se crea PST. |
| version | FileFormatVersion | La versión del archivo PST. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si el nombre del archivo es nulo o está vacío |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

Crea el PST en un stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se crea PST. |
| version | FileFormatVersion | La versión del archivo PST. |
| leaveStreamOpen | Boolean | Deje el flujo abierto cuando se elimine PersonalStorage. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si el nombre del archivo es nulo o está vacío |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

Crea el nuevo archivo PST con el nombre de archivo especificado.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | El nombre completo del archivo. |
| version | FileFormatVersion | La versión del archivo PST. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si el nombre del archivo es nulo o está vacío |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

Crea el PST en un stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se crea PST. |
| version | FileFormatVersion | La versión del archivo PST. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si la transmisión es nula |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Crea el PST en un stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se crea PST. |
| version | FileFormatVersion | La versión del archivo PST. |
| leaveStreamOpen | Boolean | Deje el flujo abierto cuando se elimine PersonalStorage. |

### Valor_devuelto

Un objeto PersonalStorage que representa el nuevo PST.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | lanza si se crea la versión del archivo ANSI |
| ArgumentNullException | lanza si la transmisión es nula |

### Observaciones

Tenga en cuenta que ahora solo se admite la creación de versiones de archivos Unicode.

### Ver también

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* espacio de nombres [Aspose.Email.Storage.Pst](../../personalstorage)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
