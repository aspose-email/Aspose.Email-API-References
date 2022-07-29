---
title: SecurityOptions
second_title: Référence de l'API Aspose.Email pour .NET
description: Mode de sécurité pour un client de messagerie
type: docs
weight: 16950
url: /fr/net/aspose.email.clients/securityoptions/
---
## SecurityOptions enumeration

Mode de sécurité pour un client de messagerie

```csharp
[Flags]
public enum SecurityOptions
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `1` | La connexion n'est pas sécurisée. |
| SSLExplicit | `2` | Utilise la commande STARTTLS pour démarrer la connexion SSL/TLS. |
| SSLImplicit | `4` | Établit d'abord une connexion SSL/TLS. |
| SSLAuto | `6` | Utilise automatiquement le mode implicite SSL/TLS ou explicite SSL/TLS. |
| Auto | `7` | Mode de sélection automatique |

### Voir également

* espace de noms [Aspose.Email.Clients](../../aspose.email.clients)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->