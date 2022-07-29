---
title: EmlSaveOptions
second_title: Référence de l'API Aspose.Email pour .NET
description: Permet de spécifier des options supplémentaires lors de lenregistrement de MailMessage au format Eml et Emlx.
type: docs
weight: 17280
url: /fr/net/aspose.email/emlsaveoptions/
---
## EmlSaveOptions class

Permet de spécifier des options supplémentaires lors de l'enregistrement de MailMessage au format Eml et Emlx.

```csharp
public class EmlSaveOptions : SaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmlSaveOptions](emlsaveoptions)(MailMessageSaveType) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un MailMessage au format Eml et Emlx. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CheckBodyContentEncoding](../../aspose.email/emlsaveoptions/checkbodycontentencoding) { get; set; } | Définit s'il est nécessaire de vérifier l'encodage du contenu du corps du message lors de l'enregistrement. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler) { get; set; } | Représente la méthode généralement fournie par le côté appelant et gère les événements de progression. |
| [FileCompatibilityMode](../../aspose.email/emlsaveoptions/filecompatibilitymode) { get; set; } | Définit les conversions internes, qui doivent nécessairement être effectuées lors de l'enregistrement d'un message. La valeur par défaut est FileCompatibilityMode.None. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype) { get; set; } | Représente le type d'enregistrement du message. Il peut être au format eml, msg (ASCII ou Unicode), mhtml ou html. La valeur par défaut est Eml. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/emlsaveoptions/preserveembeddedmessageformat) { get; set; } | Obtient ou définit une valeur indiquant s'il est nécessaire de conserver le format du message intégré lors de la conversion en MailMessage. |
| [PreserveSignedContent](../../aspose.email/emlsaveoptions/preservesignedcontent) { get; set; } | Obtient ou définit une valeur indiquant s'il est nécessaire d'enregistrer le message signé sans modification de contenu pour fournir correctement la structure du signe numérique. |

### Voir également

* class [SaveOptions](../saveoptions)
* espace de noms [Aspose.Email](../../aspose.email)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->