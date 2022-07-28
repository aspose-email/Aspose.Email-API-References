---
title: RulePredicateFlags
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert das Regelprädikat flags
type: docs
weight: 3540
url: /de/net/aspose.email.clients.exchange/rulepredicateflags/
---
## RulePredicateFlags enumeration

Repräsentiert das Regelprädikat flags

```csharp
[Flags]
public enum RulePredicateFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Es sind keine Flags angegeben |
| ApprovalRequest | `1` | Eingehende Nachrichten müssen Genehmigungsanfragen sein, damit die Bedingung oder Ausnahme gilt. |
| NotApprovalRequest | `2` | Eingehende Nachrichten dürfen KEINE Genehmigungsanfragen sein, damit die Bedingung oder Ausnahme gilt. |
| AutomaticForward | `4` | Eingehende Nachrichten müssen automatisch weitergeleitet werden, damit die Bedingung oder Ausnahme gilt. |
| NotAutomaticForward | `8` | Eingehende Nachrichten dürfen NICHT automatisch weitergeleitet werden, damit die Bedingung oder Ausnahme gilt. |
| AutomaticReply | `10` | Eingehende Nachrichten müssen automatische Antworten sein, damit die Bedingung oder Ausnahme gilt. |
| NotAutomaticReply | `20` | Eingehende Nachrichten dürfen KEINE automatischen Antworten sein, damit die Bedingung oder Ausnahme zutrifft. |
| Encrypted | `40` | Eingehende Nachrichten müssen S/MIME-verschlüsselt sein, damit die Bedingung oder Ausnahme gilt. |
| NotEncrypted | `80` | Eingehende Nachrichten dürfen nicht S/MIME-verschlüsselt sein, damit die Bedingung oder Ausnahme gilt. |
| MeetingRequest | `100` | Eingehende Nachrichten müssen Erfüllungsanfragen sein, damit die Bedingung oder Ausnahme gilt. |
| NotMeetingRequest | `200` | Eingehende Nachrichten dürfen KEINE Erfüllungsanforderungen sein, damit die Bedingung oder Ausnahme zutrifft. |
| MeetingResponse | `400` | Eingehende Nachrichten müssen den Antworten entsprechen, damit die Bedingung oder Ausnahme gilt. |
| NotMeetingResponse | `800` | Eingehende Nachrichten dürfen NICHT mit Antworten übereinstimmen, damit die Bedingung oder Ausnahme zutrifft. |
| Ndr | `1000` | Eingehende Nachrichten müssen Unzustellbarkeitsberichte (NDRs) sein, damit die Bedingung oder Ausnahme zutrifft. |
| NotNdr | `2000` | Eingehende Nachrichten dürfen KEINE Unzustellbarkeitsberichte (NDRs) sein, damit die Bedingung oder Ausnahme zutrifft. |
| PermissionControlled | `4000` | Eingehende Nachrichten müssen berechtigungsgesteuert (RMS-geschützt) sein, damit die Bedingung oder Ausnahme gilt. |
| NotPermissionControlled | `8000` | Eingehende Nachrichten dürfen NICHT berechtigungsgesteuert (RMS-geschützt) sein, damit die Bedingung oder Ausnahme gilt. |
| HasAttachment | `10000` | Eine eingehende Nachricht muss Anhänge haben, damit die Bedingung oder Ausnahme zutrifft |
| HasNotAttachment | `20000` | Eine eingehende Nachricht muss KEINE Anhänge haben, damit die Bedingung oder Ausnahme zutrifft |
| ReadReceipt | `40000` | Eingehende Nachrichten müssen Lesebestätigungen sein, damit die Bedingung oder Ausnahme zutrifft |
| NotReadReceipt | `80000` | Eingehende Nachrichten dürfen KEINE Lesebestätigungen sein, damit die Bedingung oder Ausnahme zutrifft |
| Signed | `100000` | Eingehende Nachrichten müssen S/MIME-signiert sein, damit die Bedingung oder Ausnahme gilt. |
| NotSigned | `200000` | Eingehende Nachrichten dürfen NICHT S/MIME-signiert sein, damit die Bedingung oder Ausnahme gilt. |
| Voicemail | `400000` | Eingehende Nachrichten müssen Voicemails sein, damit die Bedingung oder Ausnahme zutrifft. |
| NotVoicemail | `800000` | Eingehende Nachrichten dürfen KEINE Voicemails sein, damit die Bedingung oder Ausnahme zutrifft. |
| SentToMe | `1000000` | Der Besitzer des Postfachs muss in der ToRecipients-Eigenschaft eingehender Nachrichten enthalten sein, damit die Bedingung oder Ausnahme gilt. |
| NotSentToMe | `2000000` | Der Besitzer des Postfachs darf nicht in der ToRecipients-Eigenschaft der eingehenden Nachrichten enthalten sein, damit die Bedingung oder Ausnahme zutrifft. |
| SentCcMe | `4000000` | Der Besitzer des Postfachs muss in der CcRecipients-Eigenschaft eingehender Nachrichten enthalten sein, damit die Bedingung oder Ausnahme gilt. |
| NotSentCcMe | `8000000` | Der Besitzer des Postfachs darf nicht in der CcRecipients-Eigenschaft eingehender Nachrichten enthalten sein, damit die Bedingung oder Ausnahme zutrifft. |
| SentOnlyToMe | `10000000` | Der Besitzer des Postfachs muss der einzige in der ToRecipients-Eigenschaft eingehender Nachrichten sein, damit die Bedingung oder Ausnahme zutrifft. |
| NotSentOnlyToMe | `20000000` | Der Besitzer des Postfachs darf nicht der einzige in der ToRecipients-Eigenschaft eingehender Nachrichten sein, damit die Bedingung oder Ausnahme zutrifft. |
| SentToOrCcMe | `40000000` | Der Besitzer des Postfachs muss sich entweder in einer ToRecipients- oder CcRecipients-Eigenschaft eingehender Nachrichten befinden, damit die Bedingung oder Ausnahme zutrifft |

### Siehe auch

* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
