---
title: Class ExchangeClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.Dav.ExchangeClient class. The ExchangeClient class allows applications to manage EMail box in Microsoft Exchange Server by using WebDav Exchange Store Protocol
type: docs
weight: 1710
url: /net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

The ExchangeClient class allows applications to manage E-Mail box in Microsoft Exchange Server by using WebDav Exchange Store Protocol.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Constructors

| Name | Description |
| --- | --- |
| [ExchangeClient](exchangeclient/#constructor)(string, ICredentials) | Initialize a new instance of the class `ExchageClient` |
| [ExchangeClient](exchangeclient/#constructor_1)(string, string, string) | Initialize a new instance of the class `ExchageClient` |
| [ExchangeClient](exchangeclient/#constructor_2)(string, string, string, string) | Initialize a new instance of the class `ExchageClient` |

## Properties

| Name | Description |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate/) { get; set; } | Gets or sets the client certificate. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer/) { get; set; } | Gets or sets the cookie container. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials/) { get; set; } | Gets or sets the credentials |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding/) { get; set; } | Gets or sets the encoding. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive/) { get; set; } | Indicates whether to keep alive. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename/) { get; set; } | Gets or sets log file name |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo/) { get; } | Gets the mailbox information. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri/) { get; set; } | Gets or sets the mailbox uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate/) { get; set; } | Indicates whether to do pre-authentication. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy/) { get; set; } | Gets or sets the proxy. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked/) { get; set; } | Gets or sets a value indicating whether [send chunked]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout/) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |

## Methods

| Name | Description |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage/#appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage/#appendmessage_1)(string, MailMessage, bool) | Uploads the mail message to the specified folder |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup/#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup/#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Backups the content of the specified folders |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact/)(Contact) | Creates a contact item in the Exchange store. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder/)(string, string) | Creates the new folder with the specified name in the specified parent folder. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact/#deletecontact_1)(Contact) | Deletes the contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact/#deletecontact)(MapiContact) | Deletes the contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact/#deletecontact_2)(string) | Deletes the contact. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder/)(string) | Deletes the folder |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage/#deletemessage)(string) | Deletes the mail message. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage/#deletemessage_1)(string, bool) | Deletes the mail message. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment/)(string) | Fetches the attachment |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage/)(string) | Fetches the mapi message with specified uri. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage/)(string) | Fetches the mail message with specified uri. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists/#folderexists)(string, string) | Checks whether the specified folder exists. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists/#folderexists_1)(string, string, out ExchangeFolderInfo) | Checks whether the specified folder exists. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts/)(string) | Lists contacts located in the specified folder on server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo/)(string) | Gets the folder information. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes/)() | Lists mailboxes in the global address list. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo/#getmailboxinfo)() | Get the information of the mailbox |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo/#getmailboxinfo_1)(string) | Gets the mailbox information |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize/#getmailboxsize)() | Get the size of the maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize/#getmailboxsize_1)(string) | Get the size of the maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo/)() | Returns exchange server version info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts/)(string) | Lists contacts located in the specified folder on server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes/)() | Lists mailboxes in the global address list. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages)(string) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_3)(string, bool) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_1)(string, ExchangeListMessagesOptions) | Lists the mail message in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_4)(string, int) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_6)(string, string) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_5)(string, int, ExchangeListMessagesOptions) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_2)(string, MailQuery, bool) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages/#listmessages_7)(string, string, bool) | Lists the messages. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid/)(string, string) | Lists the messages by id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders/)() | Gets collection of public folders from root public folder |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders/#listsubfolders)(ExchangeFolderInfo) | Gets collection of child public folders from parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders/#listsubfolders_1)(string) | Gets collection of child folders from parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems/#moveitems_1)(string, params string[]) | Moves items. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems/#moveitems)(string, bool, params string[]) | Moves items. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage/#movemessage)(ExchangeMessageInfo, string) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage/#movemessage_3)(string, string) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage/#movemessage_1)(ExchangeMessageInfo, string, bool) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage/#movemessage_2)(string, bool, string) | Moves the message. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts/)(string) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore_1)(PersonalStorage, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore_3)(Stream, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore_5)(string, RestoreOptions) | Restores exchange folders from the specified personal storage file. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore/#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the specified personal storage file. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage/#savemessage)(string, Stream) | Saves the message. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage/#savemessage_1)(string, string) | Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML). if you want to parse the mail message files, use [`MailMessage`](../../aspose.email/mailmessage/). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send/)(MailMessage) | Sends the mail message. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag/#setreadflag)(string) | Marks the specifeid message as read. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag/#setreadflag_1)(string, bool) | Marks the specifeid message as read. |

### See Also

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase/)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav/)
* assembly [Aspose.Email](../../)


