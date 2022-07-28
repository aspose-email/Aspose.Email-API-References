---
title: LogEntry
second_title: Aspose.Email för .NET API-referens
description: Representerar ett loggmeddelande. Innehåller de gemensamma egenskaperna som krävs för alla loggmeddelanden.
type: docs
weight: 20520
url: /sv/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Representerar ett loggmeddelande. Innehåller de gemensamma egenskaperna som krävs för alla loggmeddelanden.

```csharp
public class LogEntry
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LogEntry](logentry#constructor)() | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_1)(byte[]) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_5)(string) | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Initiera en ny instans av en[`LogEntry`](../logentry) class. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Skapa en ny instans av[`LogEntry`](../logentry) med en fullständig uppsättning konstruktorparametrar |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | AppDomain där vi kör |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Binär meddelandetext att logga. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Kategorinamn som används för att dirigera loggposten till en eller flera diskbänkar. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Ordbok över nyckel/värdepar att spela in. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Får felmeddelandet med[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Händelsenummer eller identifierare. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Hämtar eller ställer in det inre undantagsobjektet. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Datorns namn. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Meddelandetext att logga. Värde från metoden ToString() från meddelandeobjekt. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Kodning för binär meddelandetext |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | Den unika identifieraren för logghändelsen som genereras automatiskt och monotont ökar. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Loggpostens svårighetsgrad som en[`Severity`](./severity) uppräkning. (Ospecificerat, information, varning eller fel). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | Namnet på .NET-tråden. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Datum och tid för logginmatningsmeddelandet. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Ytterligare beskrivning av loggpostmeddelandet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Lägg till ett fel- eller varningsmeddelande i början av meddelandesträngbyggaren. Används av distributören för att registrera problem. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Skapar en ny[`LogEntry`](../logentry) det är en kopia av den aktuella instansen. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Se även

* namnutrymme [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
