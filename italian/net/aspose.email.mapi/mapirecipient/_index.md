---
title: MapiRecipient
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta le informazioni sul destinatario nel messaggio di Microsoft Outlook.
type: docs
weight: 18620
url: /it/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

Rappresenta le informazioni sul destinatario nel messaggio di Microsoft Outlook.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | Ottiene il tipo dell'indirizzo di il destinatario o il mittente del messaggio. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | Ottiene il contenuto. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | Ottiene o imposta il nome visualizzato del destinatario o del mittente del messaggio . |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | Ottiene o imposta l'indirizzo e-mail del destinatario o del mittente del messaggio . |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | Ottiene l'indirizzo email dell'organizzazione. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | Ottiene il tipo di ricettante. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | Stato della risposta del destinatario a una convocazione di riunione. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | Ottiene il tipo del destinatario o del mittente. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | Ottiene i sottoarchivi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
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
