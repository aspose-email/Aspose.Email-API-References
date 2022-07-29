---
title: GetUsersSettings
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupère les paramètres spécifiés pour un ensemble dutilisateurs.
type: docs
weight: 80
url: /fr/net/aspose.email.clients.exchange/autodiscoverservice/getuserssettings/
---
## AutodiscoverService.GetUsersSettings method

Récupère les paramètres spécifiés pour un ensemble d'utilisateurs.

```csharp
public GetUserSettingsResponseCollection GetUsersSettings(IEnumerable<string> userSmtpAddresses, 
    params UserSettingName[] userSettingNames)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| userSmtpAddresses | IEnumerable`1 | Les adresses SMTP des utilisateurs. |
| userSettingNames | UserSettingName[] | Les noms des paramètres utilisateur. |

### Return_Value

Un objet GetUserSettingsResponseCollection contenant les réponses pour chaque utilisateur individuel.

### Voir également

* class [GetUserSettingsResponseCollection](../../getusersettingsresponsecollection)
* enum [UserSettingName](../../usersettingname)
* class [AutodiscoverService](../../autodiscoverservice)
* espace de noms [Aspose.Email.Clients.Exchange](../../autodiscoverservice)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->