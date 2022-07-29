---
title: CreateOrUpdateOverride
second_title: Référence de l'API Aspose.Email pour .NET
description: Créer un remplacement pour un expéditeur identifié par une adresse SMTP. Les futurs messages provenant de cette adresse SMTP seront systématiquement classés comme spécifié dans le remplacement. Remarque  - Si un remplacement existe déjà avec la même adresse SMTP les champs classifyAs et name de ce remplacement sont mis à jour avec les valeurs fournies. - Le nombre maximal de remplacements pris en charge pour une boîte aux lettres est de 1000 basé sur des adresses SMTP dexpéditeur uniques.
type: docs
weight: 160
url: /fr/net/aspose.email.clients.graph/igraphclient/createorupdateoverride/
---
## CreateOrUpdateOverride(MailAddress, ClassificationType) {#createorupdateoverride_1}

Créer un remplacement pour un expéditeur identifié par une adresse SMTP. Les futurs messages provenant de cette adresse SMTP seront systématiquement classés comme spécifié dans le remplacement. Remarque : - Si un remplacement existe déjà avec la même adresse SMTP, les champs classifyAs et name de ce remplacement sont mis à jour avec les valeurs fournies. - Le nombre maximal de remplacements pris en charge pour une boîte aux lettres est de 1000, basé sur des adresses SMTP d'expéditeur uniques.

```csharp
public ClassificationOverride CreateOrUpdateOverride(MailAddress sender, 
    ClassificationType classifyAs)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sender | MailAddress | Informations sur l'adresse e-mail de l'expéditeur pour lequel le remplacement est créé. |
| classifyAs | ClassificationType | Valeur qui spécifie comment les messages entrants d'un expéditeur spécifique doivent toujours être classés. |

### Voir également

* class [ClassificationOverride](../../classificationoverride)
* class [MailAddress](../../../aspose.email/mailaddress)
* enum [ClassificationType](../../classificationtype)
* interface [IGraphClient](../../igraphclient)
* espace de noms [Aspose.Email.Clients.Graph](../../igraphclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateOrUpdateOverride(ClassificationOverride) {#createorupdateoverride}

Créer un remplacement pour un expéditeur identifié par une adresse SMTP. Les futurs messages provenant de cette adresse SMTP seront systématiquement classés comme spécifié dans le remplacement. Remarque : - Si un remplacement existe déjà avec la même adresse SMTP, les champs classifyAs et name de ce remplacement sont mis à jour avec les valeurs fournies. - Le nombre maximal de remplacements pris en charge pour une boîte aux lettres est de 1000, basé sur des adresses SMTP d'expéditeur uniques.

```csharp
public ClassificationOverride CreateOrUpdateOverride(ClassificationOverride classificationOverride)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| classificationOverride | ClassificationOverride |  |

### Voir également

* class [ClassificationOverride](../../classificationoverride)
* interface [IGraphClient](../../igraphclient)
* espace de noms [Aspose.Email.Clients.Graph](../../igraphclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->