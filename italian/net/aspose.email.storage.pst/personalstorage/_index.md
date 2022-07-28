---
title: PersonalStorage
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta il file della tabella di archiviazione personale .pst.
type: docs
weight: 20290
url: /it/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Rappresenta il file della tabella di archiviazione personale (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Inizializza una nuova istanza di[`PersonalStorage`](../personalstorage) class. Consente di impostare un metodo di callback per la gestione delle eccezioni che si verificano durante l'attraversamento PST. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Ottiene un valore che indica se il pst corrente supporta la scrittura. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Ottiene il formato del file. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Ottiene un valore che indica se il formato del file PST è Unicode. Esistono due versioni del formato del file PST: Unicode e ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Ottiene la cartella principale di PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Ottiene l'archivio dei messaggi PST. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Crea il PST in un flusso. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Crea il nuovo file PST con il nome file specificato. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Crea il PST in un flusso. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Crea il PST in un flusso. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Crea il nuovo file PST con il nome file specificato. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Crea il PST in un flusso. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | Carica PST da file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | Carica PST da file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | Carica PST da file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | Carica PST da file. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Carica PST da file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Carica PST dallo stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Carica PST dallo stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | Carica PST da file. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Carica PST dallo stream. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Carica PST da file. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Modifica le proprietà del messaggio. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Converte l'oggetto corrente nel formato specificato. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Crea la cartella dei messaggi interpersonali standard (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Crea la cartella dei messaggi interpersonali standard (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio di o al ripristino di risorse non gestite. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella cartella. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella cartella. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Estrae gli allegati. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Estrae gli allegati. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Ricevi il messaggio da PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Ricevi il messaggio da PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Ricevi il messaggio da PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Ottiene la proprietà specificata dell'elemento, senza estrarre completamente l'elemento. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Trova gli identificatori dei messaggi per la cartella corrente. Potrebbe essere utile in caso di lettura di file pst danneggiati quando i metodi GetContents ed EnumerateMessages potrebbero generare un'eccezione. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Trova gli identificatori delle sottocartelle per la cartella corrente. Potrebbe essere utile in caso di lettura di file pst danneggiati quando i metodi GetSubfolders ed EnumerateFolders potrebbero generare un'eccezione. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Ottiene la cartella personale da PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Ottiene la cartella personale da PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Ottiene la cartella principale del messaggio. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Ottiene la cartella principale del messaggio. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Ottiene la cartella dei messaggi interpersonali standard (IPM) da PST. Outlook può creare un numero di cartelle predefinite, come Posta in uscita, Posta eliminata, Posta inviata ecc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Carica PST da stream. Questo metodo viene utilizzato quando viene creato un oggetto PersonalStorage utilizzando il costruttore. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | Carica PST da file. Questo metodo viene utilizzato quando viene creato un oggetto PersonalStorage utilizzando il costruttore. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Unisce la memoria pst con uno o più altri flussi pst. Pertanto, il flusso combinato sono sorgenti. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Unisce la memoria pst con uno o più altri file pst. Pertanto, i file combinati sono sorgenti. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Sposta una cartella specificata in una nuova cartella principale all'interno del pst. corrente |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Sposta un messaggio specificato in una nuova cartella all'interno del pst. corrente |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Salva l'oggetto corrente in un formato file specificato in uno stream. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Salva l'oggetto corrente in un formato file specificato in un file diverso. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Salva il messaggio, con entryID specificato, in uno stream. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Divide la memoria pst in base a criteri. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Divide la memoria pst in parti di dimensioni inferiori. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Ottiene la cartella associata all'ID voce specificato. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Salva il messaggio, con entryID specificato, in uno stream. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
