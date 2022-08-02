---
title: Find
second_title: Referencia de la API de Aspose.Email para .NET
description: Encuentra propiedades en la lista según su PropertySet
type: docs
weight: 100
url: /es/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Encuentra propiedades en la lista según su PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet para encontrar |

### Valor_devuelto

Gama de[`PropertyDescriptor`](../../propertydescriptor)objetos con PropertySet requerido si se encuentran en la lista; de lo contrario matriz vacía.

### Ver también

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Encuentra la propiedad en la lista con el nombre especificado

```csharp
public PropertyDescriptor Find(string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | El nombre utilizado para referirse a la propiedad. |

### Valor_devuelto

[`PropertyDescriptor`](../../propertydescriptor) objeto si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Encuentra[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propiedad en lista

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | Int32 | identificación para encontrar |
| type | PropertyDataType | Tipo de datos de una propiedad |

### Valor_devuelto

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objeto con etiqueta definida si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Encuentra[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propiedades en list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | Int32 | identificación para encontrar |

### Valor_devuelto

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Matriz de objetos con etiqueta definida si se encuentra en la lista; de lo contrario matriz vacía.

### Ver también

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Encuentra[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propiedad en lista

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| tag | Int64 | Etiqueta para encontrar |

### Valor_devuelto

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objeto con etiqueta definida si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Encuentra[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) propiedad en la lista de acuerdo con los parámetros requeridos

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | Nombre de una propiedad |
| type | PropertyDataType | Tipo de datos de una propiedad |
| propertySet | Guid | PropertySet de una propiedad |

### Valor_devuelto

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objeto si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Encuentra[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)propiedad en la lista de acuerdo con los parámetros requeridos Esta es una operación de búsqueda simplificada sin comparación de tipos de datos.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | Nombre de una propiedad |
| propertySet | Guid | PropertySet de una propiedad |

### Valor_devuelto

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objeto si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Encuentra[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) propiedad en la lista de acuerdo con los parámetros requeridos

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| lid | Int64 | Identificación larga de una propiedad |
| type | PropertyDataType | Tipo de datos de una propiedad |
| propertySet | Guid | PropertySet de una propiedad |

### Valor_devuelto

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objeto si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Encuentra[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)propiedad en la lista de acuerdo con los parámetros requeridos Esta es una operación de búsqueda simplificada sin comparación de tipos de datos.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| lid | Int64 | Identificación larga de una propiedad |
| propertySet | Guid | PropertySet de una propiedad |

### Valor_devuelto

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objeto si se encuentra en la lista; de lo contrario nulo.

### Ver también

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espacio de nombres [Aspose.Email.Mapi](../../knownpropertylist)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
