---
title: "Aspose::Email::Clients::TokenProvider::TokenProvider constructor"
linktitle: "TokenProvider"
articleTitle: "TokenProvider"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the TokenProvider class"
type: docs
weight: 10
url: /cpp/aspose.email.clients/tokenprovider/tokenprovider/
---

## TokenProvider (1 of 4) {#tokenprovider_1}

Initializes a new instance of the TokenProvider class

**Returns:** Aspose::Email::Clients::

```cpp
TokenProvider(System::String requestUrl, System::String clientId, System::String clientSecret, System::String refreshToken)
```

| Parameter | Description |
| --- | --- |
| requestUrl | The url to obtain access token. |
| clientId | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | The client secret obtained during application registration. |
| refreshToken | OAuth 2.0 refresh token |

---

## TokenProvider (2 of 4) {#tokenprovider_2}

Initializes a new instance of the TokenProvider class

**Returns:** Aspose::Email::Clients::

```cpp
TokenProvider(System::String requestUrl, System::String clientId, System::String clientSecret, System::String refreshToken, System::String login, System::String password)
```

| Parameter | Description |
| --- | --- |
| requestUrl | The url to obtain access token. |
| clientId | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | The client secret obtained during application registration. |
| refreshToken | OAuth 2.0 refresh token |
| login | login for basic authorization |
| password | password for basic authorization |

---

## TokenProvider (3 of 4) {#tokenprovider_3}

Initializes a new instance of the TokenProvider class

**Returns:** Aspose::Email::Clients::

```cpp
TokenProvider(System::String requestUrl, System::String clientId, System::String clientSecret, System::String refreshToken, System::String login, System::String password, System::ArrayPtr< System::Collections::Generic::KeyValuePair< System::String, System::String >> extraParameters)
```

| Parameter | Description |
| --- | --- |
| requestUrl | The url to obtain access token. |
| clientId | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | The client secret obtained during application registration. |
| refreshToken | OAuth 2.0 refresh token |
| login | login for basic authorization |
| password | password for basic authorization |
| extraParameters |  |

---

## TokenProvider (4 of 4) {#tokenprovider_4}

Initializes a new instance of the TokenProvider class

**Returns:** Aspose::Email::Clients::

```cpp
TokenProvider(System::String requestUrl, System::String clientId, System::String clientSecret, System::String refreshToken, System::ArrayPtr< System::Collections::Generic::KeyValuePair< System::String, System::String >> extraParameters)
```

| Parameter | Description |
| --- | --- |
| requestUrl | The url to obtain access token. |
| clientId | The client ID obtained from the Microsoft account Developer Center during application registration. |
| clientSecret | The client secret obtained during application registration. |
| refreshToken | OAuth 2.0 refresh token |
| extraParameters |  |

