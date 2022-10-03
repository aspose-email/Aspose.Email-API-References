---
title: Pop3Client
second_title: Aspose.Email for Java API Reference
description: Allows applications to access and manipulate  messages by using the Post Office Protocol Version 3 POP3.
type: docs
weight: 564
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
| [beginCommitDeletes(IConnection connection)](#beginCommitDeletes-com.aspose.email.IConnection-) | Begins to commit the deletions. |
| [beginCommitDeletes(IConnection connection, System.AsyncCallback callback)](#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to commit the deletions. |
| [beginCommitDeletes(IConnection connection, System.AsyncCallback callback, Object state)](#beginCommitDeletes-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to commit the deletions. |
| [beginCommitDeletes()](#beginCommitDeletes--) | Begins to commit the deletions. |
| [beginCommitDeletes(System.AsyncCallback callback)](#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-) | Begins to commit the deletions. |
| [beginCommitDeletes(System.AsyncCallback callback, Object state)](#beginCommitDeletes-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to commit the deletions. |
| [endCommitDeletes(System.IAsyncResult asyncResult)](#endCommitDeletes-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [commitDeletes(int sleep)](#commitDeletes-int-) | Commit the deletions |
| [commitDeletes(IConnection connection)](#commitDeletes-com.aspose.email.IConnection-) | Commit the deletions |
| [commitDeletes()](#commitDeletes--) | Commit the deletions |
| [getDefaultPort()](#getDefaultPort--) | Gets default port for client |
| [getAllowedAuthentication()](#getAllowedAuthentication--) | Gets or sets enumeration of allowed by user authentication types |
| [setAllowedAuthentication(long value)](#setAllowedAuthentication-long-) | Gets or sets enumeration of allowed by user authentication types |
| [getSupportedAuthentication()](#getSupportedAuthentication--) | Gets enumeration of supported by server authentication types |
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
| [endDeleteMessage(System.IAsyncResult asyncResult)](#endDeleteMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [deleteMessage(IConnection connection, int sequenceNumber)](#deleteMessage-com.aspose.email.IConnection-int-) | Deletes the message |
| [deleteMessage(IConnection connection, String uniqueId)](#deleteMessage-com.aspose.email.IConnection-java.lang.String-) | Deletes the message |
| [deleteMessage(int sequenceNumber)](#deleteMessage-int-) | Deletes the message |
| [deleteMessage(String uniqueId)](#deleteMessage-java.lang.String-) | Deletes the message |
| [beginDeleteMessages(IConnection connection)](#beginDeleteMessages-com.aspose.email.IConnection-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(IConnection connection, System.AsyncCallback callback)](#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginDeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins delete all messages asynchronously |
| [beginDeleteMessages()](#beginDeleteMessages--) | Begins delete all messages asynchronously |
| [beginDeleteMessages(System.AsyncCallback callback)](#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-) | Begins delete all messages asynchronously |
| [beginDeleteMessages(System.AsyncCallback callback, Object state)](#beginDeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins delete all messages asynchronously |
| [endDeleteMessages(System.IAsyncResult asyncResult)](#endDeleteMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [deleteMessages(IConnection connection)](#deleteMessages-com.aspose.email.IConnection-) | Deletes all messages |
| [deleteMessages()](#deleteMessages--) | Deletes all messages |
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
| [endFetchMessage(System.IAsyncResult asyncResult)](#endFetchMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [fetchMessage(IConnection connection, String uniqueId)](#fetchMessage-com.aspose.email.IConnection-java.lang.String-) | Fetches the message |
| [fetchMessage(IConnection connection, int sequenceNumber)](#fetchMessage-com.aspose.email.IConnection-int-) | Fetches the message |
| [fetchMessage(String uniqueId)](#fetchMessage-java.lang.String-) | Fetches the message |
| [fetchMessage(int sequenceNumber)](#fetchMessage-int-) | Fetches the message |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)](#beginFetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers, System.AsyncCallback callback, Object state)](#beginFetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(Iterable<String> uids, System.AsyncCallback callback, Object state)](#beginFetchMessagesByUids-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-) | Begins FetchMessages operation asynchronously |
| [beginFetchMessagesByUids(IConnection connection, Iterable<String> uids, System.AsyncCallback callback, Object state)](#beginFetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins FetchMessages operation asynchronously |
| [endFetchMessages(System.IAsyncResult asyncResult)](#endFetchMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [fetchMessagesBySequences(Iterable<Integer> sequenceNumbers)](#fetchMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Fetches the messages |
| [fetchMessagesByUids(Iterable<String> uids)](#fetchMessagesByUids-java.lang.Iterable-java.lang.String--) | Fetches the messages |
| [fetchMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumbers)](#fetchMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Fetches the messages |
| [fetchMessagesByUids(IConnection connection, Iterable<String> uids)](#fetchMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Fetches the messages |
| [beginGetMailboxInfo(IConnection connection)](#beginGetMailboxInfo-com.aspose.email.IConnection-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback)](#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo()](#beginGetMailboxInfo--) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(System.AsyncCallback callback)](#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-) | Begins to get the mailbox status info |
| [beginGetMailboxInfo(System.AsyncCallback callback, Object state)](#beginGetMailboxInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the mailbox status info |
| [endGetMailboxInfo(System.IAsyncResult asyncResult)](#endGetMailboxInfo-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMailboxInfo(IConnection connection)](#getMailboxInfo-com.aspose.email.IConnection-) | Gets the mailbox status info |
| [getMailboxInfo(IConnection connection, boolean closeTransaction)](#getMailboxInfo-com.aspose.email.IConnection-boolean-) | Gets the mailbox status info |
| [getMailboxInfo(boolean closeTransaction)](#getMailboxInfo-boolean-) | Gets the mailbox status info |
| [getMailboxInfo()](#getMailboxInfo--) | Gets the mailbox status info |
| [beginGetMailboxSize(IConnection connection)](#beginGetMailboxSize-com.aspose.email.IConnection-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(IConnection connection, System.AsyncCallback callback)](#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMailboxSize-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize()](#beginGetMailboxSize--) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(System.AsyncCallback callback)](#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-) | Begins GetMailboxSize operation asynchronously |
| [beginGetMailboxSize(System.AsyncCallback callback, Object state)](#beginGetMailboxSize-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMailboxSize operation asynchronously |
| [endGetMailboxSize(System.IAsyncResult asyncResult)](#endGetMailboxSize-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMailboxSize(IConnection connection)](#getMailboxSize-com.aspose.email.IConnection-) | Gets the size of the mailbox |
| [getMailboxSize()](#getMailboxSize--) | Gets the size of the mailbox |
| [beginGetMessageCount(IConnection connection)](#beginGetMessageCount-com.aspose.email.IConnection-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(IConnection connection, boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.email.IConnection-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount()](#beginGetMessageCount--) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(System.AsyncCallback callback)](#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(System.AsyncCallback callback, Object state)](#beginGetMessageCount-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction)](#beginGetMessageCount-boolean-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback)](#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageCount operation asynchronously |
| [beginGetMessageCount(boolean closeTransaction, System.AsyncCallback callback, Object state)](#beginGetMessageCount-boolean-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageCount operation asynchronously |
| [endGetMessageCount(System.IAsyncResult asyncResult)](#endGetMessageCount-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMessageCount(IConnection connection)](#getMessageCount-com.aspose.email.IConnection-) | Gets the message count |
| [getMessageCount(IConnection connection, boolean closeTransaction)](#getMessageCount-com.aspose.email.IConnection-boolean-) | Gets the message count |
| [getMessageCount()](#getMessageCount--) | Gets the message count |
| [getMessageCount(boolean closeTransaction)](#getMessageCount-boolean-) | Gets the message count |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber)](#beginGetMessageHeaders-int-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId)](#beginGetMessageHeaders-java.lang.String-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback)](#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins getting message headers |
| [beginGetMessageHeaders(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageHeaders-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins getting message headers |
| [endGetMessageHeaders(System.IAsyncResult asyncResult)](#endGetMessageHeaders-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMessageHeaders(IConnection connection, int sequenceNumber)](#getMessageHeaders-com.aspose.email.IConnection-int-) | Gets the message headers |
| [getMessageHeaders(int sequenceNumber)](#getMessageHeaders-int-) | Gets the message headers |
| [getMessageHeaders(IConnection connection, String uniqueId)](#getMessageHeaders-com.aspose.email.IConnection-java.lang.String-) | Gets the message headers |
| [getMessageHeaders(String uniqueId)](#getMessageHeaders-java.lang.String-) | Gets the message headers |
| [beginGetMessageSize(IConnection connection, int sequenceNumber)](#beginGetMessageSize-com.aspose.email.IConnection-int-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageSize-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber)](#beginGetMessageSize-int-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageSize-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageSize-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId)](#beginGetMessageSize-java.lang.String-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId, System.AsyncCallback callback)](#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins GetMessageSize operation asynchronously |
| [beginGetMessageSize(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageSize-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins GetMessageSize operation asynchronously |
| [endGetMessageSize(System.IAsyncResult asyncResult)](#endGetMessageSize-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMessageSize(IConnection connection, String uniqueId)](#getMessageSize-com.aspose.email.IConnection-java.lang.String-) | Gets the size of the message |
| [getMessageSize(String uniqueId)](#getMessageSize-java.lang.String-) | Gets the size of the message |
| [getMessageSize(IConnection connection, int sequenceNumber)](#getMessageSize-com.aspose.email.IConnection-int-) | Gets the size of the message |
| [getMessageSize(int sequenceNumber)](#getMessageSize-int-) | Gets the size of the message |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageUniqueId-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber)](#beginGetMessageUniqueId-int-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the message unique id |
| [beginGetMessageUniqueId(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageUniqueId-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the message unique id |
| [endGetMessageUniqueId(System.IAsyncResult asyncResult)](#endGetMessageUniqueId-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMessageUniqueId(IConnection connection, int sequenceNumber)](#getMessageUniqueId-com.aspose.email.IConnection-int-) | Gets the message unique id |
| [getMessageUniqueId(int sequenceNumber)](#getMessageUniqueId-int-) | Gets the message unique id |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber)](#beginGetMessageInfo-com.aspose.email.IConnection-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields)](#beginGetMessageInfo-int-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber)](#beginGetMessageInfo-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback)](#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(int sequenceNumber, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(IConnection connection, String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-com.aspose.email.IConnection-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields)](#beginGetMessageInfo-java.lang.String-int-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback)](#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, int fields, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-java.lang.String-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId)](#beginGetMessageInfo-java.lang.String-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, System.AsyncCallback callback)](#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-) | Begins to get the information for that message |
| [beginGetMessageInfo(String uniqueId, System.AsyncCallback callback, Object state)](#beginGetMessageInfo-java.lang.String-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to get the information for that message |
| [endGetMessageInfo(System.IAsyncResult asyncResult)](#endGetMessageInfo-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [getMessageInfo(IConnection connection, String uniqueId, int fields)](#getMessageInfo-com.aspose.email.IConnection-java.lang.String-int-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, String uniqueId)](#getMessageInfo-com.aspose.email.IConnection-java.lang.String-) | Gets the information for that message |
| [getMessageInfo(String uniqueId)](#getMessageInfo-java.lang.String-) | Gets the information for that message |
| [getMessageInfo(String uniqueId, int fields)](#getMessageInfo-java.lang.String-int-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, int sequenceNumber, int fields)](#getMessageInfo-com.aspose.email.IConnection-int-int-) | Gets the information for that message |
| [getMessageInfo(IConnection connection, int sequenceNumber)](#getMessageInfo-com.aspose.email.IConnection-int-) | Gets the information for that message |
| [getMessageInfo(int sequenceNumber)](#getMessageInfo-int-) | Gets the information for that message |
| [getMessageInfo(int sequenceNumber, int fields)](#getMessageInfo-int-int-) | Gets the information for that message |
| [beginListMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection)](#beginListMessages-com.aspose.email.IConnection-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessages operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-) | Begins ListMessage operation asynchronously |
| [beginListMessages(IConnection connection, MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [beginListMessages()](#beginListMessages--) | Begins ListMessages operation asynchronously |
| [beginListMessages(System.AsyncCallback callback)](#beginListMessages-com.aspose.ms.System.AsyncCallback-) | Begins ListMessages operation asynchronously |
| [beginListMessages(System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessages operation asynchronously |
| [beginListMessages(MailQuery query)](#beginListMessages-com.aspose.email.MailQuery-) | Begins ListMessage operation asynchronously |
| [beginListMessages(MailQuery query, System.AsyncCallback callback)](#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-) | Begins ListMessage operation asynchronously |
| [beginListMessages(MailQuery query, System.AsyncCallback callback, Object state)](#beginListMessages-com.aspose.email.MailQuery-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins ListMessage operation asynchronously |
| [endListMessages(System.IAsyncResult asyncResult)](#endListMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [listMessagesByUids(Iterable<String> uniqueIdLst)](#listMessagesByUids-java.lang.Iterable-java.lang.String--) | Lists the messages. |
| [listMessagesBySequences(Iterable<Integer> sequenceNumberLst)](#listMessagesBySequences-java.lang.Iterable-java.lang.Integer--) | Lists the messages. |
| [listMessagesByUids(IConnection connection, Iterable<String> uniqueIdLst)](#listMessagesByUids-com.aspose.email.IConnection-java.lang.Iterable-java.lang.String--) | Lists the messages. |
| [listMessagesBySequences(IConnection connection, Iterable<Integer> sequenceNumberLst)](#listMessagesBySequences-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Lists the messages. |
| [listMessages(IConnection connection)](#listMessages-com.aspose.email.IConnection-) | Lists the messages. |
| [listMessages(IConnection connection, boolean closeTransaction)](#listMessages-com.aspose.email.IConnection-boolean-) | Lists the messages. |
| [listMessages(IConnection connection, MailQuery query)](#listMessages-com.aspose.email.IConnection-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages(IConnection connection, int fields)](#listMessages-com.aspose.email.IConnection-int-) | Lists the messages. |
| [listMessages(IConnection connection, int fields, boolean closeTransaction, MailQuery query)](#listMessages-com.aspose.email.IConnection-int-boolean-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages()](#listMessages--) | Lists the messages. |
| [listMessages(boolean closeTransaction)](#listMessages-boolean-) | Lists the messages. |
| [listMessages(MailQuery query)](#listMessages-com.aspose.email.MailQuery-) | Lists the messages. |
| [listMessages(int fields)](#listMessages-int-) | Lists the messages. |
| [listMessages(int fields, boolean closeTransaction, MailQuery query)](#listMessages-int-boolean-com.aspose.email.MailQuery-) | Lists the messages. |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-) | Begins load list of Pop3MessageInfo asynchronously |
| [beginLoadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList, System.AsyncCallback callback, Object state)](#beginLoadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins load list of Pop3MessageInfo asynchronously |
| [endLoadMessageInfoList(System.IAsyncResult asyncResult)](#endLoadMessageInfoList-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [loadMessageInfoListBySequence(Iterable<Integer> sequenceNumberList)](#loadMessageInfoListBySequence-java.lang.Iterable-java.lang.Integer--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoListBySequence(IConnection connection, Iterable<Integer> sequenceNumberList)](#loadMessageInfoListBySequence-com.aspose.email.IConnection-java.lang.Iterable-java.lang.Integer--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoList(Iterable<Pop3MessageInfo> messageInfoList)](#loadMessageInfoList-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Loads list of Pop3MessageInfo |
| [loadMessageInfoList(IConnection connection, Iterable<Pop3MessageInfo> messageInfoList)](#loadMessageInfoList-com.aspose.email.IConnection-java.lang.Iterable-com.aspose.email.Pop3MessageInfo--) | Loads list of Pop3MessageInfo |
| [beginNoop(IConnection connection)](#beginNoop-com.aspose.email.IConnection-) | Begins 'No operation' command. |
| [beginNoop(IConnection connection, System.AsyncCallback callback)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins 'No operation' command. |
| [beginNoop(IConnection connection, System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins 'No operation' command. |
| [beginNoop()](#beginNoop--) | Begins 'No operation' command. |
| [beginNoop(System.AsyncCallback callback)](#beginNoop-com.aspose.ms.System.AsyncCallback-) | Begins 'No operation' command. |
| [beginNoop(System.AsyncCallback callback, Object state)](#beginNoop-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins 'No operation' command. |
| [endNoop(System.IAsyncResult asyncResult)](#endNoop-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [noop(IConnection connection)](#noop-com.aspose.email.IConnection-) | 'No operation' command |
| [noop()](#noop--) | 'No operation' command |
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
| [endSaveMessage(System.IAsyncResult asyncResult)](#endSaveMessage-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [saveMessage(IConnection connection, String uniqueId, OutputStream outputStream)](#saveMessage-com.aspose.email.IConnection-java.lang.String-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(IConnection connection, String uniqueId, String fileName)](#saveMessage-com.aspose.email.IConnection-java.lang.String-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(IConnection connection, int sequenceNumber, OutputStream outputStream)](#saveMessage-com.aspose.email.IConnection-int-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(IConnection connection, int sequenceNumber, String fileName)](#saveMessage-com.aspose.email.IConnection-int-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(String uniqueId, OutputStream outputStream)](#saveMessage-java.lang.String-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(String uniqueId, String fileName)](#saveMessage-java.lang.String-java.lang.String-) | Fetches and save the message into a file |
| [saveMessage(int sequenceNumber, OutputStream outputStream)](#saveMessage-int-java.io.OutputStream-) | Fetches and save the message as a stream |
| [saveMessage(int sequenceNumber, String fileName)](#saveMessage-int-java.lang.String-) | Fetches and save the message into a file |
| [beginUndeleteMessages(IConnection connection)](#beginUndeleteMessages-com.aspose.email.IConnection-) | Begins undeletes the messages. |
| [beginUndeleteMessages(IConnection connection, System.AsyncCallback callback)](#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins undeletes the messages. |
| [beginUndeleteMessages(IConnection connection, System.AsyncCallback callback, Object state)](#beginUndeleteMessages-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins undeletes the messages. |
| [beginUndeleteMessages()](#beginUndeleteMessages--) | Begins undeletes the messages. |
| [beginUndeleteMessages(System.AsyncCallback callback)](#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-) | Begins undeletes the messages. |
| [beginUndeleteMessages(System.AsyncCallback callback, Object state)](#beginUndeleteMessages-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins undeletes the messages. |
| [endUndeleteMessages(System.IAsyncResult asyncResult)](#endUndeleteMessages-com.aspose.ms.System.IAsyncResult-) | Waits for the asynchronous operation to complete. |
| [undeleteMessages(IConnection connection)](#undeleteMessages-com.aspose.email.IConnection-) | Undeletes the messages. |
| [undeleteMessages()](#undeleteMessages--) | Undeletes the messages. |
| [beginValidateCredentials(IConnection connection)](#beginValidateCredentials-com.aspose.email.IConnection-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(IConnection connection, System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.email.IConnection-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [beginValidateCredentials()](#beginValidateCredentials--) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-) | Begins to execute credentials validation |
| [beginValidateCredentials(System.AsyncCallback callback, Object state)](#beginValidateCredentials-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Begins to execute credentials validation |
| [endValidateCredentials(System.IAsyncResult asyncResult)](#endValidateCredentials-com.aspose.ms.System.IAsyncResult-) | Waits for the pending asynchronous operation to complete. |
| [validateCredentials(IConnection connection)](#validateCredentials-com.aspose.email.IConnection-) | Executes credentials validation |
| [validateCredentials()](#validateCredentials--) | Executes credentials validation |
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
### beginCommitDeletes() {#beginCommitDeletes--}
```
public final System.IAsyncResult beginCommitDeletes()
```


Begins to commit the deletions.

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
### endCommitDeletes(System.IAsyncResult asyncResult) {#endCommitDeletes-com.aspose.ms.System.IAsyncResult-}
```
public final void endCommitDeletes(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### commitDeletes(int sleep) {#commitDeletes-int-}
```
public final void commitDeletes(int sleep)
```


Commit the deletions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sleep | int | Timeout in milliseconds |

### commitDeletes(IConnection connection) {#commitDeletes-com.aspose.email.IConnection-}
```
public final void commitDeletes(IConnection connection)
```


Commit the deletions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### commitDeletes() {#commitDeletes--}
```
public final void commitDeletes()
```


Commit the deletions

### getDefaultPort() {#getDefaultPort--}
```
public int getDefaultPort()
```


Gets default port for client

**Returns:**
int
### getAllowedAuthentication() {#getAllowedAuthentication--}
```
public final long getAllowedAuthentication()
```


Gets or sets enumeration of allowed by user authentication types

**Returns:**
long
### setAllowedAuthentication(long value) {#setAllowedAuthentication-long-}
```
public final void setAllowedAuthentication(long value)
```


Gets or sets enumeration of allowed by user authentication types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSupportedAuthentication() {#getSupportedAuthentication--}
```
public final long getSupportedAuthentication()
```


Gets enumeration of supported by server authentication types

**Returns:**
long
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
### endDeleteMessage(System.IAsyncResult asyncResult) {#endDeleteMessage-com.aspose.ms.System.IAsyncResult-}
```
public final void endDeleteMessage(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

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
### beginDeleteMessages() {#beginDeleteMessages--}
```
public final System.IAsyncResult beginDeleteMessages()
```


Begins delete all messages asynchronously

**Returns:**
com.aspose.ms.System.IAsyncResult - IAsyncResult that represents the status of an asynchronous operation.

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state.
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
### endDeleteMessages(System.IAsyncResult asyncResult) {#endDeleteMessages-com.aspose.ms.System.IAsyncResult-}
```
public final void endDeleteMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

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

### deleteMessages() {#deleteMessages--}
```
public final void deleteMessages()
```


Deletes all messages

--------------------

The POP3 server marks the message as deleted. The POP3 server does not actually delete the message until the POP3 session enters the UPDATE state.

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
### beginGetMailboxInfo() {#beginGetMailboxInfo--}
```
public final System.IAsyncResult beginGetMailboxInfo()
```


Begins to get the mailbox status info

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
### getMailboxInfo() {#getMailboxInfo--}
```
public final Pop3MailboxInfo getMailboxInfo()
```


Gets the mailbox status info

**Returns:**
[Pop3MailboxInfo](../../com.aspose.email/pop3mailboxinfo) - Mailbox information
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
### beginGetMailboxSize() {#beginGetMailboxSize--}
```
public final System.IAsyncResult beginGetMailboxSize()
```


Begins GetMailboxSize operation asynchronously

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
### getMailboxSize() {#getMailboxSize--}
```
public final long getMailboxSize()
```


Gets the size of the mailbox

**Returns:**
long - size of the mailbox in bytes
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
### beginGetMessageCount() {#beginGetMessageCount--}
```
public final System.IAsyncResult beginGetMessageCount()
```


Begins GetMessageCount operation asynchronously

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
### beginListMessages() {#beginListMessages--}
```
public final System.IAsyncResult beginListMessages()
```


Begins ListMessages operation asynchronously

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
### beginNoop() {#beginNoop--}
```
public final System.IAsyncResult beginNoop()
```


Begins 'No operation' command.

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
### endNoop(System.IAsyncResult asyncResult) {#endNoop-com.aspose.ms.System.IAsyncResult-}
```
public final void endNoop(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### noop(IConnection connection) {#noop-com.aspose.email.IConnection-}
```
public void noop(IConnection connection)
```


'No operation' command

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### noop() {#noop--}
```
public void noop()
```


'No operation' command

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
### endSaveMessage(System.IAsyncResult asyncResult) {#endSaveMessage-com.aspose.ms.System.IAsyncResult-}
```
public final void endSaveMessage(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

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
### beginUndeleteMessages() {#beginUndeleteMessages--}
```
public final System.IAsyncResult beginUndeleteMessages()
```


Begins undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

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
### endUndeleteMessages(System.IAsyncResult asyncResult) {#endUndeleteMessages-com.aspose.ms.System.IAsyncResult-}
```
public final void endUndeleteMessages(System.IAsyncResult asyncResult)
```


Waits for the asynchronous operation to complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | com.aspose.ms.System.IAsyncResult | The reference to the pending asynchronous request to wait for. |

### undeleteMessages(IConnection connection) {#undeleteMessages-com.aspose.email.IConnection-}
```
public final void undeleteMessages(IConnection connection)
```


Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | [IConnection](../../com.aspose.email/iconnection) | Connection to a server |

### undeleteMessages() {#undeleteMessages--}
```
public final void undeleteMessages()
```


Undeletes the messages. If any messages have been marked as deleted by the POP3 server, they are unmarked.

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
### beginValidateCredentials() {#beginValidateCredentials--}
```
public final System.IAsyncResult beginValidateCredentials()
```


Begins to execute credentials validation

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
### validateCredentials() {#validateCredentials--}
```
public boolean validateCredentials()
```


Executes credentials validation

**Returns:**
boolean - True if authentication was successful, otherwise false.
