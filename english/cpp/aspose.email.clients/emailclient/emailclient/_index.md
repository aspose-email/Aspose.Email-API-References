---
title: "Aspose::Email::Clients::EmailClient::EmailClient constructor"
linktitle: "EmailClient"
articleTitle: "EmailClient"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the EmailClient class."
type: docs
weight: 10
url: /cpp/aspose.email.clients/emailclient/emailclient/
---

## EmailClient (1 of 9) {#emailclient_1}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type)
```

| Parameter | Description |
| --- | --- |
| type |  |

---

## EmailClient (2 of 9) {#emailclient_2}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port)
```

| Parameter | Description |
| --- | --- |
| host | The host name. |
| port | The port number. |

---

## EmailClient (3 of 9) {#emailclient_3}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, Aspose::Email::Clients::SecurityOptions securityOptions)
```

| Parameter | Description |
| --- | --- |
| host | The host name. |
| port | The port number. |
| securityOptions | Security mode for a mail client |

---

## EmailClient (4 of 9) {#emailclient_4}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::String password)
```

| Parameter | Description |
| --- | --- |
| host | The host name. |
| port | The port number. |
| username | The username. |
| password | The account password. Password limitations are defined by server implementation, which the client connects. |

---

## EmailClient (5 of 9) {#emailclient_5}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::String password, Aspose::Email::Clients::SecurityOptions securityOptions)
```

| Parameter | Description |
| --- | --- |
| host | The host name. |
| port | The port number. |
| username | The username. |
| password | The account password. Password limitations are defined by server implementation, which the client connects. |
| securityOptions | Security mode for a mail client |

---

## EmailClient (6 of 9) {#emailclient_6}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::String authInfo, bool useOAuth)
```

| Parameter | Description |
| --- | --- |
| host | The host. |
| port | The port. |
| username | The username. |
| authInfo | A string representation of the user password or the access token. AuthInfo limitations are defined by server implementation, which the client connects. |
| useOAuth | Defines whether OAuth is used to login to the server |

---

## EmailClient (7 of 9) {#emailclient_7}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::String authInfo, bool useOAuth, Aspose::Email::Clients::SecurityOptions securityOptions)
```

| Parameter | Description |
| --- | --- |
| host | The host. |
| port | The port. |
| username | The username. |
| authInfo | A string representation of the user password or the access token. |
| useOAuth | Defines whether OAuth is used to login to the server |
| securityOptions | Security mode for a mail client |

---

## EmailClient (8 of 9) {#emailclient_8}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::SharedPtr < ITokenProvider > tokenProvider)
```

| Parameter | Description |
| --- | --- |
| host | The host. |
| port | The port. |
| username | The username. |
| tokenProvider | TokenProvider allowing to retrieve access token. |

---

## EmailClient (9 of 9) {#emailclient_9}

Initializes a new instance of the EmailClient class.

**Returns:** Aspose::Email::Clients::

```cpp
EmailClient(System::String type, System::String host, int32_t port, System::String username, System::SharedPtr < ITokenProvider > tokenProvider, Aspose::Email::Clients::SecurityOptions securityOptions)
```

| Parameter | Description |
| --- | --- |
| host | The host. |
| port | The port. |
| username | The username. |
| tokenProvider | TokenProvider allowing to retrieve access token. |
| securityOptions |  |

