---
title: RightsManagementLicense
second_title: Aspose.Email per riferimento all'API .NET
description: Contiene le impostazioni del modello di politica dei diritti per il modello applicato al messaggio di posta elettronica in fase di sincronizzazione.
type: docs
weight: 1900
url: /it/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Contiene le impostazioni del modello di politica dei diritti per il modello applicato al messaggio di posta elettronica in fase di sincronizzazione.

```csharp
public class RightsManagementLicense
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Specifica la data di scadenza della licenza. L'elemento ContentExpiryDate è impostato su "9999-12-30T23:59:59.999Z" se la licenza di gestione dei diritti non ha una data di scadenza impostata. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Specifica se il contenuto dell'e-mail originale può essere modificato dall'utente quando l'utente inoltra, risponde o risponde a tutti al messaggio e-mail. Il valore è TRUE se l'e-mail può essere modificata dall'utente; in caso contrario, FALSE. Un valore di FALSE richiede che il client DEVE escludere il messaggio di posta elettronica con diritti gestiti originale dalla richiesta SmartForward o SmartReply. Di conseguenza, le risposte in linea non sono consentite se l'elemento EditAllowed è impostato su FALSE. Quando EditAllowed è impostato su FALSE e ReplaceMime non è presente in una richiesta SmartForward o SmartReply, il server aggiungerà il messaggio di posta elettronica con gestione dei diritti originale come allegato al nuovo messaggio. Al contrario, se è presente ReplaceMime, il server non allegherà il messaggio e-mail originale con gestione dei diritti come allegato. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Specifica se il contenuto dell'e-mail originale può essere modificato dall'utente quando l'utente inoltra, risponde o risponde a tutti al messaggio e-mail. Il valore è TRUE se l'e-mail può essere modificata dall'utente; in caso contrario, FALSE. Un valore di FALSE richiede che il client DEVE escludere il messaggio di posta elettronica con diritti gestiti originale dalla richiesta SmartForward o SmartReply. Di conseguenza, le risposte in linea non sono consentite se l'elemento EditAllowed è impostato su FALSE. Quando EditAllowed è impostato su FALSE e ReplaceMime non è presente in una richiesta SmartForward o SmartReply, il server aggiungerà il messaggio di posta elettronica con gestione dei diritti originale come allegato al nuovo messaggio. Al contrario, se composemail:ReplaceMime è presente, il server non allegherà il messaggio e-mail originale con gestione dei diritti come allegato. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Specifica se la protezione IRM sul messaggio di posta elettronica può essere rimossa dall'utente. Il valore è TRUE se l'utente può rimuovere la protezione IRM quando l'utente inoltra, risponde o risponde a tutto il messaggio di posta elettronica; in caso contrario, FALSE. Se un messaggio e-mail con gestione dei diritti viene inoltrato o risposto utilizzando il comando SmartForward o SmartReply, vengono valutate le seguenti condizioni: - Il modello della politica dei diritti originale ha l'elemento ExportAllowed impostato su TRUE - Il TemplateID sul nuovo messaggio è impostato sul modello "Nessuna restrizione" (valore di ID modello "00000000-0000-0000-0000-000000000000") Se entrambe le condizioni sono vere, la protezione IRM viene rimossa dal messaggio in uscita. Il messaggio originale mantiene la protezione IRM. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Specifica se l'utente può copiare il contenuto dal messaggio di posta elettronica. Il valore è TRUE se il contenuto del messaggio di posta elettronica può essere tagliato, copiato o è possibile acquisire una schermata del contenuto; in caso contrario, FALSO. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Specifica se l'utente può inoltrare il messaggio di posta elettronica. Il valore è TRUE se l'utente può inoltrare il messaggio di posta elettronica; in caso contrario, FALSO. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Specifica se l'utente può modificare l'elenco dei destinatari quando l'utente inoltra o risponde al messaggio di posta elettronica. Il valore è TRUE se l'utente può modificare l'elenco dei destinatari (1); in caso contrario, FALSO. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Specifica se l'utente è il proprietario del messaggio di posta elettronica. Il valore è TRUE se l'utente è il proprietario del messaggio di posta elettronica; altrimenti FALSO. Un valore TRUE indica che l'utente autenticato dispone dei diritti di proprietario su questo messaggio. Questo elemento viene utilizzato solo a scopo di presentazione delle informazioni. Gli elementi Consentiti (EditAllowed, ReplyAllowed, ecc.) vengono utilizzati per valutare se una determinata azione è consentita o limitata. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Specifica se l'e-mail può essere stampata dall'utente. Questo elemento non indica il supporto client per la stampa di un messaggio di posta elettronica; specifica solo se il messaggio di posta elettronica può essere stampato se il client supporta la stampa. Il valore è TRUE se il messaggio di posta elettronica può essere stampato dall'utente; in caso contrario, FALSO. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Specifica se le applicazioni di terze parti possono accedere al contenuto del messaggio di posta elettronica a livello di codice. Il valore è TRUE se le applicazioni di terze parti possono accedere al contenuto del messaggio di posta elettronica a livello di codice; altrimenti FALSO. Un valore TRUE indica se il contenuto protetto è accessibile da altre applicazioni. Il contenuto protetto è costituito dal corpo del messaggio e dagli allegati. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Specifica se l'utente può rispondere a tutti i destinatari (1) del messaggio di posta elettronica originale. Il valore è TRUE se l'utente può rispondere a tutti i destinatari del messaggio di posta elettronica; in caso contrario, FALSO. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Specifica se l'utente può rispondere al messaggio di posta elettronica. Il valore è TRUE se l'utente può rispondere al messaggio di posta elettronica; in caso contrario, FALSO. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Contiene una descrizione del modello di politica dei diritti rappresentato dall'elemento principale RightsManagementLicense. Questo elemento viene utilizzato solo a scopo di presentazione informativa. La lunghezza massima dell'elemento TemplateDescription è 10240 caratteri. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Contiene una stringa che identifica il modello di politica dei diritti rappresentato dall'elemento principale RightsManagementLicense. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Specifica il nome del modello di politica dei diritti rappresentato dall'elemento principale RightsManagementLicense. Questo elemento viene utilizzato solo a scopo di presentazione informativa. La lunghezza massima dell'elemento TemplateName è 256 caratteri. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
