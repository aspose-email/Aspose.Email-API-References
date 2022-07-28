---
title: PidTagPropertyDescriptor
second_title: Aspose.Email per riferimento all'API .NET
description: La classe contiene informazioni sulla descrizione della proprietà.
type: docs
weight: 18990
url: /it/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

La classe contiene informazioni sulla descrizione della proprietà.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Inizializza una nuova istanza di[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una proprietà definita da un ID proprietà a 16 bit e un tipo di proprietà a 16 bit. L'ID proprietà per una proprietà con tag è compreso nell'intervallo 0x001 � 0x7FFF. Gli ID proprietà nell'intervallo 0x8000 � 0x8FFF sono riservati per l'assegnazione a proprietà denominate |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Inizializza una nuova istanza di[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una proprietà definita da un ID proprietà a 16 bit e un tipo di proprietà a 16 bit. L'ID proprietà per una proprietà con tag è compreso nell'intervallo 0x001 � 0x7FFF. Gli ID proprietà nell'intervallo 0x8000 � 0x8FFF sono riservati per l'assegnazione a proprietà denominate |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Inizializza una nuova istanza di[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una proprietà definita da un ID proprietà a 16 bit e un tipo di proprietà a 16 bit. L'ID proprietà per una proprietà con tag è compreso nell'intervallo 0x001 � 0x7FFF. Gli ID proprietà nell'intervallo 0x8000 � 0x8FFF sono riservati per l'assegnazione a proprietà denominate |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Inizializza una nuova istanza di[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una proprietà definita da un ID proprietà a 16 bit e un tipo di proprietà a 16 bit. L'ID proprietà per una proprietà con tag è compreso nell'intervallo 0x001 � 0x7FFF. Gli ID proprietà nell'intervallo 0x8000 � 0x8FFF sono riservati per l'assegnazione a proprietà denominate |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Inizializza una nuova istanza di[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una proprietà definita da un ID proprietà a 16 bit e un tipo di proprietà a 16 bit. L'ID proprietà per una proprietà con tag è compreso nell'intervallo 0x001 � 0x7FFF. Gli ID proprietà nell'intervallo 0x8000 � 0x8FFF sono riservati per l'assegnazione a proprietà denominate |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Il nome utilizzato per fare riferimento alla proprietà nella documentazione. Il prefisso del nome canonico identifica le caratteristiche di base di una proprietà per l'implementatore. La struttura di denominazione canonica utilizza tre categorie denotate dai seguenti prefissi al nome della proprietà canonica: * Prefisso PidLid: proprietà identificate da una quantità a 32 bit senza segno insieme a un insieme di proprietà. * Prefisso PidName: proprietà identificate da un nome stringa insieme a un insieme di proprietà. * Prefisso PidTag: proprietà identificate da una quantità a 16 bit senza segno. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Il tipo di valore della proprietà, come descritto in [MS-OXCDATA], che specifica il tipo di valori consentiti per la proprietà. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Ottiene una quantità a 16 bit senza segno che identifica una proprietà con tag. Gli ID proprietà non sono necessariamente univoci. Ad eccezione degli ID proprietà nell'intervallo da 0x6800 a 0x7BFF, la combinazione di ID proprietà e tipo di dati è univoca. Gli ID proprietà nell'intervallo da 0x6800 a 0x7BFF sono definiti dalla classe di messaggio. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indica se il tipo di dati contiene più valori |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Ottiene una stringa che identifica una proprietà. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Un tag di proprietà è un numero a 32 bit che contiene un identificatore di proprietà univoco nei bit da 16 a 31 e un tipo di proprietà nei bit da 0 a 15. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Determina se l'oggetto System.Object specificato è uguale all'oggetto System.Object. corrente |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Serve come funzione hash per un tipo. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Restituisce una stringa che rappresenta la descrizione della proprietà. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Determina se gli oggetti specificati sono uguali tra loro. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Converte il valore del tag in proprietà con tag |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Determina se gli oggetti specificati non sono uguali tra loro. |

### Guarda anche

* class [PropertyDescriptor](../propertydescriptor)
* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
