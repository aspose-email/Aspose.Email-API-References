---
title: "Aspose::Email::Clients::Imap::ImapClient::CommitDeletes method"
linktitle: "CommitDeletes"
articleTitle: "CommitDeletes"
second_title: "Aspose.Email for C++"
description: "Commit the deletions"
type: docs
weight: 540
url: /cpp/aspose.email.clients.imap/imapclient/commitdeletes/
---

## CommitDeletes (1 of 10) {#commitdeletes_1}

Commit the deletions

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes()
```

---

## CommitDeletes (2 of 10) {#commitdeletes_2}

Commit the deletions

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(int32_t sleep)
```

| Parameter | Description |
| --- | --- |
| sleep | Wait time complete the operation in milliseconds |

---

## CommitDeletes (3 of 10) {#commitdeletes_3}

Commit the deletions

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## CommitDeletes (4 of 10) {#commitdeletes_4}

Commit the deletions

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < IConnection > connection, int32_t sleep)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| sleep | Wait time complete the operation in milliseconds |

---

## CommitDeletes (5 of 10) {#commitdeletes_5}

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < IConnection > connection, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uidSet | Set of unique identifiers for messages |

---

## CommitDeletes (6 of 10) {#commitdeletes_6}

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < IConnection > connection, System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## CommitDeletes (7 of 10) {#commitdeletes_7}

Commit the deletions

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < IConnection > connection, System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| uniqueId | The uid of a message |

---

## CommitDeletes (8 of 10) {#commitdeletes_8}

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> uidSet)
```

| Parameter | Description |
| --- | --- |
| uidSet | Set of unique identifiers for messages |

---

## CommitDeletes (9 of 10) {#commitdeletes_9}

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::String startUid, System::String endUid)
```

| Parameter | Description |
| --- | --- |
| startUid | The starting UID of a message list |
| endUid | The ending UID of a message list |

---

## CommitDeletes (10 of 10) {#commitdeletes_10}

Commit the deletions This method works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
CommitDeletes(System::String uniqueId)
```

| Parameter | Description |
| --- | --- |
| uniqueId | The uid of a message |

