---
title: LogEntry
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un messaggio di registro. Contiene le proprietà comuni richieste per tutti i messaggi di registro.
type: docs
weight: 20520
url: /it/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Rappresenta un messaggio di registro. Contiene le proprietà comuni richieste per tutti i messaggi di registro.

```csharp
public class LogEntry
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LogEntry](logentry#constructor)() | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_1)(byte[]) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_5)(string) | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Inizializza una nuova istanza di a[`LogEntry`](../logentry) classe. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Crea una nuova istanza di[`LogEntry`](../logentry) con un set completo di parametri del costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | L'AppDomain in cui stiamo eseguendo |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Corpo del messaggio binario da registrare. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Nome della categoria utilizzato per instradare la voce di registro a uno o più sink. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Dizionario delle coppie chiave/valore da registrare. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Ottiene il messaggio di errore con il[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Numero evento o identificatore. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Ottiene o imposta l'oggetto eccezione interno. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Nome del computer. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Corpo del messaggio da registrare. Valore dal metodo ToString() dall'oggetto messaggio. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Codifica per il corpo del messaggio binario |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | L'identificatore univoco dell'evento di registro che viene generato automaticamente e aumenta in modo monotono. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Severità della voce del registro come a[`Severity`](./severity) enumerazione. (Non specificato, Informazioni, Avvertimento o Errore). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | Il nome del thread .NET. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Data e ora del messaggio di immissione del registro. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Descrizione aggiuntiva del messaggio della voce di registro. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Aggiunge un messaggio di errore o di avviso all'inizio del generatore di stringhe di messaggi. Utilizzato dal distributore per registrare i problemi. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Crea un nuovo[`LogEntry`](../logentry) questa è una copia dell'istanza corrente. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Guarda anche

* spazio dei nomi [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
