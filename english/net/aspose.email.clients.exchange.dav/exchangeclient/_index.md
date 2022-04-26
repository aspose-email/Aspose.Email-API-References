---
title: ExchangeClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1610
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
| [ClientCertificate](clientcertificate) { get; set; } | Gets or sets the client certificate. |
| [CookieContainer](cookiecontainer) { get; set; } | Gets or sets the cookie container. |
| [Encoding](encoding) { get; set; } | Gets or sets the encoding. |
| [KeepAlive](keepalive) { get; set; } | Indicates whether to keep alive. |
| [MailboxInfo](mailboxinfo) { get; } | Gets the mailbox information. |
| [PreAuthenticate](preauthenticate) { get; set; } | Indicates whether to do pre-authentication. |
| [SendChunked](sendchunked) { get; set; } | Gets or sets a value indicating whether [send chunked]. |

## Methods

| Name | Description |
| --- | --- |
| [AppendMessage](appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(string, MailMessage, bool) | Uploads the mail message to the specified folder |
| [Backup](backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Backups the content of the specified folders |
| [Backup](backup)(ExchangeFolderInfoCollection, string, BackupOptions) | Backups the content of the specified folders |
| [CreateContact](createcontact)(Contact) | Creates a contact item in the Exchange store. |
| [CreateFolder](createfolder)(string, string) | Creates the new folder with the specified name in the specified parent folder. |
| [DeleteContact](deletecontact)(Contact) | Deletes the contact. |
| [DeleteContact](deletecontact)(MapiContact) | Deletes the contact. |
| [DeleteContact](deletecontact)(string) | Deletes the contact. |
| [DeleteFolder](deletefolder)(string) | Deletes the folder |
| [DeleteMessage](deletemessage)(string) | Deletes the mail message. |
| [DeleteMessage](deletemessage)(string, bool) | Deletes the mail message. |
| [FetchAttachment](fetchattachment)(string) | Fetches the attachment |
| [FetchMapiMessage](fetchmapimessage)(string) | Fetches the mapi message with specified uri. |
| [FetchMessage](fetchmessage)(string) | Fetches the mail message with specified uri. |
| [FolderExists](folderexists)(string, string) | Checks whether the specified folder exists. |
| [FolderExists](folderexists)(string, string, out ExchangeFolderInfo) | Checks whether the specified folder exists. |
| [GetContacts](getcontacts)(string) | Lists contacts located in the specified folder on server |
| [GetFolderInfo](getfolderinfo)(string) | Gets the folder information. |
| [GetMailboxes](getmailboxes)() | Lists mailboxes in the global address list. |
| [GetMailboxInfo](getmailboxinfo)() | Get the information of the mailbox |
| [GetMailboxInfo](getmailboxinfo)(string) | Gets the mailbox information |
| [GetMailboxSize](getmailboxsize)() | Get the size of the maibox |
| [GetMailboxSize](getmailboxsize)(string) | Get the size of the maibox |
| [GetVersionInfo](getversioninfo)() | Returns exchange server version info |
| [ListContacts](listcontacts)(string) | Lists contacts located in the specified folder on server |
| [ListMailboxes](listmailboxes)() | Lists mailboxes in the global address list. |
| [ListMessages](listmessages)(string) | Lists the messages. |
| [ListMessages](listmessages)(string, bool) | List the messages in the specified folder |
| [ListMessages](listmessages)(string, ExchangeListMessagesOptions) | Lists the mail message in the specified folder. |
| [ListMessages](listmessages)(string, int) | Lists the messages. |
| [ListMessages](listmessages)(string, string) | Lists the messages. |
| [ListMessages](listmessages)(string, int, ExchangeListMessagesOptions) | List the messages in the specified folder |
| [ListMessages](listmessages)(string, MailQuery, bool) | Lists the messages. |
| [ListMessages](listmessages)(string, string, bool) | Lists the messages. |
| [ListMessagesById](listmessagesbyid)(string, string) | Lists the messages by id. |
| [ListPublicFolders](listpublicfolders)() | Gets collection of public folders from root public folder |
| [ListSubFolders](listsubfolders)(ExchangeFolderInfo) | Gets collection of child public folders from parent |
| [ListSubFolders](listsubfolders)(string) | Gets collection of child folders from parent |
| [MoveItems](moveitems)(string, params string[]) | Moves items. |
| [MoveItems](moveitems)(string, bool, params string[]) | Moves items. |
| [MoveMessage](movemessage)(ExchangeMessageInfo, string) | Moves the message. |
| [MoveMessage](movemessage)(string, string) | Moves the message. |
| [MoveMessage](movemessage)(ExchangeMessageInfo, string, bool) | Moves the message. |
| [MoveMessage](movemessage)(string, bool, string) | Moves the message. |
| [ResolveContacts](resolvecontacts)(string) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [Restore](restore)(PersonalStorage, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](restore)(Stream, RestoreOptions) | Restores exchange folders from the given personal storage. |
| [Restore](restore)(string, RestoreOptions) | Restores exchange folders from the specified personal storage file. |
| [Restore](restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](restore)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the given personal storage. |
| [Restore](restore)(string, ExchangeFolderInfoCollection, RestoreOptions) | Restores the specified exchange folders from the specified personal storage file. |
| [SaveMessage](savemessage)(string, Stream) | Saves the message. |
| [SaveMessage](savemessage)(string, string) | Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML). if you want to parse the mail message files, use [`MailMessage`](../../aspose.email/mailmessage). |
| [Send](send)(MailMessage) | Sends the mail message. |
| [SetReadFlag](setreadflag)(string) | Marks the specifeid message as read. |
| [SetReadFlag](setreadflag)(string, bool) | Marks the specifeid message as read. |

### See Also

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
