---
title: MboxToPst
second_title: Aspose.Email for .NET API Reference
description: Converts an Mbox storage to PST.
type: docs
weight: 20
url: /net/aspose.email.storage/mailstorageconverter/mboxtopst/
---
## MboxToPst(string, string) {#mboxtopst_6}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(string mboxFileName, string pstFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | String | Mbox file name. |
| pstFileName | String | PST file name. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *mboxFileName* is null or empty. |
| ArgumentException | If *pstFileName* is null or empty. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(string, string, MailHandler) {#mboxtopst_7}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(string mboxFileName, string pstFileName, 
    MailHandler mailHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | String | Mbox file name. |
| pstFileName | String | PST file name. |
| mailHandler | MailHandler | The [`MailHandler`](../../mailstorageconverter.mailhandler) delegate is called for each message that is read from Mbox. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *mboxFileName* is null or empty. |
| ArgumentException | If *pstFileName* is null or empty. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MailHandler](../../mailstorageconverter.mailhandler)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(Stream, string) {#mboxtopst_2}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(Stream mboxrdDataStream, string pstFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | Stream | A Stream that represents data in Mbox format. |
| pstFileName | String | PST file name. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *mboxrdDataStream* is null. |
| ArgumentException | If *pstFileName* is null or empty. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(Stream, string, MailHandler) {#mboxtopst_3}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(Stream mboxrdDataStream, string pstFileName, 
    MailHandler mailHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | Stream | A Stream that represents data in Mbox format. |
| pstFileName | String | PST file name. |
| mailHandler | MailHandler | The [`MailHandler`](../../mailstorageconverter.mailhandler) delegate is called for each message that is read from Mbox. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *mboxrdDataStream* is null. |
| ArgumentException | If *pstFileName* is null or empty. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MailHandler](../../mailstorageconverter.mailhandler)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(string, Stream) {#mboxtopst_4}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(string mboxFileName, Stream pstDataStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | String | Mbox file name. |
| pstDataStream | Stream | A Stream that represents data in Pst format. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *mboxFileName* is null or empty. |
| ArgumentNullException | If *pstDataStream* is null. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(string, Stream, MailHandler) {#mboxtopst_5}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(string mboxFileName, Stream pstDataStream, 
    MailHandler mailHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | String | Mbox file name. |
| pstDataStream | Stream | A Stream that represents data in Pst format. |
| mailHandler | MailHandler | The [`MailHandler`](../../mailstorageconverter.mailhandler) delegate is called for each message that is read from Mbox. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | If *mboxFileName* is null or empty. |
| ArgumentNullException | If *pstDataStream* is null. |

### Remarks

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MailHandler](../../mailstorageconverter.mailhandler)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(Stream, Stream) {#mboxtopst}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(Stream mboxrdDataStream, Stream pstDataStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | Stream | A Stream that represents data in Mbox format. |
| pstDataStream | Stream | A Stream that represents data in Pst format. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *mboxrdDataStream* is null. |
| ArgumentNullException | If *pstDataStream* is null. |

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(Stream, Stream, MailHandler) {#mboxtopst_1}

Converts an Mbox storage to PST.

```csharp
public static PersonalStorage MboxToPst(Stream mboxrdDataStream, Stream pstDataStream, 
    MailHandler mailHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | Stream | A Stream that represents data in Mbox format. |
| pstDataStream | Stream | A Stream that represents data in Pst format. |
| mailHandler | MailHandler | The [`MailHandler`](../../mailstorageconverter.mailhandler) delegate is called for each message that is read from Mbox. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *mboxrdDataStream* is null. |
| ArgumentNullException | If *pstDataStream* is null. |

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MailHandler](../../mailstorageconverter.mailhandler)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

---

## MboxToPst(MboxStorageReader, PersonalStorage, string, MailHandler) {#mboxtopst_8}

Converts an Mbox storage to PST.

```csharp
public static void MboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, 
    string pstFolderName, MailHandler mailHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mboxStorageReader | MboxStorageReader | An [`MboxStorageReader`](../../../aspose.email.storage.mbox/mboxstoragereader) that represents an mbox-based mail storage reader. |
| pst | PersonalStorage | A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) that represents a pst storage. |
| pstFolderName | String | The folder name, at the root of the pst, where Mbox messages will be added. If this folder doesn't exist, it will be created. If the folder exists and isn't empty, new messages will be added to the existing ones. |
| mailHandler | MailHandler | The [`MailHandler`](../../mailstorageconverter.mailhandler) delegate is called for each message that is read from Mbox. |

### Return Value

A [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) object that represents the converted storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *mboxStorageReader* is null. |
| ArgumentNullException | If *pst* is null. |

### See Also

* class [MboxStorageReader](../../../aspose.email.storage.mbox/mboxstoragereader)
* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MailHandler](../../mailstorageconverter.mailhandler)
* class [MailStorageConverter](../../mailstorageconverter)
* namespace [Aspose.Email.Storage](../../mailstorageconverter)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
