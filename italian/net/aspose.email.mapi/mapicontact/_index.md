---
title: MapiContact
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta le informazioni di contatto di Outlook
type: docs
weight: 18190
url: /it/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Rappresenta le informazioni di contatto di Outlook

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | Inizializza una nuova istanza di[`MapiContact`](../mapicontact) classe |
| [MapiContact](mapicontact#constructor_1)(string, string) | Inizializza una nuova istanza di[`MapiContact`](../mapicontact) classe. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | Inizializza una nuova istanza di[`MapiContact`](../mapicontact) classe. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | Inizializza una nuova istanza di[`MapiContact`](../mapicontact) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | Ottiene gli allegati nel contatto. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene le informazioni di fatturazione associate a un articolo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ottiene il testo del messaggio. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ottiene il[`BodyRtf`](../mapimessageitembase/bodyrtf) del messaggio convertito in HTML, se presente, altrimenti una stringa vuota. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ottiene o imposta il testo del messaggio in formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ottiene il tipo del corpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene parole chiave o categorie per l'oggetto messaggio. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene i nomi delle aziende associate a un articolo. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | Specificare le proprietà per un massimo di tre diversi indirizzi e-mail e tre diversi indirizzi fax |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | Specifica gli eventi associati a un contatto |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'ID elemento, utilizzato con un server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ottiene una stringa con distinzione tra maiuscole e minuscole che identifica la classe del messaggio definita dal mittente, ad esempio IPM.Note. La classe del messaggio specifica il tipo, lo scopo o il contenuto del messaggio. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene le informazioni sul chilometraggio associate a un articolo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ottiene la mappatura della proprietà denominata. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | Le proprietà servono per specificare il nome della persona rappresentata dal contatto |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | Specifica altri campi di contatto. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | Specifica altre informazioni di contatto aggiuntive |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | Contiene la foto del contatto[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | Specificare tre indirizzi fisici: Indirizzo di casa, Indirizzo di lavoro e Altro indirizzo. Uno degli indirizzi può essere contrassegnato come indirizzo postale |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | Le proprietà vengono utilizzate per memorizzare i dettagli professionali per la persona rappresentata dal contatto |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ottiene i destinatari del messaggio. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ottiene la sensibilità. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ottiene o imposta l'oggetto del messaggio. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ottiene un prefisso dell'oggetto che in genere indica un'azione su un messaggio, ad esempio "FW: " per l'inoltro. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ottiene i sottoarchivi. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | Specificare i numeri di telefono per il contatto |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | legge[`MapiContact`](../mapicontact) dal flusso specificato contenente vCard. Le versioni vCard supportate sono 2.1 e 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | legge[`MapiContact`](../mapicontact) dal file vCard specificato Le versioni vCard supportate sono 2.1 e 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | legge[`MapiContact`](../mapicontact) dal flusso specificato contenente vCard. Le versioni vCard supportate sono 2.1 e 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | legge[`MapiContact`](../mapicontact) dal file vCard specificato Le versioni vCard supportate sono 2.1 e 3.0 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ottiene la proprietà MAPI in base al descrittore di proprietà. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ottiene il valore della proprietà specificata dal tag come tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ottiene il valore della proprietà specificata dal tag come tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ottiene il valore int32 della proprietà specificata dal tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | Ottieni il MapiMessage che rappresenta il contatto. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fornisce la corretta rimozione della proprietà da tutte le raccolte. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | Salva questo[`MapiContact`](../mapicontact) nello stream specificato con il formato vCard. La versione vCard supportata è 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | Salva questo[`MapiContact`](../mapicontact) al file vCard con opzioni predefinite. La versione vCard supportata è 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | Salva questo[`MapiContact`](../mapicontact) allo stream specificato con un formato utilizzando le opzioni predefinite. Il formato di salvataggio supportato è vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | Salva questo[`MapiContact`](../mapicontact) al flusso specificato utilizzando le opzioni di salvataggio specificate. Le opzioni di salvataggio supportate sono[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | Salva questo[`MapiContact`](../mapicontact)al file specificato con un formato utilizzando le opzioni predefinite. Il formato di salvataggio supportato è vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | Salva questo[`MapiContact`](../mapicontact) in un file utilizzando le opzioni di salvataggio specificate. Le opzioni di salvataggio supportate sono[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | Imposta il contenuto del corpo. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Imposta il contenuto del corpo. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Ottiene o imposta il testo del messaggio in formato RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Imposta i flag dei messaggi. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Imposta la proprietà. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Imposta la proprietà MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Prova a ottenere i dati della proprietà con la chiave del tag specificata. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ottiene il valore della proprietà specificata come tipo DateTime. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ottiene il valore della proprietà specificata come tipo Int32. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ottiene il valore della proprietà specificata come tipo Long. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Prova a ottenere i dati di una proprietà come stringa con il tag specificato. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Prova a ottenere i dati di una proprietà come stringa con tag e codepage specificati. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |

### Guarda anche

* class [MapiMessageItemBase](../mapimessageitembase)
* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
