---
title: GetAccessToken
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft das oAuth-Zugriffstoken ab. Wenn das Token existiert und sein Ablaufdatum nicht abgelaufen ist gibt es das aktuelle Token zurück ansonsten fordert es ein neues Token von einem Server an.
type: docs
weight: 110
url: /de/net/aspose.email.clients/tokenprovider/getaccesstoken/
---
## GetAccessToken() {#getaccesstoken}

Ruft das oAuth-Zugriffstoken ab. Wenn das Token existiert und sein Ablaufdatum nicht abgelaufen ist, gibt es das aktuelle Token zurück, ansonsten fordert es ein neues Token von einem Server an.

```csharp
public virtual OAuthToken GetAccessToken()
```

### Rückgabewert

Gibt das oAuth-Zugriffstoken zurück

### Siehe auch

* class [OAuthToken](../../oauthtoken)
* class [TokenProvider](../../tokenprovider)
* namensraum [Aspose.Email.Clients](../../tokenprovider)
* Montage [Aspose.Email](../../../)

---

## GetAccessToken(bool) {#getaccesstoken_1}

Ruft oAuth-Zugriffstoken ab.

```csharp
public virtual OAuthToken GetAccessToken(bool ignoreExistingToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ignoreExistingToken | Boolean | Wenn "ignoreExistingToken" wahr ist, fordert es ein neues Token von einem Server an. Andernfalls hängt das Verhalten davon ab, ob ein Token vorhanden ist oder nicht. Wenn ein Token vorhanden ist und sein Ablaufdatum nicht abgelaufen ist, wird das aktuelle Token zurückgegeben, andernfalls wird ein neues Token von einem Server angefordert. |

### Rückgabewert

Gibt das oAuth-Zugriffstoken zurück

### Siehe auch

* class [OAuthToken](../../oauthtoken)
* class [TokenProvider](../../tokenprovider)
* namensraum [Aspose.Email.Clients](../../tokenprovider)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->