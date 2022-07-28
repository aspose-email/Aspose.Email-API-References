---
title: MapiProperty
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta la proprietà mapi.
type: docs
weight: 18560
url: /it/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

Rappresenta la proprietà mapi.

```csharp
public class MapiProperty
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | Inizializza una nuova istanza della classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | Inizializza una nuova istanza della classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Inizializza una nuova istanza di[`MapiProperty`](../mapiproperty) class. Questo sovraccarico viene utilizzato per creare una proprietà con più valori, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | Inizializza una nuova istanza della classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | Inizializza una nuova istanza della classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Inizializza una nuova istanza di[`MapiProperty`](../mapiproperty) classe. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | Inizializza una nuova istanza della classe MapiProperty. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Ottiene i dati binari. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Ottiene il tipo di dati. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Ottiene il descrittore della proprietà MAPI |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Ottiene l'indicatore. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indica se la proprietà è una proprietà denominata. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indica se i dati binari sono con segno. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Ottiene l'elenco delle voci VM. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Ottiene il nome. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Ottiene il PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Ottiene il tag. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | Crea la proprietà mapi dai byte. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Crea la proprietà mapi dalla data e ora. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | Crea la proprietà mapi da long. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | Crea la proprietà mapi da long. |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | Ottiene i primi byte dei dati binari come booleani. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Ottiene la valuta come stringa utilizzando la tabella codici specificata. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | Ottiene i primi byte dei dati binari come datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | Ottiene i byte dei dati binari come double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | Ottiene i byte dei dati binari come float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | Ottiene i byte dei dati binari come DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | Ottiene i byte dei dati binari come Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | Ottiene i primi 4 byte dei dati binari come int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | Ottiene i primi 8 byte dei dati binari finché sono lunghi. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | Ottiene i primi 2 byte dei dati binari come brevi. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | Ottiene i dati binari come stringa. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Ottiene i dati binari come stringa utilizzando la tabella codici specificata. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Ottiene il valore come oggetto |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Restituisce aString che rappresenta la correnteObject . |

### Guarda anche

* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
