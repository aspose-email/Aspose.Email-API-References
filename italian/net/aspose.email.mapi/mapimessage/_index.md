---
title: MapiMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un documento in formato messaggio di Outlook che può essere analizzato.
type: docs
weight: 18450
url: /it/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Rappresenta un documento in formato messaggio di Outlook che può essere analizzato.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Inizializza una nuova istanza di[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Inizializza una nuova istanza di[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Inizializza una nuova istanza di[`MapiMessage`](../mapimessage) classe. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Inizializza una nuova istanza di[`MapiMessage`](../mapimessage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Ottiene gli allegati nel messaggio. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene le informazioni di fatturazione associate a un articolo. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Ottiene il testo del messaggio. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ottiene il[`BodyRtf`](../mapimessageitembase/bodyrtf) del messaggio convertito in HTML, se presente, altrimenti una stringa vuota. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ottiene o imposta il testo del messaggio in formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ottiene il tipo del corpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene parole chiave o categorie per l'oggetto messaggio. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Ottiene o imposta la data e l'ora il mittente del messaggio ha inviato un messaggio. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene i nomi delle aziende associate a un articolo. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Ottiene l'argomento del primo messaggio in un thread di conversazione. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Ottiene o imposta la data e l'ora in cui è stato recapitato un messaggio. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Ottiene un elenco dei nomi visualizzati di tutti i destinatari dei messaggi di copia per conoscenza nascosta (BCC), separati da punto e virgola (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Ottiene un elenco dei nomi visualizzati di qualsiasi destinatario del messaggio di copia per conoscenza (CC), separati da punto e virgola (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Ottiene il nome visualizzato per il messaggio. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Ottiene un prefisso del nome visualizzato. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Ottiene un elenco dei nomi visualizzati dei destinatari principali del messaggio (A), separati da punto e virgola (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Ottiene i flag dei messaggi. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Ottiene le intestazioni del messaggio di trasporto |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Ottiene l'ID messaggio del messaggio. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'ID elemento, utilizzato con un server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ottiene una stringa con distinzione tra maiuscole e minuscole che identifica la classe del messaggio definita dal mittente, ad esempio IPM.Note. La classe del messaggio specifica il tipo, lo scopo o il contenuto del messaggio. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Ottiene il formato del messaggio di Outlook. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene le informazioni sul chilometraggio associate a un articolo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ottiene la mappatura della proprietà denominata. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Ottiene l'oggetto normalizzato del messaggio. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Ottiene o imposta un valore che indica se è richiesta la conferma di lettura. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ottiene i destinatari del messaggio. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Ottiene o imposta la risposta ai nomi. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Ottiene il tipo di indirizzo e-mail del mittente del messaggio. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Ottiene o imposta l'indirizzo e-mail del mittente del messaggio. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Ottiene o imposta il nome visualizzato del mittente del messaggio. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Ottiene o imposta l'indirizzo e-mail del mittente del messaggio. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ottiene la sensibilità. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Ottiene il tipo di indirizzo per l'utente di messaggistica rappresentato dal mittente. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Ottiene o imposta l'indirizzo e-mail per l'utente di messaggistica rappresentato dal mittente. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Ottiene o imposta il nome visualizzato per l'utente di messaggistica rappresentato dal mittente. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Ottiene o imposta l'indirizzo e-mail per l'utente di messaggistica rappresentato dal mittente. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ottiene o imposta l'oggetto del messaggio. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ottiene un prefisso dell'oggetto che in genere indica un'azione su un messaggio, ad esempio "FW: " per l'inoltro. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ottiene i sottoarchivi. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Ottiene le informazioni sulla busta del messaggio specifiche per il trasporto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Crea un'istanza di MapiMessage da MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Crea un'istanza di MapiMessage da MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Crea un'istanza di MapiMessage da MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Crea un'istanza di MapiMessage da una raccolta di proprietà Mapi. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Carica il messaggio dallo stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Carica il messaggio dal file. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Carica il messaggio dallo stream con opzioni aggiuntive. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Carica il messaggio dal file con opzioni aggiuntive. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Carica il messaggio dalla struttura dati Transport Neutral Encapsulation Format (TNEF) |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Carica il messaggio dalla struttura dati Transport Neutral Encapsulation Format (TNEF) |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Aggiunge la proprietà personalizzata. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Aggiunge la proprietà personalizzata. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Verifica se questo messaggio può essere trattato come un messaggio di rimbalzo. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Ottiene la raccolta di MapiProperties personalizzate. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ottiene la proprietà MAPI in base al descrittore di proprietà. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ottiene il valore della proprietà specificata dal tag come tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ottiene il valore della proprietà specificata dal tag come tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ottiene il valore int32 della proprietà specificata dal tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ottiene il valore stringa della proprietà specificata da tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fornisce la corretta rimozione della proprietà da tutte le raccolte. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Salva nel flusso specificato come Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Salva nel file specificato come Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Salva il messaggio come flusso con opzioni aggiuntive. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Salva il messaggio come file con opzioni aggiuntive. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Salva nel flusso specificato come modello di file di Outlook (formato OFT). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Salva nel file specificato come modello di file di Outlook (formato OFT). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Salva messaggio in formato TNEF. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Salva messaggio in formato TNEF. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Imposta il contenuto del corpo. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Imposta il contenuto del corpo. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Ottiene o imposta il testo del messaggio in formato RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Imposta i flag dei messaggi. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Imposta la proprietà. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Imposta la proprietà MAPI. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Imposta il valore della proprietà della stringa. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Crea un'istanza di MailMessage da questo MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Converti MapiMessage in oggetto IMapiMessageItem in dipendenza con MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Prova a ottenere i dati della proprietà con la chiave del tag specificata. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ottiene il valore della proprietà specificata come tipo DateTime. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ottiene il valore della proprietà specificata come tipo Int32. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ottiene il valore della proprietà specificata come tipo Long. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Prova a ottenere i dati di una proprietà come stringa con il tag specificato. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Prova a ottenere i dati di una proprietà come stringa con tag e codepage specificati. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Distrugge gli allegati nei file dei messaggi di Outlook specificati. DestroyAttachments ignorerà l'analisi dell'allegato. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Determina se il flusso specificato ha un formato MSG. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Determina se il file specificato ha un formato MSG. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Rimuove tutti gli allegati dai file dei messaggi di Outlook specificati. |

### Osservazioni

Le istanze della classe MapiMessage vengono utilizzate per rappresentare i file di documento dei messaggi di Microsoft Outlook che vengono analizzati dalla classe MapiMessageReader. Per accedere a mittente, destinatario e contenuto di un messaggio di posta elettronica, utilizzare le proprietà associate della classe MapiMessage.

### Esempi

L'esempio seguente mostra come leggere i file dei messaggi di Outlook.

[C#]

[Visual Basic]

```csharp
//Apri i file dei messaggi di Outlook
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/leggi l'oggetto
onsole.WriteLine("Subject:" + msg.Subject);

/nome del mittente
onsole.WriteLine("From:" + msg.SenderName);

/corpo del messaggio
onsole.WriteLine("Body:" + msg.Body);

/Allegati
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Apri i file dei messaggi di Outlook 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'leggi soggetto 
Console.WriteLine("Subject:" + msg.Subject) 

'nome del mittente 
Console.WriteLine("From:" + msg.SenderName) 

'corpo del messaggio 
Console.WriteLine("Body:" + msg.Body) 

'Allegati 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Guarda anche

* class [MapiMessageItemBase](../mapimessageitembase)
* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
