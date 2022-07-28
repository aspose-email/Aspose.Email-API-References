---
title: RulePredicateFlags
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el predicado de reglas flags
type: docs
weight: 3540
url: /es/net/aspose.email.clients.exchange/rulepredicateflags/
---
## RulePredicateFlags enumeration

Representa el predicado de reglas flags

```csharp
[Flags]
public enum RulePredicateFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se especifican banderas |
| ApprovalRequest | `1` | Los mensajes entrantes deben ser solicitudes de aprobación para que se aplique la condición o excepción. |
| NotApprovalRequest | `2` | Los mensajes entrantes NO deben ser solicitudes de aprobación para que se aplique la condición o excepción. |
| AutomaticForward | `4` | Los mensajes entrantes deben ser reenvíos automáticos para que se aplique la condición o excepción. |
| NotAutomaticForward | `8` | Los mensajes entrantes NO deben ser reenvíos automáticos para que se aplique la condición o excepción. |
| AutomaticReply | `10` | Los mensajes entrantes deben ser respuestas automáticas para que se aplique la condición o excepción. |
| NotAutomaticReply | `20` | Los mensajes entrantes NO deben ser respuestas automáticas para que se aplique la condición o excepción. |
| Encrypted | `40` | Los mensajes entrantes deben estar cifrados con S/MIME para que se aplique la condición o excepción. |
| NotEncrypted | `80` | Los mensajes entrantes no deben estar encriptados con S/MIME para que se aplique la condición o excepción. |
| MeetingRequest | `100` | Los mensajes entrantes deben ser solicitudes de reunión para que se aplique la condición o excepción. |
| NotMeetingRequest | `200` | Los mensajes entrantes NO deben ser solicitudes de reunión para que se aplique la condición o excepción. |
| MeetingResponse | `400` | Los mensajes entrantes deben cumplir con las respuestas para que se aplique la condición o excepción. |
| NotMeetingResponse | `800` | Los mensajes entrantes NO deben cumplir con las respuestas para que se aplique la condición o excepción. |
| Ndr | `1000` | Los mensajes entrantes deben ser informes de no entrega (NDR) para que se aplique la condición o excepción. |
| NotNdr | `2000` | Los mensajes entrantes NO deben ser informes de no entrega (NDR) para que se aplique la condición o excepción. |
| PermissionControlled | `4000` | Los mensajes entrantes deben estar controlados por permisos (protegidos por RMS) para que se aplique la condición o excepción. |
| NotPermissionControlled | `8000` | Los mensajes entrantes NO deben estar controlados por permisos (protegidos por RMS) para que se aplique la condición o excepción. |
| HasAttachment | `10000` | Los mensajes entrantes deben tener archivos adjuntos para que se aplique la condición o excepción |
| HasNotAttachment | `20000` | Los mensajes entrantes NO deben tener archivos adjuntos para que se aplique la condición o excepción |
| ReadReceipt | `40000` | Los mensajes entrantes deben ser recibos de lectura para que se aplique la condición o excepción |
| NotReadReceipt | `80000` | Los mensajes entrantes NO deben ser recibos de lectura para que se aplique la condición o excepción |
| Signed | `100000` | Los mensajes entrantes deben tener la firma S/MIME para que se aplique la condición o excepción. |
| NotSigned | `200000` | Los mensajes entrantes NO deben tener la firma S/MIME para que se aplique la condición o excepción. |
| Voicemail | `400000` | Los mensajes entrantes deben ser mensajes de voz para que se aplique la condición o excepción. |
| NotVoicemail | `800000` | Los mensajes entrantes NO pueden ser mensajes de voz para que se aplique la condición o excepción. |
| SentToMe | `1000000` | El propietario del buzón debe estar en la propiedad ToRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| NotSentToMe | `2000000` | El propietario del buzón no puede estar en la propiedad ToRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| SentCcMe | `4000000` | El propietario del buzón debe estar en la propiedad CcRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| NotSentCcMe | `8000000` | El propietario del buzón no puede estar en la propiedad CcRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| SentOnlyToMe | `10000000` | El propietario del buzón debe ser el único en la propiedad ToRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| NotSentOnlyToMe | `20000000` | El propietario del buzón no puede ser el único en la propiedad ToRecipients de los mensajes entrantes para que se aplique la condición o excepción. |
| SentToOrCcMe | `40000000` | El propietario del buzón debe estar en la propiedad ToRecipients o CcRecipients de los mensajes entrantes para que se aplique la condición o excepción |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
