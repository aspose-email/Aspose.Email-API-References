---
title: MapiDistributionList
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta loggetto Elenco di distribuzione personale.
type: docs
weight: 18360
url: /it/net/aspose.email.mapi/mapidistributionlist/
---
## MapiDistributionList class

Rappresenta l'oggetto Elenco di distribuzione personale.

```csharp
public sealed class MapiDistributionList : MapiMessageItemBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiDistributionList](mapidistributionlist#constructor)() | Inizializza una nuova istanza di[`MapiDistributionList`](../mapidistributionlist) classe. |
| [MapiDistributionList](mapidistributionlist#constructor_1)(string, MapiDistributionListMemberCollection) | Inizializza una nuova istanza di[`MapiDistributionList`](../mapidistributionlist) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Ottiene gli allegati nel messaggio. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene le informazioni di fatturazione associate a un articolo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ottiene il testo del messaggio. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ottiene il[`BodyRtf`](../mapimessageitembase/bodyrtf) del messaggio convertito in HTML, se presente, altrimenti una stringa vuota. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ottiene o imposta il testo del messaggio in formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ottiene il tipo del corpo. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene parole chiave o categorie per l'oggetto messaggio. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene i nomi delle aziende associate a un articolo. |
| [DisplayName](../../aspose.email.mapi/mapidistributionlist/displayname) { get; set; } | Ottiene o imposta il nome visibile dall'utente della lista di distribuzione personale. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'ID elemento, utilizzato con un server |
| [Members](../../aspose.email.mapi/mapidistributionlist/members) { get; } | Ottiene l'elenco dei membri della lista di distribuzione personale. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ottiene una stringa con distinzione tra maiuscole e minuscole che identifica la classe del messaggio definita dal mittente, ad esempio IPM.Note. La classe del messaggio specifica il tipo, lo scopo o il contenuto del messaggio. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene le informazioni sul chilometraggio associate a un articolo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ottiene la mappatura della proprietà denominata. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ottiene i destinatari del messaggio. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ottiene la sensibilità. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ottiene o imposta l'oggetto del messaggio. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ottiene un prefisso dell'oggetto che in genere indica un'azione su un messaggio, ad esempio "FW: " per l'inoltro. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ottiene i sottoarchivi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
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
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fornisce la corretta rimozione della proprietà da tutte le raccolte. |
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save)(Stream) | Salva il flusso specificato. |
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save_1)(string) | Salva il nome file specificato. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Imposta il contenuto del corpo. |
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
