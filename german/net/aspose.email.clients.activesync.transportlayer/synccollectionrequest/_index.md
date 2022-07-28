---
title: SyncCollectionRequest
second_title: Aspose.Email für .NET-API-Referenz
description: Klasse enthält Befehle und Optionen die für eine bestimmte Sammlung gelten.
type: docs
weight: 2190
url: /de/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

Klasse enthält Befehle und Optionen, die für eine bestimmte Sammlung gelten.

```csharp
public class SyncCollectionRequest
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Gibt die Server-ID des zu synchronisierenden Ordners an. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Enthält Vorgänge, die für eine Sammlung gelten. Verfügbare Operationen sind Hinzufügen, Löschen, Ändern, Abrufen und SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Gibt an, ob Elemente, die in der Konversationsmodalität enthalten sind, in die Ergebnisse der Sync-Antwort eingeschlossen werden sollen. Wenn der Wert des ConversationMode-Elements auf TRUE gesetzt wird, werden alle E-Mails abgerufen, die mit den Konversationen übereinstimmen, die innerhalb des angegebenen Datumsfilters empfangen wurden. Obwohl der Text der E-Mails außerhalb dieses zeitbasierten Filters nicht abgerufen wird, werden die Textvorschauen abgerufen, wenn die Vorschau angefordert wurde. Das Festlegen des ConversationMode-Elementwerts auf FALSE in einer Synchronisierungsanforderung führt zur Synchronisierung von Elemente, die die Kriterien des Werts des FilterType-Elements (Abschnitt 2.2.3.64) erfüllen. Das Festlegen des ConversationMode-Elementwerts auf TRUE erweitert die Ergebnismenge, sodass sie auch alle Elemente mit identischen Werten für email2:ConversationId ([MS-ASEMAIL] Abschnitt 2.2.2.14) wie die in der FilterType-Ergebnismenge enthält. Der ConversationMode-Elementwert hat keine Auswirkungen auf Elemente außerhalb der durch das CollectionId-Element angegebenen Sammlung (Abschnitt 2.2.3.30.5); die Ergebnismenge ist immer auf Elemente in der angegebenen Sammlung beschränkt. Der ConversationMode-Elementwert begrenzt oder erweitert nur die Ergebnisse, die durch den FilterType-Elementwert bestimmt werden. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Anfragen, die angeben, dass alle gelöschten Elemente in den Ordner „Gelöschte Elemente“ verschoben werden SOLLTEN. Wenn das Element „DeletesAsMoves“ auf „false“ gesetzt ist, ist die Löschung dauerhaft. Wenn der Client Elemente dauerhaft löschen möchte, MUSS die Anforderung das Element DeletesAsMoves mit dem Wert FALSE enthalten. Der Standardwert TRUE gibt an, dass alle gelöschten Elemente in den Ordner „Gelöschte Elemente“ verschoben werden. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Fordert an, dass der Server alle ausstehenden Änderungen an der Sammlung, die durch das ServerId-Element (Abschnitt 2.2.3.151.6) angegeben ist, in seine Antwort aufnimmt. Wenn es seit der letzten Synchronisation Änderungen gegeben hat, enthält die Serverantwort ein Commands-Element (Abschnitt 2.2.3.32) , das Hinzufügungen, Löschungen und Änderungen enthält. Wenn der Client nicht möchte, dass die Serveränderungen zurückgegeben werden, MUSS die Anfrage enthalten das GetChanges-Element mit dem Wert FALSE. Der Wert TRUE gibt an, dass der Client die Rückgabe der Serveränderungen wünscht. Der Wert TRUE wird angenommen, wenn das GetChanges-Element leer ist. Wenn das GetChanges-Element nicht in der Anforderung vorhanden ist, hängt das Verhalten vom Wert des SyncKey-Elements ab, wie in Abschnitt 2.2.3.166.4 angegeben. Wenn das SyncKey-Element einen Wert von 0 hat, dann wird die Anfrage behandelt, als ob das GetChanges-Element auf FALSE gesetzt wäre. Wenn das SyncKey-Element einen Wert ungleich Null hat, wird die Anfrage so behandelt, als ob das GetChanges-Element gesetzt wäre auf WAHR. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Gibt Optionen an, die bestimmte Aspekte der Durchführung der Synchronisierung steuern. Zulässige Anzahl 0...2. Synchronisierungsoptionen ermöglichen es dem Client, Kürzungs- und Inhaltseinstellungen anzugeben. Diese Einstellungen sind in einem untergeordneten airsyncbase:BodyPreference-Element gekapselt, wie in [MS-ASAIRS] Abschnitt 2.2.2.7 angegeben. Da Synchronisierungsoptionen für eine Sammlung angegeben werden, kann der Client einen eindeutigen airsyncbase:BodyPreference-Elementwert für jede zu synchronisierende Sammlung angeben. Weitere Einzelheiten zum airsyncbase:BodyPreference-Element finden Sie in [MS-ASAIRS] Abschnitt 2.2. 2.7. Der Server behält den Optionsblock über Anforderungen hinweg bei, wobei er ein Konzept verwendet, das als "Sticky Options" bezeichnet wird. Wenn der Optionsblock nicht in einer Anfrage enthalten ist, wird der vorherige Optionsblock verwendet. Wenn der Client neue Optionen angibt, indem er einen Optionsblock in die Anfrage einfügt, MUSS der Server den ursprünglichen Optionsblock durch den neuen Optionsblock ersetzen. Wenn zwei Optionselemente in einer einzigen Sync-Befehlsanforderung enthalten sind, MUSS eines der Optionselemente Geben Sie die Synchronisierungsoptionen für die SMS-Klasse an, während das andere Optionselement die Optionen für die Standardklasse des angegebenen Ordners angibt. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Nicht geghostete Elemente der Contact-Klasse und der Calendar-Klasse können als untergeordnete Elemente des Supported-Elements eingeschlossen werden. Einzelheiten zur Verwendung von Geistereigenschaften finden Sie in Abschnitt 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | Der SyncKey-Wert wird vom Server verwendet, um den Synchronisierungsstatus einer Sammlung zu markieren. Ein Synchronisierungsschlüssel mit dem Wert 0 (Null) initialisiert den Synchronisierungsstatus auf dem Server und bewirkt eine vollständige Synchronisierung der Sammlung. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Gibt eine maximale Anzahl geänderter Elemente in einer Sammlung oder einer Anforderung an, die in die Synchronisierungsantwort aufgenommen werden SOLLTEN. Wenn WindowSize nicht definiert ist, verhält sich der Server so, als ob ein WindowSize-Element mit einem Wert von 100 übermittelt würde. Der Server interpretiert den Wert 0 (null) und Werte über 512 als 512. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
