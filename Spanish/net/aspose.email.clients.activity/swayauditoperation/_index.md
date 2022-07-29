---
title: SwayAuditOperation
second_title: Referencia de la API de Aspose.Email para .NET
description: Operación de auditoría de balanceo
type: docs
weight: 2800
url: /es/net/aspose.email.clients.activity/swayauditoperation/
---
## SwayAuditOperation enumeration

Operación de auditoría de balanceo

```csharp
public enum SwayAuditOperation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Create | `1` | El usuario crea un Sway. |
| Delete | `2` | El usuario elimina un Sway. |
| View | `3` | El usuario visualiza un Sway. |
| Edit | `4` | El usuario edita un Sway. |
| Duplicate | `5` | El usuario duplica un Sway. |
| Share | `7` | El usuario inicia el uso compartido de un Sway. Este evento captura la acción del usuario de hacer clic en un destino compartido específico dentro del menú compartido de Sway. El evento no indica si el usuario realmente sigue y completa la acción de compartir. |
| ChangeShareLevel | `8` | El usuario cambia el nivel de recurso compartido de un Sway. Este evento captura al usuario cambiando el ámbito de uso compartido asociado con un Sway. Por ejemplo, público en comparación con dentro de la organización. |
| RevokeShare | `9` | El usuario deja de compartir un Sway al revocar el acceso. Al revocar el acceso, se modifican los vínculos asociados con un Sway. |
| EnableDuplication | `10` | El usuario habilita la duplicación de un Sway (activado de forma predeterminada). |
| DisableDuplication | `11` | El usuario deshabilita la duplicación de un Sway (desactivado por defecto). |
| ServiceOn | `12` | El usuario activa Sway para toda la organización a través del centro de administración de Office 365 (activado de forma predeterminada). |
| ServiceOff | `13` | El usuario deshabilita Sway para toda la organización a través del centro de administración de Office 365 (desactivado de forma predeterminada). |
| ExternalSharingOn | `14` | El usuario habilita el uso compartido externo para toda la organización a través del centro de administración de Office 365. |
| ExternalSharingOff | `15` | El usuario deshabilita el uso compartido externo para toda la organización a través del centro de administración de Office 365. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->