---
title: ImapMessageInfo
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un objet de message Imap.
type: docs
weight: 16370
url: /fr/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Représente un objet de message Imap.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur Answered. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Obtient une copie carbone invisible du message électronique. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Obtient CC du message e-mail. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Obtient une valeur indiquant l'identifiant de la conversation. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | La date d'origine spécifie la date et l'heure auxquelles le créateur du message a indiqué que le message était complet et prêt à entrer dans le système de distribution du courrier. Par exemple, cela peut être l'heure à laquelle un utilisateur appuie sur le bouton "envoyer" ou "soumettre" dans un programme d'application. Dans tous les cas, il n'est spécifiquement pas destiné à indiquer l'heure à laquelle le message est réellement transporté, mais plutôt l'heure à laquelle l'humain ou autre créateur du message a mis le message dans sa forme finale, prêt pour le transport. (Par exemple, un utilisateur d'ordinateur portable qui n'est pas connecté à un réseau peut mettre un message en file d'attente pour livraison. La date d'origine est destinée à contenir la date et l'heure auxquelles l'utilisateur a mis le message en file d'attente, et non l'heure à laquelle l'utilisateur s'est connecté au réseau pour envoyer le message.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur Supprimé. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur Draft. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Obtient des paramètres supplémentaires d'un message. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur Flagged. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Obtient les indicateurs de message. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Obtient la liste des auteurs de ce message. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Obtient les en-têtes du message électronique. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | La date et l'heure internes du message sur le serveur. Ce n'est pas la date et l'heure dans l'en-tête [RFC-2822], mais plutôt une date et une heure qui reflètent le moment où le message a été reçu. - Dans le cas de messages livrés via [SMTP], cela DEVRAIT être la date et l'heure de livraison finale du message telles que définies par [SMTP]. - Dans le cas de messages délivrés par la commande IMAP4rev1 COPY, cela DEVRAIT être la date et l'heure internes du message source. - Dans le cas de messages délivrés par la commande IMAP4rev1 APPEND, cela DEVRAIT être la date et l'heure spécifiées dans la description de la commande APPEND. - Tous les autres cas sont définis par l'implémentation. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur de lecture. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Le champ List-Unsubscribe décrit la commande (de préférence par courrier) pour désabonner directement l'utilisateur (en le supprimant de la liste). Pour plus de détails, veuillez consulter https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Obtient l'ID du message. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Obtient la séquence de modification de ce message. En savoir plus : https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Obtient le dossier parent pour le message |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Obtient une propriété mapi. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Obtient une valeur indiquant si la propriété Flags contient l'indicateur récent. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Obtient la liste des adresses qui doivent recevoir des réponses à ce message. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Obtient l'expéditeur de ce message. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Obtient le numéro de séquence du message. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Obtient la taille du message électronique. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Obtient l'objet du message électronique. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Obtient les destinataires du message électronique. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Obtient l'ID unique du message. |

## Méthodes

| Nom | La description |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Obtient une valeur indiquant si la propriété Flags contient l'indicateur de mot clé. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Effectue les tâches associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir également

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* espace de noms [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
