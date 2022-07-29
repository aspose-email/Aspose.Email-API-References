---
title: OOFMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica il messaggio fuori sede per un determinato pubblico. Exchange 2007 Exchange 2010 ed Exchange 2013 richiedono che il messaggio di risposta per i destinatari esterni sconosciuti ed esterni noti sia lo stesso. La proprietà supporta i seguenti tre segmenti di pubblico per un messaggio fuori sede Interno un utente che fa parte della stessa organizzazione dellutente mittente. Esterno noto un utente che è esterno allorganizzazione dellutente mittente ma è rappresentato nei contatti dellutente mittente. Esterno sconosciuto un utente che è al di fuori dellorganizzazione dellutente mittente. organizzazione e non è rappresentato nei contatti dellutente mittente.
type: docs
weight: 1610
url: /it/net/aspose.email.clients.activesync.transportlayer/oofmessage/
---
## OOFMessage class

Specifica il messaggio fuori sede per un determinato pubblico. Exchange 2007, Exchange 2010 ed Exchange 2013 richiedono che il messaggio di risposta per i destinatari esterni sconosciuti ed esterni noti sia lo stesso. La proprietà supporta i seguenti tre segmenti di pubblico per un messaggio fuori sede: Interno: un utente che fa parte della stessa organizzazione dell'utente mittente. Esterno noto: un utente che è esterno all'organizzazione dell'utente mittente, ma è rappresentato nei contatti dell'utente mittente. Esterno sconosciuto: un utente che è al di fuori dell'organizzazione dell'utente mittente. organizzazione e non è rappresentato nei contatti dell'utente mittente.

```csharp
public class OOFMessage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OOFMessage](oofmessage)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AppliesToExternalKnown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalknown) { get; set; } | Indica che il messaggio OOF si applica agli utenti esterni conosciuti. |
| [AppliesToExternalUnknown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalunknown) { get; set; } | Indica che il messaggio OOF si applica a utenti esterni sconosciuti. |
| [AppliesToInternal](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestointernal) { get; set; } | Indica che il messaggio OOF si applica agli utenti interni. |
| [BodyType](../../aspose.email.clients.activesync.transportlayer/oofmessage/bodytype) { get; set; } | Specifica il formato del messaggio OOF. Di seguito sono riportati i valori consentiti per l'elemento BodyType: - Text - HTML |
| [Enabled](../../aspose.email.clients.activesync.transportlayer/oofmessage/enabled) { get; set; } | Specifica se un messaggio OOF viene inviato a questo pubblico mentre l'utente mittente è OOF. |
| [ReplyMessage](../../aspose.email.clients.activesync.transportlayer/oofmessage/replymessage) { get; set; } | Specifica il messaggio da mostrare a un pubblico particolare quando l'utente è fuori sede. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->