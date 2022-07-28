---
title: QueryType
second_title: Aspose.Email für .NET-API-Referenz
description: Gibt die Schlüsselwörter an die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach John mit John Frum oder Barry Johnson übereinstimmen aber nicht mit James Littlejohn. Alle nicht leeren Texteigenschaften in der GAL die mithilfe von ANR indiziert werden werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form LinkId  Wert wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt - Ordner können auf folgende Weise angegeben werden Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner einschließlich Entwurf Posteingang und Unterordner Postausgang und Gesendete Elemente  Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen Der Basisoperator And Abschnitt 2.2.3.10 Ein dateTime-Filter der mithilfe von GreaterThan Abschnitt 2.2.3.78 und LessThan angegeben wird Elemente Abschnitt 2.2.3.87 FreeText-Elemente Abschnitt 2.2.3.73 die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt.
type: docs
weight: 1780
url: /de/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Gibt die Schlüsselwörter an, die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück, die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach „John“ mit „John Frum“ oder „Barry Johnson“ übereinstimmen, aber nicht mit „James Littlejohn“. Alle nicht leeren Texteigenschaften in der GAL, die mithilfe von ANR indiziert werden, werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form: LinkId == Wert, wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt: - Ordner können auf folgende Weise angegeben werden: Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner, einschließlich Entwurf, Posteingang und Unterordner, Postausgang und Gesendete Elemente – Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen: Der Basisoperator: And (Abschnitt 2.2.3.10) Ein dateTime-Filter, der mithilfe von GreaterThan (Abschnitt 2.2.3.78) und LessThan angegeben wird Elemente (Abschnitt 2.2.3.87) FreeText-Elemente (Abschnitt 2.2.3.73), die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt.

```csharp
public class QueryType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [QueryType](querytype)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Identifiziert die Klasse des Elements. Die gültigen airsync:Class-Elementwerte sind: - Aufgaben - E-Mail - Kalender - Kontakte - Notizen - SMS Die folgenden Klassen werden für Postfachsuchen unterstützt, wenn die Protokollversion 12.1 ist: E-Mail, Kalender, Kontakte, Aufgaben. Die SMS- und Notes-Klassen sind nur verfügbar, wenn die Protokollversion 14.0 oder 14.1 ist. Die Suchanforderung kann ein oder mehrere Class-Elemente in der Anforderung enthalten, um den in der Suchantwort enthaltenen Datentyp einzuschränken. Wenn ein oder mehrere Class-Elemente nicht in der Suchanforderung enthalten sind, gibt der Server alle unterstützten Klassen zurück. Wenn die Klasse als untergeordnetes Element eines anderen Elements als des And-Elements enthalten ist, antwortet der Server mit einem Statuswert von 8 (SearchTooComplex). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Gibt den Ordner an, in dem gesucht werden soll. Wenn DeepTraversal vorhanden ist, gilt es für alle Ordner unter jeder CollectionId. Wenn die CollectionId als untergeordnetes Element eines anderen Elements als And enthalten ist, antwortet der Server mit einem Statuswert von 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Gibt die Konversation an, nach der gesucht werden soll. Der Wert ist eine GUID. Die ConversationId wird nicht unterstützt, wenn die Protokollversion 12.1 ist. Wenn die ConversationId als untergeordnetes Element eines anderen Elements als des And-Elements enthalten ist, antwortet der Server mit einem Statuswert von 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Gibt einen Zeichenfolgenwert an, nach dem gesucht werden soll. Wenn die FreeText-Eigenschaft anders als die And-Eigenschaft festgelegt ist, antwortet der Server mit einem Statuswert von 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Gibt eine Eigenschaft und einen Wert an, die während einer Suche auf „Größer als“-Bedingungen verglichen werden. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Gibt eine Eigenschaft und einen Wert an, die während einer Suche auf „Kleiner als“-Bedingungen verglichen werden. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
