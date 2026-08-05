---
title: "Aspose::Email::Attachment::Attachment constructor"
linktitle: "Attachment"
articleTitle: "Attachment"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the Attachment class."
type: docs
weight: 10
url: /cpp/aspose.email/attachment/attachment/
---

## Attachment (1 of 9) {#attachment_1}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of the file. |

---

## Attachment (2 of 9) {#attachment_2}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::String fileName, System::String mediaType)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of the file. |
| mediaType | Type media type name. |

---

## Attachment (3 of 9) {#attachment_3}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::String fileName, System::SharedPtr < Aspose::Email::Mime::ContentType > contentType)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of the file. |
| contentType | The ContentType . |

---

## Attachment (4 of 9) {#attachment_4}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::SharedPtr < System::IO::Stream > contentStream, System::String name)
```

| Parameter | Description |
| --- | --- |
| contentStream | The content stream of attachment. |
| name | The attachment name. |

---

## Attachment (5 of 9) {#attachment_5}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::SharedPtr < System::IO::Stream > contentStream, System::String name, System::String mediaType)
```

| Parameter | Description |
| --- | --- |
| contentStream | The content stream of attachment. |
| name | The attachment name. |
| mediaType | The media type name. |

---

## Attachment (6 of 9) {#attachment_6}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::SharedPtr < System::IO::Stream > contentStream, System::SharedPtr < Aspose::Email::Mime::ContentType > contentType)
```

| Parameter | Description |
| --- | --- |
| contentStream | The content stream of attachment. |
| contentType | The ContentType . |

---

## Attachment (7 of 9) {#attachment_7}

**Returns:** Aspose::Email::

```cpp
Attachment()
```

---

## Attachment (8 of 9) {#attachment_8}

**Returns:** Aspose::Email::

```cpp
Attachment(System::SharedPtr < System::IO::MemoryStream > content, System::SharedPtr < Aspose::Email::Mime::ContentType > contentType, System::String name, System::String contentLocation, System::String contentId)
```

| Parameter | Description |
| --- | --- |
| content |  |
| contentType |  |
| name |  |
| contentLocation |  |
| contentId |  |

---

## Attachment (9 of 9) {#attachment_9}

Initializes a new instance of the Attachment class.

**Returns:** Aspose::Email::

```cpp
Attachment(System::SharedPtr < Aspose::Email::Mime::MimePart > part)
```

| Parameter | Description |
| --- | --- |
| part | An attachment mime part |

