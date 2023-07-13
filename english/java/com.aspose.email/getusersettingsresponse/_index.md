---
title: GetUserSettingsResponse
second_title: Aspose.Email for Java API Reference
description: Represents the response to a GetUsersSettings call for an individual user.
type: docs
weight: 275
url: /java/com.aspose.email/getusersettingsresponse/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AutodiscoverResponse](../../com.aspose.email/autodiscoverresponse)
```
public final class GetUserSettingsResponse extends AutodiscoverResponse
```

Represents the response to a GetUsersSettings call for an individual user.
## Constructors

| Constructor | Description |
| --- | --- |
| [GetUserSettingsResponse()](#GetUserSettingsResponse--) | Initializes a new instance of the [GetUserSettingsResponse](../../com.aspose.email/getusersettingsresponse) class. |
## Methods

| Method | Description |
| --- | --- |
| [<T>tryGetSettingValue(int setting)](#-T-tryGetSettingValue-int-) | Tries the get the user setting value. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCode()](#getErrorCode--) | Gets the error code that was returned by the service. |
| [getErrorMessage()](#getErrorMessage--) | Gets the error message that was returned by the service. |
| [getRedirectTarget()](#getRedirectTarget--) | Gets the redirectionTarget (URL or email address) |
| [getSettings()](#getSettings--) | Gets the requested settings for the user. |
| [getSmtpAddress()](#getSmtpAddress--) | Gets the SMTP address this response applies to. |
| [getUserSettingErrors()](#getUserSettingErrors--) | Gets error information for settings that could not be returned. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GetUserSettingsResponse() {#GetUserSettingsResponse--}
```
public GetUserSettingsResponse()
```


Initializes a new instance of the [GetUserSettingsResponse](../../com.aspose.email/getusersettingsresponse) class.

### <T>tryGetSettingValue(int setting) {#-T-tryGetSettingValue-int-}
```
public T <T>tryGetSettingValue(int setting)
```


Tries the get the user setting value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setting | int | The setting. |

**Returns:**
T - True if setting was available.
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
### getErrorCode() {#getErrorCode--}
```
public final int getErrorCode()
```


Gets the error code that was returned by the service.

**Returns:**
int
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Gets the error message that was returned by the service.

Value: The error message.

**Returns:**
java.lang.String
### getRedirectTarget() {#getRedirectTarget--}
```
public final String getRedirectTarget()
```


Gets the redirectionTarget (URL or email address)

**Returns:**
java.lang.String
### getSettings() {#getSettings--}
```
public final System.Collections.Generic.IGenericDictionary<Integer,Object> getSettings()
```


Gets the requested settings for the user.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.Integer,java.lang.Object>
### getSmtpAddress() {#getSmtpAddress--}
```
public final String getSmtpAddress()
```


Gets the SMTP address this response applies to.

**Returns:**
java.lang.String
### getUserSettingErrors() {#getUserSettingErrors--}
```
public final System.Collections.ObjectModel.Collection<UserSettingError> getUserSettingErrors()
```


Gets error information for settings that could not be returned.

**Returns:**
com.aspose.ms.System.Collections.ObjectModel.Collection<com.aspose.email.UserSettingError>
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

