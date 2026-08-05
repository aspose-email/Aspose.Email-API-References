---
title: "Aspose::Email::Storage::Pst::PersonalStorage::FromStream method"
linktitle: "FromStream"
articleTitle: "FromStream"
second_title: "Aspose.Email for C++"
description: "Load PST from stream."
type: docs
weight: 200
url: /cpp/aspose.email.storage.pst/personalstorage/fromstream/
---

## FromStream (1 of 3) {#fromstream_1}

Load PST from stream.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromStream(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | The System.IO.Stream. |

---

## FromStream (2 of 3) {#fromstream_2}

Load PST from stream.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromStream(System::SharedPtr < System::IO::Stream > stream, bool writable)
```

| Parameter | Description |
| --- | --- |
| stream | The System.IO.Stream. |
| writable | if set to true then the the pst will support writing, otherwise it will be opened in read-only mode. |

---

## FromStream (3 of 3) {#fromstream_3}

Load PST from stream.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromStream(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < PersonalStorageLoadOptions > loadOptions)
```

| Parameter | Description |
| --- | --- |
| stream | The System.IO.Stream. |
| loadOptions | The load options. |

