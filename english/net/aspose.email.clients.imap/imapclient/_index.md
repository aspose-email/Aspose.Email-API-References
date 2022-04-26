---
title: ImapClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 14710
url: /net/aspose.email.clients.imap/imapclient/
---
## ImapClient class

Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

```csharp
public sealed class ImapClient : EmailClient
```

## Constructors

| Name | Description |
| --- | --- |
| [ImapClient](imapclient)() | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, ITokenProvider) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, ITokenProvider) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, bool) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, bool) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, RemoteCertificateValidationCallback) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, string, string, bool, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |
| [ImapClient](imapclient)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initializes a new instance of the [`ImapClient`](../imapclient) class |

## Properties

| Name | Description |
| --- | --- |
| [AllowedAuthentication](allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| [AnnotateSupported](annotatesupported) { get; set; } | Gets information whether ANNOTATE extension is supported See more: https://tools.ietf.org/html/rfc5257 |
| [AutoCommit](autocommit) { get; set; } | Indicates, whether commit operation are executed automatically when folder is changed or before connection is closed. |
| [ChildrenSupported](childrensupported) { get; set; } | Gets information whether CHILDREN extension is supported See more: https://tools.ietf.org/html/rfc3348 |
| [ClientIdentificationInfo](clientidentificationinfo) { get; set; } | Gets or sets client identification information See more: https://tools.ietf.org/html/rfc2971 |
| [CompressSupported](compresssupported) { get; set; } | Gets information whether COMPRESS extension is supported See more: https://tools.ietf.org/html/rfc4978 |
| [CondstoreSupported](condstoresupported) { get; set; } | Gets information whether CONDSTORE extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [CurrentFolder](currentfolder) { get; set; } | Gets the current folder |
| override [DefaultPort](defaultport) { get; } | Gets default port for client |
| [Delimiter](delimiter) { get; set; } | Gets or sets delimiter of folders hierarhy. |
| [EnableSupported](enablesupported) { get; set; } | Gets information whether ENABLE extension is supported See more: https://tools.ietf.org/html/rfc5161 |
| [ESearchSupported](esearchsupported) { get; set; } | Gets information whether ESEARCH extension is supported See more: https://tools.ietf.org/html/rfc4731 |
| [ExchangeIdAutomatically](exchangeidautomatically) { get; set; } | Gets or sets value which indicates whether client should to introduce information about itself to a server automatically. See more: https://tools.ietf.org/html/rfc2971 |
| [ExtendedListSupported](extendedlistsupported) { get; set; } | Gets information whether LIST Command Extension is supported See more https://tools.ietf.org/html/rfc5258 |
| [GmExt1Supported](gmext1supported) { get; set; } | Defines if Google X-GM-EXT-1 extension is supported |
| [IdSupported](idsupported) { get; set; } | Gets information whether ID extension is supported See more: https://tools.ietf.org/html/rfc2971 |
| [MailboxInfo](mailboxinfo) { get; } | Gets set of special-use mailboxes See more: http://tools.ietf.org/html/rfc6154 and https://tools.ietf.org/html/rfc8457 |
| [MoveSupported](movesupported) { get; set; } | Gets information whether MOVE extension is supported See more: https://tools.ietf.org/html/rfc6851 |
| [NamespaceSupported](namespacesupported) { get; set; } | Gets information whether NAMESPACE extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| [QresyncSupported](qresyncsupported) { get; set; } | Gets information whether QRESYNC extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [QuotaSupported](quotasupported) { get; set; } | Gets information whether quota is supported |
| [ReadOnly](readonly) { get; set; } | Gets or sets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted. |
| [SaslIrSupported](saslirsupported) { get; set; } | Gets information whether SASL Initial Client Response extension is supported See more: https://tools.ietf.org/html/rfc4959 |
| [ServerIdentificationInfo](serveridentificationinfo) { get; } | Gets server identification information See more: https://tools.ietf.org/html/rfc2971 |
| [ServerSupportedCompression](serversupportedcompression) { get; } | Gets information which compression types are supported by a server. See more: https://tools.ietf.org/html/rfc4978 |
| [SortSupported](sortsupported) { get; set; } | Gets information whether Sort command are supported |
| [SpecialUseSupported](specialusesupported) { get; set; } | Gets information whether Special-Use Mailboxes is supported See more: https://tools.ietf.org/html/rfc6154 |
| [SupportedAuthentication](supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |
| [ThreadAlgorithms](threadalgorithms) { get; } | Gets supported thread algorithms |
| [ThreadSupported](threadsupported) { get; set; } | Gets information whether Thread command are supported |
| [UidPlusSupported](uidplussupported) { get; set; } | Gets information whether UIDPLUS extension is supported See more: https://tools.ietf.org/html/rfc4315 |
| [UnselectSupported](unselectsupported) { get; set; } | Gets information whether UNSELECT extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| static [DefaultFolder](defaultfolder) { get; set; } | Default folder for ImapClients |

## Methods

| Name | Description |
| --- | --- |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlags](addmessageflags)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlags](addmessageflags)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) |  |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) |  |
| [AppendMessage](appendmessage)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(MailMessage) |  |
| [AppendMessageAsync](appendmessageasync)(string) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, MailMessage) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string) |  |
| [AppendMessageAsync](appendmessageasync)(MailMessage, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(string, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(string, MailMessage) |  |
| [AppendMessageAsync](appendmessageasync)(string, string) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, MailMessage, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, MailMessage) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, string) |  |
| [AppendMessageAsync](appendmessageasync)(string, MailMessage, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(string, string, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, MailMessage, CancellationToken) |  |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, string, CancellationToken) |  |
| [AppendMessages](appendmessages)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](appendmessages)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessagesAsync](appendmessagesasync)(IEnumerable&lt;MailMessage&gt;) |  |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) |  |
| [AppendMessagesAsync](appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, CancellationToken) |  |
| [AppendMessagesAsync](appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;) |  |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) |  |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;) |  |
| [AppendMessagesAsync](appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) |  |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) |  |
| [Backup](backup)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, Stream, BackupSettings) |  |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, string, BackupSettings) |  |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) |  |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings) |  |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) |  |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) |  |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) |  |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) |  |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlags](changemessageflags)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) |  |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) |  |
| [ClientCapabilities](clientcapabilities)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](clientcapabilities)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(params string[]) |  |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(CancellationToken, params string[]) |  |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(IConnection, params string[]) |  |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(IConnection, CancellationToken, params string[]) |  |
| [CommitDeletes](commitdeletes)() | Commit the deletions |
| [CommitDeletes](commitdeletes)(IConnection) | Commit the deletions |
| [CommitDeletes](commitdeletes)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](commitdeletes)(int) | Commit the deletions |
| [CommitDeletes](commitdeletes)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](commitdeletes)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](commitdeletes)(IConnection, int) | Commit the deletions |
| [CommitDeletes](commitdeletes)(IConnection, string) | Commit the deletions |
| [CommitDeletes](commitdeletes)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](commitdeletes)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)() |  |
| [CommitDeletesAsync](commitdeletesasync)(CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection) |  |
| [CommitDeletesAsync](commitdeletesasync)(IEnumerable&lt;string&gt;) |  |
| [CommitDeletesAsync](commitdeletesasync)(int) |  |
| [CommitDeletesAsync](commitdeletesasync)(string) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, int) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string) |  |
| [CommitDeletesAsync](commitdeletesasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(int, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(string, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(string, string) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, int, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, string) |  |
| [CommitDeletesAsync](commitdeletesasync)(string, string, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, string, CancellationToken) |  |
| [CopyMessage](copymessage)(int, string) | Copies the message |
| [CopyMessage](copymessage)(string, string) | Copies the message |
| [CopyMessage](copymessage)(IConnection, int, string) | Copies the message |
| [CopyMessage](copymessage)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(int, string) |  |
| [CopyMessageAsync](copymessageasync)(string, string) |  |
| [CopyMessageAsync](copymessageasync)(IConnection, int, string) |  |
| [CopyMessageAsync](copymessageasync)(IConnection, string, string) |  |
| [CopyMessageAsync](copymessageasync)(int, string, CancellationToken) |  |
| [CopyMessageAsync](copymessageasync)(string, string, CancellationToken) |  |
| [CopyMessageAsync](copymessageasync)(IConnection, int, string, CancellationToken) |  |
| [CopyMessageAsync](copymessageasync)(IConnection, string, string, CancellationToken) |  |
| [CopyMessages](copymessages)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](copymessages)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessages](copymessages)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](copymessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessages](copymessages)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessages](copymessages)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessages](copymessages)(IEnumerable&lt;int&gt;, string, bool) | Copy messages |
| [CopyMessages](copymessages)(int, int, string) | Copy messages |
| [CopyMessages](copymessages)(string, string, string) | Copy messages |
| [CopyMessages](copymessages)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessages](copymessages)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;int&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;string&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(int, int, string) |  |
| [CopyMessagesAsync](copymessagesasync)(string, string, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, int, int, string) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, string, string, string) |  |
| [CopyMessagesAsync](copymessagesasync)(int, int, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(string, string, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, int, int, string, CancellationToken) |  |
| [CopyMessagesAsync](copymessagesasync)(IConnection, string, string, string, CancellationToken) |  |
| [CreateFolder](createfolder)(string) | Creates a folder with the specified name |
| [CreateFolder](createfolder)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](createfolderasync)(string) |  |
| [CreateFolderAsync](createfolderasync)(IConnection, string) |  |
| [CreateFolderAsync](createfolderasync)(string, CancellationToken) |  |
| [CreateFolderAsync](createfolderasync)(IConnection, string, CancellationToken) |  |
| [DeleteFolder](deletefolder)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolder](deletefolder)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](deletefolderasync)(string) |  |
| [DeleteFolderAsync](deletefolderasync)(IConnection, string) |  |
| [DeleteFolderAsync](deletefolderasync)(string, CancellationToken) |  |
| [DeleteFolderAsync](deletefolderasync)(IConnection, string, CancellationToken) |  |
| [DeleteMessage](deletemessage)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](deletemessage)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](deletemessage)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessage](deletemessage)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](deletemessage)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessage](deletemessage)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](deletemessage)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(int) |  |
| [DeleteMessageAsync](deletemessageasync)(string) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string) |  |
| [DeleteMessageAsync](deletemessageasync)(int, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(int, long) |  |
| [DeleteMessageAsync](deletemessageasync)(string, bool) |  |
| [DeleteMessageAsync](deletemessageasync)(string, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(string, long) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, long) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, bool) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long) |  |
| [DeleteMessageAsync](deletemessageasync)(int, long, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(string, bool, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(string, long, bool) |  |
| [DeleteMessageAsync](deletemessageasync)(string, long, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, long, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, bool, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, bool) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(string, long, bool, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, bool, CancellationToken) |  |
| [DeleteMessages](deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages](deletemessages)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessages](deletemessages)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](deletemessages)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(int, int) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, bool) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, bool, CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, bool, CancellationToken) |  |
| override [Dispose](dispose)() | Finalizes all operations with a server. |
| [ExistFolder](existfolder)(string) | Check whether this folder exists |
| [ExistFolder](existfolder)(IConnection, string) | Check whether this folder exists |
| [ExistFolder](existfolder)(string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolder](existfolder)(IConnection, string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolderAsync](existfolderasync)(string) |  |
| [ExistFolderAsync](existfolderasync)(IConnection, string) |  |
| [ExistFolderAsync](existfolderasync)(string, CancellationToken) |  |
| [ExistFolderAsync](existfolderasync)(IConnection, string, CancellationToken) |  |
| [FetchAttachment](fetchattachment)(int, string) | Fetches the specified attachment |
| [FetchAttachment](fetchattachment)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](fetchattachmentasync)(int, string) |  |
| [FetchAttachmentAsync](fetchattachmentasync)(IConnection, int, string) |  |
| [FetchAttachmentAsync](fetchattachmentasync)(int, string, CancellationToken) |  |
| [FetchAttachmentAsync](fetchattachmentasync)(IConnection, int, string, CancellationToken) |  |
| [FetchMessage](fetchmessage)(int) | Fetches the message |
| [FetchMessage](fetchmessage)(string) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessage](fetchmessage)(int, bool) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int) |  |
| [FetchMessageAsync](fetchmessageasync)(string) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string) |  |
| [FetchMessageAsync](fetchmessageasync)(int, bool) |  |
| [FetchMessageAsync](fetchmessageasync)(int, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(string, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, bool) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(int, bool, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, bool, CancellationToken) |  |
| [FetchMessages](fetchmessages)(IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;int&gt;) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [GetFolderInfo](getfolderinfo)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfo](getfolderinfo)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](getfolderinfoasync)(string) |  |
| [GetFolderInfoAsync](getfolderinfoasync)(IConnection, string) |  |
| [GetFolderInfoAsync](getfolderinfoasync)(string, CancellationToken) |  |
| [GetFolderInfoAsync](getfolderinfoasync)(IConnection, string, CancellationToken) |  |
| [GetMessageThreads](getmessagethreads)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreads](getmessagethreads)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](getmessagethreadsasync)(BaseSearchConditions) |  |
| [GetMessageThreadsAsync](getmessagethreadsasync)(BaseSearchConditions, CancellationToken) |  |
| [GetMessageThreadsAsync](getmessagethreadsasync)(IConnection, BaseSearchConditions) |  |
| [GetMessageThreadsAsync](getmessagethreadsasync)(IConnection, BaseSearchConditions, CancellationToken) |  |
| [GetNamespaces](getnamespaces)() | Gets namespaces that are available on a server. |
| [GetNamespaces](getnamespaces)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](getnamespacesasync)() |  |
| [GetNamespacesAsync](getnamespacesasync)(CancellationToken) |  |
| [GetNamespacesAsync](getnamespacesasync)(IConnection) |  |
| [GetNamespacesAsync](getnamespacesasync)(IConnection, CancellationToken) |  |
| [GetQuota](getquota)(string) | Gets quota information |
| [GetQuota](getquota)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](getquotaasync)(string) |  |
| [GetQuotaAsync](getquotaasync)(IConnection, string) |  |
| [GetQuotaAsync](getquotaasync)(string, CancellationToken) |  |
| [GetQuotaAsync](getquotaasync)(IConnection, string, CancellationToken) |  |
| [GetQuotaRoot](getquotaroot)(string) | Gets quota root information for mailbox |
| [GetQuotaRoot](getquotaroot)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](getquotarootasync)(string) |  |
| [GetQuotaRootAsync](getquotarootasync)(IConnection, string) |  |
| [GetQuotaRootAsync](getquotarootasync)(string, CancellationToken) |  |
| [GetQuotaRootAsync](getquotarootasync)(IConnection, string, CancellationToken) |  |
| [IntroduceClient](introduceclient)() | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(IConnection) | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)() |  |
| [IntroduceClientAsync](introduceclientasync)(CancellationToken) |  |
| [IntroduceClientAsync](introduceclientasync)(IConnection) |  |
| [IntroduceClientAsync](introduceclientasync)(ImapIdentificationInfo) |  |
| [IntroduceClientAsync](introduceclientasync)(IConnection, CancellationToken) |  |
| [IntroduceClientAsync](introduceclientasync)(IConnection, ImapIdentificationInfo) |  |
| [IntroduceClientAsync](introduceclientasync)(ImapIdentificationInfo, CancellationToken) |  |
| [IntroduceClientAsync](introduceclientasync)(IConnection, ImapIdentificationInfo, CancellationToken) |  |
| [ListAttachments](listattachments)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](listattachmentsasync)(int) |  |
| [ListAttachmentsAsync](listattachmentsasync)(int, CancellationToken) |  |
| [ListFolders](listfolders)() | Gets the list of folders in the mailbox |
| [ListFolders](listfolders)(bool) | Gets the list of folders in the mailbox |
| [ListFolders](listfolders)(IConnection) | Gets the list of folders in the mailbox |
| [ListFolders](listfolders)(string) | Gets the list of subfolders in the specified folder |
| [ListFolders](listfolders)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFolders](listfolders)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFolders](listfolders)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](listfolders)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFolders](listfolders)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFolders](listfolders)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)() |  |
| [ListFoldersAsync](listfoldersasync)(bool) |  |
| [ListFoldersAsync](listfoldersasync)(CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection) |  |
| [ListFoldersAsync](listfoldersasync)(string) |  |
| [ListFoldersAsync](listfoldersasync)(bool, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, bool) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string) |  |
| [ListFoldersAsync](listfoldersasync)(string, bool) |  |
| [ListFoldersAsync](listfoldersasync)(string, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, bool, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(string, bool, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) |  |
| [ListFoldersAsync](listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) |  |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) |  |
| [ListMessage](listmessage)(int) | Gets information about a message. |
| [ListMessage](listmessage)(string) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, int) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, string) | Gets information about a message. |
| [ListMessage](listmessage)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(int) |  |
| [ListMessageAsync](listmessageasync)(string) |  |
| [ListMessageAsync](listmessageasync)(IConnection, int) |  |
| [ListMessageAsync](listmessageasync)(IConnection, string) |  |
| [ListMessageAsync](listmessageasync)(int, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(int, IEnumerable&lt;string&gt;) |  |
| [ListMessageAsync](listmessageasync)(string, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(string, IEnumerable&lt;string&gt;) |  |
| [ListMessageAsync](listmessageasync)(IConnection, int, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;) |  |
| [ListMessageAsync](listmessageasync)(IConnection, string, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;) |  |
| [ListMessageAsync](listmessageasync)(int, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(string, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessageAsync](listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessages](listmessages)() | Gets the list of messages in the current folder |
| [ListMessages](listmessages)(bool) | Gets the list of messages in the current folder |
| [ListMessages](listmessages)(IConnection) | Gets the list of messages in the current folder |
| [ListMessages](listmessages)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessages](listmessages)(int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](listmessages)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(string) | Gets the list of messages in the specified folder |
| [ListMessages](listmessages)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessages](listmessages)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessages](listmessages)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessages](listmessages)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](listmessages)(string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessages](listmessages)(IConnection, string, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, string, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessages](listmessages)(string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(IConnection, string, ImapListFields, int) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessages](listmessages)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)() |  |
| [ListMessagesAsync](listmessagesasync)(bool) |  |
| [ListMessagesAsync](listmessagesasync)(CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection) |  |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;) |  |
| [ListMessagesAsync](listmessagesasync)(int) |  |
| [ListMessagesAsync](listmessagesasync)(long) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(string) |  |
| [ListMessagesAsync](listmessagesasync)(bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, int) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, long) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string) |  |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(long, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery, int) |  |
| [ListMessagesAsync](listmessagesasync)(string, bool) |  |
| [ListMessagesAsync](listmessagesasync)(string, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, long, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, int) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, bool) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery, int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(string, bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(string, bool, IEnumerable&lt;string&gt;) |  |
| [ListMessagesAsync](listmessagesasync)(string, MailQuery, int) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, MailQuery, int) |  |
| [ListMessagesAsync](listmessagesasync)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(string, MailQuery, int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, MailQuery, int, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessagesByPage](listmessagesbypage)(int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](listmessagesbypageasync)(int, int, PageSettings) |  |
| [ListMessagesByPageAsync](listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) |  |
| [ListMessagesByPageAsync](listmessagesbypageasync)(int, int, PageSettings, CancellationToken) |  |
| [ListMessagesByPageAsync](listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) |  |
| [MoveFolder](movefolder)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolder](movefolder)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](movefolderasync)(string, string) |  |
| [MoveFolderAsync](movefolderasync)(IConnection, string, string) |  |
| [MoveFolderAsync](movefolderasync)(string, string, CancellationToken) |  |
| [MoveFolderAsync](movefolderasync)(IConnection, string, string, CancellationToken) |  |
| [MoveMessage](movemessage)(int, string) | Moves the message |
| [MoveMessage](movemessage)(string, string) | Moves the message |
| [MoveMessage](movemessage)(IConnection, int, string) | Moves the messaeg |
| [MoveMessage](movemessage)(IConnection, string, string) | Moves the message |
| [MoveMessage](movemessage)(int, string, bool) | Moves the message |
| [MoveMessage](movemessage)(string, string, bool) | Moves the message |
| [MoveMessage](movemessage)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessage](movemessage)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](movemessageasync)(int, string) |  |
| [MoveMessageAsync](movemessageasync)(string, string) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string) |  |
| [MoveMessageAsync](movemessageasync)(int, string, bool) |  |
| [MoveMessageAsync](movemessageasync)(int, string, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(string, string, bool) |  |
| [MoveMessageAsync](movemessageasync)(string, string, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, bool) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, bool) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(int, string, bool, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(string, string, bool, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, bool, CancellationToken) |  |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, bool, CancellationToken) |  |
| [MoveMessages](movemessages)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](movemessages)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessages](movemessages)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessages](movemessages)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](movemessages)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessages](movemessages)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](movemessages)(int, int, string) | Moves the message |
| [MoveMessages](movemessages)(string, string, string) | Moves the message |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessages](movemessages)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessages](movemessages)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessages](movemessages)(IConnection, string, string, string) | Moves the message |
| [MoveMessages](movemessages)(int, int, string, bool) | Moves the message |
| [MoveMessages](movemessages)(string, string, string, bool) | Moves the message |
| [MoveMessages](movemessages)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessages](movemessages)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(int, int, string) |  |
| [MoveMessagesAsync](movemessagesasync)(string, string, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, bool) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, bool, CancellationToken) |  |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, bool, CancellationToken) |  |
| override [Noop](noop)() | 'No operation' command |
| override [Noop](noop)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)() |  |
| [NoopAsync](noopasync)(CancellationToken) |  |
| [NoopAsync](noopasync)(IConnection) |  |
| [NoopAsync](noopasync)(IConnection, CancellationToken) |  |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlags](removemessageflags)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) |  |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) |  |
| [RenameFolder](renamefolder)(string, string) | Renames a specified folder to a new name |
| [RenameFolder](renamefolder)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](renamefolderasync)(string, string) |  |
| [RenameFolderAsync](renamefolderasync)(IConnection, string, string) |  |
| [RenameFolderAsync](renamefolderasync)(string, string, CancellationToken) |  |
| [RenameFolderAsync](renamefolderasync)(IConnection, string, string, CancellationToken) |  |
| [RequestCheckpoint](requestcheckpoint)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpoint](requestcheckpoint)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](requestcheckpointasync)() |  |
| [RequestCheckpointAsync](requestcheckpointasync)(CancellationToken) |  |
| [RequestCheckpointAsync](requestcheckpointasync)(IConnection) |  |
| [RequestCheckpointAsync](requestcheckpointasync)(IConnection, CancellationToken) |  |
| [Restore](restore)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings) |  |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) |  |
| [ResumeMonitoring](resumemonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [ResumeMonitoringAsync](resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) |  |
| [SaveMessage](savemessage)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(int, Stream) |  |
| [SaveMessageAsync](savemessageasync)(int, string) |  |
| [SaveMessageAsync](savemessageasync)(string, Stream) |  |
| [SaveMessageAsync](savemessageasync)(string, string) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string) |  |
| [SaveMessageAsync](savemessageasync)(int, Stream, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(int, string, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(string, Stream, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(string, string, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream, CancellationToken) |  |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string, CancellationToken) |  |
| [SelectFolder](selectfolder)(string) | Selects the specified folder |
| [SelectFolder](selectfolder)(IConnection, string) | Selects the specified folder |
| [SelectFolder](selectfolder)(string, bool?) | Selects the specified folder |
| [SelectFolder](selectfolder)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(string) |  |
| [SelectFolderAsync](selectfolderasync)(IConnection, string) |  |
| [SelectFolderAsync](selectfolderasync)(string, bool?) |  |
| [SelectFolderAsync](selectfolderasync)(string, CancellationToken) |  |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, bool?) |  |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, CancellationToken) |  |
| [SelectFolderAsync](selectfolderasync)(string, bool?, CancellationToken) |  |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, bool?, CancellationToken) |  |
| [SetQuota](setquota)(string, string, int) | Sets quota information |
| [SetQuota](setquota)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](setquotaasync)(string, string, int) |  |
| [SetQuotaAsync](setquotaasync)(IConnection, string, string, int) |  |
| [SetQuotaAsync](setquotaasync)(string, string, int, CancellationToken) |  |
| [SetQuotaAsync](setquotaasync)(IConnection, string, string, int, CancellationToken) |  |
| [SortMessageThreads](sortmessagethreads)(SortConditions) | Get message threads. |
| [SortMessageThreads](sortmessagethreads)(IConnection, SortConditions) | Get message threads. |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(SortConditions) |  |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(IConnection, SortConditions) |  |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(SortConditions, CancellationToken) |  |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(IConnection, SortConditions, CancellationToken) |  |
| [StartMonitoring](startmonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StartMonitoringAsync](startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) |  |
| [StopMonitoring](stopmonitoring)() | Stops any monitoring of changes. |
| [StopMonitoring](stopmonitoring)(string) | Stops monitoring of message changes for specified folder. |
| [StopMonitoringAsync](stopmonitoringasync)() |  |
| [StopMonitoringAsync](stopmonitoringasync)(string) |  |
| [SubscribeFolder](subscribefolder)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolder](subscribefolder)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](subscribefolderasync)(string) |  |
| [SubscribeFolderAsync](subscribefolderasync)(IConnection, string) |  |
| [SubscribeFolderAsync](subscribefolderasync)(string, CancellationToken) |  |
| [SubscribeFolderAsync](subscribefolderasync)(IConnection, string, CancellationToken) |  |
| [UndeleteMessage](undeletemessage)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(int) |  |
| [UndeleteMessageAsync](undeletemessageasync)(string) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string) |  |
| [UndeleteMessageAsync](undeletemessageasync)(int, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(int, long) |  |
| [UndeleteMessageAsync](undeletemessageasync)(string, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(string, long) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, long) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, long) |  |
| [UndeleteMessageAsync](undeletemessageasync)(int, long, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(string, long, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, long, CancellationToken) |  |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, long, CancellationToken) |  |
| [UnselectFolder](unselectfolder)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](unselectfolder)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolder](unselectfolder)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](unselectfolder)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](unselectfolderasync)() |  |
| [UnselectFolderAsync](unselectfolderasync)(bool) |  |
| [UnselectFolderAsync](unselectfolderasync)(CancellationToken) |  |
| [UnselectFolderAsync](unselectfolderasync)(IConnection) |  |
| [UnselectFolderAsync](unselectfolderasync)(bool, CancellationToken) |  |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, bool) |  |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, CancellationToken) |  |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, bool, CancellationToken) |  |
| [UnsubscribeFolder](unsubscribefolder)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolder](unsubscribefolder)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(string) |  |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(IConnection, string) |  |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(string, CancellationToken) |  |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(IConnection, string, CancellationToken) |  |
| override [ValidateCredentials](validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)() |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(CancellationToken) |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection) |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection, CancellationToken) |  |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
