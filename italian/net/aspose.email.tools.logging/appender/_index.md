---
title: Appender
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta la classe base per Appender.
type: docs
weight: 20430
url: /it/net/aspose.email.tools.logging/appender/
---
## Appender class

Rappresenta la classe base per Appender.

```csharp
public abstract class Appender : IAppender, IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Formatter](../../aspose.email.tools.logging/appender/formatter) { get; set; } | Ottiene o imposta il formattatore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Append](../../aspose.email.tools.logging/appender/append)(LogEntry) | Aggiunge la voce di registro specificata all'apper. |
| virtual [AppendHeader](../../aspose.email.tools.logging/appender/appendheader)() | Avvia il file di registro con un'intestazione specifica. |
| virtual [Close](../../aspose.email.tools.logging/appender/close)() | Chiude l'appendice. |
| [Dispose](../../aspose.email.tools.logging/appender/dispose)() | Rilascia le risorse non gestite utilizzate dall'appender. |
| virtual [Initialize](../../aspose.email.tools.logging/appender/initialize)() | Inizializza l'istanza appender. |

### Guarda anche

* interface [IAppender](../iappender)
* spazio dei nomi [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->