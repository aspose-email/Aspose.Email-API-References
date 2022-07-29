---
title: OlmStorage
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt die Outlook für Mac-Speicherdatei .OLM dar.
type: docs
weight: 20120
url: /de/net/aspose.email.storage.olm/olmstorage/
---
## OlmStorage class

Stellt die Outlook für Mac-Speicherdatei (.OLM) dar.

```csharp
public class OlmStorage : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [OlmStorage](olmstorage#constructor_1)(Stream) | Initialisiert eine neue Instanz von[`OlmStorage`](../olmstorage) Klasse. |
| [OlmStorage](olmstorage#constructor_2)(string) | Initialisiert eine neue Instanz von[`OlmStorage`](../olmstorage) Klasse. |
| [OlmStorage](olmstorage#constructor)(TraversalExceptionsCallback) | Initialisiert eine neue Instanz der[`OlmStorage`](../olmstorage)class. Ermöglicht das Festlegen einer Callback-Methode zum Behandeln von Ausnahmen, die während des OLM-Speicherdurchlaufs auftreten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FolderHierarchy](../../aspose.email.storage.olm/olmstorage/folderhierarchy) { get; } | Ruft die Ordnerhierarchie ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../aspose.email.storage.olm/olmstorage/fromfile)(string) | OLM-Speicher aus Datei laden. |
| static [FromStream](../../aspose.email.storage.olm/olmstorage/fromstream)(Stream) | OLM aus Stream laden. |
| [Dispose](../../aspose.email.storage.olm/olmstorage/dispose)() | Führt anwendungsdefinierte Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| [EnumerateMessages](../../aspose.email.storage.olm/olmstorage/enumeratemessages)(OlmFolder) | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage)(OlmMessageInfo) | Holen Sie sich die Nachricht aus dem OLM-Speicher. |
| [GetFolder](../../aspose.email.storage.olm/olmstorage/getfolder)(string, bool) | Ruft den Ordner nach Namen ab. |
| [GetFolders](../../aspose.email.storage.olm/olmstorage/getfolders)() | Ruft eine Sammlung von Ordnern ab. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load)(Stream) | OLM-Speicher aus Stream laden. Diese Methode wird verwendet, wenn ein OlmStorage-Objekt mithilfe des Konstruktors mit dem TraversalExceptionsCallback-Parameter erstellt wird. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load_1)(string) | OLM-Speicher aus Datei laden. Diese Methode wird verwendet, wenn ein OlmStorage-Objekt mithilfe des Konstruktors mit dem Parameter TraversalExceptionsCallback erstellt wird. |

### Siehe auch

* namensraum [Aspose.Email.Storage.Olm](../../aspose.email.storage.olm)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->