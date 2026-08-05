---
title: "Aspose::Email::Tools::Logging::LogEntry::LogEntry constructor"
linktitle: "LogEntry"
articleTitle: "LogEntry"
second_title: "Aspose.Email for C++"
description: "Initialize a new instance of a LogEntry class."
type: docs
weight: 10
url: /cpp/aspose.email.tools.logging/logentry/logentry/
---

## LogEntry (1 of 13) {#logentry_1}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry()
```

---

## LogEntry (2 of 13) {#logentry_2}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message)
```

| Parameter | Description |
| --- | --- |
| message | The message. |

---

## LogEntry (3 of 13) {#logentry_3}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::DateTime time)
```

| Parameter | Description |
| --- | --- |
| message | The message. |
| time | The time. |

---

## LogEntry (4 of 13) {#logentry_4}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::Exception innerException)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| innerException | The inner exception to log. |

---

## LogEntry (5 of 13) {#logentry_5}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::SharedPtr < LogLevel > severity)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| severity | Log entry severity as a Severity enumeration. (Unspecified, Information, Warning or Error). |

---

## LogEntry (6 of 13) {#logentry_6}

Initialize a new instance of a LogEntry class.

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::Exception innerException, System::SharedPtr < LogLevel > severity)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| innerException | The inner exception to log. |
| severity | Log entry severity as a Severity enumeration. (Unspecified, Information, Warning or Error). |

---

## LogEntry (7 of 13) {#logentry_7}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::SharedPtr < System::Collections::Generic::IDictionary< System::String, System::String >> properties)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| properties | Dictionary of key/value pairs to record. |

---

## LogEntry (8 of 13) {#logentry_8}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::ArrayPtr< uint8_t > binaryDataMessage)
```

| Parameter | Description |
| --- | --- |
| binaryDataMessage | Binary message body to log. |

---

## LogEntry (9 of 13) {#logentry_9}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::ArrayPtr< uint8_t > binaryDataMessage, System::SharedPtr < System::Text::Encoding > messageEncoding)
```

| Parameter | Description |
| --- | --- |
| binaryDataMessage | Binary message body to log. |
| messageEncoding | Encoding for binary message |

---

## LogEntry (10 of 13) {#logentry_10}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::ArrayPtr< uint8_t > binaryDataMessage, System::SharedPtr < System::Collections::Generic::IDictionary< System::String, System::String >> properties)
```

| Parameter | Description |
| --- | --- |
| binaryDataMessage | Binary message body to log. |
| properties | Dictionary of key/value pairs to record. |

---

## LogEntry (11 of 13) {#logentry_11}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::ArrayPtr< uint8_t > binaryDataMessage, System::SharedPtr < System::Text::Encoding > messageEncoding, System::SharedPtr < System::Collections::Generic::IDictionary< System::String, System::String >> properties)
```

| Parameter | Description |
| --- | --- |
| binaryDataMessage | Binary message body to log. |
| messageEncoding | Encoding for binary message |
| properties | Dictionary of key/value pairs to record. |

---

## LogEntry (12 of 13) {#logentry_12}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::SharedPtr < LogLevel > severity, System::String category, int32_t eventId, System::String title, System::SharedPtr < System::Collections::Generic::IDictionary< System::String, System::String >> properties)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| severity | Log entry severity as a Severity enumeration. (Unspecified, Information, Warning or Error). |
| category | Category name used to route the log entry to a one or more sinks. |
| eventId | Event number or identifier. |
| title | Additional description of the log entry message. |
| properties | Dictionary of key/value pairs to record. |

---

## LogEntry (13 of 13) {#logentry_13}

Create a new instance of LogEntry with a full set of constructor parameters

**Returns:** Aspose::Email::Tools::Logging::

```cpp
LogEntry(System::String message, System::Exception innerException, System::SharedPtr < LogLevel > severity, System::String category, int32_t eventId, System::String title, System::SharedPtr < System::Collections::Generic::IDictionary< System::String, System::String >> properties)
```

| Parameter | Description |
| --- | --- |
| message | Message body to log. Value from ToString() method from message object. |
| innerException | The inner exception to log. |
| severity | Log entry severity as a Severity enumeration. (Unspecified, Information, Warning or Error). |
| category | Category name used to route the log entry to a one or more sinks. |
| eventId | Event number or identifier. |
| title | Additional description of the log entry message. |
| properties | Dictionary of key/value pairs to record. |

