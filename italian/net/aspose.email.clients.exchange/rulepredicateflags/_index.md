---
title: RulePredicateFlags
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta i flag RulePredicate
type: docs
weight: 3540
url: /it/net/aspose.email.clients.exchange/rulepredicateflags/
---
## RulePredicateFlags enumeration

Rappresenta i flag RulePredicate

```csharp
[Flags]
public enum RulePredicateFlags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessun flag specificato |
| ApprovalRequest | `1` | I messaggi in arrivo devono essere richieste di approvazione affinché la condizione o l'eccezione si applichino. |
| NotApprovalRequest | `2` | I messaggi in arrivo NON devono essere richieste di approvazione affinché la condizione o l'eccezione si applichino. |
| AutomaticForward | `4` | I messaggi in arrivo devono essere inoltrati automaticamente affinché la condizione o l'eccezione si applichino. |
| NotAutomaticForward | `8` | I messaggi in arrivo NON devono essere inoltrati automaticamente affinché la condizione o l'eccezione si applichino. |
| AutomaticReply | `10` | I messaggi in arrivo devono essere risposte automatiche affinché la condizione o l'eccezione si applichino. |
| NotAutomaticReply | `20` | I messaggi in arrivo NON devono essere risposte automatiche affinché la condizione o l'eccezione si applichino. |
| Encrypted | `40` | I messaggi in arrivo devono essere crittografati S/MIME affinché la condizione o l'eccezione si applichino. |
| NotEncrypted | `80` | I messaggi in arrivo non devono essere crittografati S/MIME affinché la condizione o l'eccezione si applichino. |
| MeetingRequest | `100` | I messaggi in arrivo devono essere richieste di riunione affinché la condizione o l'eccezione si applichino. |
| NotMeetingRequest | `200` | I messaggi in arrivo NON devono essere richieste di incontro affinché la condizione o l'eccezione si applichino. |
| MeetingResponse | `400` | I messaggi in arrivo devono soddisfare le risposte affinché la condizione o l'eccezione si applichino. |
| NotMeetingResponse | `800` | I messaggi in arrivo NON devono soddisfare le risposte affinché la condizione o l'eccezione si applichino. |
| Ndr | `1000` | I messaggi in arrivo devono essere rapporti di mancato recapito (NDR) affinché la condizione o l'eccezione si applichino. |
| NotNdr | `2000` | I messaggi in arrivo NON devono essere rapporti di mancato recapito (NDR) affinché la condizione o l'eccezione si applichino. |
| PermissionControlled | `4000` | I messaggi in arrivo devono essere controllati tramite autorizzazione (protetto da RMS) affinché la condizione o l'eccezione si applichino. |
| NotPermissionControlled | `8000` | I messaggi in arrivo NON devono essere controllati tramite autorizzazione (protetto da RMS) affinché la condizione o l'eccezione si applichino. |
| HasAttachment | `10000` | Un messaggio in arrivo deve avere allegati affinché la condizione o l'eccezione si applichino |
| HasNotAttachment | `20000` | Un messaggio in arrivo NON deve avere allegati affinché la condizione o l'eccezione si applichino |
| ReadReceipt | `40000` | I messaggi in arrivo devono essere conferme di lettura affinché la condizione o l'eccezione si applichino |
| NotReadReceipt | `80000` | I messaggi in arrivo NON devono essere conferme di lettura affinché la condizione o l'eccezione si applichino |
| Signed | `100000` | I messaggi in arrivo devono essere firmati S/MIME affinché la condizione o l'eccezione si applichino. |
| NotSigned | `200000` | I messaggi in arrivo NON devono essere firmati S/MIME affinché la condizione o l'eccezione si applichino. |
| Voicemail | `400000` | I messaggi in arrivo devono essere messaggi di posta vocale affinché la condizione o l'eccezione si applichino. |
| NotVoicemail | `800000` | I messaggi in arrivo NON possono essere messaggi di posta vocale affinché la condizione o l'eccezione si applichino. |
| SentToMe | `1000000` | Il proprietario della casella di posta deve essere nella proprietà ToRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| NotSentToMe | `2000000` | Il proprietario della casella di posta non può essere nella proprietà ToRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| SentCcMe | `4000000` | Il proprietario della casella di posta deve essere nella proprietà CcRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| NotSentCcMe | `8000000` | Il proprietario della casella di posta non può essere nella proprietà CcRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| SentOnlyToMe | `10000000` | Il proprietario della casella di posta deve essere l'unico nella proprietà ToRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| NotSentOnlyToMe | `20000000` | Il proprietario della casella di posta non può essere l'unico nella proprietà ToRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino. |
| SentToOrCcMe | `40000000` | Il proprietario della casella di posta deve trovarsi in una proprietà ToRecipients o CcRecipients dei messaggi in arrivo affinché la condizione o l'eccezione si applichino |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
