---
title: MailMessage.Save
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Save message as a file
type: docs
weight: 560
url: /net/aspose.email/mailmessage/save/
---
## Save(string) {#save_2}

Save message as a file

```csharp
public virtual void Save(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of a file to save message. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Save(string, SaveOptions) {#save_3}

Save message as a file with additional options.

```csharp
public virtual void Save(string fileName, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Stream into which message is saved. |
| options | SaveOptions | Additional options for saving[`SaveOptions`](../../saveoptions/). |

### Examples

The following example shows how to save an email message as HTML without embedding resources.

```csharp
[C#]

        var fileName = "EmailWithAttachEmbedded.eml";
        var eml = MailMessage.Load(fileName);

        var options = new HtmlSaveOptions()
        {
            ResourceRenderingMode = ResourceRenderingMode.EmbedIntoHtml,
            SaveResourceHandler =
                (AttachmentBase attachment, out string resourcePath) =>
                {
                    attachment.Save(attachment.ContentId);
                    resourcePath = Path.Combine(".", attachment.ContentId);
                }
        };

        eml.Save($"{fileName}.html", options);
```

```csharp
[VB.NET]

	Dim fileName = "EmailWithAttachEmbedded.eml"
        Dim eml = MailMessage.Load(fileName)
	
        Dim options = New HtmlSaveOptions() With {
            .ResourceRenderingMode = ResourceRenderingMode.EmbedIntoHtml,
            .SaveResourceHandler = Function(ByVal attachment As AttachmentBase, <Out> ByRef resourcePath As String)
                                       attachment.Save(attachment.ContentId)
                                       resourcePath = Path.Combine(".", attachment.ContentId)
                                   End Function
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

Save message as a stream with additional options.

```csharp
public virtual void Save(Stream stream, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream into which message is saved. |
| options | SaveOptions | Additional options for saving[`SaveOptions`](../../saveoptions/). |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Save message as a stream

```csharp
public virtual void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream into which message is saved |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


