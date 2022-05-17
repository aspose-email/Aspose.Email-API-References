---
title: Pop3Client
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 16740
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
| [CommitDeletesAsync](commitdeletesasync)() | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(int) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(IConnection, CancellationToken) | Commit the deletions |
| [CommitDeletesAsync](commitdeletesasync)(int, CancellationToken) | Commit the deletions |
| [DeleteMessage](deletemessage)(int) | Deletes the message |
| [DeleteMessage](deletemessage)(string) | Deletes the message |
| [DeleteMessage](deletemessage)(IConnection, int) | Deletes the message |
| [DeleteMessage](deletemessage)(IConnection, string) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(int) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(string) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(int, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(string, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(IConnection, int, CancellationToken) | Deletes the message |
| [DeleteMessageAsync](deletemessageasync)(IConnection, string, CancellationToken) | Deletes the message |
| [DeleteMessages](deletemessages)() | Deletes all messages |
| [DeleteMessages](deletemessages)(IConnection) | Deletes all messages |
| [DeleteMessagesAsync](deletemessagesasync)() | Deletes all messages |
| [DeleteMessagesAsync](deletemessagesasync)(CancellationToken) | Deletes all messages |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection) | Deletes all messages |
| [DeleteMessagesAsync](deletemessagesasync)(IConnection, CancellationToken) | Deletes all messages |
| [FetchMessage](fetchmessage)(int) | Fetches the message |
| [FetchMessage](fetchmessage)(string) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, int) | Fetches the message |
| [FetchMessage](fetchmessage)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(string, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, int, CancellationToken) | Fetches the message |
| [FetchMessageAsync](fetchmessageasync)(IConnection, string, CancellationToken) | Fetches the message |
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
| [GetMailboxInfo](getmailboxinfo)() | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(bool) | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(IConnection) | Gets the mailbox status info |
| [GetMailboxInfo](getmailboxinfo)(IConnection, bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)() | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(bool, CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, bool) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, CancellationToken) | Gets the mailbox status info |
| [GetMailboxInfoAsync](getmailboxinfoasync)(IConnection, bool, CancellationToken) | Gets the mailbox status info |
| [GetMailboxSize](getmailboxsize)() | Gets the size of the mailbox |
| [GetMailboxSize](getmailboxsize)(IConnection) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](getmailboxsizeasync)() | Gets the size of the mailbox |
| [GetMailboxSizeAsync](getmailboxsizeasync)(CancellationToken) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](getmailboxsizeasync)(IConnection) | Gets the size of the mailbox |
| [GetMailboxSizeAsync](getmailboxsizeasync)(IConnection, CancellationToken) | Gets the size of the mailbox |
| [GetMessageCount](getmessagecount)() | Gets the message count |
| [GetMessageCount](getmessagecount)(bool) | Gets the message count |
| [GetMessageCount](getmessagecount)(IConnection) | Gets the message count |
| [GetMessageCount](getmessagecount)(IConnection, bool) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)() | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(bool) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(CancellationToken) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(IConnection) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(bool, CancellationToken) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, bool) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, CancellationToken) | Gets the message count |
| [GetMessageCountAsync](getmessagecountasync)(IConnection, bool, CancellationToken) | Gets the message count |
| [GetMessageHeaders](getmessageheaders)(int) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(string) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(IConnection, int) | Gets the message headers |
| [GetMessageHeaders](getmessageheaders)(IConnection, string) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(int) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(string) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, int) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, string) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(int, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(string, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, int, CancellationToken) | Gets the message headers |
| [GetMessageHeadersAsync](getmessageheadersasync)(IConnection, string, CancellationToken) | Gets the message headers |
| [GetMessageInfo](getmessageinfo)(int) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(string) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, int) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, string) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfo](getmessageinfo)(IConnection, string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(int) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(string) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(int, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(string, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, Pop3ListFields) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(int, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(string, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, int, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageInfoAsync](getmessageinfoasync)(IConnection, string, Pop3ListFields, CancellationToken) | Gets the information for that message |
| [GetMessageSize](getmessagesize)(int) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(string) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(IConnection, int) | Gets the size of the message |
| [GetMessageSize](getmessagesize)(IConnection, string) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(int) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(string) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, int) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, string) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(int, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(string, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, int, CancellationToken) | Gets the size of the message |
| [GetMessageSizeAsync](getmessagesizeasync)(IConnection, string, CancellationToken) | Gets the size of the message |
| [GetMessageUniqueId](getmessageuniqueid)(int) | Gets the message unique id |
| [GetMessageUniqueId](getmessageuniqueid)(IConnection, int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(IConnection, int) | Gets the message unique id |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(int, CancellationToken) | Gets the message unique id |
| [GetMessageUniqueIdAsync](getmessageuniqueidasync)(IConnection, int, CancellationToken) | Gets the message unique id |
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
| [ListMessagesAsync](listmessagesasync)() | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(bool) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(IConnection) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(MailQuery) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(bool, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(IConnection, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(IConnection, bool, CancellationToken) | Lists the messages. Gets an information for earch message |
| [ListMessagesAsync](listmessagesasync)(IConnection, MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(Pop3ListFields, bool, MailQuery, CancellationToken) | Lists the messages. |
| [ListMessagesAsync](listmessagesasync)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Lists the messages. |
| [LoadMessageInfoList](loadmessageinfolist)(IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IConnection, IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoList](loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;int&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| [LoadMessageInfoListAsync](loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Loads list of Pop3MessageInfo |
| override [Noop](noop)() | 'No operation' command |
| override [Noop](noop)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)() | 'No operation' command |
| [NoopAsync](noopasync)(CancellationToken) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection) | 'No operation' command |
| [NoopAsync](noopasync)(IConnection, CancellationToken) | 'No operation' command |
| [SaveMessage](savemessage)(int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(int, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(string, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(IConnection, int, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(IConnection, int, string) | Fetches and save the message into a file |
| [SaveMessage](savemessage)(IConnection, string, Stream) | Fetches and save the message as a stream |
| [SaveMessage](savemessage)(IConnection, string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(int, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(int, string) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(string, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(int, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(int, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(string, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(string, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(IConnection, int, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(IConnection, int, string, CancellationToken) | Fetches and save the message into a file |
| [SaveMessageAsync](savemessageasync)(IConnection, string, Stream, CancellationToken) | Fetches and save the message as a stream |
| [SaveMessageAsync](savemessageasync)(IConnection, string, string, CancellationToken) | Fetches and save the message into a file |
| [UndeleteMessages](undeletemessages)() | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessages](undeletemessages)(IConnection) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](undeletemessagesasync)() | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](undeletemessagesasync)(CancellationToken) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](undeletemessagesasync)(IConnection) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| [UndeleteMessagesAsync](undeletemessagesasync)(IConnection, CancellationToken) | Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked. |
| override [ValidateCredentials](validatecredentials)() | Executes credentials validation |
| [ValidateCredentials](validatecredentials)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)() | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(CancellationToken) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection) | Executes credentials validation |
| [ValidateCredentialsAsync](validatecredentialsasync)(IConnection, CancellationToken) | Executes credentials validation |

### See Also

* class [EmailClient](../../aspose.email.clients/emailclient)
* namespace [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
