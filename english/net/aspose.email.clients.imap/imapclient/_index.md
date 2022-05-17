---
title: ImapClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 16250
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
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Adds the flags to the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AddMessageFlagsAsync](addmessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Adds the flags of the message |
| [AppendMessage](appendmessage)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessage](appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(IConnection, MailMessage) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(IConnection, string) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(IConnection, MailMessage, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, string) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, MailMessage, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessageAsync](appendmessageasync)(IConnection, string, string, CancellationToken) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages](appendmessages)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessagesAsync](appendmessagesasync)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](appendmessagesasync)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [AppendMessagesAsync](appendmessagesasync)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Uploads the mail messages to the current folder |
| [Backup](backup)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [Backup](backup)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | Backups the content of the specified folders |
| [BackupAsync](backupasync)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | Backups the content of the specified folders |
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
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ChangeMessageFlagsAsync](changemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Changes the flags of the message |
| [ClientCapabilities](clientcapabilities)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](clientcapabilities)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(IConnection, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](clientcapabilitiesasync)(IConnection, CancellationToken, params string[]) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
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
| [CommitDeletesAsync](commitdeletesasync)() | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(int) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, int) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, int, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, string) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, string, string, CancellationToken) | Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [CopyMessage](copymessage)(int, string) | Copies the message |
| [CopyMessage](copymessage)(string, string) | Copies the message |
| [CopyMessage](copymessage)(IConnection, int, string) | Copies the message |
| [CopyMessage](copymessage)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(int, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(string, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(IConnection, int, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(IConnection, string, string) | Copies the message |
| [CopyMessageAsync](copymessageasync)(int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](copymessageasync)(string, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](copymessageasync)(IConnection, int, string, CancellationToken) | Copies the message |
| [CopyMessageAsync](copymessageasync)(IConnection, string, string, CancellationToken) | Copies the message |
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
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;int&gt;, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) | Copy the messaeg |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(int, int, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(string, string, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](copymessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, int, int, string) | Copy the messaeg |
| [CopyMessagesAsync](copymessagesasync)(IConnection, string, string, string) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(int, int, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(string, string, string, CancellationToken) | Copy messages |
| [CopyMessagesAsync](copymessagesasync)(IConnection, int, int, string, CancellationToken) | Copy the messaeg |
| [CopyMessagesAsync](copymessagesasync)(IConnection, string, string, string, CancellationToken) | Copy messages |
| [CreateFolder](createfolder)(string) | Creates a folder with the specified name |
| [CreateFolder](createfolder)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](createfolderasync)(string) | Creates a folder with the specified name |
| [CreateFolderAsync](createfolderasync)(IConnection, string) | Creates a folder with the specified name |
| [CreateFolderAsync](createfolderasync)(string, CancellationToken) | Creates a folder with the specified name |
| [CreateFolderAsync](createfolderasync)(IConnection, string, CancellationToken) | Creates a folder with the specified name |
| [DeleteFolder](deletefolder)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolder](deletefolder)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](deletefolderasync)(string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](deletefolderasync)(IConnection, string) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](deletefolderasync)(string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteFolderAsync](deletefolderasync)(IConnection, string, CancellationToken) | Deletes a specified folder. This method represents IMAP DELETE command |
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
| [DeleteMessageAsync](deletemessageasync)(int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](deletemessageasync)(int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessageAsync](deletemessageasync)(string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
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
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, long) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, int, int, long, CancellationToken) | Marks a message with the specified sequence number as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, bool) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, CancellationToken) | Marks a message with the specified unique identifier as deleted |
| [DeleteMessagesAsync](deletemessagesasync)(string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, string, string, long, bool, CancellationToken) | Marks a message with the specified unique identifier as deleted and commits the deletions if user specifies this. This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| override [Dispose](dispose)() | Finalizes all operations with a server. |
| [ExistFolder](existfolder)(string) | Check whether this folder exists |
| [ExistFolder](existfolder)(IConnection, string) | Check whether this folder exists |
| [ExistFolder](existfolder)(string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolder](existfolder)(IConnection, string, out ImapFolderInfo) | Check whether this folder exists, extract folder info if so |
| [ExistFolderAsync](existfolderasync)(string) | Check whether this folder exists |
| [ExistFolderAsync](existfolderasync)(IConnection, string) | Check whether this folder exists |
| [ExistFolderAsync](existfolderasync)(string, CancellationToken) | Check whether this folder exists |
| [ExistFolderAsync](existfolderasync)(IConnection, string, CancellationToken) | Check whether this folder exists |
| [FetchAttachment](fetchattachment)(int, string) | Fetches the specified attachment |
| [FetchAttachment](fetchattachment)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](fetchattachmentasync)(int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](fetchattachmentasync)(IConnection, int, string) | Fetches the specified attachment |
| [FetchAttachmentAsync](fetchattachmentasync)(int, string, CancellationToken) | Fetches the specified attachment |
| [FetchAttachmentAsync](fetchattachmentasync)(IConnection, int, string, CancellationToken) | Fetches the specified attachment |
| [FetchMessage](fetchmessage)(int) | Fetches the message |
| [FetchMessage](fetchmessage)(string) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessage](fetchmessage)(int, bool) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int, bool) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, bool) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int, bool, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, bool, CancellationToken) | Fetches the message |
| [FetchMessages](fetchmessages)(IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages |
| [FetchMessages](fetchmessages)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Fetches the messages asynchronously |
| [FetchMessagesAsync](fetchmessagesasync)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Fetches the messages asynchronously |
| [GetFolderInfo](getfolderinfo)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfo](getfolderinfo)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](getfolderinfoasync)(string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](getfolderinfoasync)(IConnection, string) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](getfolderinfoasync)(string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetFolderInfoAsync](getfolderinfoasync)(IConnection, string, CancellationToken) | Returns information about the specified folder without selecting it |
| [GetMessageThreads](getmessagethreads)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreads](getmessagethreads)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](getmessagethreadsasync)(BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](getmessagethreadsasync)(BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetMessageThreadsAsync](getmessagethreadsasync)(IConnection, BaseSearchConditions) | Get message threads. |
| [GetMessageThreadsAsync](getmessagethreadsasync)(IConnection, BaseSearchConditions, CancellationToken) | Get message threads. |
| [GetNamespaces](getnamespaces)() | Gets namespaces that are available on a server. |
| [GetNamespaces](getnamespaces)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](getnamespacesasync)() | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](getnamespacesasync)(CancellationToken) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](getnamespacesasync)(IConnection) | Gets namespaces that are available on a server. |
| [GetNamespacesAsync](getnamespacesasync)(IConnection, CancellationToken) | Gets namespaces that are available on a server. |
| [GetQuota](getquota)(string) | Gets quota information |
| [GetQuota](getquota)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](getquotaasync)(string) | Gets quota information |
| [GetQuotaAsync](getquotaasync)(IConnection, string) | Gets quota information |
| [GetQuotaAsync](getquotaasync)(string, CancellationToken) | Gets quota information |
| [GetQuotaAsync](getquotaasync)(IConnection, string, CancellationToken) | Gets quota information |
| [GetQuotaRoot](getquotaroot)(string) | Gets quota root information for mailbox |
| [GetQuotaRoot](getquotaroot)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](getquotarootasync)(string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](getquotarootasync)(IConnection, string) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](getquotarootasync)(string, CancellationToken) | Gets quota root information for mailbox |
| [GetQuotaRootAsync](getquotarootasync)(IConnection, string, CancellationToken) | Gets quota root information for mailbox |
| [IntroduceClient](introduceclient)() | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(IConnection) | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClient](introduceclient)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)() | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(IConnection) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(IConnection, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(IConnection, ImapIdentificationInfo) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [IntroduceClientAsync](introduceclientasync)(IConnection, ImapIdentificationInfo, CancellationToken) | Introduces client information to a server. |
| [ListAttachments](listattachments)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](listattachmentsasync)(int) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListAttachmentsAsync](listattachmentsasync)(int, CancellationToken) | Gets the message attachments list. Gets an information for each attachment in message. |
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
| [ListFoldersAsync](listfoldersasync)() | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(IConnection) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(IConnection, bool) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(IConnection, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(IConnection, string) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(IConnection, bool, CancellationToken) | Gets the list of folders in the mailbox |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListFoldersAsync](listfoldersasync)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | Gets the list of subfolders in the specified folder |
| [ListMessage](listmessage)(int) | Gets information about a message. |
| [ListMessage](listmessage)(string) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, int) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, string) | Gets information about a message. |
| [ListMessage](listmessage)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessage](listmessage)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(int) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(string) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, int) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, string) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, int, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, string, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
| [ListMessageAsync](listmessageasync)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) | Gets information about a message. |
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
| [ListMessagesAsync](listmessagesasync)() | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IConnection) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](listmessagesasync)(MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, long) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, string) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](listmessagesasync)(MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool, CancellationToken) | Gets the list of messages in the current folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, long, CancellationToken) | Gets the list of messages in the current folder that have a modification sequence bigger than specified value. Please, see more https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, bool) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(string, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, bool, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, MailQuery, int) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | Gets the list of messages in the specified folder |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, MailQuery, int, CancellationToken) | Gets the list of messages in the current folder. |
| [ListMessagesAsync](listmessagesasync)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) | Gets the list of messages in the specified folder |
| [ListMessagesByPage](listmessagesbypage)(int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPage](listmessagesbypage)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](listmessagesbypageasync)(int, int, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) | Gets the list of messages |
| [ListMessagesByPageAsync](listmessagesbypageasync)(int, int, PageSettings, CancellationToken) | Gets the list of messages |
| [ListMessagesByPageAsync](listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Gets the list of messages |
| [MoveFolder](movefolder)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolder](movefolder)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](movefolderasync)(string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](movefolderasync)(IConnection, string, string) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](movefolderasync)(string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveFolderAsync](movefolderasync)(IConnection, string, string, CancellationToken) | Moves specified folder and its subfolders to new location. |
| [MoveMessage](movemessage)(int, string) | Moves the message |
| [MoveMessage](movemessage)(string, string) | Moves the message |
| [MoveMessage](movemessage)(IConnection, int, string) | Moves the messaeg |
| [MoveMessage](movemessage)(IConnection, string, string) | Moves the message |
| [MoveMessage](movemessage)(int, string, bool) | Moves the message |
| [MoveMessage](movemessage)(string, string, bool) | Moves the message |
| [MoveMessage](movemessage)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessage](movemessage)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](movemessageasync)(int, string) | Moves the message |
| [MoveMessageAsync](movemessageasync)(string, string) | Moves the message |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string) | Moves the messaeg |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string) | Moves the message |
| [MoveMessageAsync](movemessageasync)(int, string, bool) | Moves the message |
| [MoveMessageAsync](movemessageasync)(int, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](movemessageasync)(string, string, bool) | Moves the message |
| [MoveMessageAsync](movemessageasync)(string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, bool) | Moves the messaeg |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, bool) | Moves the message |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, CancellationToken) | Moves the message |
| [MoveMessageAsync](movemessageasync)(int, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](movemessageasync)(string, string, bool, CancellationToken) | Moves the message |
| [MoveMessageAsync](movemessageasync)(IConnection, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessageAsync](movemessageasync)(IConnection, string, string, bool, CancellationToken) | Moves the message |
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
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(int, int, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(string, string, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, bool) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, bool) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(int, int, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(string, string, string, bool, CancellationToken) | Moves the message |
| [MoveMessagesAsync](movemessagesasync)(IConnection, int, int, string, bool, CancellationToken) | Moves the messaeg |
| [MoveMessagesAsync](movemessagesasync)(IConnection, string, string, string, bool, CancellationToken) | Moves the message |
| override [Noop](noop)() | 'No operation' command |
| override [Noop](noop)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)() | 'No operation' command |
| [NoopAsync](noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection, CancellationToken) | 'No operation' command |
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
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RemoveMessageFlagsAsync](removemessageflagsasync)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | Removes the flags of the message |
| [RenameFolder](renamefolder)(string, string) | Renames a specified folder to a new name |
| [RenameFolder](renamefolder)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](renamefolderasync)(string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](renamefolderasync)(IConnection, string, string) | Renames a specified folder to a new name |
| [RenameFolderAsync](renamefolderasync)(string, string, CancellationToken) | Renames a specified folder to a new name |
| [RenameFolderAsync](renamefolderasync)(IConnection, string, string, CancellationToken) | Renames a specified folder to a new name |
| [RequestCheckpoint](requestcheckpoint)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpoint](requestcheckpoint)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](requestcheckpointasync)() | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](requestcheckpointasync)(CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](requestcheckpointasync)(IConnection) | Requests a checkpoint of the currently selected mailbox. |
| [RequestCheckpointAsync](requestcheckpointasync)(IConnection, CancellationToken) | Requests a checkpoint of the currently selected mailbox. |
| [Restore](restore)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings) | Begins to restore imap folders from the given personal storage. |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Begins to restore imap folders from the given personal storage. |
| [ResumeMonitoring](resumemonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [ResumeMonitoringAsync](resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [SaveMessage](savemessage)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessage](savemessage)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessage](savemessage)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string, CancellationToken) | Downloads the message with the specified sequence number and writes its data into a local file |
| [SelectFolder](selectfolder)(string) | Selects the specified folder |
| [SelectFolder](selectfolder)(IConnection, string) | Selects the specified folder |
| [SelectFolder](selectfolder)(string, bool?) | Selects the specified folder |
| [SelectFolder](selectfolder)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(string) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(IConnection, string) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(string, bool?) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, bool?) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(string, bool?, CancellationToken) | Selects the specified folder |
| [SelectFolderAsync](selectfolderasync)(IConnection, string, bool?, CancellationToken) | Selects the specified folder |
| [SetQuota](setquota)(string, string, int) | Sets quota information |
| [SetQuota](setquota)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](setquotaasync)(string, string, int) | Sets quota information |
| [SetQuotaAsync](setquotaasync)(IConnection, string, string, int) | Sets quota information |
| [SetQuotaAsync](setquotaasync)(string, string, int, CancellationToken) | Sets quota information |
| [SetQuotaAsync](setquotaasync)(IConnection, string, string, int, CancellationToken) | Sets quota information |
| [SortMessageThreads](sortmessagethreads)(SortConditions) | Get message threads. |
| [SortMessageThreads](sortmessagethreads)(IConnection, SortConditions) | Get message threads. |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(IConnection, SortConditions) | Sort message threads. |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(SortConditions, CancellationToken) | Sort message threads. |
| [SortMessageThreadsAsync](sortmessagethreadsasync)(IConnection, SortConditions, CancellationToken) | Sort message threads. |
| [StartMonitoring](startmonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StartMonitoringAsync](startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Starts monitoring of message changes for specified folder. |
| [StopMonitoring](stopmonitoring)() | Stops any monitoring of changes. |
| [StopMonitoring](stopmonitoring)(string) | Stops monitoring of message changes for specified folder. |
| [StopMonitoringAsync](stopmonitoringasync)() | Stops any monitoring of changes. |
| [StopMonitoringAsync](stopmonitoringasync)(string) | Stops monitoring of message changes for specified folder. |
| [SubscribeFolder](subscribefolder)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolder](subscribefolder)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](subscribefolderasync)(string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](subscribefolderasync)(IConnection, string) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](subscribefolderasync)(string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [SubscribeFolderAsync](subscribefolderasync)(IConnection, string, CancellationToken) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [UndeleteMessage](undeletemessage)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessage](undeletemessage)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessage](undeletemessage)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, long) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, long) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, int, long, CancellationToken) | Marks a message with the specified sequence number as not deleted |
| [UndeleteMessageAsync](undeletemessageasync)(IConnection, string, long, CancellationToken) | Marks a message with the specified sequence number as not deleted. |
| [UnselectFolder](unselectfolder)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](unselectfolder)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolder](unselectfolder)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolder](unselectfolder)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](unselectfolderasync)() | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](unselectfolderasync)(bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](unselectfolderasync)(CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](unselectfolderasync)(IConnection) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](unselectfolderasync)(bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, bool) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, CancellationToken) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnselectFolderAsync](unselectfolderasync)(IConnection, bool, CancellationToken) | Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691 |
| [UnsubscribeFolder](unsubscribefolder)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolder](unsubscribefolder)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(IConnection, string) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [UnsubscribeFolderAsync](unsubscribefolderasync)(IConnection, string, CancellationToken) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| override [ValidateCredentials](validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
