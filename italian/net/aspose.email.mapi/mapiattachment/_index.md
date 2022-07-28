---
title: MapiAttachment
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta lallegato nel messaggio di posta elettronica.
type: docs
weight: 17880
url: /it/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Rappresenta l'allegato nel messaggio di posta elettronica.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Ottiene o imposta i dati dell'allegato binario. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Ottiene il contenuto. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Ottiene il nome visualizzato dell'oggetto ole in un allegato. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Ottiene un'estensione del nome file che indica il tipo di documento di un allegato. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Ottiene il nome file di base e l'estensione di un allegato, escluso il percorso. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | L'ID elemento, utilizzato con un server |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Ottiene il nome file lungo e l'estensione di un allegato, escluso il percorso. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Ottiene informazioni di formattazione su un allegato MIME (Multipurpose Internet Mail Extensions) . |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Ottiene un oggetto allegato a cui si accede in genere tramite l'interfaccia OLE IStorage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Ottiene i sottoarchivi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Ottiene la proprietà MAPI in base al descrittore di proprietà. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ottiene il valore della proprietà specificata dal tag come tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ottiene il valore della proprietà specificata dal tag come tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ottiene il valore int32 della proprietà specificata dal tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ottiene il valore stringa della proprietà specificata da tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Fornisce la corretta rimozione della proprietà da tutte le raccolte. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Salva il contenuto dell'allegato. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Salva il contenuto dell'allegato. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Imposta la proprietà. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Imposta la proprietà MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Prova a ottenere i dati della proprietà con la chiave del tag specificata. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ottiene il valore della proprietà specificata come tipo DateTime. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ottiene il valore della proprietà specificata come tipo Int32. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ottiene il valore della proprietà specificata come tipo Long. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Prova a ottenere i dati di una proprietà come stringa con il tag specificato. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Prova a ottenere i dati di una proprietà come stringa con tag e codepage specificati. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |

### Guarda anche

* class [MapiPropertyContainer](../mapipropertycontainer)
* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
