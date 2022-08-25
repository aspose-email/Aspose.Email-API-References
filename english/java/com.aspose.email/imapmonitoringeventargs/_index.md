---
title: ImapMonitoringEventArgs
second_title: Aspose.Email for Java API Reference
description:  Class contains monitoring event data.
type: docs
weight: 320
url: /java/com.aspose.email/imapmonitoringeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ImapMonitoringEventArgs extends System.EventArgs
```

Class contains monitoring event data.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages)](#ImapMonitoringEventArgs-java.lang.String-com.aspose.email.ImapMessageInfo---com.aspose.email.ImapMessageInfo---) | Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class |
| [ImapMonitoringEventArgs(String folderName, Throwable error)](#ImapMonitoringEventArgs-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class |
## Methods

| Method | Description |
| --- | --- |
| [getFolderName()](#getFolderName--) | Gets specified folder for monitoring operation. |
| [getError()](#getError--) | Gets error of IMAP IDLE operation. |
| [getNewMessages()](#getNewMessages--) | Gets new messages |
| [getDeletedMessages()](#getDeletedMessages--) | Gets deleted messages |
### ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages) {#ImapMonitoringEventArgs-java.lang.String-com.aspose.email.ImapMessageInfo---com.aspose.email.ImapMessageInfo---}
```
public ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages)
```


Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderName | java.lang.String | specified folder for monitoring operation |
| newMessages | com.aspose.email.ImapMessageInfo[] | Contains information about new messages |
| deletedMessages | com.aspose.email.ImapMessageInfo[] | Contains information about deleted messages |

### ImapMonitoringEventArgs(String folderName, Throwable error) {#ImapMonitoringEventArgs-java.lang.String-java.lang.Throwable-}
```
public ImapMonitoringEventArgs(String folderName, Throwable error)
```


Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderName | java.lang.String | specified folder for monitoring operation |
| error | java.lang.Throwable | Error of IMAP IDLE operation |

### getFolderName() {#getFolderName--}
```
public final String getFolderName()
```


Gets specified folder for monitoring operation.

**Returns:**
java.lang.String
### getError() {#getError--}
```
public final Throwable getError()
```


Gets error of IMAP IDLE operation.

**Returns:**
java.lang.Throwable
### getNewMessages() {#getNewMessages--}
```
public final ImapMessageInfo[] getNewMessages()
```


Gets new messages

**Returns:**
com.aspose.email.ImapMessageInfo[]
### getDeletedMessages() {#getDeletedMessages--}
```
public final ImapMessageInfo[] getDeletedMessages()
```


Gets deleted messages

**Returns:**
com.aspose.email.ImapMessageInfo[]
