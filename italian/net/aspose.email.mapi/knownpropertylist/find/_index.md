---
title: Find
second_title: Aspose.Email per riferimento all'API .NET
description: Trova le proprietà nellelenco in base al suo PropertySet
type: docs
weight: 100
url: /it/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Trova le proprietà nell'elenco in base al suo PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet da trovare |

### Valore di ritorno

Matrice di[`PropertyDescriptor`](../../propertydescriptor)oggetti con PropertySet richiesto se presenti nell'elenco; array altrimenti vuoto.

### Guarda anche

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Trova la proprietà nell'elenco con il nome specificato

```csharp
public PropertyDescriptor Find(string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il nome utilizzato per riferirsi alla proprietà. |

### Valore di ritorno

[`PropertyDescriptor`](../../propertydescriptor) oggetto se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Trova[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) proprietà nell'elenco

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | Int32 | id da trovare |
| type | PropertyDataType | Tipo di dati di una proprietà |

### Valore di ritorno

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) oggetto con tag definito se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Trova[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) proprietà in list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | Int32 | id da trovare |

### Valore di ritorno

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Array di oggetti con tag definito se presenti nell'elenco; array altrimenti vuoto.

### Guarda anche

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Trova[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) proprietà nell'elenco

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | Int64 | Tag da trovare |

### Valore di ritorno

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) oggetto con tag definito se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Trova[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) proprietà nell'elenco in base ai parametri richiesti

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome di una proprietà |
| type | PropertyDataType | Tipo di dati di una proprietà |
| propertySet | Guid | PropertySet di una proprietà |

### Valore di ritorno

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) oggetto se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Trova[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)proprietà nell'elenco in base ai parametri richiesti Questa è un'operazione di ricerca semplificata senza confronto del tipo di dati.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome di una proprietà |
| propertySet | Guid | PropertySet di una proprietà |

### Valore di ritorno

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) oggetto se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Trova[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) proprietà nell'elenco in base ai parametri richiesti

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lid | Int64 | Identificazione lunga di una proprietà |
| type | PropertyDataType | Tipo di dati di una proprietà |
| propertySet | Guid | PropertySet di una proprietà |

### Valore di ritorno

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) oggetto se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Trova[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)proprietà nell'elenco in base ai parametri richiesti Questa è un'operazione di ricerca semplificata senza confronto del tipo di dati.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lid | Int64 | Identificazione lunga di una proprietà |
| propertySet | Guid | PropertySet di una proprietà |

### Valore di ritorno

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) oggetto se presente nell'elenco; altrimenti nullo.

### Guarda anche

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* spazio dei nomi [Aspose.Email.Mapi](../../knownpropertylist)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
