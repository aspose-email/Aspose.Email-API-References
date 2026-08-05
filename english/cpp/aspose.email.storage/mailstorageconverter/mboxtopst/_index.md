---
title: "Aspose::Email::Storage::MailStorageConverter::MboxToPst method"
linktitle: "MboxToPst"
articleTitle: "MboxToPst"
second_title: "Aspose.Email for C++"
description: "Converts an Mbox storage to PST."
type: docs
weight: 30
url: /cpp/aspose.email.storage/mailstorageconverter/mboxtopst/
---

## MboxToPst (1 of 12) {#mboxtopst_1}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::SharedPtr < Mbox::MboxStorageReader > mboxStorageReader, System::SharedPtr < Pst::PersonalStorage > pst, System::String pstFolderName, MailStorageConverter::MailHandler mailHandler)
```

| Parameter | Description |
| --- | --- |
| mboxStorageReader | An MboxStorageReader that represents an mbox-based mail storage reader. |
| pst | A PersonalStorage that represents a pst storage. |
| pstFolderName | The folder name, at the root of the pst, where Mbox messages will be added. If this folder doesn't exist, it will be created. If the folder exists and isn't empty, new messages will be added to the existing ones. |
| mailHandler | The MailHandler delegate is called for each message that is read from Mbox . |

---

## MboxToPst (2 of 12) {#mboxtopst_2}

Converts an Mbox storage to PST.

**Returns:** static void Aspose::Email::Storage::

```cpp
MboxToPst(System::SharedPtr < Mbox::MboxStorageReader > mboxStorageReader, System::SharedPtr < Pst::PersonalStorage > pst, System::String pstFolderName, System::SharedPtr < MboxToPstConversionOptions > options)
```

| Parameter | Description |
| --- | --- |
| mboxStorageReader | An MboxStorageReader that represents an mbox-based mail storage reader. |
| pst | A PersonalStorage that represents a pst storage. |
| pstFolderName | The folder name, at the root of the pst, where Mbox messages will be added. If this folder doesn't exist, it will be created. If the folder exists and isn't empty, new messages will be added to the existing ones. |
| options | An MboxToPstConversionOptions additional options when converting from Mbox to PST |

---

## MboxToPst (3 of 12) {#mboxtopst_3}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::SharedPtr < System::IO::Stream > mboxrdDataStream, System::SharedPtr < System::IO::Stream > pstDataStream)
```

| Parameter | Description |
| --- | --- |
| mboxrdDataStream | A Stream that represents data in Mbox format. |
| pstDataStream | A Stream that represents data in Pst format. |

---

## MboxToPst (4 of 12) {#mboxtopst_4}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::SharedPtr < System::IO::Stream > mboxrdDataStream, System::SharedPtr < System::IO::Stream > pstDataStream, MailStorageConverter::MailHandler mailHandler)
```

| Parameter | Description |
| --- | --- |
| mboxrdDataStream | A Stream that represents data in Mbox format. |
| pstDataStream | A Stream that represents data in Pst format. |
| mailHandler | The MailHandler delegate is called for each message that is read from Mbox . |

---

## MboxToPst (5 of 12) {#mboxtopst_5}

Converts an Mbox storage to PST.

**Returns:** static System::SharedPtr < Pst::PersonalStorage > Aspose::Email::Storage::

```cpp
MboxToPst(System::SharedPtr < System::IO::Stream > mboxrdDataStream, System::SharedPtr < System::IO::Stream > pstDataStream, System::SharedPtr < MboxToPstConversionOptions > options)
```

| Parameter | Description |
| --- | --- |
| mboxrdDataStream | A Stream that represents data in Mbox format. |
| pstDataStream | A Stream that represents data in Pst format. |
| options | An MboxToPstConversionOptions additional options when converting from Mbox to PST |

---

## MboxToPst (6 of 12) {#mboxtopst_6}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::SharedPtr < System::IO::Stream > mboxrdDataStream, System::String pstFileName)
```

| Parameter | Description |
| --- | --- |
| mboxrdDataStream | A Stream that represents data in Mbox format. |
| pstFileName | PST file name. |

---

## MboxToPst (7 of 12) {#mboxtopst_7}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::SharedPtr < System::IO::Stream > mboxrdDataStream, System::String pstFileName, MailStorageConverter::MailHandler mailHandler)
```

| Parameter | Description |
| --- | --- |
| mboxrdDataStream | A Stream that represents data in Mbox format. |
| pstFileName | PST file name. |
| mailHandler | The MailHandler delegate is called for each message that is read from Mbox . |

---

## MboxToPst (8 of 12) {#mboxtopst_8}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::String mboxFileName, System::SharedPtr < System::IO::Stream > pstDataStream)
```

| Parameter | Description |
| --- | --- |
| mboxFileName | Mbox file name. |
| pstDataStream | A Stream that represents data in Pst format. |

---

## MboxToPst (9 of 12) {#mboxtopst_9}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::String mboxFileName, System::SharedPtr < System::IO::Stream > pstDataStream, MailStorageConverter::MailHandler mailHandler)
```

| Parameter | Description |
| --- | --- |
| mboxFileName | Mbox file name. |
| pstDataStream | A Stream that represents data in Pst format. |
| mailHandler | The MailHandler delegate is called for each message that is read from Mbox . |

---

## MboxToPst (10 of 12) {#mboxtopst_10}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::String mboxFileName, System::String pstFileName)
```

| Parameter | Description |
| --- | --- |
| mboxFileName | Mbox file name. |
| pstFileName | PST file name. |

---

## MboxToPst (11 of 12) {#mboxtopst_11}

Converts an Mbox storage to PST.

**Returns:** A PersonalStorage object that represents the converted storage.

```cpp
MboxToPst(System::String mboxFileName, System::String pstFileName, MailStorageConverter::MailHandler mailHandler)
```

| Parameter | Description |
| --- | --- |
| mboxFileName | Mbox file name. |
| pstFileName | PST file name. |
| mailHandler | The MailHandler delegate is called for each message that is read from Mbox . |

---

## MboxToPst (12 of 12) {#mboxtopst_12}

Converts an Mbox storage to PST.

**Returns:** static System::SharedPtr < Pst::PersonalStorage > Aspose::Email::Storage::

```cpp
MboxToPst(System::String mboxFileName, System::String pstFileName, System::SharedPtr < MboxToPstConversionOptions > options)
```

| Parameter | Description |
| --- | --- |
| mboxFileName | Mbox file name. |
| pstFileName | PST file name. |
| options | An MboxToPstConversionOptions additional options when converting from Mbox to PST |

