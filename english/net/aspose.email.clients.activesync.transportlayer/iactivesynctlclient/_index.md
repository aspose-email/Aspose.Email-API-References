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
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Contains a values that is used by the server to mark the synchronization state of a every synchronized collection. Where dictionary key is server Id and dictionary value is SyncKey. For GetItemEstimate and Sync commands. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Used by the server to track the current state of the client. For operations with folders only |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | The HeartbeatInterval element is a child element of the Ping element in Ping command requests and responses. In Ping command requests, it specifies the length of time, in seconds, that the server SHOULD wait before sending a response if no new items are added to the specified set of folders, as specified in section 3.1.5.6. The HeartbeatInterval element is also returned by the server with a status code of 5 and specifies either the minimum or maximum interval that is allowed when the client has requested a heartbeat interval that is outside the acceptable range. |

## Methods

| Name | Description |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | The FolderCreate creates a new folder as a child folder of the specified parent folder. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Deletes the collection with the matching identifier. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync)() | The FolderSync synchronizes the collection hierarchy but does not synchronize the items in the collections themselves. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync)(bool) | The FolderSync synchronizes the collection hierarchy but does not synchronize the items in the collections themselves. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate)(FolderInfo) | The FolderUpdate command moves a folder from one location to another on the server. The command is also used to rename a folder. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate)(string, string, string) | The FolderUpdate command moves a folder from one location to another on the server. The command is also used to rename a folder. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | The GetAttachment retrieves an email attachment from the server. The GetAttachment is not supported when the protocol version is 14.0 or 14.1. Use the Fetch element of the ItemOperations command instead. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate)(IEnumerable&lt;ItemEstimateRequest&gt;) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate)(ItemEstimateRequest) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate)(params ItemEstimateRequest[]) | The GetItemEstimate command gets an estimate of the number of items in a collection or folder on the server that have to be synchronized. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | The ItemOperations provides batched online handling of the Fetch, the EmptyFolderContents, and the Move operations. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse)(IEnumerable&lt;MeetingResponseRequest&gt;) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse)(params MeetingResponseRequest[]) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse)(UserResponse, string, string) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse)(UserResponse, string, string, string, string) | Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | The MoveItems command moves an item or items from one folder on the server to another. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems)(IEnumerable&lt;MoveItemData&gt;) | The MoveItems command moves an item or items from one folder on the server to another. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems)(params MoveItemData[]) | The MoveItems command moves an item or items from one folder on the server to another. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(IEnumerable&lt;PingParameter&gt;) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(params PingParameter[]) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(int, IEnumerable&lt;PingParameter&gt;) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(int, params PingParameter[]) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(string, FolderClass) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping)(int, string, FolderClass) | The Ping command is used to request that the server monitor specified folders for changes that would require the client to resynchronize. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | The Provision command enables client devices to request from the server the security policy settings that the administrator sets, such as the minimum personal identification number (PIN) password length requirement. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey)() | Reset SyncKeys for GetItemEstimate and Sync operations for all collections. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey)(string) | Reset SyncKey for GetItemEstimate and Sync operations for defined collection. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Reset SyncKey for operations with folders |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | The ResolveRecipients is used to resolve a list of supplied recipients, to retrieve their free/busy information, and optionally, to retrieve their S/MIME certificates so that clients can send encrypted S/MIME email messages. Retrieval of free/busy information using the Availability element in the ResolveRecipients command is not supported when the protocol version is 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | The Search is used to find entries in an address book, mailbox, or document library (UNC or Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail)(string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail)(string, bool) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail)(string, bool, string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail)(string, bool, string, string) | The SendMail is used by clients to send MIME-formatted email messages to the server. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | The Settings supports get and set operations on global properties and Out of Office (OOF) settings for the user. The Settings also sends device information to the server, implements the device password/personal identification number (PIN) recovery, and retrieves a list of the user's email addresses. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | The SmartForward command is used by clients to forward messages without retrieving the full, original message from the server. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | The SmartReply command is used by clients to reply to messages without retrieving the full, original message from the server. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | The Sync synchronizes changes in a collection between the client and the server. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(X509Certificate) | The ValidateCert command is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(X509Certificate, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail. |

### See Also

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
