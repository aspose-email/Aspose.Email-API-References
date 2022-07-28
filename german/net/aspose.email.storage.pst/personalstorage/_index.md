---
title: PersonalStorage
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert die Datei Personal Storage Table .pst.
type: docs
weight: 20290
url: /de/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Repräsentiert die Datei Personal Storage Table (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Initialisiert eine neue Instanz der[`PersonalStorage`](../personalstorage) class. Ermöglicht das Festlegen einer Rückrufmethode zum Behandeln von Ausnahmen, die während des PST-Durchlaufs auftreten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob die aktuelle pst das Schreiben unterstützt. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Ruft das Dateiformat ab. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Ruft einen Wert ab, der angibt, ob das PST-Dateiformat Unicode ist. Es gibt zwei Versionen des PST-Dateiformats: Unicode und ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Ruft den Stammordner von PST ab. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Ruft den PST-Nachrichtenspeicher ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Erstellt die PST in einem Stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Erstellt die neue PST-Datei mit dem angegebenen Dateinamen. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Erstellt die PST in einem Stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Erstellt die PST in einem Stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Erstellt die neue PST-Datei mit dem angegebenen Dateinamen. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Erstellt die PST in einem Stream. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | PST aus Datei laden. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | PST aus Datei laden. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | PST aus Datei laden. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | PST aus Datei laden. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | PST aus Datei laden. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | PST aus Stream laden. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | PST aus Stream laden. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | PST aus Datei laden. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | PST aus Stream laden. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | PST aus Datei laden. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Ändert die Nachrichteneigenschaften. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Konvertiert das aktuelle Objekt in das angegebene Format. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Erstellt den Standardordner für zwischenmenschliche Nachrichten (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Erstellt den Standardordner für zwischenmenschliche Nachrichten (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Führt anwendungsdefinierte Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Macht den Enumerator verfügbar, der eine Iteration von Nachrichten im Ordner unterstützt. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Extrahiert die Anhänge. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Extrahiert die Anhänge. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Holen Sie sich die Nachricht von PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Holen Sie sich die Nachricht von PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Holen Sie sich die Nachricht von PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Ruft die angegebene Eigenschaft des Elements ab, ohne das Element vollständig zu extrahieren. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Findet die Bezeichner von Nachrichten für den aktuellen Ordner. Dies kann nützlich sein, wenn eine beschädigte pst gelesen wird, wenn die Methoden GetContents und EnumerateMessages eine Ausnahme auslösen könnten. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Findet die Bezeichner von Unterordnern für den aktuellen Ordner. Dies kann nützlich sein, wenn beschädigte PST-Dateien gelesen werden, wenn die Methoden GetSubfolders und EnumerateFolders eine Ausnahme auslösen könnten. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Ruft den persönlichen Ordner von PST ab. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Ruft den persönlichen Ordner von PST ab. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Ruft den übergeordneten Ordner der Nachricht ab. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Ruft den übergeordneten Ordner der Nachricht ab. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Ruft den Standardordner für zwischenmenschliche Nachrichten (IPM) aus PST ab. Outlook kann eine Reihe von Standardordnern erstellen, wie Postausgang, Gelöschte Objekte, Gesendete Objekte usw. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | PST aus Stream laden. Diese Methode wird verwendet, wenn ein PersonalStorage-Objekt mit dem Konstruktor erstellt wird. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | PST aus Datei laden. Diese Methode wird verwendet, wenn ein PersonalStorage-Objekt mit dem Konstruktor erstellt wird. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Führt den pst-Speicher mit einem oder mehreren anderen pst-Streams zusammen. Somit sind die kombinierten Streams Quellen. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Führt den PST-Speicher mit einer oder mehreren anderen PST-Dateien zusammen. Somit sind die kombinierten Dateien Quellen. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Verschiebt einen angegebenen Ordner in einen neuen übergeordneten Ordner innerhalb der aktuellen pst. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Verschiebt eine angegebene Nachricht in einen neuen Ordner innerhalb der aktuellen PST. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Speichert das aktuelle Objekt in einem angegebenen Dateiformat in einem Stream. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Speichert das aktuelle Objekt in einem bestimmten Dateiformat in einer anderen Datei. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Speichert die Nachricht mit der angegebenen Eintrags-ID in einem Stream. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Teilt den PST-Speicher nach Kriterien auf. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Teilt den PST-Speicher in kleinere Teile auf. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Ruft den Ordner ab, der der angegebenen Eintrags-ID zugeordnet ist. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Speichert die Nachricht mit der angegebenen Eintrags-ID in einem Stream. |

### Siehe auch

* namensraum [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
