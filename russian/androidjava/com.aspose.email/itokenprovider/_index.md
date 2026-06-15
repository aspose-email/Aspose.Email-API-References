---
title: ITokenProvider
second_title: Aspose.Email for Android via Java API Reference
description: Определяет интерфейс, позволяющий получить токен доступа.
type: docs
weight: 464
url: /ru/androidjava/com.aspose.email/itokenprovider/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface ITokenProvider extends System.IDisposable
```

Определяет интерфейс, позволяющий получить токен доступа.
## Methods

| Method | Описание |
| --- | --- |
| [getAccessToken()](#getAccessToken--) | Получает токен доступа oAuth. |
| [getAccessToken(boolean ignoreExistingToken)](#getAccessToken-boolean-) | Получает токен доступа oAuth. |
### getAccessToken() {#getAccessToken--}
```
public abstract OAuthToken getAccessToken()
```


Получает токен доступа oAuth. Если токен существует и его срок действия не истёк, возвращает текущий токен, иначе запрашивает новый токен у сервера.

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
### getAccessToken(boolean ignoreExistingToken) {#getAccessToken-boolean-}
```
public abstract OAuthToken getAccessToken(boolean ignoreExistingToken)
```


Получает токен доступа oAuth.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ignoreExistingToken | boolean | Если ignoreExistingToken истинно, запрашивает новый токен у сервера. В противном случае поведение зависит от того, существует токен или нет. Если токен существует и его срок действия не истёк, возвращает текущий токен, иначе запрашивает новый токен у сервера. |

**Returns:**
[OAuthToken](../../com.aspose.email/oauthtoken) - Returns oAuth access token
