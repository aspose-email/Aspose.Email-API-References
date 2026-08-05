---
title: "Aspose::Email::Clients::Pop3::Pop3Client::ListMessages method"
linktitle: "ListMessages"
articleTitle: "ListMessages"
second_title: "Aspose.Email for C++"
description: "Lists the messages."
type: docs
weight: 530
url: /cpp/aspose.email.clients.pop3/pop3client/listmessages/
---

## ListMessages (1 of 14) {#listmessages_1}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages()
```

---

## ListMessages (2 of 14) {#listmessages_2}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(bool closeTransaction)
```

| Parameter | Description |
| --- | --- |
| closeTransaction | Indicates if current transaction has to be closed, before the list is retrieved. |

---

## ListMessages (3 of 14) {#listmessages_3}

Lists the messages.

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(Pop3ListFields fields)
```

| Parameter | Description |
| --- | --- |
| fields | The fields that we want get |

---

## ListMessages (4 of 14) {#listmessages_4}

Lists the messages.

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(Pop3ListFields fields, bool closeTransaction, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| fields | The fields that we want get |
| closeTransaction | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | The MailQuery object. |

---

## ListMessages (5 of 14) {#listmessages_5}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## ListMessages (6 of 14) {#listmessages_6}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, bool closeTransaction)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| closeTransaction | Indicates if current transaction has to be closed, before the list is retrieved. |

---

## ListMessages (7 of 14) {#listmessages_7}

Lists the messages.

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, Pop3ListFields fields)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fields | The fields that we want get |

---

## ListMessages (8 of 14) {#listmessages_8}

Lists the messages.

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, Pop3ListFields fields, bool closeTransaction, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| fields | The fields that we want get |
| closeTransaction | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | The MailQuery object. |

---

## ListMessages (9 of 14) {#listmessages_9}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |

---

## ListMessages (10 of 14) {#listmessages_10}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |

---

## ListMessages (11 of 14) {#listmessages_11}

Lists the messages.

**Returns:** Collection of Pop3MessageInfo objects.

```cpp
ListMessages(System::SharedPtr < IConnection > connection, System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| query | The MailQuery object. |

---

## ListMessages (12 of 14) {#listmessages_12}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< int32_t >> sequenceNumberLst)
```

| Parameter | Description |
| --- | --- |
| sequenceNumberLst | sequenceNumber list for Pop3MessageInfo to retrieve from a server. |

---

## ListMessages (13 of 14) {#listmessages_13}

Lists the messages. Gets an information for earch message

**Returns:** Pop3MessageInfoCollection

```cpp
ListMessages(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uniqueIdLst)
```

| Parameter | Description |
| --- | --- |
| uniqueIdLst | UniqueId list for Pop3MessageInfo to retrieve from a server. |

---

## ListMessages (14 of 14) {#listmessages_14}

Lists the messages.

**Returns:** Collection of Pop3MessageInfo objects.

```cpp
ListMessages(System::SharedPtr < Tools::Search::MailQuery > query)
```

| Parameter | Description |
| --- | --- |
| query | The MailQuery object. |

