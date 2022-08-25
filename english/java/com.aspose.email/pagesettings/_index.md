---
title: PageSettings
second_title: Aspose.Email for Java API Reference
description:  The settings for the ImapClient.ListMessagesByPage method
type: docs
weight: 548
url: /java/com.aspose.email/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

The settings for the ImapClient.ListMessagesByPage method
## Constructors

| Constructor | Description |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getConnection()](#getConnection--) | Connection to a server. |
| [setConnection(IConnection value)](#setConnection-com.aspose.email.IConnection-) | Connection to a server. |
| [getIgnoreExceptions()](#getIgnoreExceptions--) | If the property is set to true, exceptions that occur during message processing will be caught and placed in the ImapPageInfo.Items.Exceptions. |
| [setIgnoreExceptions(boolean value)](#setIgnoreExceptions-boolean-) | If the property is set to true, exceptions that occur during message processing will be caught and placed in the ImapPageInfo.Items.Exceptions. |
| [getFolderName()](#getFolderName--) | The messages folder |
| [setFolderName(String value)](#setFolderName-java.lang.String-) | The messages folder |
| [getAscendingSorting()](#getAscendingSorting--) | Gets or sets value which indicates if client uses ascending or descending sorting. |
| [setAscendingSorting(boolean value)](#setAscendingSorting-boolean-) | Gets or sets value which indicates if client uses ascending or descending sorting. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getConnection() {#getConnection--}
```
public final IConnection getConnection()
```


Connection to a server.

**Returns:**
[IConnection](../../com.aspose.email/iconnection)
### setConnection(IConnection value) {#setConnection-com.aspose.email.IConnection-}
```
public final void setConnection(IConnection value)
```


Connection to a server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IConnection](../../com.aspose.email/iconnection) |  |

### getIgnoreExceptions() {#getIgnoreExceptions--}
```
public final boolean getIgnoreExceptions()
```


If the property is set to true, exceptions that occur during message processing will be caught and placed in the ImapPageInfo.Items.Exceptions.

**Returns:**
boolean
### setIgnoreExceptions(boolean value) {#setIgnoreExceptions-boolean-}
```
public final void setIgnoreExceptions(boolean value)
```


If the property is set to true, exceptions that occur during message processing will be caught and placed in the ImapPageInfo.Items.Exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFolderName() {#getFolderName--}
```
public final String getFolderName()
```


The messages folder

**Returns:**
java.lang.String
### setFolderName(String value) {#setFolderName-java.lang.String-}
```
public final void setFolderName(String value)
```


The messages folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAscendingSorting() {#getAscendingSorting--}
```
public final boolean getAscendingSorting()
```


Gets or sets value which indicates if client uses ascending or descending sorting. Set true if you want to use ascending sorting, otherwise set false.

**Returns:**
boolean
### setAscendingSorting(boolean value) {#setAscendingSorting-boolean-}
```
public final void setAscendingSorting(boolean value)
```


Gets or sets value which indicates if client uses ascending or descending sorting. Set true if you want to use ascending sorting, otherwise set false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

