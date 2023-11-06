---
title: OAuthToken
second_title: Aspose.Email for Java API Reference
description: Contains OAuth token data such like token value token type expiration date.
type: docs
weight: 545
url: /java/com.aspose.email/oauthtoken/
---

**Inheritance:**
java.lang.Object
```
public class OAuthToken
```

Contains OAuth token data such like token value, token type, expiration date.
## Constructors

| Constructor | Description |
| --- | --- |
| [OAuthToken(String token)](#OAuthToken-java.lang.String-) | Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class |
| [OAuthToken(String token, Date expirationDate)](#OAuthToken-java.lang.String-java.util.Date-) | Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class |
| [OAuthToken(String token, int tokenType, Date expirationDate)](#OAuthToken-java.lang.String-int-java.util.Date-) | Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [getClass()](#getClass--) |  |
| [getExpirationDate()](#getExpirationDate--) | Gets expiration date of the token. |
| [getExpired()](#getExpired--) | Indicates whether token is expired |
| [getToken()](#getToken--) | Gets token value |
| [getTokenType()](#getTokenType--) | Gets OAuth token type |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OAuthToken(String token) {#OAuthToken-java.lang.String-}
```
public OAuthToken(String token)
```


Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| token | java.lang.String | Refresh token value |

### OAuthToken(String token, Date expirationDate) {#OAuthToken-java.lang.String-java.util.Date-}
```
public OAuthToken(String token, Date expirationDate)
```


Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| token | java.lang.String | Access token value |
| expirationDate | java.util.Date | Expiration date of the token. |

### OAuthToken(String token, int tokenType, Date expirationDate) {#OAuthToken-java.lang.String-int-java.util.Date-}
```
public OAuthToken(String token, int tokenType, Date expirationDate)
```


Initializes a new instance of the [OAuthToken](../../com.aspose.email/oauthtoken) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| token | java.lang.String | Token value |
| tokenType | int | OAuth token type |
| expirationDate | java.util.Date | Expiration date of the token. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean - true if the specified object is equal to the current object; otherwise, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpirationDate() {#getExpirationDate--}
```
public final Date getExpirationDate()
```


Gets expiration date of the token.

**Returns:**
java.util.Date
### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Indicates whether token is expired

**Returns:**
boolean
### getToken() {#getToken--}
```
public final String getToken()
```


Gets token value

**Returns:**
java.lang.String
### getTokenType() {#getTokenType--}
```
public final int getTokenType()
```


Gets OAuth token type

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
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


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
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

