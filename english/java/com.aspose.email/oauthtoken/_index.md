---
title: OAuthToken
second_title: Aspose.Email for Java API Reference
description:  Contains OAuth token data such like token value token type expiration date.
type: docs
weight: 534
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
| [getTokenType()](#getTokenType--) | Gets OAuth token type |
| [getToken()](#getToken--) | Gets token value |
| [getExpirationDate()](#getExpirationDate--) | Gets expiration date of the token. |
| [getExpired()](#getExpired--) | Indicates whether token is expired |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
| [toString()](#toString--) | Returns a string that represents the current object. |
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

### getTokenType() {#getTokenType--}
```
public final int getTokenType()
```


Gets OAuth token type

**Returns:**
int
### getToken() {#getToken--}
```
public final String getToken()
```


Gets token value

**Returns:**
java.lang.String
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
