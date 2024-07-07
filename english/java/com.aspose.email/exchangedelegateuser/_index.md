---
title: ExchangeDelegateUser
second_title: Aspose.Email for Java API Reference
description: Represents a user who is granted access to the principal mailbox
type: docs
weight: 204
url: /java/com.aspose.email/exchangedelegateuser/
---

**Inheritance:**
java.lang.Object
```
public final class ExchangeDelegateUser
```

Represents a user who is granted access to the principal mailbox
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeDelegateUser()](#ExchangeDelegateUser--) | Initializes a new instance of the [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) class |
| [ExchangeDelegateUser(String primarySmtpAddress, int permissionLevel)](#ExchangeDelegateUser-java.lang.String-int-) | Initializes a new instance of the [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) class for the specified user and sets the specified permission level on all folders |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFolderPermissions()](#getFolderPermissions--) | Gets or sets the folder permissions for the delegate user |
| [getOptions()](#getOptions--) | Gets or sets additional options |
| [getUserInfo()](#getUserInfo--) | Gets or sets the user information |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFolderPermissions(ExchangeDelegatePermissions value)](#setFolderPermissions-com.aspose.email.ExchangeDelegatePermissions-) | Gets or sets the folder permissions for the delegate user |
| [setOptions(int value)](#setOptions-int-) | Gets or sets additional options |
| [setUserInfo(ExchangeFolderUserInfo value)](#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-) | Gets or sets the user information |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeDelegateUser() {#ExchangeDelegateUser--}
```
public ExchangeDelegateUser()
```


Initializes a new instance of the [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) class

### ExchangeDelegateUser(String primarySmtpAddress, int permissionLevel) {#ExchangeDelegateUser-java.lang.String-int-}
```
public ExchangeDelegateUser(String primarySmtpAddress, int permissionLevel)
```


Initializes a new instance of the [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) class for the specified user and sets the specified permission level on all folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primarySmtpAddress | java.lang.String | A user primary smtp address |
| permissionLevel | int | A permission level that is granted to the user on all folders |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolderPermissions() {#getFolderPermissions--}
```
public final ExchangeDelegatePermissions getFolderPermissions()
```


Gets or sets the folder permissions for the delegate user

**Returns:**
[ExchangeDelegatePermissions](../../com.aspose.email/exchangedelegatepermissions)
### getOptions() {#getOptions--}
```
public final int getOptions()
```


Gets or sets additional options

**Returns:**
int
### getUserInfo() {#getUserInfo--}
```
public final ExchangeFolderUserInfo getUserInfo()
```


Gets or sets the user information

**Returns:**
[ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFolderPermissions(ExchangeDelegatePermissions value) {#setFolderPermissions-com.aspose.email.ExchangeDelegatePermissions-}
```
public final void setFolderPermissions(ExchangeDelegatePermissions value)
```


Gets or sets the folder permissions for the delegate user

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeDelegatePermissions](../../com.aspose.email/exchangedelegatepermissions) |  |

### setOptions(int value) {#setOptions-int-}
```
public final void setOptions(int value)
```


Gets or sets additional options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUserInfo(ExchangeFolderUserInfo value) {#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-}
```
public final void setUserInfo(ExchangeFolderUserInfo value)
```


Gets or sets the user information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

