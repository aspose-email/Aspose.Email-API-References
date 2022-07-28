---
title: PersonalStorage
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le fichier de table de stockage personnel .pst.
type: docs
weight: 20290
url: /fr/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Représente le fichier de table de stockage personnel (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Initialise une nouvelle instance du[`PersonalStorage`](../personalstorage) class. Permet de définir une méthode de rappel pour gérer les exceptions qui se produisent lors de la traversée PST. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Obtient une valeur indiquant si le pst actuel prend en charge l'écriture. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Obtient le format de fichier. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Obtient une valeur indiquant si le format de fichier PST est Unicode. Il existe deux versions du format de fichier PST : Unicode et ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Obtient le dossier racine de PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Obtient le magasin de messages PST. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Crée le PST dans un flux. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Crée le nouveau fichier PST avec le nom de fichier spécifié. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Crée le PST dans un flux. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Crée le PST dans un flux. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Crée le nouveau fichier PST avec le nom de fichier spécifié. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Crée le PST dans un flux. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | Charger PST à partir du fichier. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | Charger PST à partir du fichier. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | Charger PST à partir du fichier. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | Charger PST à partir du fichier. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Charger PST à partir du fichier. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Charger PST à partir du flux. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Charger PST à partir du flux. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | Charger PST à partir du fichier. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Charger PST à partir du flux. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Charger PST à partir du fichier. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Modifie les propriétés du message. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Convertit l'objet actuel au format spécifié. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Crée le dossier de messages interpersonnels standard (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Crée le dossier de messages interpersonnels standard (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Effectue des tâches définies par l'application associées à la libération, de la libération ou de la réinitialisation des ressources non gérées. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Extrait les pièces jointes. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Extrait les pièces jointes. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Récupérez le message de PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Récupérez le message de PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Récupérez le message de PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Obtient la propriété spécifiée de l'élément, sans extraire complètement l'élément. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Trouve les identifiants des messages pour le dossier actuel. Cela peut être utile en cas de lecture de pst corrompu lorsque les méthodes GetContents et EnumerateMessages peuvent lever une exception. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Trouve les identifiants des sous-dossiers pour le dossier actuel. Cela peut être utile en cas de lecture de pst corrompu lorsque les méthodes GetSubfolders et EnumerateFolders peuvent lever une exception. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Obtient le dossier personnel de PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Obtient le dossier personnel de PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Obtient le dossier parent du message. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Obtient le dossier parent du message. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Obtient le dossier de messages interpersonnels standard (IPM) à partir de PST. Outlook peut créer un certain nombre de dossiers par défaut, tels que Boîte d'envoi, Éléments supprimés, Éléments envoyés, etc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Charger PST à partir du flux. Cette méthode est utilisée lorsqu'un objet PersonalStorage est créé à l'aide du constructeur. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | Charger PST à partir du fichier. Cette méthode est utilisée lorsqu'un objet PersonalStorage est créé à l'aide du constructeur. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Fusionne le stockage pst avec un ou plusieurs autres flux pst. Ainsi, les flux combinés sont des sources. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Fusionne le stockage pst avec un ou plusieurs autres fichiers pst. Ainsi, les fichiers combinés sont des sources. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Déplace un dossier spécifié vers un nouveau dossier parent dans le pst actuel. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Déplace un message spécifié vers un nouveau dossier dans le pst actuel. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Enregistre l'objet actuel dans un format de fichier spécifié dans un flux. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Enregistre l'objet actuel dans un format de fichier spécifié dans un autre fichier. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Enregistre le message, avec l'ID d'entrée spécifié, dans un flux. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Divise le stockage pst en fonction de critères. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Divise le stockage pst en parties de taille inférieure. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Obtient le dossier associé à l'ID d'entrée spécifié. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Enregistre le message, avec l'ID d'entrée spécifié, dans un flux. |

### Voir également

* espace de noms [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
