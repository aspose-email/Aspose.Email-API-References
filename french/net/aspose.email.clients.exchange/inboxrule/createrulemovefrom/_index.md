---
title: CreateRuleMoveFrom
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée une règle de boîte de réception qui déplace les messages des expéditeurs spécifiés vers le dossier spécifié
type: docs
weight: 50
url: /fr/net/aspose.email.clients.exchange/inboxrule/createrulemovefrom/
---
## InboxRule.CreateRuleMoveFrom method

Crée une règle de boîte de réception qui déplace les messages des expéditeurs spécifiés vers le dossier spécifié

```csharp
public static InboxRule CreateRuleMoveFrom(MailAddress from, string destinationFolderId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| from | MailAddress | UN[`EmailAddress`](../../../aspose.email.personalinfo/emailaddress) de l'expéditeur |
| destinationFolderId | String | Un identifiant de dossier dans lequel les messages seront déplacés |

### Return_Value

Un créé[`InboxRule`](../../inboxrule)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *from* est`nul` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* est`nul`ou`vide` |

### Voir également

* class [MailAddress](../../../aspose.email/mailaddress)
* class [InboxRule](../../inboxrule)
* espace de noms [Aspose.Email.Clients.Exchange](../../inboxrule)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->