---
title: Find
second_title: Référence de l'API Aspose.Email pour .NET
description: Trouve les propriétés dans la liste en fonction de son PropertySet
type: docs
weight: 100
url: /fr/net/aspose.email.mapi/knownpropertylist/find/
---
## Find(params Guid[]) {#find_8}

Trouve les propriétés dans la liste en fonction de son PropertySet

```csharp
public PropertyDescriptor[] Find(params Guid[] propertySets)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| propertySets | Guid[] | PropertySet à rechercher |

### Return_Value

Tableau de[`PropertyDescriptor`](../../propertydescriptor)les objets avec le PropertySet requis s'ils se trouvent dans la liste ; sinon tableau vide.

### Voir également

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(string) {#find_7}

Trouve la propriété dans la liste avec le nom spécifié

```csharp
public PropertyDescriptor Find(string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom utilisé pour désigner la propriété. |

### Return_Value

[`PropertyDescriptor`](../../propertydescriptor) objet s'il est trouvé dans la liste ; sinon nul.

### Voir également

* class [PropertyDescriptor](../../propertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(int, PropertyDataType) {#find_4}

Trouve[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propriété dans la liste

```csharp
public PidTagPropertyDescriptor Find(int id, PropertyDataType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | Int32 | identifiant à trouver |
| type | PropertyDataType | Type de données d'une propriété |

### Return_Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objet avec balise définie s'il se trouve dans la liste ; sinon nul.

### Voir également

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(int) {#find_6}

Trouve[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propriétés dans list

```csharp
public PidTagPropertyDescriptor[] Find(int id)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | Int32 | identifiant à trouver |

### Return_Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) Tableau d'objets avec balise définie s'ils se trouvent dans la liste ; sinon tableau vide.

### Voir également

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(long) {#find_5}

Trouve[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) propriété dans la liste

```csharp
public PidTagPropertyDescriptor Find(long tag)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| tag | Int64 | Balise à trouver |

### Return_Value

[`PidTagPropertyDescriptor`](../../pidtagpropertydescriptor) objet avec balise définie s'il se trouve dans la liste ; sinon nul.

### Voir également

* class [PidTagPropertyDescriptor](../../pidtagpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(string, PropertyDataType, Guid) {#find_2}

Trouve[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) propriété dans la liste selon les paramètres requis

```csharp
public PidNamePropertyDescriptor Find(string name, PropertyDataType type, Guid propertySet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom d'une propriété |
| type | PropertyDataType | Type de données d'une propriété |
| propertySet | Guid | PropertySet d'une propriété |

### Return_Value

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objet s'il est trouvé dans la liste ; sinon nul.

### Voir également

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(string, Guid) {#find_3}

Trouve[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor)propriété dans la liste selon les paramètres requis Il s'agit d'une opération de recherche simplifiée sans comparaison de type de données.

```csharp
public PidNamePropertyDescriptor Find(string name, Guid propertySet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom d'une propriété |
| propertySet | Guid | PropertySet d'une propriété |

### Return_Value

[`PidNamePropertyDescriptor`](../../pidnamepropertydescriptor) objet s'il est trouvé dans la liste ; sinon nul.

### Voir également

* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(long, PropertyDataType, Guid) {#find}

Trouve[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) propriété dans la liste selon les paramètres requis

```csharp
public PidLidPropertyDescriptor Find(long lid, PropertyDataType type, Guid propertySet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| lid | Int64 | Identifiant long d'une propriété |
| type | PropertyDataType | Type de données d'une propriété |
| propertySet | Guid | PropertySet d'une propriété |

### Return_Value

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objet s'il est trouvé dans la liste ; sinon nul.

### Voir également

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* enum [PropertyDataType](../../propertydatatype)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

---

## Find(long, Guid) {#find_1}

Trouve[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor)propriété dans la liste selon les paramètres requis Il s'agit d'une opération de recherche simplifiée sans comparaison de type de données.

```csharp
public PidLidPropertyDescriptor Find(long lid, Guid propertySet)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| lid | Int64 | Identifiant long d'une propriété |
| propertySet | Guid | PropertySet d'une propriété |

### Return_Value

[`PidLidPropertyDescriptor`](../../pidlidpropertydescriptor) objet s'il est trouvé dans la liste ; sinon nul.

### Voir également

* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [KnownPropertyList](../../knownpropertylist)
* espace de noms [Aspose.Email.Mapi](../../knownpropertylist)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
