---
title: VCardContact.LoadAsMultiple
second_title: Aspose.Email for .NET API Reference
description: VCardContact method. Loads list of contacts from multi contact stream
type: docs
weight: 170
url: /net/aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple/
---
## LoadAsMultiple(string, Encoding, CancellationToken) {#loadasmultiple_7}

Loads list of contacts from multi contact stream.

```csharp
public static List<VCardContact> LoadAsMultiple(string filePath, Encoding encoding, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| encoding | Encoding | Stream data encoding,if null then UTF8 will be used. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

List of contacs

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsMultiple(Stream, Encoding, CancellationToken) {#loadasmultiple_3}

Loads list of contacts from multi contact stream.

```csharp
public static List<VCardContact> LoadAsMultiple(Stream stream, Encoding encoding, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source stream |
| encoding | Encoding | Stream data encoding,if null then UTF8 will be used. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

List of contacs

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsMultiple(Stream) {#loadasmultiple}

Loads list of contacts from multi contact stream.

```csharp
public static List<VCardContact> LoadAsMultiple(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source stream |

### Return Value

List of contacs

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsMultiple(Stream, VCardLoadOptions) {#loadasmultiple_1}

Loads list of contacts from multi contact stream.

```csharp
public static List<VCardContact> LoadAsMultiple(Stream stream, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source stream |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

### Return Value

List of contacts

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if stream is null |
| NotSupportedException | Throws if the stream is not readable |

### See Also

* class [VCardLoadOptions](../../vcardloadoptions/)
* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsMultiple(string) {#loadasmultiple_4}

Loads list of contacts from multi contact file.

```csharp
public static List<VCardContact> LoadAsMultiple(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Source file |

### Return Value

List of contacts

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsMultiple(string, VCardLoadOptions) {#loadasmultiple_5}

```csharp
public static List<VCardContact> LoadAsMultiple(string filePath, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Source file |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

### Return Value

List of contacts

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws if filePath is null or empty |

### See Also

* class [VCardLoadOptions](../../vcardloadoptions/)
* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)


