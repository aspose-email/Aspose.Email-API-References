---
title: SyncCollectionRequest
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 2190
url: /net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

Class contains commands and options that apply to a particular collection.

```csharp
public class SyncCollectionRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Specifies the server ID of the folder to be synchronized. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Contains operations that apply to a collection. Available operations are Add, Delete, Change, Fetch, and SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Specifies whether to include items that are included within the conversation modality within the results of the Sync response. Setting the ConversationMode element value to TRUE results in retrieving all emails that match the conversations received within the date filter specified. However, although the body of the emails outside of that time based filter will not be retrieved, the text previews will be retrieved if the previews were requested.Setting the ConversationMode element value to FALSE in a Sync request results in the synchronization of items that meet the criteria of the FilterType element (section 2.2.3.64) value. Setting the ConversationMode element value to TRUE expands the result set to also include any items with identical email2:ConversationId ([MS-ASEMAIL] section 2.2.2.14) values to those in the FilterType result set. The ConversationMode element value has no impact on items outside the collection specified by the CollectionId element (section 2.2.3.30.5); the result set is always limited to items in the specified collection. The ConversationMode element value only limits or expands the results determined by the FilterType element value. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Requests that indicates that any deleted items SHOULD be moved to the Deleted Items folder. If the DeletesAsMoves element is set to false, the deletion is permanent. If the client wants to permanently delete items, the request MUST include the DeletesAsMoves element with a value of FALSE. A value of TRUE, which is the default, indicates that any deleted items are moved to the Deleted Items folder. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Requests that the server include in its response any pending changes to the collection that is specified by the ServerId element (section 2.2.3.151.6). If there have been changes since the last synchronization, the server response includes a Commands element (section 2.2.3.32) that contains additions, deletions, and changes. If the client does not want the server changes returned, the request MUST include the GetChanges element with a value of FALSE. A value of TRUE indicates that the client wants the server changes to be returned. A value of TRUE is assumed when the GetChanges element is empty. When the GetChanges element is not present in the request, the behavior depends on the value of the SyncKey element, as specified in section 2.2.3.166.4. If the SyncKey element has a value of 0, then the request is handled as if the GetChanges element were set to FALSE. If the SyncKey element has a non-zero value, then the request is handled as if the GetChanges element were set to TRUE. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Specifies options that control certain aspects of how the synchronization is performed. Number allowed 0...2. Synchronization options enable the client to specify truncation and content settings. These settings are encapsulated within a airsyncbase:BodyPreference child element, as specified in [MS-ASAIRS] section 2.2.2.7. Because synchronization options are specified on a collection, the client can specify a unique airsyncbase:BodyPreference element value for each collection that it is being synchronized. For more details about the airsyncbase:BodyPreference element, see [MS-ASAIRS] section 2.2.2.7. The server preserves the Options block across requests, using a concept referred to as "sticky options". If the Options block is not included in a request, the previous Options block is used. Whenever the client specifies new options by including an Options block in the request, the server MUST replace the original Options block with the new Options block. If two Options elements are included in a single Sync command request, one of the Options elements MUST specify the synchronization options for the SMS class, while the other Options element specifies the options for the default class of the given folder. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Elements of the Contact class and the Calendar class that are not ghosted can be included as child elements of the Supported element. For details about the use of ghosted properties, see section 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | SyncKey value is used by the server to mark the synchronization state of a collection. A synchronization key of value 0 (zero) initializes the synchronization state on the server and causes a full synchronization of the collection. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Specifies a maximum number of changed items in a collection or a request that SHOULD be included in the synchronization response. If the WindowSize is not defined, the server behaves as if a WindowSize element with a value of 100 were submitted. The server interprets the value 0 (zero) and values above 512 as 512. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
