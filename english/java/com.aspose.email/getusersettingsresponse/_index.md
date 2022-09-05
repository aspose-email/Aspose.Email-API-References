---
title: GetUserSettingsResponse
second_title: Aspose.Email for Java API Reference
description:  Represents the response to a GetUsersSettings call for an individual user.
type: docs
weight: 274
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
| [getSmtpAddress()](#getSmtpAddress--) | Gets the SMTP address this response applies to. |
| [getRedirectTarget()](#getRedirectTarget--) | Gets the redirectionTarget (URL or email address) |
| [getSettings()](#getSettings--) | Gets the requested settings for the user. |
| [getUserSettingErrors()](#getUserSettingErrors--) | Gets error information for settings that could not be returned. |
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
### getSmtpAddress() {#getSmtpAddress--}
```
public final String getSmtpAddress()
```


Gets the SMTP address this response applies to.

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
### getUserSettingErrors() {#getUserSettingErrors--}
```
public final System.Collections.ObjectModel.Collection<UserSettingError> getUserSettingErrors()
```


Gets error information for settings that could not be returned.

**Returns:**
com.aspose.ms.System.Collections.ObjectModel.Collection<com.aspose.email.UserSettingError>
