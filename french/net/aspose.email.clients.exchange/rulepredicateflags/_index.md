---
title: RulePredicateFlags
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le RulePredicate flags
type: docs
weight: 3540
url: /fr/net/aspose.email.clients.exchange/rulepredicateflags/
---
## RulePredicateFlags enumeration

Représente le RulePredicate flags

```csharp
[Flags]
public enum RulePredicateFlags
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Aucun indicateur n'est spécifié |
| ApprovalRequest | `1` | Les messages entrants doivent être des demandes d'approbation pour que la condition ou l'exception s'applique. |
| NotApprovalRequest | `2` | Les messages entrants ne doivent PAS être des demandes d'approbation pour que la condition ou l'exception s'applique. |
| AutomaticForward | `4` | Les messages entrants doivent être des transferts automatiques pour que la condition ou l'exception s'applique. |
| NotAutomaticForward | `8` | Les messages entrants ne doivent PAS être des transferts automatiques pour que la condition ou l'exception s'applique. |
| AutomaticReply | `10` | Les messages entrants doivent être des réponses automatiques pour que la condition ou l'exception s'applique. |
| NotAutomaticReply | `20` | Les messages entrants ne doivent PAS être des réponses automatiques pour que la condition ou l'exception s'applique. |
| Encrypted | `40` | Les messages entrants doivent être cryptés S/MIME pour que la condition ou l'exception s'applique. |
| NotEncrypted | `80` | Les messages entrants ne doivent pas être cryptés S/MIME pour que la condition ou l'exception s'applique. |
| MeetingRequest | `100` | Les messages entrants doivent répondre aux demandes pour que la condition ou l'exception s'applique. |
| NotMeetingRequest | `200` | Les messages entrants ne doivent PAS répondre aux demandes pour que la condition ou l'exception s'applique. |
| MeetingResponse | `400` | Les messages entrants doivent répondre aux réponses pour que la condition ou l'exception s'applique. |
| NotMeetingResponse | `800` | Les messages entrants ne doivent PAS répondre aux réponses pour que la condition ou l'exception s'applique. |
| Ndr | `1000` | Les messages entrants doivent être des rapports de non-remise (NDR) pour que la condition ou l'exception s'applique. |
| NotNdr | `2000` | Les messages entrants ne doivent PAS être des rapports de non-remise (NDR) pour que la condition ou l'exception s'applique. |
| PermissionControlled | `4000` | Les messages entrants doivent faire l'objet d'un contrôle d'autorisation (protégé par RMS) pour que la condition ou l'exception s'applique. |
| NotPermissionControlled | `8000` | Les messages entrants ne doivent PAS faire l'objet d'un contrôle d'autorisation (protégé par RMS) pour que la condition ou l'exception s'applique. |
| HasAttachment | `10000` | Un message entrant doit avoir des pièces jointes pour que la condition ou l'exception s'applique |
| HasNotAttachment | `20000` | Un message entrant ne doit PAS avoir de pièces jointes pour que la condition ou l'exception s'applique |
| ReadReceipt | `40000` | Les messages entrants doivent être des confirmations de lecture pour que la condition ou l'exception s'applique |
| NotReadReceipt | `80000` | Les messages entrants ne doivent PAS être des confirmations de lecture pour que la condition ou l'exception s'applique |
| Signed | `100000` | Les messages entrants doivent être signés S/MIME pour que la condition ou l'exception s'applique. |
| NotSigned | `200000` | Les messages entrants ne doivent PAS être signés S/MIME pour que la condition ou l'exception s'applique. |
| Voicemail | `400000` | Les messages entrants doivent être des messages vocaux pour que la condition ou l'exception s'applique. |
| NotVoicemail | `800000` | Les messages entrants ne peuvent PAS être des messages vocaux pour que la condition ou l'exception s'applique. |
| SentToMe | `1000000` | Le propriétaire de la boîte aux lettres doit figurer dans la propriété ToRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| NotSentToMe | `2000000` | Le propriétaire de la boîte aux lettres ne peut pas figurer dans la propriété ToRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| SentCcMe | `4000000` | Le propriétaire de la boîte aux lettres doit figurer dans la propriété CcRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| NotSentCcMe | `8000000` | Le propriétaire de la boîte aux lettres ne peut pas être dans la propriété CcRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| SentOnlyToMe | `10000000` | Le propriétaire de la boîte aux lettres doit être le seul dans la propriété ToRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| NotSentOnlyToMe | `20000000` | Le propriétaire de la boîte aux lettres ne peut pas être le seul dans la propriété ToRecipients des messages entrants pour que la condition ou l'exception s'applique. |
| SentToOrCcMe | `40000000` | Le propriétaire de la boîte aux lettres doit se trouver dans une propriété ToRecipients ou CcRecipients des messages entrants pour que la condition ou l'exception s'applique |

### Voir également

* espace de noms [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
