---
title: "Aspose::Email::Mapi::MapiContact::Save method"
linktitle: "Save"
articleTitle: "Save"
second_title: "Aspose.Email for C++"
description: "Saves this MapiContact into the given stream with vCard format."
type: docs
weight: 160
url: /cpp/aspose.email.mapi/mapicontact/save/
---

## Save (1 of 6) {#save_1}

Saves this MapiContact into the given stream with vCard format. The supported vCard version is 2.1

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to save to |

---

## Save (2 of 6) {#save_2}

Saves this MapiContact to the given stream with a format using the default options. The supported save format is vCard

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::SharedPtr < System::IO::Stream > stream, Aspose::Email::Mapi::ContactSaveFormat saveFormat)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to save to |
| saveFormat | A save format |

---

## Save (3 of 6) {#save_3}

Saves this MapiContact to the given stream using specified save options. The supported save options is VCardSaveOptions

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < Aspose::Email::Mapi::ContactSaveOptions > saveOptions)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to save to |
| saveOptions | A save options |

---

## Save (4 of 6) {#save_4}

Saves this MapiContact to the vCard file with a default options. The supported vCard version is 2.1

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::String filePath)
```

| Parameter | Description |
| --- | --- |
| filePath | A vCard file name |

---

## Save (5 of 6) {#save_5}

Saves this MapiContact to the specified file with a format using the default options. The supported save format is vCard.

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::String filePath, Aspose::Email::Mapi::ContactSaveFormat saveFormat)
```

| Parameter | Description |
| --- | --- |
| filePath | A vCard file name |
| saveFormat | A save format |

---

## Save (6 of 6) {#save_6}

Saves this MapiContact into file using specified save options. The supported save options is VCardSaveOptions

**Returns:** void Aspose::Email::Mapi::

```cpp
Save(System::String filePath, System::SharedPtr < Aspose::Email::Mapi::ContactSaveOptions > saveOptions)
```

| Parameter | Description |
| --- | --- |
| filePath | A vCard file name |
| saveOptions | A save options |

