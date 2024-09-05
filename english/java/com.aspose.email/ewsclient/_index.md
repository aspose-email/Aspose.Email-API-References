---
title: EWSClient
second_title: Aspose.Email for Java API Reference
description: Provides access to MS Exchange Server by using Exchange Web Services EWS.
type: docs
weight: 165
url: /java/com.aspose.email/ewsclient/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.ExchangeClientBase](../../com.aspose.email/exchangeclientbase)
```
public abstract class EWSClient extends ExchangeClientBase
```

Provides access to MS Exchange Server by using Exchange Web Services (EWS).
## Fields

| Field | Description |
| --- | --- |
| [CalendarFolderServerNotifications](#CalendarFolderServerNotifications) | Occurs when arises specified event type for Calendar folder. |
| [ContactsFolderServerNotifications](#ContactsFolderServerNotifications) | Occurs when arises specified event type for Contacts folder. |
| [DeletedItemsFolderServerNotifications](#DeletedItemsFolderServerNotifications) | Occurs when arises specified event type for DeletedItems folder. |
| [DraftsFolderServerNotifications](#DraftsFolderServerNotifications) | Occurs when arises specified event type for Drafts folder. |
| [InboxFolderServerNotifications](#InboxFolderServerNotifications) | Occurs when arises specified event type for Inbox folder. |
| [JournalFolderServerNotifications](#JournalFolderServerNotifications) | Occurs when arises specified event type for Journal folder. |
| [NotesFolderServerNotifications](#NotesFolderServerNotifications) | Occurs when arises specified event type for Notes folder. |
| [OutboxFolderServerNotifications](#OutboxFolderServerNotifications) | Occurs when arises specified event type for Outbox folder. |
| [RootFolderServerNotifications](#RootFolderServerNotifications) | Occurs when arises specified event type for Root folder. |
| [SentItemsFolderServerNotifications](#SentItemsFolderServerNotifications) | Occurs when arises specified event type for SentItems folder. |
| [TasksFolderServerNotifications](#TasksFolderServerNotifications) | Occurs when arises specified event type for Tasks folder. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [disableSAAJCertificateValidation()](#disableSAAJCertificateValidation--) | Disable SAAJ certificate validation |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarFolderEventFilter()](#getCalendarFolderEventFilter--) | getCalendarFolderEventFilter. |
| [getClass()](#getClass--) |  |
| [getContactsFolderEventFilter()](#getContactsFolderEventFilter--) | getContactsFolderEventFilter. |
| [getCredentials()](#getCredentials--) | Gets or sets the credentials |
| [getDeletedItemsFolderEventFilter()](#getDeletedItemsFolderEventFilter--) | getDeletedItemsFolderEventFilter. |
| [getDraftsFolderEventFilter()](#getDraftsFolderEventFilter--) | getDraftsFolderEventFilter. |
| [getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-int-boolean-java.lang.String-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-int-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(int serverVersion, String mailboxUri, String username, String password)](#getEWSClient-int-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-int-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, String domain)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(URL mailboxUrl)](#getEWSClient-java.net.URL-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(URL mailboxUrl, int serverVersion)](#getEWSClient-java.net.URL-int-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getInboxFolderEventFilter()](#getInboxFolderEventFilter--) | getInboxFolderEventFilter. |
| [getJournalFolderEventFilter()](#getJournalFolderEventFilter--) | getJournalFolderEventFilter. |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getMailboxUri()](#getMailboxUri--) | Gets or sets the mailbox uri |
| [getNotesFolderEventFilter()](#getNotesFolderEventFilter--) | getNotesFolderEventFilter. |
| [getNotificationTimeout()](#getNotificationTimeout--) | getNotificationTimeout. |
| [getNotificationsCheckInterval()](#getNotificationsCheckInterval--) | getNotificationsCheckInterval. |
| [getOutboxFolderEventFilter()](#getOutboxFolderEventFilter--) | getOutboxFolderEventFilter. |
| [getProxy()](#getProxy--) | Gets or sets the proxy. |
| [getRootFolderEventFilter()](#getRootFolderEventFilter--) | getRootFolderEventFilter. |
| [getSentItemsFolderEventFilter()](#getSentItemsFolderEventFilter--) | getSentItemsFolderEventFilter. |
| [getTasksFolderEventFilter()](#getTasksFolderEventFilter--) | getTasksFolderEventFilter. |
| [getTimeout()](#getTimeout--) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [hashCode()](#hashCode--) |  |
| [listItemsWithChangeKey(boolean value)](#listItemsWithChangeKey-boolean-) | Sets value indicating whether List Items result URI includes ChangeKey value. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetLogSettings()](#resetLogSettings--) | Resets logging settings to default. |
| [setCalendarFolderEventFilter(int value)](#setCalendarFolderEventFilter-int-) | setCalendarFolderEventFilter. |
| [setCommonLogFileName(String value)](#setCommonLogFileName-java.lang.String-) | Sets log file name for all sessions. |
| [setContactsFolderEventFilter(int value)](#setContactsFolderEventFilter-int-) | setContactsFolderEventFilter. |
| [setCredentials(System.Net.ICredentials value)](#setCredentials-com.aspose.ms.System.Net.ICredentials-) | Gets or sets the credentials |
| [setDeletedItemsFolderEventFilter(int value)](#setDeletedItemsFolderEventFilter-int-) | setDeletedItemsFolderEventFilter. |
| [setDraftsFolderEventFilter(int value)](#setDraftsFolderEventFilter-int-) | setDraftsFolderEventFilter. |
| [setInboxFolderEventFilter(int value)](#setInboxFolderEventFilter-int-) | setInboxFolderEventFilter. |
| [setJournalFolderEventFilter(int value)](#setJournalFolderEventFilter-int-) | setJournalFolderEventFilter. |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setMailboxUri(String value)](#setMailboxUri-java.lang.String-) | Gets or sets the mailbox uri |
| [setNotesFolderEventFilter(int value)](#setNotesFolderEventFilter-int-) | setNotesFolderEventFilter. |
| [setNotificationTimeout(int value)](#setNotificationTimeout-int-) | setNotificationTimeout. |
| [setNotificationsCheckInterval(int value)](#setNotificationsCheckInterval-int-) | setNotificationsCheckInterval. |
| [setOutboxFolderEventFilter(int value)](#setOutboxFolderEventFilter-int-) | setOutboxFolderEventFilter. |
| [setProxy(System.Net.WebProxy value)](#setProxy-com.aspose.ms.System.Net.WebProxy-) | Gets or sets the proxy. |
| [setRootFolderEventFilter(int value)](#setRootFolderEventFilter-int-) | setRootFolderEventFilter. |
| [setSentItemsFolderEventFilter(int value)](#setSentItemsFolderEventFilter-int-) | setSentItemsFolderEventFilter. |
| [setTasksFolderEventFilter(int value)](#setTasksFolderEventFilter-int-) | setTasksFolderEventFilter. |
| [setTimeout(int value)](#setTimeout-int-) | Gets or sets the number of milliseconds to wait before the operation times out. |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [toString()](#toString--) |  |
| [useOAUTHImpersonation(boolean value)](#useOAUTHImpersonation-boolean-) | Sets value indicating whether OAUTH2 Impersonation is used. |
| [useSAAJAPI(boolean value)](#useSAAJAPI-boolean-) | Sets value indicating whether SAAJ is used. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarFolderServerNotifications {#CalendarFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> CalendarFolderServerNotifications
```


Occurs when arises specified event type for Calendar folder.

### ContactsFolderServerNotifications {#ContactsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> ContactsFolderServerNotifications
```


Occurs when arises specified event type for Contacts folder.

### DeletedItemsFolderServerNotifications {#DeletedItemsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> DeletedItemsFolderServerNotifications
```


Occurs when arises specified event type for DeletedItems folder.

### DraftsFolderServerNotifications {#DraftsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> DraftsFolderServerNotifications
```


Occurs when arises specified event type for Drafts folder.

### InboxFolderServerNotifications {#InboxFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> InboxFolderServerNotifications
```


Occurs when arises specified event type for Inbox folder.

### JournalFolderServerNotifications {#JournalFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> JournalFolderServerNotifications
```


Occurs when arises specified event type for Journal folder.

### NotesFolderServerNotifications {#NotesFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> NotesFolderServerNotifications
```


Occurs when arises specified event type for Notes folder.

### OutboxFolderServerNotifications {#OutboxFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> OutboxFolderServerNotifications
```


Occurs when arises specified event type for Outbox folder.

### RootFolderServerNotifications {#RootFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> RootFolderServerNotifications
```


Occurs when arises specified event type for Root folder.

### SentItemsFolderServerNotifications {#SentItemsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> SentItemsFolderServerNotifications
```


Occurs when arises specified event type for SentItems folder.

### TasksFolderServerNotifications {#TasksFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> TasksFolderServerNotifications
```


Occurs when arises specified event type for Tasks folder.

### close() {#close--}
```
public void close()
```




### disableSAAJCertificateValidation() {#disableSAAJCertificateValidation--}
```
public static void disableSAAJCertificateValidation()
```


Disable SAAJ certificate validation

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getCalendarFolderEventFilter() {#getCalendarFolderEventFilter--}
```
public int getCalendarFolderEventFilter()
```


getCalendarFolderEventFilter.

**Returns:**
int - a int.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContactsFolderEventFilter() {#getContactsFolderEventFilter--}
```
public int getContactsFolderEventFilter()
```


getContactsFolderEventFilter.

**Returns:**
int - a int.
### getCredentials() {#getCredentials--}
```
public System.Net.ICredentials getCredentials()
```


Gets or sets the credentials

Value: ICredentials

**Returns:**
com.aspose.ms.System.Net.ICredentials
### getDeletedItemsFolderEventFilter() {#getDeletedItemsFolderEventFilter--}
```
public int getDeletedItemsFolderEventFilter()
```


getDeletedItemsFolderEventFilter.

**Returns:**
int - a int.
### getDraftsFolderEventFilter() {#getDraftsFolderEventFilter--}
```
public int getDraftsFolderEventFilter()
```


getDraftsFolderEventFilter.

**Returns:**
int - a int.
### getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-int-boolean-java.lang.String-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverVersion | int | Exchange server versions |
| formbasedAuthenticationRequired | boolean | Set true if form-based authentication is required, otherwise set false. |
| formbasedAuthenticationLocation | java.lang.String | url for form-based authentication |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-int-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverVersion | int | Exchange server versions |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(int serverVersion, String mailboxUri, String username, String password) {#getEWSClient-int-java.lang.String-java.lang.String-java.lang.String-}
```
public static IEWSClient getEWSClient(int serverVersion, String mailboxUri, String username, String password)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverVersion | int | Exchange server versions |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-int-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |
| timeout | int | Sets the number of milliseconds to wait before the operation times out. |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, String domain) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, String domain)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| domain | java.lang.String | The domain name |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| domain | java.lang.String | The domain name |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(URL mailboxUrl) {#getEWSClient-java.net.URL-}
```
public static IEWSClient getEWSClient(URL mailboxUrl)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUrl | java.net.URL | The URL of mailbox |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(URL mailboxUrl, int serverVersion) {#getEWSClient-java.net.URL-int-}
```
public static IEWSClient getEWSClient(URL mailboxUrl, int serverVersion)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUrl | java.net.URL | The URL of mailbox |
| serverVersion | int | Exchange server versions |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getInboxFolderEventFilter() {#getInboxFolderEventFilter--}
```
public int getInboxFolderEventFilter()
```


getInboxFolderEventFilter.

**Returns:**
int - a int.
### getJournalFolderEventFilter() {#getJournalFolderEventFilter--}
```
public int getJournalFolderEventFilter()
```


getJournalFolderEventFilter.

**Returns:**
int - a int.
### getLogFileName() {#getLogFileName--}
```
public final String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getMailboxUri() {#getMailboxUri--}
```
public String getMailboxUri()
```


Gets or sets the mailbox uri

Value: Uri of the mailbox

**Returns:**
java.lang.String
### getNotesFolderEventFilter() {#getNotesFolderEventFilter--}
```
public int getNotesFolderEventFilter()
```


getNotesFolderEventFilter.

**Returns:**
int - a int.
### getNotificationTimeout() {#getNotificationTimeout--}
```
public int getNotificationTimeout()
```


getNotificationTimeout.

**Returns:**
int - a int.
### getNotificationsCheckInterval() {#getNotificationsCheckInterval--}
```
public int getNotificationsCheckInterval()
```


getNotificationsCheckInterval.

**Returns:**
int - a int.
### getOutboxFolderEventFilter() {#getOutboxFolderEventFilter--}
```
public int getOutboxFolderEventFilter()
```


getOutboxFolderEventFilter.

**Returns:**
int - a int.
### getProxy() {#getProxy--}
```
public System.Net.WebProxy getProxy()
```


Gets or sets the proxy.

**Returns:**
com.aspose.ms.System.Net.WebProxy
### getRootFolderEventFilter() {#getRootFolderEventFilter--}
```
public int getRootFolderEventFilter()
```


getRootFolderEventFilter.

**Returns:**
int - a int.
### getSentItemsFolderEventFilter() {#getSentItemsFolderEventFilter--}
```
public int getSentItemsFolderEventFilter()
```


getSentItemsFolderEventFilter.

**Returns:**
int - a int.
### getTasksFolderEventFilter() {#getTasksFolderEventFilter--}
```
public int getTasksFolderEventFilter()
```


getTasksFolderEventFilter.

**Returns:**
int - a int.
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

Value: Timeout in milliseconds

**Returns:**
int
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public final boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### listItemsWithChangeKey(boolean value) {#listItemsWithChangeKey-boolean-}
```
public static void listItemsWithChangeKey(boolean value)
```


Sets value indicating whether List Items result URI includes ChangeKey value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if ChangeKey included to URI. |

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

### setCalendarFolderEventFilter(int value) {#setCalendarFolderEventFilter-int-}
```
public void setCalendarFolderEventFilter(int value)
```


setCalendarFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setCommonLogFileName(String value) {#setCommonLogFileName-java.lang.String-}
```
public static void setCommonLogFileName(String value)
```


Sets log file name for all sessions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The log file name. |

### setContactsFolderEventFilter(int value) {#setContactsFolderEventFilter-int-}
```
public void setContactsFolderEventFilter(int value)
```


setContactsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setCredentials(System.Net.ICredentials value) {#setCredentials-com.aspose.ms.System.Net.ICredentials-}
```
public void setCredentials(System.Net.ICredentials value)
```


Gets or sets the credentials

Value: ICredentials

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.ICredentials |  |

### setDeletedItemsFolderEventFilter(int value) {#setDeletedItemsFolderEventFilter-int-}
```
public void setDeletedItemsFolderEventFilter(int value)
```


setDeletedItemsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setDraftsFolderEventFilter(int value) {#setDraftsFolderEventFilter-int-}
```
public void setDraftsFolderEventFilter(int value)
```


setDraftsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setInboxFolderEventFilter(int value) {#setInboxFolderEventFilter-int-}
```
public void setInboxFolderEventFilter(int value)
```


setInboxFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setJournalFolderEventFilter(int value) {#setJournalFolderEventFilter-int-}
```
public void setJournalFolderEventFilter(int value)
```


setJournalFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public final void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMailboxUri(String value) {#setMailboxUri-java.lang.String-}
```
public void setMailboxUri(String value)
```


Gets or sets the mailbox uri

Value: Uri of the mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNotesFolderEventFilter(int value) {#setNotesFolderEventFilter-int-}
```
public void setNotesFolderEventFilter(int value)
```


setNotesFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setNotificationTimeout(int value) {#setNotificationTimeout-int-}
```
public void setNotificationTimeout(int value)
```


setNotificationTimeout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setNotificationsCheckInterval(int value) {#setNotificationsCheckInterval-int-}
```
public void setNotificationsCheckInterval(int value)
```


setNotificationsCheckInterval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setOutboxFolderEventFilter(int value) {#setOutboxFolderEventFilter-int-}
```
public void setOutboxFolderEventFilter(int value)
```


setOutboxFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setProxy(System.Net.WebProxy value) {#setProxy-com.aspose.ms.System.Net.WebProxy-}
```
public void setProxy(System.Net.WebProxy value)
```


Gets or sets the proxy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.WebProxy |  |

### setRootFolderEventFilter(int value) {#setRootFolderEventFilter-int-}
```
public void setRootFolderEventFilter(int value)
```


setRootFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setSentItemsFolderEventFilter(int value) {#setSentItemsFolderEventFilter-int-}
```
public void setSentItemsFolderEventFilter(int value)
```


setSentItemsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setTasksFolderEventFilter(int value) {#setTasksFolderEventFilter-int-}
```
public void setTasksFolderEventFilter(int value)
```


setTasksFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds).

Value: Timeout in milliseconds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public final void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### useOAUTHImpersonation(boolean value) {#useOAUTHImpersonation-boolean-}
```
public static void useOAUTHImpersonation(boolean value)
```


Sets value indicating whether OAUTH2 Impersonation is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if OAUTH2 Impersonation should be used. |

### useSAAJAPI(boolean value) {#useSAAJAPI-boolean-}
```
public static void useSAAJAPI(boolean value)
```


Sets value indicating whether SAAJ is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if SAAJ API should be used. |

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

