---
title: OAuthToken
second_title: Aspose.Email for Android via Java API 参考
description: 包含 OAuth 令牌数据，例如令牌值、令牌类型和过期日期。
type: docs
weight: 334
url: /zh/androidjava/com.aspose.email/oauthtoken/
---

**Inheritance:**
java.lang.Object
```
public class OAuthToken
```

包含 OAuth 令牌数据，如令牌值、令牌类型、过期日期。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OAuthToken(String token)](#OAuthToken-java.lang.String-) | 初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。 |
| [OAuthToken(String token, Date expirationDate)](#OAuthToken-java.lang.String-java.util.Date-) | 初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。 |
| [OAuthToken(String token, int tokenType, Date expirationDate)](#OAuthToken-java.lang.String-int-java.util.Date-) | 初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [getClass()](#getClass--) |  |
| [getExpirationDate()](#getExpirationDate--) | 获取令牌的过期日期。 |
| [getExpired()](#getExpired--) | 指示令牌是否已过期 |
| [getToken()](#getToken--) | 获取令牌值 |
| [getTokenType()](#getTokenType--) | 获取 OAuth 令牌类型 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OAuthToken(String token) {#OAuthToken-java.lang.String-}
```
public OAuthToken(String token)
```


初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| token | java.lang.String | 刷新令牌值 |

### OAuthToken(String token, Date expirationDate) {#OAuthToken-java.lang.String-java.util.Date-}
```
public OAuthToken(String token, Date expirationDate)
```


初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| token | java.lang.String | 访问令牌值 |
| expirationDate | java.util.Date | 令牌的过期日期。 |

### OAuthToken(String token, int tokenType, Date expirationDate) {#OAuthToken-java.lang.String-int-java.util.Date-}
```
public OAuthToken(String token, int tokenType, Date expirationDate)
```


初始化 [OAuthToken](../../com.aspose.email/oauthtoken) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| token | java.lang.String | 令牌值 |
| tokenType | int | OAuth 令牌类型 |
| expirationDate | java.util.Date | 令牌的过期日期。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于当前对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 如果指定的对象等于当前对象则为 true；否则为 false。
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


获取令牌的过期日期。

**Returns:**
java.util.Date
### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


指示令牌是否已过期

**Returns:**
boolean
### getToken() {#getToken--}
```
public final String getToken()
```


获取令牌值

**Returns:**
java.lang.String
### getTokenType() {#getTokenType--}
```
public final int getTokenType()
```


获取 OAuth 令牌类型

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为特定类型的哈希函数。

**Returns:**
int - 当前对象的哈希码。
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


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

