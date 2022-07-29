---
title: Add
second_title: Référence de l'API Aspose.Email pour .NET
description: Ajoute le nouveau destinataire.
type: docs
weight: 20
url: /fr/net/aspose.email.mapi/mapirecipientcollection/add/
---
## Add(string, string, MapiRecipientType) {#add_2}

Ajoute le nouveau destinataire.

```csharp
public void Add(string address, string displayName, MapiRecipientType recipientType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| address | String | L'adresse e-mail du destinataire. |
| displayName | String | Le nom d'affichage du destinataire. |
| recipientType | MapiRecipientType | Type de destinataire. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | lève si l'adresse du destinataire est nulle ou vide. |
| ArgumentException | est lancé si l'adresse du destinataire n'est pas dans un format reconnu. |

### Remarques

Lors de l'ajout d'un nouveau destinataire, la valeur de MapiMessage.DisplayTo ou MapiMessage.DisplayBcc ou MapiMessage.DisplayCC est également mise à jour en fonction du type de destinataire.

### Voir également

* enum [MapiRecipientType](../../mapirecipienttype)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* espace de noms [Aspose.Email.Mapi](../../mapirecipientcollection)
* Assemblée [Aspose.Email](../../../)

---

## Add(string, string, string, MapiRecipientType) {#add_3}

Ajoute le nouveau destinataire.

```csharp
public void Add(string address, string addressType, string displayName, 
    MapiRecipientType recipientType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| address | String | L'adresse e-mail du destinataire. |
| addressType | String | Le type d'adresse. |
| displayName | String | Le nom d'affichage du destinataire. |
| recipientType | MapiRecipientType | Type de destinataire. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | lève si l'adresse du destinataire est nulle ou vide. |
| ArgumentException | est lancé si l'adresse du destinataire n'est pas dans un format reconnu. |

### Remarques

Lors de l'ajout d'un nouveau destinataire, la valeur de MapiMessage.DisplayTo ou MapiMessage.DisplayBcc ou MapiMessage.DisplayCC est également mise à jour en fonction du type de destinataire.

### Voir également

* enum [MapiRecipientType](../../mapirecipienttype)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* espace de noms [Aspose.Email.Mapi](../../mapirecipientcollection)
* Assemblée [Aspose.Email](../../../)

---

## Add(MapiRecipient) {#add}

Ajoute un objet à la fin duCollection .

```csharp
public void Add(MapiRecipient item)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| item | MapiRecipient | L'objet à ajouter à la fin duCollection. La valeur peut être nulle pour les types de référence. |

### Voir également

* class [MapiRecipient](../../mapirecipient)
* class [MapiRecipientCollection](../../mapirecipientcollection)
* espace de noms [Aspose.Email.Mapi](../../mapirecipientcollection)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->