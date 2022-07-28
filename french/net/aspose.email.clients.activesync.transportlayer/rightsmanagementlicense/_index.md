---
title: RightsManagementLicense
second_title: Référence de l'API Aspose.Email pour .NET
description: Contient les paramètres de modèle de stratégie de droits pour le modèle appliqué au message électronique en cours de synchronisation.
type: docs
weight: 1900
url: /fr/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Contient les paramètres de modèle de stratégie de droits pour le modèle appliqué au message électronique en cours de synchronisation.

```csharp
public class RightsManagementLicense
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Spécifie la date d'expiration de la licence. L'élément ContentExpiryDate est défini sur "9999-12-30T23:59:59.999Z" si la licence de gestion des droits n'a pas de date d'expiration définie. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Spécifie si le contenu de l'e-mail d'origine peut être modifié par l'utilisateur lorsque l'utilisateur transfère, répond ou répond à tous l'e-mail. La valeur est TRUE si l'e-mail peut être modifié par l'utilisateur ; sinon, FALSE. Une valeur de FALSE exige que le client DOIT exclure le message électronique d'origine géré par des droits de la demande SmartForward ou SmartReply. Par conséquent, les réponses en ligne ne sont pas autorisées si l'élément EditAllowed est défini sur FALSE. Lorsque EditAllowed est défini sur FALSE et que ReplaceMime n'est pas présent dans une demande SmartForward ou SmartReply, le serveur ajoute le message électronique original géré par des droits en tant que pièce jointe au nouveau message. Inversement, si ReplaceMime est présent, le serveur ne joindra pas l'e-mail d'origine en tant que pièce jointe. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Spécifie si le contenu de l'e-mail d'origine peut être modifié par l'utilisateur lorsque l'utilisateur transfère, répond ou répond à tous l'e-mail. La valeur est TRUE si l'e-mail peut être modifié par l'utilisateur ; sinon, FALSE. Une valeur de FALSE exige que le client DOIT exclure le message électronique d'origine géré par des droits de la demande SmartForward ou SmartReply. Par conséquent, les réponses en ligne ne sont pas autorisées si l'élément EditAllowed est défini sur FALSE. Lorsque EditAllowed est défini sur FALSE et que ReplaceMime n'est pas présent dans une demande SmartForward ou SmartReply, le serveur ajoute le message électronique original géré par des droits en tant que pièce jointe au nouveau message. Inversement, si composemail:ReplaceMime est présent, le serveur ne joindra pas l'e-mail d'origine en tant que pièce jointe. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Spécifie si la protection IRM sur le message électronique peut être supprimée par l'utilisateur. La valeur est TRUE si l'utilisateur peut supprimer la protection IRM lorsqu'il transfère, répond ou répond à tous au message électronique ; sinon, FALSE. Si un e-mail géré par des droits est transféré ou répond à l'aide de la commande SmartForward ou SmartReply, les conditions suivantes sont évaluées : - Le modèle de stratégie de droits d'origine a l'élément ExportAllowed défini sur TRUE - Le TemplateID sur le nouveau Le message est défini sur le modèle "Aucune restriction" (valeur de TemplateID "00000000-0000-0000-0000-000000000000") Si les deux conditions sont vraies, la protection IRM est supprimée du message sortant. Le message d'origine conserve sa protection IRM. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Spécifie si l'utilisateur peut copier le contenu du message électronique. La valeur est TRUE si le contenu du message électronique peut être coupé, copié ou si une capture d'écran peut être effectuée du contenu ; sinon, FAUX. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Spécifie si l'utilisateur peut transférer le message électronique. La valeur est TRUE si l'utilisateur peut transférer le message électronique ; sinon, FAUX. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Spécifie si l'utilisateur peut modifier la liste des destinataires lorsqu'il transfère ou répond au message électronique. La valeur est TRUE si l'utilisateur peut modifier la liste des destinataires (1) ; sinon, FAUX. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Spécifie si l'utilisateur est le propriétaire du message électronique. La valeur est TRUE si l'utilisateur est le propriétaire du message électronique ; sinon, FAUX. Une valeur TRUE indique que l'utilisateur authentifié a des droits de propriétaire sur ce message. Cet élément est utilisé uniquement à des fins de présentation d'informations. Les éléments autorisés (EditAllowed, ReplyAllowed, etc.) sont utilisés pour évaluer si une action particulière est autorisée ou restreinte. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Spécifie si l'e-mail peut être imprimé par l'utilisateur. Cet élément n'indique pas la prise en charge du client pour l'impression d'un message électronique ; il spécifie uniquement si le message électronique peut être imprimé si le client prend en charge l'impression. La valeur est VRAI si l'e-mail peut être imprimé par l'utilisateur ; sinon, FAUX. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Spécifie si le contenu du message électronique est accessible par programmation par des applications tierces. La valeur est TRUE si des applications tierces peuvent accéder au contenu du message électronique par programmation ; sinon, FAUX. Une valeur TRUE indique si le contenu protégé est accessible par d'autres applications. Le contenu protégé comprend le corps du message et les pièces jointes. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Spécifie si l'utilisateur peut répondre à tous les destinataires (1) du message électronique d'origine. La valeur est TRUE si l'utilisateur peut répondre à tous les destinataires du message électronique ; sinon, FAUX. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Spécifie si l'utilisateur est autorisé à répondre au message électronique. La valeur est TRUE si l'utilisateur peut répondre au message électronique ; sinon, FAUX. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Contient une description du modèle de stratégie de droits représenté par l'élément parent RightsManagementLicense. Cet élément est utilisé uniquement à des fins de présentation informative. La longueur maximale de l'élément TemplateDescription est de 10240 caractères. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Contient une chaîne qui identifie le modèle de stratégie de droits représenté par l'élément parent RightsManagementLicense. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Spécifie le nom du modèle de stratégie de droits représenté par l'élément parent RightsManagementLicense. Cet élément est utilisé uniquement à des fins de présentation informative. La longueur maximale de l'élément TemplateName est de 256 caractères. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
