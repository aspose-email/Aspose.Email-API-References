---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.email.clients.activesync.transportlayer/
---


## Classes

| Class | Description |
| --- | --- |
| [AccountInformation](./accountinformation) | Contains user's account information. |
| [ActiveSyncTLClient](./activesynctlclient) | Basic class for ActiveSync client implementations |
| [AutodiscoverResult](./autodiscoverresult) | Result of the Autodiscover operation |
| [Body](./body) | Specifies a free-form, variable-length data field associated with a stored item on the server. |
| [BodyPart](./bodypart) | Specifies details about the message part of an e-mail in a response. The BodyPart element MUST be included in a command response when the BodyPartPreference is specified in a request. |
| [BodyPreference](./bodypreference) | Contains preference information related to the type and size of information that is returned from searching, synchronizing, or fetching. |
| [CertificateStatuses](./certificatestatuses) | Indicates whether certificate was successfully validated. |
| [DataContainer](./datacontainer) | Contains data for a particular object, such as a contact, email message, calendar appointment, or task item. The DataContainer can be used to change items, add items, or fetch items on the client device or server. |
| [DeviceInformation](./deviceinformation) | Request that is used for sending the client device's properties to the server. |
| [DevicePasswordRequest](./devicepasswordrequest) | Specifies the request to set recovery password of the client device by the server. To clear an existing recovery password, the client MUST send an empty Password. |
| [EASProvisionDoc](./easprovisiondoc) | Specifies the collection of security settings for device provisioning. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Contains request about deleting the contents of a folder. EmptyFolderContents supports a single child element of the Options element, the DeleteSubFolders, which determines whether subfolders contained in the folder are deleted. If the DeleteSubFolders option is not included in the request, the subfolders of the specified CollectionId are not deleted. |
| [FolderInfo](./folderinfo) | FolderInfo class contains folder information |
| [FolderSyncResult](./foldersyncresult) | Contains changes to the folder hierarchy. |
| [ItemEstimate](./itemestimate) | Contains an assessment on the requested folder |
| [ItemEstimateOptions](./itemestimateoptions) | Contains elements that filter the results of the GetItemEstimate operation. |
| [ItemEstimateRequest](./itemestimaterequest) | Contains ItemEstimate request parameters |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifies the body of the response as containing the operation that deletes the contents of a folder. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Contains the properties that are returned for item(s) in the response. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Contains request about retrieving an item from the server. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Contains responce about retrieving an items from the server. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Contains request about moving a conversation to specific folder. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifies the body of the response as containing the operation that moves a given conversation. |
| [ItemOperationsRequest](./itemoperationsrequest) | Contains ItemOperations request. |
| [ItemOperationsResponse](./itemoperationsresponse) | Contains ItemOperations response. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Contains the options for the ItemOperations.EmptyFolderContents operation |
| [ItOpFetchOptions](./itopfetchoptions) | Contains the options for the ItemOperations.Fetch operation. |
| [ItOpMoveOptions](./itopmoveoptions) | Contains the options for the ItemOperations.Move operation. |
| [MeetingResponseRequest](./meetingresponserequest) | Specifies the meeting request that is being responded to, the response to that meeting request, and the folder on the server that the meeting request is located in. |
| [MeetingResponseResult](./meetingresponseresult) | Meeting response result object |
| [MoveItemData](./moveitemdata) | Contains information about moving items |
| [MoveItemResponse](./moveitemresponse) | Contains information that describe the moved items. |
| [OOFMessage](./oofmessage) | Specifies the OOF message for a particular audience. Exchange 2007, Exchange 2010, and Exchange 2013 require that the reply message for unknown external and known external audiences be the same. The property supports the following three audiences for an OOF message: Internal — A user who is in the same organization as the sending user. Known external — A user who is outside the sending user's organization, but is represented in the sending user's contacts. Unknown external — A user who is outside the sending user's organization and is not represented in the sending user's contacts. |
| [OOFReqParametrs](./oofreqparametrs) | Gets OOF information settings from the server. |
| [OOFRequest](./oofrequest) | Specifies a class for retrieving and setting Out of Office (OOF) information. |
| [OOFResponse](./oofresponse) | Specifies a class for retrieving and setting Out of Office (OOF) information. |
| [OOFSettings](./oofsettings) | OOF information settings. |
| [PictureRequest](./picturerequest) | Indicates that the client is requesting that photos be returned in the server response. The Picture is not supported when the protocol version is 12.1 or 14.0. Contains the data related to the photos request. |
| [PictureRespose](./picturerespose) | Contains the data related to the contact photos. The Picture is not supported when the protocol version is 12.1 or 14.0. |
| [PingParameter](./pingparameter) | Contains the ping command parameters |
| [ProvisionPolicy](./provisionpolicy) | Specifies a security policy. |
| [ProvisionPolicyData](./provisionpolicydata) | Specifies the settings for a policy. |
| [ProvisionRequest](./provisionrequest) | Contains request information for provision command |
| [ProvisionResponse](./provisionresponse) | Contains response information for provision command |
| [QueryType](./querytype) | Specifies the keywords to use for matching the entries in the store that is being searched. The value of the Query is used as a prefix-string matching pattern, and returns entries that match the beginning of the string. For example, searching for "John" would match "John Frum" or "Barry Johnson", but would not match "James Littlejohn". All nonempty text properties in the GAL that are indexed by using ANR are compared with the Query element value. Search comparisons are performed by using case-insensitive matching. For a Windows SharePoint Services document library search, this protocol supports queries of the following form: LinkId == value, where value specifies the URL of the item or folder and LinkId indicates that the value is to be compared to the link ID property. For mailbox search, the query syntax is as follows: - Folders can be specified in the following ways: Specified ID Specified folder and subfolders All email folders, including Draft, Inbox and subfolders, Outbox, and Sent Items - The basic keyword query can be composed of the following: The basic operator: And (section 2.2.3.10) A dateTime filter specified by using the GreaterThan (section 2.2.3.78) and LessThan elements (section 2.2.3.87) FreeText elements (section 2.2.3.73) that contain keywords The basic keyword query is executed against all indexed properties. |
| [Recipient](./recipient) | Represents a single recipient that has been resolved. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Indicates to the server that free/busy data is being requested by the client and identifies the start time and end time of the free/busy data to retrieve. The Availability is not supported when the protocol version is 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifies status and free/busy data of the users or distribution lists identified in the request for the time identified by the StartTime and EndTime. When the Availability is included in a ResolveRecipients request, the server retrieves free/busy information for the users identified in the To elements included in the request, and returns the free/busy information in the MergedFreeBusy in the response. When the server parses the request, the server first resolves the recipients identified by the To elements, and then determines the users free/busy information for the specified time span, before returning the free/busy data in the MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Contains information about the certificates for a recipient. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Contains the options for resolving the list of recipients. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Contains information to resolve recipients. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Contains information as to whether the recipient was resolved. If the recipient was resolved, the it also contains the type of recipient, the email address that the recipient resolved to, and, optionally, the S/MIME certificate for the recipient. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Contains rights management information settings retrieved from the server. |
| [RightsManagementLicense](./rightsmanagementlicense) | Contains the rights policy template settings for the template applied to the e-mail message being synchronized. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Contains the template identifier, name, and description of a rights policy template available on the client. |
| [SearchCondition](./searchcondition) | Specifies a condition for search requests |
| [SearchOptions](./searchoptions) | Contains the search options. The UserName and Password can only be sent in the request after receiving a Status value of 14. The server requires these credentials to access the requested resources. The client MUST only send these over a secure or trusted connection, and only in response to a Status value of 14. The supported options vary according to the store that is being searched. The following table lists the valid options for each store. GAL: Range, UserName, Password, Picture Mailbox: Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Range, UserName, Password The BodyPartPreference is only valid in Search command requests that include a ConversationId. |
| [SearchQuery](./searchquery) | Specifies the keywords to use for matching the entries in the store that is being searched. The value of the Query is used as a prefix-string matching pattern, and returns entries that match the beginning of the string. For example, searching for "John" would match "John Frum" or "Barry Johnson", but would not match "James Littlejohn". All nonempty text properties in the GAL that are indexed by using ANR are compared with the Query element value. Search comparisons are performed by using case-insensitive matching. For a Windows SharePoint Services document library search, this protocol supports queries of the following form: LinkId == value, where value specifies the URL of the item or folder and LinkId indicates that the value is to be compared to the link ID property. For mailbox search, the query syntax is as follows: - Folders can be specified in the following ways: Specified ID Specified folder and subfolders All email folders, including Draft, Inbox and subfolders, Outbox, and Sent Items - The basic keyword query can be composed of the following: The basic operator: And (section 2.2.3.10) A dateTime filter specified by using the GreaterThan (section 2.2.3.78) and LessThan elements (section 2.2.3.87) FreeText elements (section 2.2.3.73) that contain keywords The basic keyword query is executed against all indexed properties. |
| [SearchRequest](./searchrequest) | Contains search request information |
| [SearchRequestStore](./searchrequeststore) | Specify the name, query and options for the search. |
| [SearchResponse](./searchresponse) | Contains search response information |
| [SearchResponseStore](./searchresponsestore) | Contains the Status, Result, Range, and Total elements for the returned mailbox entries. |
| [SearchResult](./searchresult) | Container for an individual matching mailbox item. When the store that is being searched is the mailbox: - There is one Result element for each match that is found in the mailbox. If no matches are found, an empty Result element is present in the Store container element of the response XML. - Inside the Result element, the Properties element contains a list of requested properties for the mailbox item. When the store that is being searched is the document library: - The first result that is returned in the Search response is the metadata for the Root folder or item to which the LinkId value is pointing. The client can choose to ignore this entry if it does not require it. - If the documentlibrary:LinkId element value in the request points to a folder, the metadata properties of the folder are returned as the first item, and the contents of the folder are returned as subsequent results. The Range applies to these results with no difference; for example, the index 0 would always be for the root item to which the link is pointing. - If the documentlibrary:LinkId element value in the request points to an item, only one result is returned: the metadata for the item. - Inside the Result element, the Properties element contains a list of requested properties for the mailbox item. |
| [SearchResultProperties](./searchresultproperties) | The Search command response Properties is a container for properties that apply to an individual entry that matches the Query element search string. For example, the Properties element contains an element for each nonempty, text-valued GAL property that is attached to the matching GAL entry. Only those properties that are attached to the specific GAL entry are returned; therefore different sets of properties can be returned in the response XML for different matching GAL entries. Each element in the Properties container is scoped to the appropriate namespace that is specified in the top-level Search element. |
| [ServerInfo](./serverinfo) | Server settings in Autodiscover operation |
| [SettingsRequest](./settingsrequest) | The Settings command supports get and set operations on global properties and Out of Office (OOF) settings for the user. The Settings command also sends device information to the server, implements the device password/personal identification number (PIN) recovery, and retrieves a list of the user's email addresses. |
| [SettingsResponse](./settingsresponse) | Specifies a response with Out of Office (OOF) settings and list of the user's accounts. |
| [SmartRequest](./smartrequest) | Contains smart request information |
| [SmartRequestSource](./smartrequestsource) | Contains information about the source message. |
| [Status](./status) | Indicates the result of an operation. |
| [SyncAddClientOperation](./syncaddclientoperation) | Creates a new object in a collection on the client. |
| [SyncAddResponse](./syncaddresponse) | Serves to indicate that a new object has to be created in a collection. |
| [SyncAddServerOperation](./syncaddserveroperation) | Creates a new object in a collection on the server. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Contains properties of an existing object on the client device that were modified. The changed object is identified by its ServerId element. |
| [SyncChangeResponse](./syncchangeresponse) | Serves to Indicate that an object has been modified. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Contains properties of an existing object on the the server that were modified. The changed object is identified by its ServerId element. |
| [SyncCollectionRequest](./synccollectionrequest) | Class contains commands and options that apply to a particular collection. |
| [SyncCollectionResponse](./synccollectionresponse) | Class contains commands and options that apply to a Sync response. |
| [SyncCommandsRequest](./synccommandsrequest) | Contains operations that apply to a collection. Available operations are Add, Delete, Change, Fetch, and SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Contains operations that apply to a collection. Available operations are Add, Delete, Change, Fetch, and SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Deletes an object on the client device or the server. The object is identified by its ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Requests the application data of an item that was truncated in a synchronization response from the server. |
| [SyncOperationResponse](./syncoperationresponse) | Base abstract class for Sync operation responses |
| [SyncOperationsResponse](./syncoperationsresponse) | Contains responses to operations such as Add, Fetch, Change that are processed by the server. The response contains a status code and other information, depending on the operation. |
| [SyncOptions](./syncoptions) | Specifies options that control certain aspects of how the synchronization is performed. |
| [SyncRequest](./syncrequest) | Contains Sync request parameters |
| [UserInformationResponse](./userinformationresponse) | Contains status of the request and a list of a user’s account information (email addresses). |
| [ValueConverter](./valueconverter) | Class converts ActiveSync protocol version from string representation to enum and back. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | ActiveSync client interface |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Base ActiveSync client interface |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum specifies type of authentication |
| [AirSync](./airsync) | AirSync namespace of the ActiveSync protocol |
| [AirSyncBase](./airsyncbase) | AirSyncBase namespace of the ActiveSync protocol |
| [AirsyncClass](./airsyncclass) | Identifies the class of the item. The following classes are supported for mailbox searches when the protocol version is 12.1: - Email - Calendar - Contacts - Tasks The SMS and Notes classes are only available if the protocol version is 14.0 or 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | Specifies an optional time window for the objects |
| [AllowBluetooth](./allowbluetooth) | Specifies the use of Bluetooth on the device. |
| [ASProtocolVersions](./asprotocolversions) | The ASProtocolVersions indicates the versions of the ActiveSync protocol. |
| [BehaviorReplacement](./behaviorreplacement) | Specifies how to resolve the conflict that occurs when an object has been changed on both the client and the server. The value specifies which object—the client object or the server object—to keep if there is a conflict. |
| [BodyType](./bodytype) | Specifies the format type of the body content of the item. |
| [Calendar](./calendar) | Calendar namespace of the ActiveSync protocol |
| [CertificateRetrieval](./certificateretrieval) | Specifies whether S/MIME certificates SHOULD be returned by the server for each resolved recipient. |
| [CommandCodes](./commandcodes) | The following table provides the numeric codes that correspond to the ActiveSync commands. The numeric code is used in the Command code field of the base64 encoded URI to specify the command. |
| [CommandParameters](./commandparameters) | Command parameters. |
| [ComposeMail](./composemail) | ComposeMail namespace of the ActiveSync protocol |
| [Contacts](./contacts) | Contacts namespace of the ActiveSync protocol |
| [Contacts2](./contacts2) | Contacts2 namespace of the ActiveSync protocol |
| [DocumentLibrary](./documentlibrary) | DocumentLibrary namespace of the ActiveSync protocol |
| [Email](./email) | Email namespace of the ActiveSync protocol |
| [Email2](./email2) | Email2 namespace of the ActiveSync protocol |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Specifies the algorithm used when encrypting S/MIME messages. |
| [FolderClass](./folderclass) | Specifies the content class of the folder to be monitored. |
| [FolderHierarchy](./folderhierarchy) | FolderHierarchy namespace of the ActiveSync protocol |
| [FolderTypes](./foldertypes) | Specifies the type of the folder that was updated (renamed or moved) or added on the server. |
| [GAL](./gal) | GAL namespace of the ActiveSync protocol |
| [GetItemEstimate](./getitemestimate) | GetItemEstimate namespace of the ActiveSync protocol |
| [ItemOperations](./itemoperations) | ItemOperations namespace of the ActiveSync protocol |
| [MaxAgeFilter](./maxagefilter) | Specifies the maximum number of calendar days that can be synchronized. |
| [MeetingResponse](./meetingresponse) | MeetingResponse namespace of the ActiveSync protocol |
| [MergedFreeBusy](./mergedfreebusy) | Specifies the free/busy information for the users or distribution list. |
| [MIMESupport](./mimesupport) | Enables MIME support for email items that are sent from the server to the client. |
| [MIMETruncation](./mimetruncation) | Specifies whether the MIME data of the email item SHOULD be truncated when it is sent from the server to the client. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Specifies the required level of complexity of the client password. For example: If the value of MinDevicePasswordComplexCharacters is 2, a password with both upper case and lower case alphabetical characters would be sufficient, as would a password with lower case alphabetical characters and numbers. |
| [Move](./move) | Move namespace of the ActiveSync protocol |
| [Namespace](./namespace) | ActiveSync Code Pages |
| [Notes](./notes) | Notes namespace of the ActiveSync protocol |
| [OofState](./oofstate) | Specifies the availability of the Oof property. |
| [Ping](./ping) | Ping namespace of the ActiveSync protocol |
| [Provision](./provision) | Provision namespace of the ActiveSync protocol |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | The value indicates the success or failure of the client to apply the policy settings retrieved from the server. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | The value indicates the success or failure of a remote wipe operation on the client. |
| [RecipientType](./recipienttype) | Indicates the type of recipient. |
| [ResolveRecipients](./resolverecipients) | ResolveRecipients namespace of the ActiveSync protocol |
| [RightsManagement](./rightsmanagement) | RightsManagement namespace of the ActiveSync protocol |
| [Search](./search) | Search namespace of the ActiveSync protocol |
| [ServerType](./servertype) | Specifies the server type |
| [Settings](./settings) | Settings namespace of the ActiveSync protocol |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Specifies the algorithm used when signing S/MIME messages. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Controls the negotiation of the encryption algorithm. |
| [StoreType](./storetype) | Contains infarmation that specify the location, for the operations. |
| [Tasks](./tasks) | Tasks namespace of the ActiveSync protocol |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Specifies the type of the folder to be created. |
| [UserResponse](./userresponse) | Indicates whether the meeting is being accepted, tentatively accepted, or declined. |
| [ValidateCert](./validatecert) | ValidateCert namespace of the ActiveSync protocol |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
