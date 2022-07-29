---
title: DestroyAttachments
second_title: Aspose.Email per riferimento all'API .NET
description: Distrugge gli allegati nei file dei messaggi di Outlook specificati. DestroyAttachments ignorerà lanalisi dellallegato.
type: docs
weight: 410
url: /it/net/aspose.email.mapi/mapimessage/destroyattachments/
---
## MapiMessage.DestroyAttachments method

Distrugge gli allegati nei file dei messaggi di Outlook specificati. DestroyAttachments ignorerà l'analisi dell'allegato.

```csharp
public static void DestroyAttachments(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il nome del file del messaggio di Outlook. |

### Esempi

L'esempio seguente mostra come distruggere gli allegati nei file dei messaggi di Outlook.

[C#]

[Visual Basic]

```csharp
//Distruggi gli allegati dai file dei messaggi di Outlook
MapiMessage.DestroyAttachment(@"c:\outlookmessage.msg");
```

```csharp
'Distruggi gli allegati dai file dei messaggi di Outlook
MapiMessage.DestroyAttachment("c:\outlookmessage.msg")
```

### Guarda anche

* class [MapiMessage](../../mapimessage)
* spazio dei nomi [Aspose.Email.Mapi](../../mapimessage)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->