---
title: SortingKey
second_title: Référence de l'API Aspose.Email pour .NET
description: Critères de tri pour la commande SORT Voir plus  https//tools.ietf.org/html/rfc5256
type: docs
weight: 16730
url: /fr/net/aspose.email.clients.imap/sortingkey/
---
## SortingKey enumeration

Critères de tri pour la commande "SORT" Voir plus : https://tools.ietf.org/html/rfc5256

```csharp
[Flags]
public enum SortingKey
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Arrival | `1` | Par date et heure internes du message. Ceci diffère du critère ON dans SEARCH, qui utilise uniquement la date interne. |
| Cc | `2` | Par la première adresse "cc". |
| Date | `4` | Par date et heure d'envoi. |
| From | `8` | Par la première adresse "De". |
| Size | `10` | Par taille du message en octets. |
| Subject | `20` | Par sujet |
| To | `40` | Par la première adresse "À". |

### Voir également

* espace de noms [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->