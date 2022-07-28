---
title: LogEntry
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert eine Protokollnachricht. Enthält die gemeinsamen Eigenschaften die für alle Protokollmeldungen erforderlich sind.
type: docs
weight: 20520
url: /de/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Repräsentiert eine Protokollnachricht. Enthält die gemeinsamen Eigenschaften, die für alle Protokollmeldungen erforderlich sind.

```csharp
public class LogEntry
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LogEntry](logentry#constructor)() | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_1)(byte[]) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_5)(string) | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Initialisiert eine neue Instanz von a[`LogEntry`](../logentry) Klasse. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Erstellen Sie eine neue Instanz von[`LogEntry`](../logentry) mit einem vollständigen Satz von Konstruktorparametern |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | Die AppDomain, in der wir laufen |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Zu protokollierender binärer Nachrichtentext. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Kategoriename, der zum Weiterleiten des Protokolleintrags an eine oder mehrere Senken verwendet wird. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Verzeichnis der aufzuzeichnenden Schlüssel/Wert-Paare. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Ruft die Fehlermeldung mit dem ab[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Ereignisnummer oder -kennung. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Ruft das innere Ausnahmeobjekt ab oder legt es fest. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Name des Computers. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Zu protokollierender Nachrichtentext. Wert aus der Methode ToString() aus dem Nachrichtenobjekt. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Kodierung für binären Nachrichtentext |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | Die eindeutige Kennung des Protokollereignisses, die automatisch generiert wird und monoton ansteigt. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Schweregrad des Protokolleintrags als a[`Severity`](./severity) Aufzählung. (Nicht spezifiziert, Information, Warnung oder Fehler). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | Der Name des .NET-Threads. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Datum und Uhrzeit der Protokolleintragsmeldung. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Zusätzliche Beschreibung der Protokolleintragsmeldung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Fügt eine Fehler- oder Warnmeldung am Anfang des Messages String Builder hinzu. Wird vom Distributor verwendet, um Probleme aufzuzeichnen. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Erstellt eine neue[`LogEntry`](../logentry) das ist eine Kopie der aktuellen Instanz. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Siehe auch

* namensraum [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
