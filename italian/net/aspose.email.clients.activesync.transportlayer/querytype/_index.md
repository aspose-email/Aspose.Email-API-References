---
title: QueryType
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica le parole chiave da utilizzare per la corrispondenza delle voci nellarchivio in cui viene eseguita la ricerca. Il valore della query viene utilizzato come modello di corrispondenza della stringa di prefisso e restituisce le voci che corrispondono allinizio della stringa. Ad esempio la ricerca di John corrisponderebbe a John Frum o Barry Johnson ma non corrisponderebbe a James Littlejohn. Tutte le proprietà di testo non vuote nel GAL indicizzate tramite ANR vengono confrontate con lelemento Query valore. I confronti di ricerca vengono eseguiti utilizzando la corrispondenza senza distinzione tra maiuscole e minuscole. Per una ricerca nella raccolta documenti di Windows SharePoint Services questo protocollo supporta le query nel formato seguente LinkId  valore dove valore specifica lURL dellelemento o della cartella e LinkId indica che il valore deve essere confrontato con la proprietà dellID collegamento. Per la ricerca nella casella di posta la sintassi della query è la seguente - Le cartelle possono essere specificate nei seguenti modi ID specificato Cartella e sottocartelle specificate Tutte le cartelle di posta elettronica inclusa Bozza Posta in arrivo e sottocartelle Posta in uscita e Posta inviata - La query della parola chiave di base può essere composta da quanto segue Loperatore di base And sezione 2.2.3.10 Un filtro dateTime specificato utilizzando GreaterThan sezione 2.2.3.78 e LessThan elementi sezione 2.2.3.87 Elementi FreeText sezione 2.2.3.73 che contengono parole chiave La query di base per parole chiave viene eseguita su tutte le proprietà indicizzate.
type: docs
weight: 1780
url: /it/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Specifica le parole chiave da utilizzare per la corrispondenza delle voci nell'archivio in cui viene eseguita la ricerca. Il valore della query viene utilizzato come modello di corrispondenza della stringa di prefisso e restituisce le voci che corrispondono all'inizio della stringa. Ad esempio, la ricerca di "John" corrisponderebbe a "John Frum" o "Barry Johnson", ma non corrisponderebbe a "James Littlejohn". Tutte le proprietà di testo non vuote nel GAL indicizzate tramite ANR vengono confrontate con l'elemento Query valore. I confronti di ricerca vengono eseguiti utilizzando la corrispondenza senza distinzione tra maiuscole e minuscole. Per una ricerca nella raccolta documenti di Windows SharePoint Services, questo protocollo supporta le query nel formato seguente: LinkId == valore, dove valore specifica l'URL dell'elemento o della cartella e LinkId indica che il valore deve essere confrontato con la proprietà dell'ID collegamento. Per la ricerca nella casella di posta, la sintassi della query è la seguente: - Le cartelle possono essere specificate nei seguenti modi: ID specificato Cartella e sottocartelle specificate Tutte le cartelle di posta elettronica, inclusa Bozza, Posta in arrivo e sottocartelle, Posta in uscita e Posta inviata - La query della parola chiave di base può essere composta da quanto segue: L'operatore di base: And (sezione 2.2.3.10) Un filtro dateTime specificato utilizzando GreaterThan (sezione 2.2.3.78) e LessThan elementi (sezione 2.2.3.87) Elementi FreeText (sezione 2.2.3.73) che contengono parole chiave La query di base per parole chiave viene eseguita su tutte le proprietà indicizzate.

```csharp
public class QueryType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QueryType](querytype)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Identifica la classe dell'elemento. I valori validi dell'elemento airsync:Class sono: - Tasks - Email - Calendar - Contacts - Notes - SMS Le seguenti classi sono supportate per le ricerche quando la versione del protocollo è 12.1: Email, Calendar, Contatti, Compiti. Le classi SMS e Notes sono disponibili solo se la versione del protocollo è 14.0 o 14.1. La richiesta di ricerca può includere uno o più elementi di classe nella richiesta per limitare il tipo di dati inclusi nella risposta di ricerca. Se uno o più elementi Class non sono inclusi nella richiesta di ricerca, il server restituirà tutte le classi supportate. Se la classe è inclusa come figlia di qualsiasi elemento diverso dall'elemento And, il server risponde con un valore di stato di 8 (SearchTooComplex). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Specifica la cartella in cui eseguire la ricerca. Se DeepTraversal è presente, si applica a tutte le cartelle sotto ogni CollectionId. Se CollectionId è incluso come figlio di qualsiasi elemento diverso da And, il server risponde con un valore di stato pari a 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Specifica la conversazione in cui cercare. Il valore è un GUID. ConversationId non è supportato quando la versione del protocollo è 12.1. Se ConversationId è incluso come figlio di qualsiasi elemento diverso da And, il server risponde con un valore Status di 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Specifica un valore di stringa per cui eseguire la ricerca. Se la proprietà FreeText è impostata su un valore diverso da And, il server risponde con un valore di stato pari a 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Specifica una proprietà e un valore che vengono confrontati per una condizione "Maggiore di" durante una ricerca. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Specifica una proprietà e un valore che vengono confrontati per una condizione "Inferiore a" durante una ricerca. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
