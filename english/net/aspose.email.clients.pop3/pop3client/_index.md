---
title: Pop3Client
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 15190
url: /net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Allows applications to access and manipulate messages by using the Post Office Protocol Version 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient
```

## Constructors

| Name | Description |
| --- | --- |
| [Pop3Client](pop3client)() | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, string, string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, string, string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, ITokenProvider, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, RemoteCertificateValidationCallback) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, bool, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Initializes a new instance of the [`Pop3Client`](../pop3client) class |

## Properties

| Name | Description |
| --- | --- |
| [AllowedAuthentication](allowedauthentication) { get; set; } | Gets or sets enumeration of allowed by user authentication types |
| override [DefaultPort](defaultport) { get; } | Gets default port for client |
| [SupportedAuthentication](supportedauthentication) { get; } | Gets enumeration of supported by server authentication types |

## Methods

| Name | Description |
| --- | --- |
| [CommitDeletes](commitdeletes)() | Commit the deletions |
| [CommitDeletes](commitdeletes)(IConnection) | Commit the deletions |
| [CommitDeletes](commitdeletes)(int) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)() |  |
| [CommitDeletesAsync](commitdeletesasync)(CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection) |  |
| [CommitDeletesAsync](commitdeletesasync)(int) |  |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, CancellationToken) |  |
| [CommitDeletesAsync](commitdeletesasync)(int, CancellationToken) |  |
| [DeleteMessage](deletemessage)(int) | Deletes the message |
| [DeleteMessage](deletemessage)(string) | Deletes the message |
| [DeleteMessage](deletemessage)(IConnection, int) | Deletes the message |
| [DeleteMessage](deletemessage)(IConnection, string) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(int) |  |
| [DeleteMessageAsync](deletemessageasync)(string) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string) |  |
| [DeleteMessageAsync](deletemessageasync)(int, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(string, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, CancellationToken) |  |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, CancellationToken) |  |
| [DeleteMessages](deletemessages)() | Deletes all messages |
| [DeleteMessages](deletemessages)(IConnection) | Deletes all messages |
| [DeleteMessagesAsync](deletemessagesasync)() |  |
| [DeleteMessagesAsync](deletemessagesasync)(CancellationToken) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection) |  |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, CancellationToken) |  |
| [FetchMessage](fetchmessage)(int) | Fetches the message |
| [FetchMessage](fetchmessage)(string) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int) |  |
| [FetchMessageAsync](fetchmessageasync)(string) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string) |  |
| [FetchMessageAsync](fetchmessageasync)(int, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(string, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, CancellationToken) |  |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string, CancellationToken) |  |
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
| [GetMailboxInfo](getmailboxinfo)() | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(bool) | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(IConnection) | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(IConnection, bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)() |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(bool) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(CancellationToken) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(bool, CancellationToken) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, bool) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, CancellationToken) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, bool, CancellationToken) |  |
| [GetMailboxSize](getmailboxsize)() | Gets the size of the mailbox |
| [GetMailboxSize](getmailboxsize)(IConnection) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](getmailboxsizeasync)() |  |
| [GetMailboxSizeAsync](getmailboxsizeasync)(CancellationToken) |  |
| [GetMailboxSizeAsync](getmailboxsizeasync)(IConnection) |  |
| [GetMailboxSizeAsync](getmailboxsizeasync)(IConnection, CancellationToken) |  |
| [GetMessageCount](getmessagecount)() | Gets the message count |
| [GetMessageCount](getmessagecount)(bool) | Gets the message count |
| [GetMessageCount](getmessagecount)(IConnection) | Gets the message count |
| [GetMessageCount](getmessagecount)(IConnection, bool) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)() |  |
| [GetMessageCountAsync](getmessagecountasync)(bool) |  |
| [GetMessageCountAsync](getmessagecountasync)(CancellationToken) |  |
| [GetMessageCountAsync](getmessagecountasync)(IConnection) |  |
| [GetMessageCountAsync](getmessagecountasync)(bool, CancellationToken) |  |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, bool) |  |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, CancellationToken) |  |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, bool, CancellationToken) |  |
| [GetMessageHeaders](getmessageheaders)(int) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(string) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(IConnection, int) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(IConnection, string) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(int) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(string) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, int) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, string) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(int, CancellationToken) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(string, CancellationToken) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, int, CancellationToken) |  |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, string, CancellationToken) |  |
| [GetMessageInfo](getmessageinfo)(int) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(string) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, int) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, string) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(int) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(string) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(int, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(int, Pop3ListFields) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(string, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(string, Pop3ListFields) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, Pop3ListFields) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, Pop3ListFields) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(int, Pop3ListFields, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(string, Pop3ListFields, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, Pop3ListFields, CancellationToken) |  |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, Pop3ListFields, CancellationToken) |  |
| [GetMessageSize](getmessagesize)(int) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(string) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(IConnection, int) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(IConnection, string) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(int) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(string) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, int) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, string) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(int, CancellationToken) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(string, CancellationToken) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, int, CancellationToken) |  |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, string, CancellationToken) |  |
| [GetMessageUniqueId](getmessageuniqueid)(int) | Gets the message unique id |
| [GetMessageUniqueId](getmessageuniqueid)(IConnection, int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(int) |  |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(IConnection, int) |  |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(int, CancellationToken) |  |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(IConnection, int, CancellationToken) |  |
| [ListMessages](listmessages)() | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(bool) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(MailQuery) | Lists the messages. |
| [ListMessages](listmessages)(Pop3ListFields) | Lists the messages. |
| [ListMessages](listmessages)(IConnection, bool) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, IEnumerable&lt;int&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, IEnumerable&lt;string&gt;) | Lists the messages. Gets an information for earch message |
| [ListMessages](listmessages)(IConnection, MailQuery) | Lists the messages. |
| [ListMessages](listmessages)(IConnection, Pop3ListFields) | Lists the messages. |
| [ListMessages](listmessages)(Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessages](listmessages)(IConnection, Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)() |  |
| [ListMessagesAsync](listmessagesasync)(bool) |  |
| [ListMessagesAsync](listmessagesasync)(CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields) |  |
| [ListMessagesAsync](listmessagesasync)(bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields) |  |
| [ListMessagesAsync](listmessagesasync)(MailQuery, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, bool, MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery) |  |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, bool, MailQuery, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) |  |
| [LoadMessageInfoList](loadmessageinfolist)(IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IConnection, IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;int&gt;) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;int&gt;, CancellationToken) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) |  |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) |  |
| override [Noop](noop)() | 'No operation' command |
| override [Noop](noop)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)() |  |
| [NoopAsync](noopasync)(CancellationToken) |  |
| [NoopAsync](noopasync)(IConnection) |  |
| [NoopAsync](noopasync)(IConnection, CancellationToken) |  |
| [SaveMessage](savemessage)(int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(int, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(string, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(IConnection, int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(IConnection, int, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(IConnection, string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(IConnection, string, string) | Fetches and save the message into a file |
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
| [UndeleteMessages](undeletemessages)() | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessages](undeletemessages)(IConnection) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](undeletemessagesasync)() |  |
| [UndeleteMessagesAsync](undeletemessagesasync)(CancellationToken) |  |
| [UndeleteMessagesAsync](undeletemessagesasync)(IConnection) |  |
| [UndeleteMessagesAsync](undeletemessagesasync)(IConnection, CancellationToken) |  |
| override [ValidateCredentials](validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)() |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(CancellationToken) |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection) |  |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection, CancellationToken) |  |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
