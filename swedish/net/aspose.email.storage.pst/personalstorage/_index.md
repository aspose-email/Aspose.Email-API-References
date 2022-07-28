---
title: PersonalStorage
second_title: Aspose.Email för .NET API-referens
description: Representerar fil för personlig lagringstabell .pst.
type: docs
weight: 20290
url: /sv/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Representerar fil för personlig lagringstabell (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Initierar en ny instans av[`PersonalStorage`](../personalstorage) class. Tillåter att ställa in en återuppringningsmetod för att hantera undantag som inträffar under PST-passering. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Får ett värde som indikerar om den aktuella PST stöder skrivning. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Hämtar filformatet. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Får ett värde som indikerar om PST-filformatet är Unicode. Det finns två versioner av PST-filformatet: Unicode och ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Hämtar rotmappen för PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Hämtar PST-meddelandearkivet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Skapar PST i en ström. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Skapar den nya PST-filen med det angivna filnamnet. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Skapar PST i en ström. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Skapar PST i en ström. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Skapar den nya PST-filen med det angivna filnamnet. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Skapar PST i en ström. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | Ladda PST från fil. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | Ladda PST från fil. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | Ladda PST från fil. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | Ladda PST från fil. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Ladda PST från fil. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Ladda PST från stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Ladda PST från stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | Ladda PST från fil. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Ladda PST från stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Ladda PST från fil. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Ändrar meddelandeegenskaperna. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Konverterar det aktuella objektet till det angivna formatet. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Skapar standardmappen för interpersonellt meddelande (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Skapar standardmappen för interpersonellt meddelande (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Visar enumeratorn, som stöder en iteration av meddelanden i mappen. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Visar enumeratorn, som stöder en iteration av meddelanden i mappen. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Extraherar bilagorna. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Extraherar bilagorna. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Få meddelandet från PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Få meddelandet från PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Få meddelandet från PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Får den angivna egenskapen för objektet, utan att extrahera objektet helt. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Hittar identifierarna för meddelanden för den aktuella mappen. Det kan vara användbart vid läsning av skadad pst när metoderna GetContents och EnumerateMessages kan orsaka ett undantag. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Hittar identifierarna för undermappar för den aktuella mappen. Det kan vara användbart vid läsning av skadad pst när metoderna GetSubfolders och EnumerateFolders kan orsaka ett undantag. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Hämtar den personliga mappen från PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Hämtar den personliga mappen från PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Hämtar den överordnade mappen för meddelandet. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Hämtar den överordnade mappen för meddelandet. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Hämtar standardmappen för interpersonellt meddelande (IPM) från PST. Outlook kan skapa ett antal standardmappar, såsom Utkorg, Borttagna objekt, Skickade objekt etc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Ladda PST från stream. Denna metod används när ett PersonalStorage-objekt skapas med konstruktorn. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | Ladda PST från fil. Denna metod används när ett PersonalStorage-objekt skapas med konstruktorn. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Slår ihop pst-lagringen med en eller flera andra pst-strömmar. Den kombinerade strömmen är alltså källor. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Slår ihop pst-lagringen med en eller flera andra pst-filer. De kombinerade filerna är alltså källor. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Flyttar en angiven mapp till en ny överordnad mapp inom den aktuella pst. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Flyttar ett angivet meddelande till en ny mapp i den aktuella pst. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Sparar det aktuella objektet till ett angivet filformat i en ström. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Sparar det aktuella objektet till ett angivet filformat i en annan fil. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Sparar meddelandet, med angivet ingångs-ID, i en stream. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Delar upp pst-lagringen baserat på kriterier. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Delar upp pst-lagringen i mindre delar. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Hämtar mappen som är kopplad till angivet post-ID. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Sparar meddelandet, med angivet ingångs-ID, i en stream. |

### Se även

* namnutrymme [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
