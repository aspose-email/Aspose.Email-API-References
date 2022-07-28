---
title: MapiNamedPropertyMappingStorage
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta la mappatura della proprietà denominata
type: docs
weight: 18520
url: /it/net/aspose.email.mapi/mapinamedpropertymappingstorage/
---
## MapiNamedPropertyMappingStorage class

Rappresenta la mappatura della proprietà denominata

```csharp
public sealed class MapiNamedPropertyMappingStorage : MapiPropertyContainer
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiNamedPropertyMappingStorage](mapinamedpropertymappingstorage)() | Inizializza una nuova istanza di[`MapiNamedPropertyMappingStorage`](../mapinamedpropertymappingstorage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Content](../../aspose.email.mapi/mapinamedpropertymappingstorage/content) { get; } | Ottiene il contenuto |
| [Name](../../aspose.email.mapi/mapinamedpropertymappingstorage/name) { get; } | Ottiene il nome |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping)(MapiProperty, long, Guid) | Aggiunge la mappatura della proprietà denominata per la proprietà denominata numerica. |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping_1)(MapiProperty, string, Guid) | Aggiunge la mappatura della proprietà denominata per la stringa denominata proprietà. |
| [GetNextAvailablePropertyId](../../aspose.email.mapi/mapinamedpropertymappingstorage/getnextavailablepropertyid)(MapiPropertyType) | Ottiene il successivo ID proprietà disponibile nel flusso di voci in base al tipo di dati della proprietà. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Ottiene la proprietà MAPI in base al descrittore di proprietà. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ottiene il valore della proprietà specificata dal tag come tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ottiene il valore della proprietà specificata dal tag come tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ottiene il valore int32 della proprietà specificata dal tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ottiene il valore stringa della proprietà specificata da tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Imposta la proprietà. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | Imposta la proprietà MAPI. |
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
