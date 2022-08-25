---
title: AutodiscoverService
second_title: Aspose.Email for Java API Reference
description:  Represents a binding to the Exchange Autodiscover Service.
type: docs
weight: 73
url: /java/com.aspose.email/autodiscoverservice/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AutodiscoverServiceBase](../../com.aspose.email/autodiscoverservicebase)
```
public final class AutodiscoverService extends AutodiscoverServiceBase
```

Represents a binding to the Exchange Autodiscover Service.
## Constructors

| Constructor | Description |
| --- | --- |
| [AutodiscoverService()](#AutodiscoverService--) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(Integer requestedServerVersion)](#AutodiscoverService-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(String domain)](#AutodiscoverService-java.lang.String-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(String domain, Integer requestedServerVersion)](#AutodiscoverService-java.lang.String-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(URI url)](#AutodiscoverService-java.net.URI-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
| [AutodiscoverService(URI url, Integer requestedServerVersion)](#AutodiscoverService-java.net.URI-java.lang.Integer-) | Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class. |
## Methods

| Method | Description |
| --- | --- |
| [getUserSettings(String userSmtpAddress, Integer[] userSettingNames)](#getUserSettings-java.lang.String-java.lang.Integer...-) | Retrieves the specified settings for single SMTP address. |
| [getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames)](#getUsersSettings-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-java.lang.String--java.lang.Integer...-) | Retrieves the specified settings for a set of users. |
| [getDomain()](#getDomain--) | Gets or sets the domain this service is bound to. |
| [setDomain(String value)](#setDomain-java.lang.String-) | Gets or sets the domain this service is bound to. |
| [getUrl()](#getUrl--) | Gets or sets the URL this service is bound to. |
| [setUrl(URI value)](#setUrl-java.net.URI-) | Gets or sets the URL this service is bound to. |
| [isExternal()](#isExternal--) | Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network). |
| [getRedirectionUrlValidationCallback()](#getRedirectionUrlValidationCallback--) | Gets or sets the redirection URL validation callback. |
| [setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value)](#setRedirectionUrlValidationCallback-com.aspose.email.AutodiscoverRedirectionUrlValidationCallback-) | Gets or sets the redirection URL validation callback. |
| [getEnableScpLookup()](#getEnableScpLookup--) | Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
| [setEnableScpLookup(boolean value)](#setEnableScpLookup-boolean-) | Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL. |
### AutodiscoverService() {#AutodiscoverService--}
```
public AutodiscoverService()
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

### AutodiscoverService(Integer requestedServerVersion) {#AutodiscoverService-java.lang.Integer-}
```
public AutodiscoverService(Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### AutodiscoverService(String domain) {#AutodiscoverService-java.lang.String-}
```
public AutodiscoverService(String domain)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domain | java.lang.String | The domain that will be used to determine the URL of the service. |

### AutodiscoverService(String domain, Integer requestedServerVersion) {#AutodiscoverService-java.lang.String-java.lang.Integer-}
```
public AutodiscoverService(String domain, Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| domain | java.lang.String | The domain that will be used to determine the URL of the service. |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### AutodiscoverService(URI url) {#AutodiscoverService-java.net.URI-}
```
public AutodiscoverService(URI url)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URI | The URL of the service. |

### AutodiscoverService(URI url, Integer requestedServerVersion) {#AutodiscoverService-java.net.URI-java.lang.Integer-}
```
public AutodiscoverService(URI url, Integer requestedServerVersion)
```


Initializes a new instance of the [AutodiscoverService](../../com.aspose.email/autodiscoverservice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URI | The URL of the service. |
| requestedServerVersion | java.lang.Integer | The requested server version. |

### getUserSettings(String userSmtpAddress, Integer[] userSettingNames) {#getUserSettings-java.lang.String-java.lang.Integer...-}
```
public final GetUserSettingsResponse getUserSettings(String userSmtpAddress, Integer[] userSettingNames)
```


Retrieves the specified settings for single SMTP address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userSmtpAddress | java.lang.String | The SMTP addresses of the user. |
| userSettingNames | java.lang.Integer[] | The user setting names.

--------------------

This method handles will run the entire Autodiscover "discovery" algorithm and will follow address and URL redirections. |

**Returns:**
[GetUserSettingsResponse](../../com.aspose.email/getusersettingsresponse) - A UserResponse object containing the requested settings for the specified user.
### getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames) {#getUsersSettings-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-java.lang.String--java.lang.Integer...-}
```
public final GetUserSettingsResponseCollection getUsersSettings(System.Collections.Generic.IGenericEnumerable<String> userSmtpAddresses, Integer[] userSettingNames)
```


Retrieves the specified settings for a set of users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userSmtpAddresses | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> | The SMTP addresses of the users. |
| userSettingNames | java.lang.Integer[] | The user setting names. |

**Returns:**
[GetUserSettingsResponseCollection](../../com.aspose.email/getusersettingsresponsecollection) - A GetUserSettingsResponseCollection object containing the responses for each individual user.
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Gets or sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL.

**Returns:**
java.lang.String
### setDomain(String value) {#setDomain-java.lang.String-}
```
public final void setDomain(String value)
```


Gets or sets the domain this service is bound to. When this property is set, the domain name is used to automatically determine the Autodiscover service URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUrl() {#getUrl--}
```
public final URI getUrl()
```


Gets or sets the URL this service is bound to.

**Returns:**
java.net.URI
### setUrl(URI value) {#setUrl-java.net.URI-}
```
public final void setUrl(URI value)
```


Gets or sets the URL this service is bound to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

### isExternal() {#isExternal--}
```
public final Boolean isExternal()
```


Gets a value indicating whether the Autodiscover service that URL points to is internal (inside the corporate network) or external (outside the corporate network).

--------------------

IsExternal is null in the following cases: - This instance has been created with a domain name and no method has been called, - This instance has been created with a URL.

**Returns:**
java.lang.Boolean
### getRedirectionUrlValidationCallback() {#getRedirectionUrlValidationCallback--}
```
public final AutodiscoverRedirectionUrlValidationCallback getRedirectionUrlValidationCallback()
```


Gets or sets the redirection URL validation callback.

Value: The redirection URL validation callback.

**Returns:**
[AutodiscoverRedirectionUrlValidationCallback](../../com.aspose.email/autodiscoverredirectionurlvalidationcallback)
### setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value) {#setRedirectionUrlValidationCallback-com.aspose.email.AutodiscoverRedirectionUrlValidationCallback-}
```
public final void setRedirectionUrlValidationCallback(AutodiscoverRedirectionUrlValidationCallback value)
```


Gets or sets the redirection URL validation callback.

Value: The redirection URL validation callback.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AutodiscoverRedirectionUrlValidationCallback](../../com.aspose.email/autodiscoverredirectionurlvalidationcallback) |  |

### getEnableScpLookup() {#getEnableScpLookup--}
```
public final boolean getEnableScpLookup()
```


Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL.

**Returns:**
boolean
### setEnableScpLookup(boolean value) {#setEnableScpLookup-boolean-}
```
public final void setEnableScpLookup(boolean value)
```


Gets or sets a value indicating whether the AutodiscoverService should perform SCP (ServiceConnectionPoint) record lookup when determining the Autodiscover service URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

