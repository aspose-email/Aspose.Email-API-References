---
title: MailMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un messaggio di posta elettronica. Consente di accedere alle proprietà del messaggio es. oggetto corpo indirizzo mittente e destinatario ecc. Inoltre può essere inviato e consegnato tramite protocolli di posta supportati.
type: docs
weight: 17710
url: /it/net/aspose.email/mailmessage/
---
## MailMessage class

Rappresenta un messaggio di posta elettronica. Consente di accedere alle proprietà del messaggio, es. oggetto, corpo, indirizzo mittente e destinatario, ecc. Inoltre può essere inviato e consegnato tramite protocolli di posta supportati.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider, ISerializable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MailMessage](mailmessage#constructor)() | Inizializza una nuova istanza di[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_2)(bool) | Inizializza una nuova istanza di[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_1)(MailAddress, MailAddress) | Inizializza una nuova istanza di[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_3)(string, string) | Inizializza una nuova istanza di[`MailMessage`](../mailmessage) classe |
| [MailMessage](mailmessage#constructor_4)(string, string, string, string) | Inizializza una nuova istanza di[`MailMessage`](../mailmessage) classe |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Ottiene la raccolta di viste alternative di message |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Ottiene la raccolta degli allegati del messaggio |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Ottiene o imposta la raccolta di indirizzi che contiene i destinatari BCC del messaggio |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Ottiene o imposta la rappresentazione in testo normale del corpo del messaggio. Se la parte testo/normale è presente in un messaggio, la proprietà restituisce i suoi dati di testo. In caso contrario, la proprietà restituisce il contenuto di testo della proprietà HtmlBody senza markup html. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Ottiene o imposta la codifica di body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Ottiene il tipo del corpo. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Ottiene o imposta la raccolta di indirizzi che contiene i destinatari CC |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Ottiene o imposta la data del messaggio |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Ottiene o imposta le notifiche di consegna |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Ottiene o imposta un testo dell'epilogo. Si trova dopo l'ultimo limite. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Ottiene o imposta l'indirizzo da |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Ottiene la raccolta di intestazioni di message |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Ottiene o imposta il corpo html |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Ottiene o imposta un valore che indica se il corpo del messaggio è in Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Ottiene o imposta un valore che indica se un messaggio è stato inviato o meno. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Ottiene un valore che indica se il messaggio è crittografato. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Ottiene un valore che indica se il messaggio è di sola lettura |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Ottiene un valore che indica se il messaggio è firmato. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Ottiene la raccolta di risorse collegate di message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Ottiene o imposta l'id del messaggio |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Ottiene un valore che indica se il messaggio EML originale è in formato TNEF. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Ottiene o imposta un testo di preambolo. Si trova prima del primo limite e generalmente include una nota esplicativa per i lettori non conformi a MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Ottiene o imposta la codifica preferita per tutte le proprietà del testo |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Ottiene o imposta la priorità del messaggio |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Ottiene o imposta l'indirizzo della conferma di lettura. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Ottiene o imposta l'elenco di indirizzi a cui rispondere per il messaggio di posta |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Ottiene o imposta l'indirizzo ReversePath |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Ottiene o imposta l'indirizzo del mittente |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Ottiene o imposta la sensibilità del messaggio |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Ottiene o imposta la riga dell'oggetto |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Ottiene o imposta la codifica di soggetto |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Ottiene o imposta l'ora UTC (Coordinated Universal Time) per le date del messaggio. Questa proprietà definisce la differenza di fuso orario, tra l'ora locale e UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Ottiene o imposta la raccolta di indirizzi che contiene i destinatari del messaggio |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Ottiene o imposta in X-Mailer il software che ha creato il messaggio di posta elettronica |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Load](../../aspose.email/mailmessage/load#load)(Stream) | Carica messaggio dallo stream |
| static [Load](../../aspose.email/mailmessage/load#load_2)(string) | Carica messaggio da file |
| static [Load](../../aspose.email/mailmessage/load#load_1)(Stream, LoadOptions) | Carica messaggio dallo stream con opzioni aggiuntive. |
| static [Load](../../aspose.email/mailmessage/load#load_3)(string, LoadOptions) | Carica messaggio da file con opzioni aggiuntive. |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Aggiungi una vista alternativa a message |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Aggiungi un allegato al messaggio |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature)(CmsSigner) | Crea un messaggio firmato. Crea una copia di sola lettura del MailMessage specificato e vi aggiunge una firma digitale. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_2)(X509Certificate2) | Crea un messaggio firmato. Crea una copia di sola lettura del MailMessage specificato e vi aggiunge una firma digitale. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_1)(CmsSigner, bool) | Crea un messaggio firmato. Crea una copia di sola lettura del MailMessage specificato e vi aggiunge una firma digitale. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_3)(X509Certificate2, bool) | Crea un messaggio firmato. Crea una copia di sola lettura del MailMessage specificato e vi aggiunge una firma digitale. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Verifica se questo messaggio può essere trattato come un messaggio di rimbalzo. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Verifica della firma esistente MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Clona questa istanza |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Crea la conferma di lettura. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt)() | Decrittografa questo messaggio |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt_1)(X509Certificate2) | Decrittografa questo messaggio |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Rilascia tutte le risorse utilizzate da MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Firma questo messaggio usando la firma DKIM (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt)(X509Certificate2) | Crittografa questo messaggio |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt_1)(X509Certificate2[]) | Crittografa questo messaggio |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Determina se l'Oggetto specificato è uguale all'Oggetto corrente. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Restituisce un enumeratore che scorre una raccolta. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Restituisce un codice hash per l'oggetto |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext_1)(bool) | Ottiene il corpo html del messaggio come testo normale. Questo metodo analizza la proprietà HtmlBody e restituisce il contenuto di testo normale ignorando il markup html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext)(HyperlinkRenderingCallback) | Ottiene il messaggio htmlbody come testo normale. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | Popola aSerializationInfo con i dati necessari per serializzare l'oggetto target. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Importa il messaggio dallo stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Compone il contenuto TNEF. Si noti che l'allegato tnef è composto se un messaggio inizialmente conteneva TNEF ed è stato caricato senza il flag FileCompatibilityMode.PreserveTnefAttachments, Questo metodo non crea un messaggio tnef da quello normale. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Rimuovi firma |
| virtual [Save](../../aspose.email/mailmessage/save#save)(Stream) | Salva il messaggio come stream |
| virtual [Save](../../aspose.email/mailmessage/save#save_2)(string) | Salva il messaggio come file |
| virtual [Save](../../aspose.email/mailmessage/save#save_1)(Stream, SaveOptions) | Salva il messaggio come flusso con opzioni aggiuntive. |
| virtual [Save](../../aspose.email/mailmessage/save#save_3)(string, SaveOptions) | Salva il messaggio come file con opzioni aggiuntive. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Imposta il corpo html. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature)(Stream) | Verifica la firma del messaggio eml specificato. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature_1)(string) | Verifica la firma del file eml specificato. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage)(Stream) | Convalida messaggio eml per corrispondere alla specifica mime. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage_1)(string) | Convalida messaggio eml per corrispondere alla specifica mime. |

### Guarda anche

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* spazio dei nomi [Aspose.Email](../../aspose.email)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
