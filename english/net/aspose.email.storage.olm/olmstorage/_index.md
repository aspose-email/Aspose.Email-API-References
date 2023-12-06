---
title: Class OlmStorage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Olm.OlmStorage class. Represents Outlook for Mac storage .OLM file
type: docs
weight: 20250
url: /net/aspose.email.storage.olm/olmstorage/
---
## OlmStorage class

Represents Outlook for Mac storage (.OLM) file.

```csharp
public class OlmStorage : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [OlmStorage](olmstorage/#constructor_1)(Stream) | Initializes a new instance of the `OlmStorage` class. |
| [OlmStorage](olmstorage/#constructor_2)(string) | Initializes a new instance of the `OlmStorage` class. |
| [OlmStorage](olmstorage/#constructor)(TraversalExceptionsCallback) | Initializes a new instance of the `OlmStorage` class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal. |

## Properties

| Name | Description |
| --- | --- |
| [FolderHierarchy](../../aspose.email.storage.olm/olmstorage/folderhierarchy/) { get; } | Gets the folder hierarchy. |

## Methods

| Name | Description |
| --- | --- |
| static [FromFile](../../aspose.email.storage.olm/olmstorage/fromfile/)(string) | Load OLM storage from file. |
| static [FromStream](../../aspose.email.storage.olm/olmstorage/fromstream/)(Stream) | Load OLM from stream. |
| [Dispose](../../aspose.email.storage.olm/olmstorage/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](../../aspose.email.storage.olm/olmstorage/enumeratemessages/)(OlmFolder) | Exposes the enumerator, which supports an iteration of messages in folder. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage/#extractmapimessage)(OlmMessageInfo) | Get the message from OLM storage. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage/#extractmapimessage_1)(string) | Get the message from OLM. |
| [GetFolder](../../aspose.email.storage.olm/olmstorage/getfolder/)(string, bool) | Gets the folder by name. |
| [GetFolders](../../aspose.email.storage.olm/olmstorage/getfolders/)() | Gets collection of folders. |
| [GetTotalItemsCount](../../aspose.email.storage.olm/olmstorage/gettotalitemscount/)() | Gets the total items count. Returns the total number of message items contained in the OLM. |
| [Load](../../aspose.email.storage.olm/olmstorage/load/#load)(Stream) | Load OLM storage from stream. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter. |
| [Load](../../aspose.email.storage.olm/olmstorage/load/#load_1)(string) | Load OLM storage from file. This method is used when a OlmStorage object is created using constructor with the TraversalExceptionsCallback parameter. |

### See Also

* namespace [Aspose.Email.Storage.Olm](../../aspose.email.storage.olm/)
* assembly [Aspose.Email](../../)


