---
title: "Aspose::Email::Clients::Imap::ImapClient::BeginClientCapabilities method"
linktitle: "BeginClientCapabilities"
articleTitle: "BeginClientCapabilities"
second_title: "Aspose.Email for C++"
description: "Notifies server which extensions are supported by client asyncronously."
type: docs
weight: 100
url: /cpp/aspose.email.clients.imap/imapclient/beginclientcapabilities/
---

## BeginClientCapabilities (1 of 6) {#beginclientcapabilities_1}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(const System::ArrayPtr< System::String > & capabilityNames)
```

| Parameter | Description |
| --- | --- |
| capabilityNames | Array of capabilities which are supported by client |

---

## BeginClientCapabilities (2 of 6) {#beginclientcapabilities_2}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(System::ArrayPtr< System::String > capabilityNames, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| capabilityNames | Array of capabilities which are supported by client |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginClientCapabilities (3 of 6) {#beginclientcapabilities_3}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(System::ArrayPtr< System::String > capabilityNames, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| capabilityNames | Array of capabilities which are supported by client |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

---

## BeginClientCapabilities (4 of 6) {#beginclientcapabilities_4}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(System::SharedPtr < IConnection > connection, const System::ArrayPtr< System::String > & capabilityNames)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| capabilityNames | Array of capabilities which are supported by client |

---

## BeginClientCapabilities (5 of 6) {#beginclientcapabilities_5}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(System::SharedPtr < IConnection > connection, System::ArrayPtr< System::String > capabilityNames, System::AsyncCallback callback)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| capabilityNames | Array of capabilities which are supported by client |
| callback | References a method to be called when a corresponding asynchronous operation completes. |

---

## BeginClientCapabilities (6 of 6) {#beginclientcapabilities_6}

Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** System::IAsyncResult that represents the status of an asynchronous operation.

```cpp
BeginClientCapabilities(System::SharedPtr < IConnection > connection, System::ArrayPtr< System::String > capabilityNames, System::AsyncCallback callback, System::SharedPtr < System::Object > state)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| capabilityNames | Array of capabilities which are supported by client |
| callback | References a method to be called when a corresponding asynchronous operation completes. |
| state | The state. |

