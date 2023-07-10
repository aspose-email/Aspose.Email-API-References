---
title: Pop3Client
second_title: Aspose.Email for Java API Reference
description: Allows applications to access and manipulate  messages by using the Post Office Protocol Version 3 POP3.
type: docs
weight: 570
url: /java/com.aspose.email/pop3client/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.EmailClient](../../com.aspose.email/emailclient)
```
public final class Pop3Client extends EmailClient
```

Allows applications to access and manipulate messages by using the Post Office Protocol Version 3 (POP3).
## Constructors

| Constructor | Description |
| --- | --- |
| [Pop3Client()](#Pop3Client--) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host)](#Pop3Client-java.lang.String-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, short securityOptions)](#Pop3Client-java.lang.String-short-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port)](#Pop3Client-java.lang.String-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, int securityOptions)](#Pop3Client-java.lang.String-int-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, String username, String password)](#Pop3Client-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, String username, String password, int securityOptions)](#Pop3Client-java.lang.String-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, String password)](#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, String password, int securityOptions)](#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions)](#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-boolean-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions)](#Pop3Client-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback)](#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
| [Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback, int securityOptions)](#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback-int-) | Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class |
## Methods

| Method | Description |
| --- | --- |
| [beginCommitDeletes()](#beginCommitDeletes--) | Begins to commit the deletions. |
| [beginCommitDeletes(IConnection connection)](#beginCommitDeletes-com.aspose.email.IConnection-) | Begins to commit the deletions. |
| [beginCommitDeletes(IConnection connection, System.AsyncCallback callback)](#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to commit the deletions. |
| [beginCommitDeletes(IConnection connection, System.AsyncCallback callback, Object state)](#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to commit the deletions. |
| [beginCommitDeletes(System.AsyncCallback callback)](#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-) | Begins to commit the deletions. |
| [beginCommitDeletes(System.AsyncCallback callback, Object state)](#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to commit the deletions. |
| [beginDeleteMessage(IConnection connection, int sequenceNumber)](#beginDeleteMessage-com.aspose.email.IConnection-int-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginDeleteMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginDeleteMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(IConnection connection, String uniqueId)](#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(int sequenceNumber)](#beginDeleteMessage-int-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback)](#beginDeleteMessage-int-com.aspose.ms.System.AsyncCallback-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginDeleteMessage-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(String uniqueId)](#beginDeleteMessage-java.lang.String-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(String uniqueId, System.AsyncCallback callback)](#beginDeleteMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessage(String uniqueId, System.AsyncCallback callback, Object state)](#beginDeleteMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins DeleteMessage operation asynchronously |
| [beginDeleteMessages()](#beginDeleteMessages--) | Begins delete all messages asynchronously |
| [beginDeleteMessages(IConnection connection)](#beginDeleteMessages-com.aspose.email.IConnection-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(IConnection connection, System.AsyncCallback callback)](#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(System.AsyncCallback callback)](#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(System.AsyncCallback callback, Object state)](#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins delete all messages asynchronously |
| [beginFetchMessage(IConnection connection, int sequenceNumber)](#beginFetchMessage-com.aspose.email.IConnection-int-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginFetchMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginFetchMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(IConnection connection, String uniqueId)](#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(int sequenceNumber)](#beginFetchMessage-int-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(int sequenceNumber, System.AsyncCallback callback)](#beginFetchMessage-int-com.aspose.ms.System.AsyncCallback-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginFetchMessage-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(String uniqueId)](#beginFetchMessage-java.lang.String-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(String uniqueId, System.AsyncCallback callback)](#beginFetchMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessage(String uniqueId, System.AsyncCallback callback, Object state)](#beginFetchMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessage operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback, Object state)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback, Object state)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginGetMailboxInfo()](#beginGetMailboxInfo--) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection)](#beginGetMailboxInfo-com.aspose.email.IConnection-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback)](#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(System.AsyncCallback callback)](#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [beginGetMailboxSize()](#beginGetMailboxSize--) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(IConnection connection)](#beginGetMailboxSize-com.aspose.email.IConnection-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(IConnection connection, System.AsyncCallback callback)](#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(System.AsyncCallback callback)](#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(System.AsyncCallback callback, Object state)](#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMessageCount()](#beginGetMessageCount--) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction)](#beginGetMessageCount-boolean-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback)](#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection)](#beginGetMessageCount-com.aspose.email.IConnection-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber)](#beginGetMessageHeaders-int-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId)](#beginGetMessageHeaders-java.lang.String-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback)](#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber)](#beginGetMessageInfo-com.aspose.email.IConnection-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber)](#beginGetMessageInfo-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields)](#beginGetMessageInfo-int-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId)](#beginGetMessageInfo-java.lang.String-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, System.AsyncCallback callback)](#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields)](#beginGetMessageInfo-java.lang.String-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageSize(IConnection connection, int sequenceNumber)](#beginGetMessageSize-com.aspose.email.IConnection-int-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber)](#beginGetMessageSize-int-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId)](#beginGetMessageSize-java.lang.String-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId, System.AsyncCallback callback)](#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber)](#beginGetMessageUniqueId-int-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the message unique id |
| [beginListMessages()](#beginListMessages--) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection)](#beginListMessages-com.aspose.email.IConnection-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [beginListMessages(MailQuery query)](#beginListMessages-com.aspose.email.MailQuery-) | Begins ListMessage operation asynchronously |
| [beginListMessages(MailQuery query, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-) | Begins ListMessage operation asynchronously |
| [beginListMessages(MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [beginListMessages(System.AsyncCallback callback)](#beginListMessages-com.aspose.ms.System.AsyncCallback-) | Begins ListMessages operation asynchronously |
| [beginListMessages(System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessages operation asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginNoop()](#beginNoop--) | Begins 'No operation' command. |
| [beginNoop(IConnection connection)](#beginNoop-com.aspose.email.IConnection-) | Begins 'No operation' command. |
| [beginNoop(IConnection connection, System.AsyncCallback callback)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins 'No operation' command. |
| [beginNoop(IConnection connection, System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins 'No operation' command. |
| [beginNoop(System.AsyncCallback callback)](#beginNoop-com.aspose.ms.System.AsyncCallback-) | Begins 'No operation' command. |
| [beginNoop(System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins 'No operation' command. |
| [beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream)](#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback)](#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state)](#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream)](#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback)](#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state)](#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(int sequenceNumber, OutputStream outputStream)](#beginSaveMessage-int-java.io.OutputStream-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback)](#beginSaveMessage-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state)](#beginSaveMessage-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(String uniqueId, OutputStream outputStream)](#beginSaveMessage-java.lang.String-java.io.OutputStream-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback)](#beginSaveMessage-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-) | Begins SaveMessage operation asynchronously |
| [beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state)](#beginSaveMessage-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins SaveMessage operation asynchronously |
| [beginUndeleteMessages()](#beginUndeleteMessages--) | Begins undeletes the messages. |
| [beginUndeleteMessages(IConnection connection)](#beginUndeleteMessages-com.aspose.email.IConnection-) | Begins undeletes the messages. |
| [beginUndeleteMessages(IConnection connection, System.AsyncCallback callback)](#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins undeletes the messages. |
| [beginUndeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins undeletes the messages. |
| [beginUndeleteMessages(System.AsyncCallback callback)](#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-) | Begins undeletes the messages. |
| [beginUndeleteMessages(System.AsyncCallback callback, Object state)](#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins undeletes the messages. |
| [beginValidateCredentials()](#beginValidateCredentials--) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection)](#beginValidateCredentials-com.aspose.email.IConnection-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [bindIPEndPoint(BindIPEndPointHandler handler)](#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a local endpoint. |
| [cancelAsyncOperation(System.IAsyncResult asyncResult)](#cancelAsyncOperation-com.aspose.ms.System.IAsyncResult-) | Cancels asynchronous operation. |
| [close()](#close--) |  |
| [commitDeletes()](#commitDeletes--) | Commit the deletions |
| [commitDeletes(IConnection connection)](#commitDeletes-com.aspose.email.IConnection-) | Commit the deletions |
| [commitDeletes(int sleep)](#commitDeletes-int-) | Commit the deletions |
| [connectIPEndPoint(BindIPEndPointHandler handler)](#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-) | Associates a Socket with a remote endpoint. |
| [createConnection()](#createConnection--) | Creates new independent connection for operations not linked to threads (not default connection). |
| [createConnection(boolean createAsDefaultConnection)](#createConnection-boolean-) | Creates new (default or independent) connection for operations. |
| [deleteMessage(IConnection connection, int sequenceNumber)](#deleteMessage-com.aspose.email.IConnection-int-) | Deletes the message |
| [deleteMessage(IConnection connection, String uniqueId)](#deleteMessage-com.aspose.email.IConnection-java.lang.String-) | Deletes the message |
| [deleteMessage(int sequenceNumber)](#deleteMessage-int-) | Deletes the message |
| [deleteMessage(String uniqueId)](#deleteMessage-java.lang.String-) | Deletes the message |
| [deleteMessages()](#deleteMessages--) | Deletes all messages |
| [deleteMessages(IConnection connection)](#deleteMessages-com.aspose.email.IConnection-) | Deletes all messages |
| [dispose()](#dispose--) | Finalizes all operations with a server. |
| [endCommitDeletes(System.IAsyncResult asyncResult)](#endCommitDeletes-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endDeleteMessage(System.IAsyncResult asyncResult)](#endDeleteMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endDeleteMessages(System.IAsyncResult asyncResult)](#endDeleteMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endFetchMessage(System.IAsyncResult asyncResult)](#endFetchMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endFetchMessages(System.IAsyncResult asyncResult)](#endFetchMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMailboxInfo(System.IAsyncResult asyncResult)](#endGetMailboxInfo-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMailboxSize(System.IAsyncResult asyncResult)](#endGetMailboxSize-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMessageCount(System.IAsyncResult asyncResult)](#endGetMessageCount-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMessageHeaders(System.IAsyncResult asyncResult)](#endGetMessageHeaders-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMessageInfo(System.IAsyncResult asyncResult)](#endGetMessageInfo-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMessageSize(System.IAsyncResult asyncResult)](#endGetMessageSize-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endGetMessageUniqueId(System.IAsyncResult asyncResult)](#endGetMessageUniqueId-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endListMessages(System.IAsyncResult asyncResult)](#endListMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endLoadMessageInfoList(System.IAsyncResult asyncResult)](#endLoadMessageInfoList-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endNoop(System.IAsyncResult asyncResult)](#endNoop-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endSaveMessage(System.IAsyncResult asyncResult)](#endSaveMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endUndeleteMessages(System.IAsyncResult asyncResult)](#endUndeleteMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [endValidateCredentials(System.IAsyncResult asyncResult)](#endValidateCredentials-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fetchMessage(IConnection connection, int sequenceNumber)](#fetchMessage-com.aspose.email.IConnection-int-) | Fetches the message |
| [fetchMessage(IConnection connection, String uniqueId)](#fetchMessage-com.aspose.email.IConnection-java.lang.String-) | Fetches the message |
| [fetchMessage(int sequenceNumber)](#fetchMessage-int-) | Fetches the message |
| [fetchMessage(String uniqueId)](#fetchMessage-java.lang.String-) | Fetches the message |
| [fetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)](#fetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Fetches the messages |
| [fetchMessagesBySequences(Iterable<Integer> sequenceNumbers)](#fetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Fetches the messages |
| [fetchMessagesByUids(IConnection connection, Iterable<String> uids)](#fetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Fetches the messages |
| [fetchMessagesByUids(Iterable<String> uids)](#fetchMessagesByUids-java.lang.Iterable-java.lang.String--) | Fetches the messages |
| [getAccessToken()](#getAccessToken--) | Gets or sets the access token. |
| [getAllowedAuthentication()](#getAllowedAuthentication--) | Gets or sets enumeration of allowed by user authentication types |
| [getCapabilities()](#getCapabilities--) | Get Capabilities. |
| [getClass()](#getClass--) |  |
| [getClientCertificates()](#getClientCertificates--) | Contains collection of clients certificates |
| [getConnectionAsgmtMode()](#getConnectionAsgmtMode--) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [getConnectionCheckupPeriod()](#getConnectionCheckupPeriod--) | Period of connection checking up in milliseconds. |
| [getConnectionState()](#getConnectionState--) | Gets the current state of the connection. |
| [getConnectionsQuantity()](#getConnectionsQuantity--) | Gets or sets quantity of connections in multy-connection mode |
| [getCurrentConnection()](#getCurrentConnection--) | Gets current connection according to ConnectionAsgmtMode option |
| [getDefaultPort()](#getDefaultPort--) | Gets default port for client |
| [getEnableLogger()](#getEnableLogger--) | Gets or sets value which allows enable/disable logger |
| [getGreetingTimeout()](#getGreetingTimeout--) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [getHost()](#getHost--) | Gets or sets the host name. |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getMailboxInfo()](#getMailboxInfo--) | Gets the mailbox status info |
| [getMailboxInfo(boolean closeTransaction)](#getMailboxInfo-boolean-) | Gets the mailbox status info |
| [getMailboxInfo(IConnection connection)](#getMailboxInfo-com.aspose.email.IConnection-) | Gets the mailbox status info |
| [getMailboxInfo(IConnection connection, boolean closeTransaction)](#getMailboxInfo-com.aspose.email.IConnection-boolean-) | Gets the mailbox status info |
| [getMailboxSize()](#getMailboxSize--) | Gets the size of the mailbox |
| [getMailboxSize(IConnection connection)](#getMailboxSize-com.aspose.email.IConnection-) | Gets the size of the mailbox |
| [getMessageCount()](#getMessageCount--) | Gets the message count |
| [getMessageCount(boolean closeTransaction)](#getMessageCount-boolean-) | Gets the message count |
| [getMessageCount(IConnection connection)](#getMessageCount-com.aspose.email.IConnection-) | Gets the message count |
| [getMessageCount(IConnection connection, boolean closeTransaction)](#getMessageCount-com.aspose.email.IConnection-boolean-) | Gets the message count |
| [getMessageHeaders(IConnection connection, int sequenceNumber)](#getMessageHeaders-com.aspose.email.IConnection-int-) | Gets the message headers |
| [getMessageHeaders(IConnection connection, String uniqueId)](#getMessageHeaders-com.aspose.email.IConnection-java.lang.String-) | Gets the message headers |
| [getMessageHeaders(int sequenceNumber)](#getMessageHeaders-int-) | Gets the message headers |
| [getMessageHeaders(String uniqueId)](#getMessageHeaders-java.lang.String-) | Gets the message headers |
| [getMessageInfo(IConnection connection, int sequenceNumber)](#getMessageInfo-com.aspose.email.IConnection-int-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, int sequenceNumber, int fields)](#getMessageInfo-com.aspose.email.IConnection-int-int-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, String uniqueId)](#getMessageInfo-com.aspose.email.IConnection-java.lang.String-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, String uniqueId, int fields)](#getMessageInfo-com.aspose.email.IConnection-java.lang.String-int-) | Gets the information for that message |
| [getMessageInfo(int sequenceNumber)](#getMessageInfo-int-) | Gets the information for that message |
| [getMessageInfo(int sequenceNumber, int fields)](#getMessageInfo-int-int-) | Gets the information for that message |
| [getMessageInfo(String uniqueId)](#getMessageInfo-java.lang.String-) | Gets the information for that message |
| [getMessageInfo(String uniqueId, int fields)](#getMessageInfo-java.lang.String-int-) | Gets the information for that message |
| [getMessageSize(IConnection connection, int sequenceNumber)](#getMessageSize-com.aspose.email.IConnection-int-) | Gets the size of the message |
| [getMessageSize(IConnection connection, String uniqueId)](#getMessageSize-com.aspose.email.IConnection-java.lang.String-) | Gets the size of the message |
| [getMessageSize(int sequenceNumber)](#getMessageSize-int-) | Gets the size of the message |
| [getMessageSize(String uniqueId)](#getMessageSize-java.lang.String-) | Gets the size of the message |
| [getMessageUniqueId(IConnection connection, int sequenceNumber)](#getMessageUniqueId-com.aspose.email.IConnection-int-) | Gets the message unique id |
| [getMessageUniqueId(int sequenceNumber)](#getMessageUniqueId-int-) | Gets the message unique id |
| [getPassword()](#getPassword--) | Gets or sets the password. |
| [getPort()](#getPort--) | Gets or sets the port. |
| [getProxy()](#getProxy--) | Gets or sets proxy for the client |
| [getSecurityOptions()](#getSecurityOptions--) | Security mode for a mail client |
| [getSupportedAuthentication()](#getSupportedAuthentication--) | Gets enumeration of supported by server authentication types |
| [getSupportedEncryption()](#getSupportedEncryption--) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [getTimeout()](#getTimeout--) | Gets or sets the timeout for mail operations |
| [getTokenProvider()](#getTokenProvider--) | Gets or sets TokenProvider allowing to retrieve access token. |
| [getUseAuthentication()](#getUseAuthentication--) | Indicates whether authentication is used. |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [getUseDefaultCredentials()](#getUseDefaultCredentials--) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [getUseMultiConnection()](#getUseMultiConnection--) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [getUsePipelining()](#getUsePipelining--) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [getUsername()](#getUsername--) | Gets or sets the username. |
| [hashCode()](#hashCode--) |  |
| [listMessages()](#listMessages--) | Lists the messages. |
| [listMessages(boolean closeTransaction)](#listMessages-boolean-) | Lists the messages. |
| [listMessages(IConnection connection)](#listMessages-com.aspose.email.IConnection-) | Lists the messages. |
| [listMessages(IConnection connection, boolean closeTransaction)](#listMessages-com.aspose.email.IConnection-boolean-) | Lists the messages. |
| [listMessages(IConnection connection, MailQuery query)](#listMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages(IConnection connection, int fields)](#listMessages-com.aspose.email.IConnection-int-) | Lists the messages. |
| [listMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query)](#listMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages(MailQuery query)](#listMessages-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages(int fields)](#listMessages-int-) | Lists the messages. |
| [listMessages(int fields, boolean closeTransaction, MailQuery query)](#listMessages-int-boolean-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumberLst)](#listMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Lists the messages. |
| [listMessagesBySequences(Iterable<Integer> sequenceNumberLst)](#listMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Lists the messages. |
| [listMessagesByUids(IConnection connection, Iterable<String> uniqueIdLst)](#listMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Lists the messages. |
| [listMessagesByUids(Iterable<String> uniqueIdLst)](#listMessagesByUids-java.lang.Iterable-java.lang.String--) | Lists the messages. |
| [loadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)](#loadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)](#loadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)](#loadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)](#loadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--) | Loads list of Pop3MessageInfo |
| [noop()](#noop--) | 'No operation' command |
| [noop(IConnection connection)](#noop-com.aspose.email.IConnection-) | 'No operation' command |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [saveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream)](#saveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(IConnection connection, int sequenceNumber, String fileName)](#saveMessage-com.aspose.email.IConnection-int-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(IConnection connection, String uniqueId, OutputStream outputStream)](#saveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(IConnection connection, String uniqueId, String fileName)](#saveMessage-com.aspose.email.IConnection-java.lang.String-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(int sequenceNumber, OutputStream outputStream)](#saveMessage-int-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(int sequenceNumber, String fileName)](#saveMessage-int-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(String uniqueId, OutputStream outputStream)](#saveMessage-java.lang.String-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(String uniqueId, String fileName)](#saveMessage-java.lang.String-java.lang.String-) | Fetches and save the message into a file |
| [setAccessToken(String value)](#setAccessToken-java.lang.String-) | Gets or sets the access token. |
| [setAllowedAuthentication(long value)](#setAllowedAuthentication-long-) | Gets or sets enumeration of allowed by user authentication types |
| [setConnectionAsgmtMode(int value)](#setConnectionAsgmtMode-int-) | Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. |
| [setConnectionCheckupPeriod(int value)](#setConnectionCheckupPeriod-int-) | Period of connection checking up in milliseconds. |
| [setConnectionsQuantity(int value)](#setConnectionsQuantity-int-) | Gets or sets quantity of connections in multy-connection mode |
| [setEnableLogger(boolean value)](#setEnableLogger-boolean-) | Gets or sets value which allows enable/disable logger |
| [setGreetingTimeout(int value)](#setGreetingTimeout-int-) | Gets or sets the greeting timeout that is used when establishing a connection. |
| [setHost(String value)](#setHost-java.lang.String-) | Gets or sets the host name. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password. |
| [setPort(int value)](#setPort-int-) | Gets or sets the port. |
| [setProxy(Proxy value)](#setProxy-com.aspose.email.Proxy-) | Gets or sets proxy for the client |
| [setSecurityOptions(int value)](#setSecurityOptions-int-) | Security mode for a mail client |
| [setSocketsLayerVersion2(boolean value)](#setSocketsLayerVersion2-boolean-) | Sets value indicating whether Sockets Layer version 2 is used. |
| [setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value)](#setSocketsLayerVersion2DisableSSLCertificateValidation-boolean-) | Disable SSL certificate validation for Sockets Layer version 2 |
| [setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value)](#setSocketsLayerVersion2SSLSocketFactory-javax.net.ssl.SSLSocketFactory-) | Set SSL Socket Factory for Sockets Layer version 2 |
| [setSupportedEncryption(int value)](#setSupportedEncryption-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [setSupportedEncryptionUnsafe(int value)](#setSupportedEncryptionUnsafe-int-) | Defines the versions of SSL/TLS encryption protocols to be used. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the timeout for mail operations |
| [setTokenProvider(ITokenProvider value)](#setTokenProvider-com.aspose.email.ITokenProvider-) | Gets or sets TokenProvider allowing to retrieve access token. |
| [setUseAuthentication(boolean value)](#setUseAuthentication-boolean-) | Indicates whether authentication is used. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseDefaultCredentials(boolean value)](#setUseDefaultCredentials-boolean-) | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. |
| [setUseMultiConnection(int value)](#setUseMultiConnection-int-) | Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. |
| [setUsePipelining(PipeliningStatus value)](#setUsePipelining-com.aspose.email.PipeliningStatus-) | Gets or sets object which indicates whether the pipelining mode is enabled. |
| [setUsername(String value)](#setUsername-java.lang.String-) | Gets or sets the username. |
| [toString()](#toString--) |  |
| [undeleteMessages()](#undeleteMessages--) | Undeletes the messages. |
| [undeleteMessages(IConnection connection)](#undeleteMessages-com.aspose.email.IConnection-) | Undeletes the messages. |
| [validateCredentials()](#validateCredentials--) | Executes credentials validation |
| [validateCredentials(IConnection connection)](#validateCredentials-com.aspose.email.IConnection-) | Executes credentials validation |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pop3Client() {#Pop3Client--}
```
public Pop3Client()
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

### Pop3Client(String host) {#Pop3Client-java.lang.String-}
```
public Pop3Client(String host)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |

### Pop3Client(String host, short securityOptions) {#Pop3Client-java.lang.String-short-}
```
public Pop3Client(String host, short securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| securityOptions | short | Security mode for a mail client |

### Pop3Client(String host, int port) {#Pop3Client-java.lang.String-int-}
```
public Pop3Client(String host, int port)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |

### Pop3Client(String host, int port, int securityOptions) {#Pop3Client-java.lang.String-int-int-}
```
public Pop3Client(String host, int port, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| securityOptions | int | Security mode for a mail client |

### Pop3Client(String host, String username, String password) {#Pop3Client-java.lang.String-java.lang.String-java.lang.String-}
```
public Pop3Client(String host, String username, String password)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| username | java.lang.String | The username |
| password | java.lang.String | The password |

### Pop3Client(String host, String username, String password, int securityOptions) {#Pop3Client-java.lang.String-java.lang.String-java.lang.String-int-}
```
public Pop3Client(String host, String username, String password, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| securityOptions | int | Security mode for a mail client |

### Pop3Client(String host, int port, String username, String password) {#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-}
```
public Pop3Client(String host, int port, String username, String password)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The username |
| password | java.lang.String | The password |

### Pop3Client(String host, int port, String username, String password, int securityOptions) {#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-int-}
```
public Pop3Client(String host, int port, String username, String password, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| securityOptions | int | Security mode for a mail client |

### Pop3Client(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions) {#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-boolean-int-}
```
public Pop3Client(String host, int port, String username, String authInfo, boolean useOAuth, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The user name |
| authInfo | java.lang.String | The user password or XOAUTH2 access token |
| useOAuth | boolean | Defines whether SASL XOAUTH2 mechanism is used to login to the server |
| securityOptions | int | Security mode for a mail client |

### Pop3Client(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions) {#Pop3Client-java.lang.String-int-java.lang.String-com.aspose.email.ITokenProvider-int-}
```
public Pop3Client(String host, int port, String username, ITokenProvider tokenProvider, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The user name |
| tokenProvider | [ITokenProvider](../../com.aspose.email/itokenprovider) | TokenProvider allowing to retrieve access token. |
| securityOptions | int | Security mode for a mail client |

### Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback) {#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback-}
```
public Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| userCertificateValidationCallback | com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback | System.Net.Security.RemoteCertificateValidationCallback |

### Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback, int securityOptions) {#Pop3Client-java.lang.String-int-java.lang.String-java.lang.String-com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback-int-}
```
public Pop3Client(String host, int port, String username, String password, System.Net.Security.RemoteCertificateValidationCallback userCertificateValidationCallback, int securityOptions)
```


Initializes a new instance of the [Pop3Client](../../com.aspose.email/pop3client) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| host | java.lang.String | The host name |
| port | int | The port number |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| userCertificateValidationCallback | com.aspose.ms.System.Net.Security.RemoteCertificateValidationCallback | System.Net.Security.RemoteCertificateValidationCallback |
| securityOptions | int | Security mode for a mail client |

### beginCommitDeletes() {#beginCommitDeletes--}
```
public final System.IAsyncResult beginCommitDeletes()
```


Begins to commit the deletions.

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginCommitDeletes(IConnection connection) {#beginCommitDeletes-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginCommitDeletes(IConnection connection)
```


Begins to commit the deletions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginCommitDeletes(IConnection connection, System.AsyncCallback callback) {#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginCommitDeletes(IConnection connection, System.AsyncCallback callback)
```


Begins to commit the deletions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginCommitDeletes(IConnection connection, System.AsyncCallback callback, Object state) {#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginCommitDeletes(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins to commit the deletions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginCommitDeletes(System.AsyncCallback callback) {#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginCommitDeletes(System.AsyncCallback callback)
```


Begins to commit the deletions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginCommitDeletes(System.AsyncCallback callback, Object state) {#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginCommitDeletes(System.AsyncCallback callback, Object state)
```


Begins to commit the deletions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, int sequenceNumber) {#beginDeleteMessage-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, int sequenceNumber)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginDeleteMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginDeleteMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, String uniqueId) {#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, String uniqueId)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback) {#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state) {#beginDeleteMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(int sequenceNumber) {#beginDeleteMessage-int-}
```
public final System.IAsyncResult beginDeleteMessage(int sequenceNumber)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback) {#beginDeleteMessage-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginDeleteMessage-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessage(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(String uniqueId) {#beginDeleteMessage-java.lang.String-}
```
public final System.IAsyncResult beginDeleteMessage(String uniqueId)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(String uniqueId, System.AsyncCallback callback) {#beginDeleteMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessage(String uniqueId, System.AsyncCallback callback)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessage(String uniqueId, System.AsyncCallback callback, Object state) {#beginDeleteMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessage(String uniqueId, System.AsyncCallback callback, Object state)
```


Begins DeleteMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessages() {#beginDeleteMessages--}
```
public final System.IAsyncResult beginDeleteMessages()
```


Begins delete all messages asynchronously

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state.
### beginDeleteMessages(IConnection connection) {#beginDeleteMessages-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginDeleteMessages(IConnection connection)
```


Begins delete all messages asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessages(IConnection connection, System.AsyncCallback callback) {#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessages(IConnection connection, System.AsyncCallback callback)
```


Begins delete all messages asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessages(IConnection connection, System.AsyncCallback callback, Object state) {#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins delete all messages asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessages(System.AsyncCallback callback) {#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginDeleteMessages(System.AsyncCallback callback)
```


Begins delete all messages asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginDeleteMessages(System.AsyncCallback callback, Object state) {#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginDeleteMessages(System.AsyncCallback callback, Object state)
```


Begins delete all messages asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, int sequenceNumber) {#beginFetchMessage-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, int sequenceNumber)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginFetchMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginFetchMessage-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, String uniqueId) {#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, String uniqueId)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback) {#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state) {#beginFetchMessage-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessage(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(int sequenceNumber) {#beginFetchMessage-int-}
```
public final System.IAsyncResult beginFetchMessage(int sequenceNumber)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(int sequenceNumber, System.AsyncCallback callback) {#beginFetchMessage-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessage(int sequenceNumber, System.AsyncCallback callback)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginFetchMessage-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessage(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(String uniqueId) {#beginFetchMessage-java.lang.String-}
```
public final System.IAsyncResult beginFetchMessage(String uniqueId)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(String uniqueId, System.AsyncCallback callback) {#beginFetchMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessage(String uniqueId, System.AsyncCallback callback)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessage(String uniqueId, System.AsyncCallback callback, Object state) {#beginFetchMessage-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessage(String uniqueId, System.AsyncCallback callback, Object state)
```


Begins FetchMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers) {#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--}
```
public final System.IAsyncResult beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback) {#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state) {#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers) {#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--}
```
public final System.IAsyncResult beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback) {#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state) {#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> |  |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(IConnection connection, Iterable<String> uids) {#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--}
```
public final System.IAsyncResult beginFetchMessagesByUids(IConnection connection, Iterable<String> uids)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback) {#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback, Object state) {#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback, Object state)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(Iterable<String> uids) {#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--}
```
public final System.IAsyncResult beginFetchMessagesByUids(Iterable<String> uids)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback) {#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback, Object state) {#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback, Object state)
```


Begins FetchMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo() {#beginGetMailboxInfo--}
```
public final System.IAsyncResult beginGetMailboxInfo()
```


Begins to get the mailbox status info

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(IConnection connection) {#beginGetMailboxInfo-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginGetMailboxInfo(IConnection connection)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state) {#beginGetMailboxInfo-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMailboxInfo(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback) {#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback, Object state) {#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(System.AsyncCallback callback) {#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMailboxInfo(System.AsyncCallback callback)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxInfo(System.AsyncCallback callback, Object state) {#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMailboxInfo(System.AsyncCallback callback, Object state)
```


Begins to get the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize() {#beginGetMailboxSize--}
```
public final System.IAsyncResult beginGetMailboxSize()
```


Begins GetMailboxSize operation asynchronously

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize(IConnection connection) {#beginGetMailboxSize-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginGetMailboxSize(IConnection connection)
```


Begins GetMailboxSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize(IConnection connection, System.AsyncCallback callback) {#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMailboxSize(IConnection connection, System.AsyncCallback callback)
```


Begins GetMailboxSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize(IConnection connection, System.AsyncCallback callback, Object state) {#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMailboxSize(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins GetMailboxSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize(System.AsyncCallback callback) {#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMailboxSize(System.AsyncCallback callback)
```


Begins GetMailboxSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMailboxSize(System.AsyncCallback callback, Object state) {#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMailboxSize(System.AsyncCallback callback, Object state)
```


Begins GetMailboxSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount() {#beginGetMessageCount--}
```
public final System.IAsyncResult beginGetMessageCount()
```


Begins GetMessageCount operation asynchronously

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(boolean closeTransaction) {#beginGetMessageCount-boolean-}
```
public final System.IAsyncResult beginGetMessageCount(boolean closeTransaction)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback) {#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback, Object state) {#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback, Object state)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection) {#beginGetMessageCount-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection, boolean closeTransaction) {#beginGetMessageCount-com.aspose.email.IConnection-boolean-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection, boolean closeTransaction)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback) {#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state) {#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection, System.AsyncCallback callback) {#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection, System.AsyncCallback callback)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(IConnection connection, System.AsyncCallback callback, Object state) {#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageCount(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(System.AsyncCallback callback) {#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageCount(System.AsyncCallback callback)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageCount(System.AsyncCallback callback, Object state) {#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageCount(System.AsyncCallback callback, Object state)
```


Begins GetMessageCount operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, int sequenceNumber) {#beginGetMessageHeaders-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, int sequenceNumber)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, String uniqueId) {#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, String uniqueId)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback) {#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(int sequenceNumber) {#beginGetMessageHeaders-int-}
```
public final System.IAsyncResult beginGetMessageHeaders(int sequenceNumber)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(String uniqueId) {#beginGetMessageHeaders-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageHeaders(String uniqueId)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback) {#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback, Object state)
```


Begins getting message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber) {#beginGetMessageInfo-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields) {#beginGetMessageInfo-com.aspose.email.IConnection-int-int-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback) {#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId, int fields) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId, int fields)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber) {#beginGetMessageInfo-int-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber, int fields) {#beginGetMessageInfo-int-int-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber, int fields)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback) {#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId) {#beginGetMessageInfo-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId, System.AsyncCallback callback) {#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId, int fields) {#beginGetMessageInfo-java.lang.String-int-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId, int fields)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback) {#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback, Object state) {#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback, Object state)
```


Begins to get the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, int sequenceNumber) {#beginGetMessageSize-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, int sequenceNumber)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, String uniqueId) {#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, String uniqueId)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback) {#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(int sequenceNumber) {#beginGetMessageSize-int-}
```
public final System.IAsyncResult beginGetMessageSize(int sequenceNumber)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(String uniqueId) {#beginGetMessageSize-java.lang.String-}
```
public final System.IAsyncResult beginGetMessageSize(String uniqueId)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(String uniqueId, System.AsyncCallback callback) {#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageSize(String uniqueId, System.AsyncCallback callback)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageSize(String uniqueId, System.AsyncCallback callback, Object state) {#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageSize(String uniqueId, System.AsyncCallback callback, Object state)
```


Begins GetMessageSize operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(IConnection connection, int sequenceNumber) {#beginGetMessageUniqueId-com.aspose.email.IConnection-int-}
```
public final System.IAsyncResult beginGetMessageUniqueId(IConnection connection, int sequenceNumber)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(int sequenceNumber) {#beginGetMessageUniqueId-int-}
```
public final System.IAsyncResult beginGetMessageUniqueId(int sequenceNumber)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback) {#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback, Object state) {#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback, Object state)
```


Begins to get the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages() {#beginListMessages--}
```
public final System.IAsyncResult beginListMessages()
```


Begins ListMessages operation asynchronously

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection) {#beginListMessages-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginListMessages(IConnection connection)
```


Begins ListMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, MailQuery query) {#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, MailQuery query)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search query. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback) {#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback, Object state) {#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback, Object state)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, System.AsyncCallback callback) {#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, System.AsyncCallback callback)
```


Begins ListMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, System.AsyncCallback callback, Object state) {#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins ListMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query, System.AsyncCallback callback, Object state) {#beginListMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginListMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query, System.AsyncCallback callback, Object state)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| fields | int | The fields that we want get |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(MailQuery query) {#beginListMessages-com.aspose.email.MailQuery-}
```
public final System.IAsyncResult beginListMessages(MailQuery query)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search query. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(MailQuery query, System.AsyncCallback callback) {#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginListMessages(MailQuery query, System.AsyncCallback callback)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(MailQuery query, System.AsyncCallback callback, Object state) {#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginListMessages(MailQuery query, System.AsyncCallback callback, Object state)
```


Begins ListMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(System.AsyncCallback callback) {#beginListMessages-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginListMessages(System.AsyncCallback callback)
```


Begins ListMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginListMessages(System.AsyncCallback callback, Object state) {#beginListMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginListMessages(System.AsyncCallback callback, Object state)
```


Begins ListMessages operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList) {#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--}
```
public final System.IAsyncResult beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback) {#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state) {#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList) {#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--}
```
public final System.IAsyncResult beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback) {#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state) {#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list to load |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList) {#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback) {#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state) {#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList) {#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback) {#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state) {#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)
```


Begins load list of Pop3MessageInfo asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop() {#beginNoop--}
```
public final System.IAsyncResult beginNoop()
```


Begins 'No operation' command.

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection) {#beginNoop-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginNoop(IConnection connection)
```


Begins 'No operation' command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection, System.AsyncCallback callback) {#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginNoop(IConnection connection, System.AsyncCallback callback)
```


Begins 'No operation' command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(IConnection connection, System.AsyncCallback callback, Object state) {#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginNoop(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins 'No operation' command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(System.AsyncCallback callback) {#beginNoop-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginNoop(System.AsyncCallback callback)
```


Begins 'No operation' command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginNoop(System.AsyncCallback callback, Object state) {#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginNoop(System.AsyncCallback callback, Object state)
```


Begins 'No operation' command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream) {#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback) {#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state) {#beginSaveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream) {#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback) {#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state) {#beginSaveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSaveMessage(IConnection connection, String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(int sequenceNumber, OutputStream outputStream) {#beginSaveMessage-int-java.io.OutputStream-}
```
public final System.IAsyncResult beginSaveMessage(int sequenceNumber, OutputStream outputStream)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback) {#beginSaveMessage-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state) {#beginSaveMessage-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSaveMessage(int sequenceNumber, OutputStream outputStream, System.AsyncCallback callback, Object state)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(String uniqueId, OutputStream outputStream) {#beginSaveMessage-java.lang.String-java.io.OutputStream-}
```
public final System.IAsyncResult beginSaveMessage(String uniqueId, OutputStream outputStream)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback) {#beginSaveMessage-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state) {#beginSaveMessage-java.lang.String-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginSaveMessage(String uniqueId, OutputStream outputStream, System.AsyncCallback callback, Object state)
```


Begins SaveMessage operation asynchronously

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages() {#beginUndeleteMessages--}
```
public final System.IAsyncResult beginUndeleteMessages()
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages(IConnection connection) {#beginUndeleteMessages-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginUndeleteMessages(IConnection connection)
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages(IConnection connection, System.AsyncCallback callback) {#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginUndeleteMessages(IConnection connection, System.AsyncCallback callback)
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages(IConnection connection, System.AsyncCallback callback, Object state) {#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginUndeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages(System.AsyncCallback callback) {#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginUndeleteMessages(System.AsyncCallback callback)
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginUndeleteMessages(System.AsyncCallback callback, Object state) {#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginUndeleteMessages(System.AsyncCallback callback, Object state)
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials() {#beginValidateCredentials--}
```
public final System.IAsyncResult beginValidateCredentials()
```


Begins to execute credentials validation

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection) {#beginValidateCredentials-com.aspose.email.IConnection-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection, System.AsyncCallback callback) {#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection, System.AsyncCallback callback)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state) {#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(System.AsyncCallback callback) {#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-}
```
public final System.IAsyncResult beginValidateCredentials(System.AsyncCallback callback)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### beginValidateCredentials(System.AsyncCallback callback, Object state) {#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginValidateCredentials(System.AsyncCallback callback, Object state)
```


Begins to execute credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback | References a method to be called when a corresponding asynchronous operation completes. |
| state | java.lang.Object | The state. |

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.
### bindIPEndPoint(BindIPEndPointHandler handler) {#bindIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void bindIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a local endpoint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | [BindIPEndPointHandler](../../com.aspose.email/bindipendpointhandler) |  |

### cancelAsyncOperation(System.IAsyncResult asyncResult) {#cancelAsyncOperation-com.aspose.ms.System.IAsyncResult-}
```
public final void cancelAsyncOperation(System.IAsyncResult asyncResult)
```


Cancels asynchronous operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | Defines asynchronous operation to cancel. |

### close() {#close--}
```
public void close()
```




### commitDeletes() {#commitDeletes--}
```
public final void commitDeletes()
```


Commit the deletions

### commitDeletes(IConnection connection) {#commitDeletes-com.aspose.email.IConnection-}
```
public final void commitDeletes(IConnection connection)
```


Commit the deletions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### commitDeletes(int sleep) {#commitDeletes-int-}
```
public final void commitDeletes(int sleep)
```


Commit the deletions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sleep | int | Timeout in milliseconds |

### connectIPEndPoint(BindIPEndPointHandler handler) {#connectIPEndPoint-com.aspose.email.BindIPEndPointHandler-}
```
public void connectIPEndPoint(BindIPEndPointHandler handler)
```


Associates a Socket with a remote endpoint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| handler | [BindIPEndPointHandler](../../com.aspose.email/bindipendpointhandler) |  |

### createConnection() {#createConnection--}
```
public IConnection createConnection()
```


Creates new independent connection for operations not linked to threads (not default connection). Invocation of this method is similar to invocation of CreateConnection(createAsDefaultConnection = false) Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Returns:**
[IConnection](../../com.aspose.email/iconnection) - Returns connection object
### createConnection(boolean createAsDefaultConnection) {#createConnection-boolean-}
```
public IConnection createConnection(boolean createAsDefaultConnection)
```


Creates new (default or independent) connection for operations. Please see more in documentation for EmailClient.ConnectionAsgmtMode property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createAsDefaultConnection | boolean | Indicates if connection has to be created as default for current thread |

**Returns:**
[IConnection](../../com.aspose.email/iconnection) - Returns connection object
### deleteMessage(IConnection connection, int sequenceNumber) {#deleteMessage-com.aspose.email.IConnection-int-}
```
public final void deleteMessage(IConnection connection, int sequenceNumber)
```


Deletes the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

### deleteMessage(IConnection connection, String uniqueId) {#deleteMessage-com.aspose.email.IConnection-java.lang.String-}
```
public final void deleteMessage(IConnection connection, String uniqueId)
```


Deletes the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

### deleteMessage(int sequenceNumber) {#deleteMessage-int-}
```
public final void deleteMessage(int sequenceNumber)
```


Deletes the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

### deleteMessage(String uniqueId) {#deleteMessage-java.lang.String-}
```
public final void deleteMessage(String uniqueId)
```


Deletes the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

### deleteMessages() {#deleteMessages--}
```
public final void deleteMessages()
```


Deletes all messages

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state.

### deleteMessages(IConnection connection) {#deleteMessages-com.aspose.email.IConnection-}
```
public final void deleteMessages(IConnection connection)
```


Deletes all messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state. |

### dispose() {#dispose--}
```
public void dispose()
```


Finalizes all operations with a server.

### endCommitDeletes(System.IAsyncResult asyncResult) {#endCommitDeletes-com.aspose.ms.System.IAsyncResult-}
```
public final void endCommitDeletes(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endDeleteMessage(System.IAsyncResult asyncResult) {#endDeleteMessage-com.aspose.ms.System.IAsyncResult-}
```
public final void endDeleteMessage(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endDeleteMessages(System.IAsyncResult asyncResult) {#endDeleteMessages-com.aspose.ms.System.IAsyncResult-}
```
public final void endDeleteMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endFetchMessage(System.IAsyncResult asyncResult) {#endFetchMessage-com.aspose.ms.System.IAsyncResult-}
```
public final MailMessage endFetchMessage(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message
### endFetchMessages(System.IAsyncResult asyncResult) {#endFetchMessages-com.aspose.ms.System.IAsyncResult-}
```
public final Iterable<MailMessage> endFetchMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
java.lang.Iterable<com.aspose.email.MailMessage> - List of [MailMessage](../../com.aspose.email/mailmessage) objects
### endGetMailboxInfo(System.IAsyncResult asyncResult) {#endGetMailboxInfo-com.aspose.ms.System.IAsyncResult-}
```
public final Pop3MailboxInfo endGetMailboxInfo(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
### endGetMailboxSize(System.IAsyncResult asyncResult) {#endGetMailboxSize-com.aspose.ms.System.IAsyncResult-}
```
public final long endGetMailboxSize(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
long - size of the mailbox in bytes
### endGetMessageCount(System.IAsyncResult asyncResult) {#endGetMessageCount-com.aspose.ms.System.IAsyncResult-}
```
public final int endGetMessageCount(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
int - message count
### endGetMessageHeaders(System.IAsyncResult asyncResult) {#endGetMessageHeaders-com.aspose.ms.System.IAsyncResult-}
```
public final HeaderCollection endGetMessageHeaders(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### endGetMessageInfo(System.IAsyncResult asyncResult) {#endGetMessageInfo-com.aspose.ms.System.IAsyncResult-}
```
public final Pop3MessageInfo endGetMessageInfo(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo)
### endGetMessageSize(System.IAsyncResult asyncResult) {#endGetMessageSize-com.aspose.ms.System.IAsyncResult-}
```
public final long endGetMessageSize(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
long - size of the message in bytes
### endGetMessageUniqueId(System.IAsyncResult asyncResult) {#endGetMessageUniqueId-com.aspose.ms.System.IAsyncResult-}
```
public final String endGetMessageUniqueId(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.String - String that represents uid of the message
### endListMessages(System.IAsyncResult asyncResult) {#endListMessages-com.aspose.ms.System.IAsyncResult-}
```
public final Pop3MessageInfoCollection endListMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Returns collection of Pop3MessageInfo
### endLoadMessageInfoList(System.IAsyncResult asyncResult) {#endLoadMessageInfoList-com.aspose.ms.System.IAsyncResult-}
```
public final Pop3MessageInfoCollection endLoadMessageInfoList(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### endNoop(System.IAsyncResult asyncResult) {#endNoop-com.aspose.ms.System.IAsyncResult-}
```
public final void endNoop(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endSaveMessage(System.IAsyncResult asyncResult) {#endSaveMessage-com.aspose.ms.System.IAsyncResult-}
```
public final void endSaveMessage(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endUndeleteMessages(System.IAsyncResult asyncResult) {#endUndeleteMessages-com.aspose.ms.System.IAsyncResult-}
```
public final void endUndeleteMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### endValidateCredentials(System.IAsyncResult asyncResult) {#endValidateCredentials-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endValidateCredentials(System.IAsyncResult asyncResult)
```


Waits for the pending asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

**Returns:**
boolean - True if authentication was successful, otherwise false.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fetchMessage(IConnection connection, int sequenceNumber) {#fetchMessage-com.aspose.email.IConnection-int-}
```
public final MailMessage fetchMessage(IConnection connection, int sequenceNumber)
```


Fetches the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message
### fetchMessage(IConnection connection, String uniqueId) {#fetchMessage-com.aspose.email.IConnection-java.lang.String-}
```
public final MailMessage fetchMessage(IConnection connection, String uniqueId)
```


Fetches the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message
### fetchMessage(int sequenceNumber) {#fetchMessage-int-}
```
public final MailMessage fetchMessage(int sequenceNumber)
```


Fetches the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message
### fetchMessage(String uniqueId) {#fetchMessage-java.lang.String-}
```
public final MailMessage fetchMessage(String uniqueId)
```


Fetches the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message
### fetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers) {#fetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--}
```
public final Iterable<MailMessage> fetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)
```


Fetches the messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> | The sequence numbers of the messages |

**Returns:**
java.lang.Iterable<com.aspose.email.MailMessage> - List of [MailMessage](../../com.aspose.email/mailmessage) objects
### fetchMessagesBySequences(Iterable<Integer> sequenceNumbers) {#fetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--}
```
public final Iterable<MailMessage> fetchMessagesBySequences(Iterable<Integer> sequenceNumbers)
```


Fetches the messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumbers | java.lang.Iterable<java.lang.Integer> | The sequence numbers of the messages |

**Returns:**
java.lang.Iterable<com.aspose.email.MailMessage> - List of [MailMessage](../../com.aspose.email/mailmessage) objects
### fetchMessagesByUids(IConnection connection, Iterable<String> uids) {#fetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--}
```
public final Iterable<MailMessage> fetchMessagesByUids(IConnection connection, Iterable<String> uids)
```


Fetches the messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |

**Returns:**
java.lang.Iterable<com.aspose.email.MailMessage> - List of [MailMessage](../../com.aspose.email/mailmessage) objects
### fetchMessagesByUids(Iterable<String> uids) {#fetchMessagesByUids-java.lang.Iterable-java.lang.String--}
```
public final Iterable<MailMessage> fetchMessagesByUids(Iterable<String> uids)
```


Fetches the messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uids | java.lang.Iterable<java.lang.String> | The sequence numbers of the messages |

**Returns:**
java.lang.Iterable<com.aspose.email.MailMessage> - List of [MailMessage](../../com.aspose.email/mailmessage) objects
### getAccessToken() {#getAccessToken--}
```
public String getAccessToken()
```


Gets or sets the access token.

Value: The string that represents access token.

**Returns:**
java.lang.String
### getAllowedAuthentication() {#getAllowedAuthentication--}
```
public final long getAllowedAuthentication()
```


Gets or sets enumeration of allowed by user authentication types

**Returns:**
long
### getCapabilities() {#getCapabilities--}
```
public String[] getCapabilities()
```


Get Capabilities.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientCertificates() {#getClientCertificates--}
```
public System.Security.Cryptography.X509Certificates.X509CertificateCollection getClientCertificates()
```


Contains collection of clients certificates

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509CertificateCollection
### getConnectionAsgmtMode() {#getConnectionAsgmtMode--}
```
public int getConnectionAsgmtMode()
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Returns:**
int
### getConnectionCheckupPeriod() {#getConnectionCheckupPeriod--}
```
public int getConnectionCheckupPeriod()
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Returns:**
int
### getConnectionState() {#getConnectionState--}
```
public final int getConnectionState()
```


Gets the current state of the connection.

**Returns:**
int
### getConnectionsQuantity() {#getConnectionsQuantity--}
```
public int getConnectionsQuantity()
```


Gets or sets quantity of connections in multy-connection mode

**Returns:**
int
### getCurrentConnection() {#getCurrentConnection--}
```
public IConnection getCurrentConnection()
```


Gets current connection according to ConnectionAsgmtMode option

**Returns:**
[IConnection](../../com.aspose.email/iconnection)
### getDefaultPort() {#getDefaultPort--}
```
public int getDefaultPort()
```


Gets default port for client

**Returns:**
int
### getEnableLogger() {#getEnableLogger--}
```
public final boolean getEnableLogger()
```


Gets or sets value which allows enable/disable logger

**Returns:**
boolean
### getGreetingTimeout() {#getGreetingTimeout--}
```
public final int getGreetingTimeout()
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use  EmailClient.Timeout (\#getTimeout.getTimeout/\#setTimeout(int).setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Returns:**
int
### getHost() {#getHost--}
```
public String getHost()
```


Gets or sets the host name.

Value: The host name.

**Returns:**
java.lang.String
### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getMailboxInfo() {#getMailboxInfo--}
```
public final Pop3MailboxInfo getMailboxInfo()
```


Gets the mailbox status info

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
### getMailboxInfo(boolean closeTransaction) {#getMailboxInfo-boolean-}
```
public final Pop3MailboxInfo getMailboxInfo(boolean closeTransaction)
```


Gets the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
### getMailboxInfo(IConnection connection) {#getMailboxInfo-com.aspose.email.IConnection-}
```
public final Pop3MailboxInfo getMailboxInfo(IConnection connection)
```


Gets the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
### getMailboxInfo(IConnection connection, boolean closeTransaction) {#getMailboxInfo-com.aspose.email.IConnection-boolean-}
```
public final Pop3MailboxInfo getMailboxInfo(IConnection connection, boolean closeTransaction)
```


Gets the mailbox status info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
### getMailboxSize() {#getMailboxSize--}
```
public final long getMailboxSize()
```


Gets the size of the mailbox

**Returns:**
long - size of the mailbox in bytes
### getMailboxSize(IConnection connection) {#getMailboxSize-com.aspose.email.IConnection-}
```
public final long getMailboxSize(IConnection connection)
```


Gets the size of the mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
long - size of the mailbox in bytes
### getMessageCount() {#getMessageCount--}
```
public final int getMessageCount()
```


Gets the message count

**Returns:**
int - message count
### getMessageCount(boolean closeTransaction) {#getMessageCount-boolean-}
```
public final int getMessageCount(boolean closeTransaction)
```


Gets the message count

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
int - message count
### getMessageCount(IConnection connection) {#getMessageCount-com.aspose.email.IConnection-}
```
public final int getMessageCount(IConnection connection)
```


Gets the message count

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
int - message count
### getMessageCount(IConnection connection, boolean closeTransaction) {#getMessageCount-com.aspose.email.IConnection-boolean-}
```
public final int getMessageCount(IConnection connection, boolean closeTransaction)
```


Gets the message count

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |

**Returns:**
int - message count
### getMessageHeaders(IConnection connection, int sequenceNumber) {#getMessageHeaders-com.aspose.email.IConnection-int-}
```
public final HeaderCollection getMessageHeaders(IConnection connection, int sequenceNumber)
```


Gets the message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection) - HeaderCollection that represents collection of the headers
### getMessageHeaders(IConnection connection, String uniqueId) {#getMessageHeaders-com.aspose.email.IConnection-java.lang.String-}
```
public final HeaderCollection getMessageHeaders(IConnection connection, String uniqueId)
```


Gets the message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection) - HeaderCollection that represents collection of the headers
### getMessageHeaders(int sequenceNumber) {#getMessageHeaders-int-}
```
public final HeaderCollection getMessageHeaders(int sequenceNumber)
```


Gets the message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection) - HeaderCollection that represents collection of the headers
### getMessageHeaders(String uniqueId) {#getMessageHeaders-java.lang.String-}
```
public final HeaderCollection getMessageHeaders(String uniqueId)
```


Gets the message headers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection) - HeaderCollection that represents collection of the headers
### getMessageInfo(IConnection connection, int sequenceNumber) {#getMessageInfo-com.aspose.email.IConnection-int-}
```
public final Pop3MessageInfo getMessageInfo(IConnection connection, int sequenceNumber)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(IConnection connection, int sequenceNumber, int fields) {#getMessageInfo-com.aspose.email.IConnection-int-int-}
```
public final Pop3MessageInfo getMessageInfo(IConnection connection, int sequenceNumber, int fields)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(IConnection connection, String uniqueId) {#getMessageInfo-com.aspose.email.IConnection-java.lang.String-}
```
public final Pop3MessageInfo getMessageInfo(IConnection connection, String uniqueId)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(IConnection connection, String uniqueId, int fields) {#getMessageInfo-com.aspose.email.IConnection-java.lang.String-int-}
```
public final Pop3MessageInfo getMessageInfo(IConnection connection, String uniqueId, int fields)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(int sequenceNumber) {#getMessageInfo-int-}
```
public final Pop3MessageInfo getMessageInfo(int sequenceNumber)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(int sequenceNumber, int fields) {#getMessageInfo-int-int-}
```
public final Pop3MessageInfo getMessageInfo(int sequenceNumber, int fields)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| fields | int | The fields that we want get |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(String uniqueId) {#getMessageInfo-java.lang.String-}
```
public final Pop3MessageInfo getMessageInfo(String uniqueId)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageInfo(String uniqueId, int fields) {#getMessageInfo-java.lang.String-int-}
```
public final Pop3MessageInfo getMessageInfo(String uniqueId, int fields)
```


Gets the information for that message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |
| fields | int | The fields that we want get |

**Returns:**
[Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) - Pop3MessageInfo
### getMessageSize(IConnection connection, int sequenceNumber) {#getMessageSize-com.aspose.email.IConnection-int-}
```
public final long getMessageSize(IConnection connection, int sequenceNumber)
```


Gets the size of the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
long - size of the message in bytes
### getMessageSize(IConnection connection, String uniqueId) {#getMessageSize-com.aspose.email.IConnection-java.lang.String-}
```
public final long getMessageSize(IConnection connection, String uniqueId)
```


Gets the size of the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
long - size of the message in bytes
### getMessageSize(int sequenceNumber) {#getMessageSize-int-}
```
public final long getMessageSize(int sequenceNumber)
```


Gets the size of the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
long - size of the message in bytes
### getMessageSize(String uniqueId) {#getMessageSize-java.lang.String-}
```
public final long getMessageSize(String uniqueId)
```


Gets the size of the message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique id of the message |

**Returns:**
long - size of the message in bytes
### getMessageUniqueId(IConnection connection, int sequenceNumber) {#getMessageUniqueId-com.aspose.email.IConnection-int-}
```
public final String getMessageUniqueId(IConnection connection, int sequenceNumber)
```


Gets the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
java.lang.String - String that represents uid of the message
### getMessageUniqueId(int sequenceNumber) {#getMessageUniqueId-int-}
```
public final String getMessageUniqueId(int sequenceNumber)
```


Gets the message unique id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |

**Returns:**
java.lang.String - String that represents uid of the message
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets or sets the password. Password limitations are defined by server implementation, which client connects.

Value: The string that represents the password.

**Returns:**
java.lang.String
### getPort() {#getPort--}
```
public int getPort()
```


Gets or sets the port.

Value: The port number.

**Returns:**
int
### getProxy() {#getProxy--}
```
public Proxy getProxy()
```


Gets or sets proxy for the client

**Returns:**
[Proxy](../../com.aspose.email/proxy)
### getSecurityOptions() {#getSecurityOptions--}
```
public int getSecurityOptions()
```


Security mode for a mail client

**Returns:**
int
### getSupportedAuthentication() {#getSupportedAuthentication--}
```
public final long getSupportedAuthentication()
```


Gets enumeration of supported by server authentication types

**Returns:**
long
### getSupportedEncryption() {#getSupportedEncryption--}
```
public int getSupportedEncryption()
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int).setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Returns:**
int
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets or sets the timeout for mail operations

Value: The timeout in milliseconds

**Returns:**
int
### getTokenProvider() {#getTokenProvider--}
```
public final ITokenProvider getTokenProvider()
```


Gets or sets TokenProvider allowing to retrieve access token.

**Returns:**
[ITokenProvider](../../com.aspose.email/itokenprovider)
### getUseAuthentication() {#getUseAuthentication--}
```
public boolean getUseAuthentication()
```


Indicates whether authentication is used.

**Returns:**
boolean
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### getUseDefaultCredentials() {#getUseDefaultCredentials--}
```
public boolean getUseDefaultCredentials()
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY!

**Returns:**
boolean
### getUseMultiConnection() {#getUseMultiConnection--}
```
public int getUseMultiConnection()
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Returns:**
int
### getUsePipelining() {#getUsePipelining--}
```
public PipeliningStatus getUsePipelining()
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Returns:**
[PipeliningStatus](../../com.aspose.email/pipeliningstatus)
### getUsername() {#getUsername--}
```
public String getUsername()
```


Gets or sets the username.

Value: The username string.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### listMessages() {#listMessages--}
```
public final Pop3MessageInfoCollection listMessages()
```


Lists the messages. Gets an information for earch message

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection

--------------------

Note that messages marked as deleted are not listed
### listMessages(boolean closeTransaction) {#listMessages-boolean-}
```
public final Pop3MessageInfoCollection listMessages(boolean closeTransaction)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(IConnection connection) {#listMessages-com.aspose.email.IConnection-}
```
public final Pop3MessageInfoCollection listMessages(IConnection connection)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(IConnection connection, boolean closeTransaction) {#listMessages-com.aspose.email.IConnection-boolean-}
```
public final Pop3MessageInfoCollection listMessages(IConnection connection, boolean closeTransaction)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(IConnection connection, MailQuery query) {#listMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-}
```
public final Pop3MessageInfoCollection listMessages(IConnection connection, MailQuery query)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Collection of Pop3MessageInfo objects.
### listMessages(IConnection connection, int fields) {#listMessages-com.aspose.email.IConnection-int-}
```
public final Pop3MessageInfoCollection listMessages(IConnection connection, int fields)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| fields | int | The fields that we want get

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query) {#listMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-}
```
public final Pop3MessageInfoCollection listMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| fields | int | The fields that we want get |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(MailQuery query) {#listMessages-com.aspose.email.MailQuery-}
```
public final Pop3MessageInfoCollection listMessages(MailQuery query)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Collection of Pop3MessageInfo objects.
### listMessages(int fields) {#listMessages-int-}
```
public final Pop3MessageInfoCollection listMessages(int fields)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fields | int | The fields that we want get

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessages(int fields, boolean closeTransaction, MailQuery query) {#listMessages-int-boolean-com.aspose.email.MailQuery-}
```
public final Pop3MessageInfoCollection listMessages(int fields, boolean closeTransaction, MailQuery query)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fields | int | The fields that we want get |
| closeTransaction | boolean | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) object. |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumberLst) {#listMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--}
```
public final Pop3MessageInfoCollection listMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumberLst)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumberLst | java.lang.Iterable<java.lang.Integer> | sequenceNumber list for [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) to retrieve from a server.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessagesBySequences(Iterable<Integer> sequenceNumberLst) {#listMessagesBySequences-java.lang.Iterable-java.lang.Integer--}
```
public final Pop3MessageInfoCollection listMessagesBySequences(Iterable<Integer> sequenceNumberLst)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberLst | java.lang.Iterable<java.lang.Integer> | sequenceNumber list for [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) to retrieve from a server.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessagesByUids(IConnection connection, Iterable<String> uniqueIdLst) {#listMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--}
```
public final Pop3MessageInfoCollection listMessagesByUids(IConnection connection, Iterable<String> uniqueIdLst)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueIdLst | java.lang.Iterable<java.lang.String> | UniqueId list for [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) to retrieve from a server.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### listMessagesByUids(Iterable<String> uniqueIdLst) {#listMessagesByUids-java.lang.Iterable-java.lang.String--}
```
public final Pop3MessageInfoCollection listMessagesByUids(Iterable<String> uniqueIdLst)
```


Lists the messages. Gets an information for earch message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueIdLst | java.lang.Iterable<java.lang.String> | UniqueId list for [Pop3MessageInfo](../../com.aspose.email/pop3messageinfo) to retrieve from a server.

--------------------

Note that messages marked as deleted are not listed |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### loadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList) {#loadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--}
```
public final Pop3MessageInfoCollection loadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)
```


Loads list of Pop3MessageInfo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### loadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList) {#loadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--}
```
public final Pop3MessageInfoCollection loadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)
```


Loads list of Pop3MessageInfo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoList | java.lang.Iterable<com.aspose.email.Pop3MessageInfo> | Message info list |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### loadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList) {#loadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--}
```
public final Pop3MessageInfoCollection loadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)
```


Loads list of Pop3MessageInfo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### loadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList) {#loadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--}
```
public final Pop3MessageInfoCollection loadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)
```


Loads list of Pop3MessageInfo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumberList | java.lang.Iterable<java.lang.Integer> | The sequence numbers list of messages |

**Returns:**
[Pop3MessageInfoCollection](../../com.aspose.email/pop3messageinfocollection) - Pop3MessageInfoCollection
### noop() {#noop--}
```
public void noop()
```


'No operation' command

### noop(IConnection connection) {#noop-com.aspose.email.IConnection-}
```
public void noop(IConnection connection)
```


'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetLogSettings() {#resetLogSettings--}
```
public final void resetLogSettings()
```


Resets logging settings to default.

### saveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream) {#saveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-}
```
public final void saveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream)
```


Fetches and save the message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

### saveMessage(IConnection connection, int sequenceNumber, String fileName) {#saveMessage-com.aspose.email.IConnection-int-java.lang.String-}
```
public final void saveMessage(IConnection connection, int sequenceNumber, String fileName)
```


Fetches and save the message into a file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| sequenceNumber | int | The sequence number of the message |
| fileName | java.lang.String | File name for message |

### saveMessage(IConnection connection, String uniqueId, OutputStream outputStream) {#saveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-}
```
public final void saveMessage(IConnection connection, String uniqueId, OutputStream outputStream)
```


Fetches and save the message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

### saveMessage(IConnection connection, String uniqueId, String fileName) {#saveMessage-com.aspose.email.IConnection-java.lang.String-java.lang.String-}
```
public final void saveMessage(IConnection connection, String uniqueId, String fileName)
```


Fetches and save the message into a file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |
| uniqueId | java.lang.String | The unique Id of the message |
| fileName | java.lang.String | File name for message |

### saveMessage(int sequenceNumber, OutputStream outputStream) {#saveMessage-int-java.io.OutputStream-}
```
public final void saveMessage(int sequenceNumber, OutputStream outputStream)
```


Fetches and save the message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

### saveMessage(int sequenceNumber, String fileName) {#saveMessage-int-java.lang.String-}
```
public final void saveMessage(int sequenceNumber, String fileName)
```


Fetches and save the message into a file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | int | The sequence number of the message |
| fileName | java.lang.String | File name for message |

### saveMessage(String uniqueId, OutputStream outputStream) {#saveMessage-java.lang.String-java.io.OutputStream-}
```
public final void saveMessage(String uniqueId, OutputStream outputStream)
```


Fetches and save the message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique Id of the message |
| outputStream | java.io.OutputStream | Stream where message will be saved |

### saveMessage(String uniqueId, String fileName) {#saveMessage-java.lang.String-java.lang.String-}
```
public final void saveMessage(String uniqueId, String fileName)
```


Fetches and save the message into a file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | The unique Id of the message |
| fileName | java.lang.String | File name for message |

### setAccessToken(String value) {#setAccessToken-java.lang.String-}
```
public void setAccessToken(String value)
```


Gets or sets the access token.

Value: The string that represents access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAllowedAuthentication(long value) {#setAllowedAuthentication-long-}
```
public final void setAllowedAuthentication(long value)
```


Gets or sets enumeration of allowed by user authentication types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setConnectionAsgmtMode(int value) {#setConnectionAsgmtMode-int-}
```
public void setConnectionAsgmtMode(int value)
```


Gets or sets value which defines mode of connection allocation in multiple threads environment There are folowing connection types: - Main connection is connection created and disposed together with mail client.It can't be created or disposed manually. - Default connection is connection default for some thread. If default connection exists and ConnectionAsgmtMode allow, all methods of email client executed in this thread will be implicitly use this connection. Only one default connection can be exist per thread. It can be created manually or automatically. It depends on EmailClient.ConnectionAsgmtMode property. These connections can be created manually with EmailClient.CreateConnection(createAsDefaultConnection = true) method. If default connection does not used(depends on connection allocation mode), main connection used implicitly instead of it. - Independent connections are connections that are not linked to threads.They can be created manually and has to be used explicitly as method parameter. These connections can be created manually with EmailClient.CreateConnection() method or EmailClient.CreateConnection(createAsDefaultConnection = false) method. There are folowing connection allocation types: - ConnectionAsgmtType.UseMainOrDefault This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread. - ConnectionAsgmtType.UseMain Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. - ConnectionAsgmtType.UseDefault Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConnectionCheckupPeriod(int value) {#setConnectionCheckupPeriod-int-}
```
public void setConnectionCheckupPeriod(int value)
```


Period of connection checking up in milliseconds. Default value is 5 min.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConnectionsQuantity(int value) {#setConnectionsQuantity-int-}
```
public void setConnectionsQuantity(int value)
```


Gets or sets quantity of connections in multy-connection mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnableLogger(boolean value) {#setEnableLogger-boolean-}
```
public final void setEnableLogger(boolean value)
```


Gets or sets value which allows enable/disable logger

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGreetingTimeout(int value) {#setGreetingTimeout-int-}
```
public final void setGreetingTimeout(int value)
```


Gets or sets the greeting timeout that is used when establishing a connection. Please note, greeting timeout can't be infinite. Email clients may execute enough long operations. To limit the time of operations users have to use  EmailClient.Timeout (\#getTimeout.getTimeout/\#setTimeout(int).setTimeout(int)) property. Values for this property have to have long intervals to not prevent long-time operations. But in some cases, if EmailClient will use only Timeout property connection establishing may take a long time. For instance, the mail client may use the automatic mode to connection establishing. In this mode, the email client goes through all possible connection parameters until the connection is established. SMTP, IMAP, and POP3 servers in case of correct connection establishing send greeting string to the client. Servers may use implicit or explicit (START TLS) SSL/TLS connection initiation. If connection mode is mismatched (for instance, the server waits for an implicit SSL connection but the client tries to establish a non-secured or explicit SSL connection), the server won't send a greeting string. In this case, the user will wait a long time until the timeout reaches a greeting string, and the client goes to the next connection option. To avoid this problem, the GreetingTimeout property has been introduced. This property allows you to set the timeout for greeting string, and reduce the time of automatic connection establishment.

Value: The greeting timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHost(String value) {#setHost-java.lang.String-}
```
public void setHost(String value)
```


Gets or sets the host name.

Value: The host name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Gets or sets the password. Password limitations are defined by server implementation, which client connects.

Value: The string that represents the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPort(int value) {#setPort-int-}
```
public void setPort(int value)
```


Gets or sets the port.

Value: The port number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setProxy(Proxy value) {#setProxy-com.aspose.email.Proxy-}
```
public void setProxy(Proxy value)
```


Gets or sets proxy for the client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Proxy](../../com.aspose.email/proxy) |  |

### setSecurityOptions(int value) {#setSecurityOptions-int-}
```
public void setSecurityOptions(int value)
```


Security mode for a mail client

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSocketsLayerVersion2(boolean value) {#setSocketsLayerVersion2-boolean-}
```
public static void setSocketsLayerVersion2(boolean value)
```


Sets value indicating whether Sockets Layer version 2 is used. By default, Sockets Layer version 2 is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | False if Sockets Layer version 1 should be used. |

### setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value) {#setSocketsLayerVersion2DisableSSLCertificateValidation-boolean-}
```
public static void setSocketsLayerVersion2DisableSSLCertificateValidation(boolean value)
```


Disable SSL certificate validation for Sockets Layer version 2

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value) {#setSocketsLayerVersion2SSLSocketFactory-javax.net.ssl.SSLSocketFactory-}
```
public static void setSocketsLayerVersion2SSLSocketFactory(SSLSocketFactory value)
```


Set SSL Socket Factory for Sockets Layer version 2

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.net.ssl.SSLSocketFactory |  |

### setSupportedEncryption(int value) {#setSupportedEncryption-int-}
```
public void setSupportedEncryption(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. PLEASE PAY YOUR ATTENTION, you may set only those versions of protocol, which are supported by .net framework. IF SOME VERSIONS OF PROTOCOL ARE NOT SUPPORTED BY YOUR CURRENT VERSION OF FRAMEWORK, THEY WILL BE IGNORED AND SKIPPED. IT MAY LEAD TO DOWNGRADE TLS SECURITY LEVEL. IN THIS CASE EXCEPTION WON'T BE GENERATED!!! Please, see [EncryptionProtocols](../../com.aspose.email/encryptionprotocols) documentation for more details. Please use \#setSupportedEncryptionUnsafe(int).setSupportedEncryptionUnsafe(int) method if you want to set the encryption protocols without any compatibility checks. Default value is: Tls | Tls11 | Tls12 | Tls13 (in case if your current version of .net framework supports these versions of TLS)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSupportedEncryptionUnsafe(int value) {#setSupportedEncryptionUnsafe-int-}
```
public final void setSupportedEncryptionUnsafe(int value)
```


Defines the versions of SSL/TLS encryption protocols to be used. This method is not safe and sets the encryption protocols without any compatibility checks. Use  SupportedEncryption (\#getSupportedEncryption.getSupportedEncryption/\#setSupportedEncryption(int).setSupportedEncryption(int)) property to safely set only protocols that definitely supported by framework. Please note, if your current framework does not support this level of security, an exception will be thrown when trying to establish a connection to the server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Gets or sets the timeout for mail operations

Value: The timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTokenProvider(ITokenProvider value) {#setTokenProvider-com.aspose.email.ITokenProvider-}
```
public final void setTokenProvider(ITokenProvider value)
```


Gets or sets TokenProvider allowing to retrieve access token.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITokenProvider](../../com.aspose.email/itokenprovider) |  |

### setUseAuthentication(boolean value) {#setUseAuthentication-boolean-}
```
public void setUseAuthentication(boolean value)
```


Indicates whether authentication is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDefaultCredentials(boolean value) {#setUseDefaultCredentials-boolean-}
```
public void setUseDefaultCredentials(boolean value)
```


Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. This option is used with NTLM authentication ONLY!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseMultiConnection(int value) {#setUseMultiConnection-int-}
```
public void setUseMultiConnection(int value)
```


Gets or sets value which indicates if client has to use multiple connections for heavy loaded operations. Please note, using of this mode not necessary has to lead to performance increasing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUsePipelining(PipeliningStatus value) {#setUsePipelining-com.aspose.email.PipeliningStatus-}
```
public void setUsePipelining(PipeliningStatus value)
```


Gets or sets object which indicates whether the pipelining mode is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PipeliningStatus](../../com.aspose.email/pipeliningstatus) |  |

### setUsername(String value) {#setUsername-java.lang.String-}
```
public void setUsername(String value)
```


Gets or sets the username.

Value: The username string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### undeleteMessages() {#undeleteMessages--}
```
public final void undeleteMessages()
```


Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

### undeleteMessages(IConnection connection) {#undeleteMessages-com.aspose.email.IConnection-}
```
public final void undeleteMessages(IConnection connection)
```


Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### validateCredentials() {#validateCredentials--}
```
public boolean validateCredentials()
```


Executes credentials validation

**Returns:**
boolean - True if authentication was successful, otherwise false.
### validateCredentials(IConnection connection) {#validateCredentials-com.aspose.email.IConnection-}
```
public final boolean validateCredentials(IConnection connection)
```


Executes credentials validation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

**Returns:**
boolean - True if authentication was successful, otherwise false.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

