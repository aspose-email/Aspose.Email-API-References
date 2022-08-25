---
title: ExchangeDelegateUser
second_title: Aspose.Email for Java API Reference
description:  Represents a user who is granted access to the principal mailbox
type: docs
weight: 202
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
| [getUserInfo()](#getUserInfo--) | Gets or sets the user information |
| [setUserInfo(ExchangeFolderUserInfo value)](#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-) | Gets or sets the user information |
| [getFolderPermissions()](#getFolderPermissions--) | Gets or sets the folder permissions for the delegate user |
| [setFolderPermissions(ExchangeDelegatePermissions value)](#setFolderPermissions-com.aspose.email.ExchangeDelegatePermissions-) | Gets or sets the folder permissions for the delegate user |
| [getOptions()](#getOptions--) | Gets or sets additional options |
| [setOptions(int value)](#setOptions-int-) | Gets or sets additional options |
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

### getUserInfo() {#getUserInfo--}
```
public final ExchangeFolderUserInfo getUserInfo()
```


Gets or sets the user information

**Returns:**
[ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo)
### setUserInfo(ExchangeFolderUserInfo value) {#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-}
```
public final void setUserInfo(ExchangeFolderUserInfo value)
```


Gets or sets the user information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo) |  |

### getFolderPermissions() {#getFolderPermissions--}
```
public final ExchangeDelegatePermissions getFolderPermissions()
```


Gets or sets the folder permissions for the delegate user

**Returns:**
[ExchangeDelegatePermissions](../../com.aspose.email/exchangedelegatepermissions)
### setFolderPermissions(ExchangeDelegatePermissions value) {#setFolderPermissions-com.aspose.email.ExchangeDelegatePermissions-}
```
public final void setFolderPermissions(ExchangeDelegatePermissions value)
```


Gets or sets the folder permissions for the delegate user

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeDelegatePermissions](../../com.aspose.email/exchangedelegatepermissions) |  |

### getOptions() {#getOptions--}
```
public final int getOptions()
```


Gets or sets additional options

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public final void setOptions(int value)
```


Gets or sets additional options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

