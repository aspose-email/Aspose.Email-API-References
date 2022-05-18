---
title: ExchangeClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 3150
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
| [ExchangeClient](exchangeclient)(string, ICredentials) | Initialize a new instance of the class [`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient)(string, string, string) | Initialize a new instance of the class [`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient)(string, string, string, string) | Initialize a new instance of the class [`ExchageClient`](../exchangeclient) |

## Properties

| Name | Description |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Gets or sets the client certificate. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Gets or sets the cookie container. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Gets or sets the credentials |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Gets or sets the encoding. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Indicates whether to keep alive. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Gets or sets log file name |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Gets the mailbox information. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Gets or sets the mailbox uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Indicates whether to do pre-authentication. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Gets or sets the proxy. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Gets or sets a value indicating whether [send chunked]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |

## Methods

| Name | Description |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage)(string, MailMessage, bool) | Uploads the mail message to the specified folder |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup)(ExchangeFolderInfoCollection, string, BackupOptions) | Backups the content of the specified folders |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Creates a contact item in the Exchange store. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Creates the new folder with the specified name in the specified parent folder. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact)(Contact) | Deletes the contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact)(MapiContact) | Deletes the contact. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact)(string) | Deletes the contact. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Deletes the folder |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage)(string) | Deletes the mail message. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage)(string, bool) | Deletes the mail message. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Fetches the attachment |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Fetches the mapi message with specified uri. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Fetches the mail message with specified uri. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists)(string, string) | Checks whether the specified folder exists. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists)(string, string, out ExchangeFolderInfo) | Checks whether the specified folder exists. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Lists contacts located in the specified folder on server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Gets the folder information. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Lists mailboxes in the global address list. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo)() | Get the information of the mailbox |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo)(string) | Gets the mailbox information |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize)() | Get the size of the maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize)(string) | Get the size of the maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Returns exchange server version info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Lists contacts located in the specified folder on server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Lists mailboxes in the global address list. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, bool) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, ExchangeListMessagesOptions) | Lists the mail message in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, int) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, string) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, int, ExchangeListMessagesOptions) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, MailQuery, bool) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages)(string, string, bool) | Lists the messages. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Lists the messages by id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Gets collection of public folders from root public folder |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders)(ExchangeFolderInfo) | Gets collection of child public folders from parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders)(string) | Gets collection of child folders from parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems)(string, params string[]) | Moves items. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems)(string, bool, params string[]) | Moves items. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage)(ExchangeMessageInfo, string) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage)(string, string) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage)(ExchangeMessageInfo, string, bool) | Moves the message. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage)(string, bool, string) | Moves the message. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(PersonalStorage, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(Stream, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(string, RestoreOptions) | Restores exchange folders from the specified personal storage file. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore)(string, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the specified personal storage file. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage)(string, Stream) | Saves the message. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage)(string, string) | Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML). if you want to parse the mail message files, use [`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Sends the mail message. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag)(string) | Marks the specifeid message as read. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag)(string, bool) | Marks the specifeid message as read. |

### See Also

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
