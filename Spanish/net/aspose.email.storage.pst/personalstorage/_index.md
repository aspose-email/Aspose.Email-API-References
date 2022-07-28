---
title: PersonalStorage
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el archivo de tabla de almacenamiento personal .pst.
type: docs
weight: 20290
url: /es/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Representa el archivo de tabla de almacenamiento personal (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Inicializa una nueva instancia del[`PersonalStorage`](../personalstorage) class. Permite configurar un método de devolución de llamada para manejar las excepciones que ocurren durante el recorrido PST. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Obtiene un valor que indica si el pst actual admite escritura. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Obtiene el formato de archivo. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Obtiene un valor que indica si el formato de archivo PST es Unicode. Hay dos versiones del formato de archivo PST: Unicode y ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Obtiene la carpeta raíz de PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Obtiene el almacén de mensajes PST. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Crea el PST en un stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Crea el nuevo archivo PST con el nombre de archivo especificado. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Crea el PST en un stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Crea el PST en un stream. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Crea el nuevo archivo PST con el nombre de archivo especificado. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Crea el PST en un stream. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | Cargar PST desde archivo. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | Cargar PST desde archivo. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | Cargar PST desde archivo. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | Cargar PST desde archivo. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Cargar PST desde archivo. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Cargar PST desde flujo. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Cargar PST desde flujo. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | Cargar PST desde archivo. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Cargar PST desde flujo. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Cargar PST desde archivo. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Cambia las propiedades del mensaje. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Convierte el objeto actual al formato especificado. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Crea la carpeta de mensajes interpersonales estándar (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Crea la carpeta de mensajes interpersonales estándar (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Realiza tareas definidas por la aplicación asociadas con la liberación, liberación o el restablecimiento de recursos no administrados. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Extrae los adjuntos. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Extrae los adjuntos. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Obtener el mensaje de PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Obtener el mensaje de PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Obtener el mensaje de PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Obtiene la propiedad especificada del elemento, sin extraer el elemento por completo. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Encuentra los identificadores de los mensajes para la carpeta actual. Puede ser útil en caso de leer archivos pst dañados cuando los métodos GetContents y EnumerateMessages pueden generar una excepción. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Encuentra los identificadores de las subcarpetas para la carpeta actual. Puede ser útil en caso de leer archivos pst corruptos cuando los métodos GetSubfolders y EnumerateFolders pueden generar una excepción. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Obtiene la carpeta personal de PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Obtiene la carpeta personal de PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Obtiene la carpeta principal del mensaje. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Obtiene la carpeta principal del mensaje. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Obtiene la carpeta de mensajes interpersonales estándar (IPM) de PST. Outlook puede crear varias carpetas predeterminadas, como Bandeja de salida, Elementos eliminados, Elementos enviados, etc. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Cargar PST desde flujo. Este método se usa cuando se crea un objeto PersonalStorage usando el constructor. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | Cargar PST desde archivo. Este método se usa cuando se crea un objeto PersonalStorage usando el constructor. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Fusiona el almacenamiento pst con uno o más flujos pst. Por lo tanto, el flujo combinado son fuentes. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Fusiona el almacenamiento pst con uno o más archivos pst. Por lo tanto, los archivos combinados son fuentes. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Mueve una carpeta especificada a una nueva carpeta principal dentro del pst actual. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Mueve un mensaje específico a una nueva carpeta dentro del pst actual. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Guarda el objeto actual en un formato de archivo especificado en una secuencia. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Guarda el objeto actual en un formato de archivo especificado en un archivo diferente. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Guarda el mensaje, con el ID de entrada especificado, en un flujo. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Divide el almacenamiento pst según los criterios. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Divide el almacenamiento pst en partes de menor tamaño. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Obtiene la carpeta asociada con el Id. de entrada especificado. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Guarda el mensaje, con el ID de entrada especificado, en un flujo. |

### Ver también

* espacio de nombres [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
