---
title: SearchOptions
second_title: Aspose.Email for .NET API Reference
description: Contains the search options. The UserName and Password can only be sent in the request after receiving a Status value of 14. The server requires these credentials to access the requested resources. The client MUST only send these over a secure or trusted connection and only in response to a Status value of 14. The supported options vary according to the store that is being searched. The following table lists the valid options for each store. GAL Range UserName Password Picture Mailbox Range DeepTraversal RebuildResults BodyPreference BodyPartPreference RightsManagementSupport DocumentLibrary Range UserName Password The BodyPartPreference is only valid in Search command requests that include a ConversationId.
type: docs
weight: 1950
url: /net/aspose.email.clients.activesync.transportlayer/searchoptions/
---
## SearchOptions class

Contains the search options. The UserName and Password can only be sent in the request after receiving a Status value of 14. The server requires these credentials to access the requested resources. The client MUST only send these over a secure or trusted connection, and only in response to a Status value of 14. The supported options vary according to the store that is being searched. The following table lists the valid options for each store. GAL: Range, UserName, Password, Picture Mailbox: Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Range, UserName, Password The BodyPartPreference is only valid in Search command requests that include a ConversationId.

```csharp
public class SearchOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SearchOptions](searchoptions)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BodyPartPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypartpreference) { get; } | Contains preference information related to the type and size of information that is returned from searching, synchronizing, or fetching a message part. |
| [BodyPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypreference) { get; } | Contains preference information related to the type and size of information that is returned from searching, synchronizing, or fetching. |
| [DeepTraversal](../../aspose.email.clients.activesync.transportlayer/searchoptions/deeptraversal) { get; set; } | Indicates that the client wants the server to search all subfolders for the folders that are specified in the query. |
| [MIMESupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/mimesupport) { get; set; } | Enables MIME support for email items that are sent from the server to the client. If the airsync:MIMESupport element is set to 'SendForSecureMIMEonly' (1) or 'SendForAll' (2) in the Search request: - The property of the airsyncbase:BodyPreference, the Type, SHOULD be included in the Search request, containing a value of 'MIME' (4) to inform the server that the device can read the MIME BLOB. - The response from the server MUST include the airsyncbase:Body, which is a child of the Properties. The airsyncbase:Body MUST contain the following properties in an S/MIME Search response: - The airsyncbase:Type with a value of 'MIME' (4) to inform the device that the data is a MIME BLOB. - The airsyncbase:EstimatedDataSize to specify the rough total size of the data. - The airsyncbase:Truncated to indicate whether the MIME BLOB is truncated. - The airsyncbase:Data that contains the full MIME BLOB. |
| [Password](../../aspose.email.clients.activesync.transportlayer/searchoptions/password) { get; set; } | Specifies the password for the given UserName. The value of the Password has a maximum length of 100 characters. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/searchoptions/picture) { get; set; } | Contains the data related to the photos request. The Picture is not supported when the protocol version is 12.1 or 14.0. |
| [Range](../../aspose.email.clients.activesync.transportlayer/searchoptions/range) { get; set; } | Specifies the maximum number of matching entries to return. The format of the Range element value is in the form of a zero-based index specifier, formed with a zero, a hyphen, and another numeric value: "m-n." The m indicates the lowest index of a zero-based array that would hold the items. The n indicates the highest index of a zero-based array that would hold the items. For example, a Range element value of 0–9 indicates 10 items, and 0–10 indicates 11 items. A Range element value of 0–0 indicates 1 item. If Range is null, the default Range value for each Store type is used. The following table identifies the default Range values and maximum results returned for each Store type: Mailbox - Default range value: 0-99 - Maximum results returned: 100 DocumentLibrary - Default range value: 0-999 - Maximum results returned: 1000 GAL - Default range value: 0-99 - Maximum results returned: 100 If the Range value specified in the request exceeds the default range value, a Status value of 12 is returned to indicate that the maximum range has been exceeded. In the Search command response, the Total property indicates an estimate of the total number of entries that matched the Query value. Search results are stored in a search folder on the server. This way, when a client comes back with the same query but a new row range, rows are pulled from the result set that is currently stored in the search folder. The entire result set does not have to be rebuilt. |
| [RebuildResults](../../aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults) { get; set; } | Forces the server to rebuild the search folder (2) that corresponds to a given query. The search results (that is, the result set) are stored in a search folder on the server. This way, when a client comes back with the same query but a new row range, rows are pulled from the result set that is currently stored in the search folder. The entire result set does not have to be rebuilt. The search folder remains unchanged until the client does one of the following to update the result set: - Sends a Search request, specifying a new query. In this case, the search folder is automatically rebuilt. The RebuildResults node does not have to be included. - Sends a Search request that includes the RebuildResults node. In this case, the server is forced to rebuild the search folder. If a new item is added, the item does not appear in the result set until the result set is updated. If an item is deleted, the server will filter the deleted item out of the result set. The client SHOULD send a new Search request with the given query and include the RebuildResults option every few days to ensure accurate results for that query. |
| [RightsManagementSupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/rightsmanagementsupport) { get; set; } | Specifies how the server returns rights-managed email messages to the client. If the value is TRUE, the server will decompress and decrypt rights-managed email messages before sending them to the client. If the value is FALSE, the server will not decompress or decrypt rights-managed email messages before sending them to the client. If the RightsManagementSupport element is not included in a request message, a default value of FALSE is assumed. |
| [UserName](../../aspose.email.clients.activesync.transportlayer/searchoptions/username) { get; set; } | Specifies the user account used to search the document from the document library. The UserName value can be up to 100 characters in length. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
