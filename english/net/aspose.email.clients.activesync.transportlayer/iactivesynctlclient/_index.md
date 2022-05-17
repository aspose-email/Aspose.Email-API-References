---
title: IActiveSyncTLClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1310
url: /net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

ActiveSync client interface

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Properties

| Name | Description |
| --- | --- |
| [AirSyncKeys](airsynckeys) { get; } | Contains a values that is used by the server to mark the synchronization state of a every synchronized collection. Where dictionary key is server Id and dictionary value is SyncKey. For GetItemEstimate and Sync commands. |
| [FoldersSyncKey](folderssynckey) { get; } | Used by the server to track the current state of the client. For operations with folders only |
| [HeartbeatInterval](heartbeatinterval) { get; set; } | The HeartbeatInterval element is a child element of the Ping element in Ping command requests and responses. In Ping command requests, it specifies the length of time, in seconds, that the server SHOULD wait before sending a response if no new items are added to the specified set of folders, as specified in section 3.1.5.6. The HeartbeatInterval element is also returned by the server with a status code of 5 and specifies either the minimum or maximum interval that is allowed when the client has requested a heartbeat interval that is outside the acceptable range. |

## Methods

| Name | Description |
| --- | --- |
| [FolderCreate](foldercreate)(string, string, UserCreatedFolderTypes) | The FolderCreate creates a new folder as a child folder of the specified parent folder. |
| [FolderDelete](folderdelete)(string) | Deletes the collection with the matching identifier. |
| [FolderSync](foldersync)() | The FolderSync synchronizes the collection hierarchy but does not synchronize the items in the collections themselves. |
| [FolderSync](foldersync)(bool) | The FolderSync synchronizes the collection hierarchy but does not synchronize the items in the collections themselves. |
| [FolderUpdate](folderupdate)(FolderInfo) | The FolderUpdate command moves a folder from one location to another on the server. The command is also used to rename a folder. |
| [FolderUpdate](folderupdate)(string, string, string) | The FolderUpdate command moves a folder from one location to another on the server. The command is also used to rename a folder. |
| [GetAttachment](getattachment)(string) | The GetAttachment retrieves an email attachment from the server. The GetAttachment is not supported when the protocol version is 14.0 or 14.1. Use the Fetch element of the ItemOperations command instead. |
| [GetItemEstimate](getitemestimate)(IEnumerable&lt;ItemEstimateRequest&gt;) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [GetItemEstimate](getitemestimate)(ItemEstimateRequest) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [GetItemEstimate](getitemestimate)(params ItemEstimateRequest[]) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [ItemOperations](itemoperations)(ItemOperationsRequest) | The ItemOperations provides batched online handling of the Fetch, the EmptyFolderContents, and the Move operations. |
| [MeetingResponse](meetingresponse)(IEnumerable&lt;MeetingResponseRequest&gt;) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](meetingresponse)(params MeetingResponseRequest[]) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](meetingresponse)(UserResponse, string, string) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](meetingresponse)(UserResponse, string, string, string, string) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MoveItem](moveitem)(string, string, string) | The MoveItems command moves an item or items from one folder on the server to another. |
| [MoveItems](moveitems)(IEnumerable&lt;MoveItemData&gt;) | The MoveItems command moves an item or items from one folder on the server to another. |
| [MoveItems](moveitems)(params MoveItemData[]) | The MoveItems command moves an item or items from one folder on the server to another. |
| [Ping](ping)(IEnumerable&lt;PingParameter&gt;) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](ping)(params PingParameter[]) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](ping)(int, IEnumerable&lt;PingParameter&gt;) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](ping)(int, params PingParameter[]) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](ping)(string, FolderClass) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](ping)(int, string, FolderClass) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Provision](provision)(ProvisionRequest) | The Provision command enables client devices to request from the server the security policy settings that the administrator sets, such as the minimum personal identification number (PIN) password length requirement. |
| [ResetAirSyncKey](resetairsynckey)() | Reset SyncKeys for GetItemEstimate and Sync operations for all collections. |
| [ResetAirSyncKey](resetairsynckey)(string) | Reset SyncKey for GetItemEstimate and Sync operations for defined collection. |
| [ResetFoldersSyncKey](resetfolderssynckey)() | Reset SyncKey for operations with folders |
| [ResolveRecipients](resolverecipients)(ResolveRecipientsRequest) | The ResolveRecipients is used to resolve a list of supplied recipients, to retrieve their free/busy information, and optionally, to retrieve their S/MIME certificates so that clients can send encrypted S/MIME email messages. Retrieval of free/busy information using the Availability element in the ResolveRecipients command is not supported when the protocol version is 12.1. |
| [Search](search)(SearchRequest) | The Search is used to find entries in an address book, mailbox, or document library (UNC or Windows SharePoint Services). |
| [SendMail](sendmail)(string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](sendmail)(string, bool) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](sendmail)(string, bool, string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](sendmail)(string, bool, string, string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [Settings](settings)(SettingsRequest) | The Settings supports get and set operations on global properties and Out of Office (OOF) settings for the user. The Settings also sends device information to the server, implements the device password/personal identification number (PIN) recovery, and retrieves a list of the user's email addresses. |
| [SmartForward](smartforward)(SmartRequest) | The SmartForward command is used by clients to forward messages without retrieving the full, original message from the server. |
| [SmartReply](smartreply)(SmartRequest) | The SmartReply command is used by clients to reply to messages without retrieving the full, original message from the server. |
| [Sync](sync)(SyncRequest) | The Sync synchronizes changes in a collection between the client and the server. |
| [ValidateCert](validatecert)(IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(X509Certificate) | The ValidateCert command is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(X509Certificate, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](validatecert)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |

### See Also

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
