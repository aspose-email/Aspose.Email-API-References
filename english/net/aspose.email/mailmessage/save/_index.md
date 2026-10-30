---
title: MailMessage.Save
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Saves the message to a file in EML format whatever the file extension
type: docs
weight: 550
url: /net/aspose.email/mailmessage/save/
---
## Save(string) {#save_2}

Saves the message to a file in EML format, whatever the file extension.

```csharp
public virtual void Save(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to write. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Save(string, SaveOptions) {#save_3}

Saves the message to a file in the format selected by the options.

```csharp
public virtual void Save(string fileName, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to write. |
| options | SaveOptions | The options; their class selects the format, such as [`MsgSaveOptions`](../../msgsaveoptions/) or [`MhtSaveOptions`](../../mhtsaveoptions/). |

## Examples

The following example shows how to save an email message as HTML with embedded images.

[C#]

```csharp
var fileName = "EmailWithAttachEmbedded.eml";
var eml = MailMessage.Load(fileName);

var options = new HtmlSaveOptions()
{
    ResourceRenderingMode = ResourceRenderingMode.EmbedIntoHtml
};

eml.Save($"{fileName}.html", options);
```

[Visual Basic]

```csharp
Dim fileName = "EmailWithAttachEmbedded.eml"
Dim eml = MailMessage.Load(fileName)

Dim options = New HtmlSaveOptions() With {
    .ResourceRenderingMode = ResourceRenderingMode.EmbedIntoHtml
}

eml.Save($"{fileName}.html", options)
```

### See Also

* class [SaveOptions](../../saveoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, SaveOptions) {#save_1}

Saves the message to a stream in the format selected by the options.

```csharp
public virtual void Save(Stream stream, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| options | SaveOptions | The options; their class selects the format, such as [`MsgSaveOptions`](../../msgsaveoptions/) or [`MhtSaveOptions`](../../mhtsaveoptions/). |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves the message to a stream in EML format.

```csharp
public virtual void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


