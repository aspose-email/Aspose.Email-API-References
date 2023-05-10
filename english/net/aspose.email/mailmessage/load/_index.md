---
title: MailMessage.Load
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Load message from file
type: docs
weight: 20
url: /net/aspose.email/mailmessage/load/
---
## Load(string) {#load_2}

Load message from file

```csharp
public static MailMessage Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Message file name. The message file must be in eml or msg format. |

### Return Value

E-mail message

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Load message from stream

```csharp
public static MailMessage Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream that represents message in eml or msg format |

### Return Value

E-mail message

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Load message from file with additional options.

```csharp
public static MailMessage Load(string fileName, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Source file pathString. |
| options | LoadOptions | Additional options [`LoadOptions`](../../loadoptions/). |

### Return Value

Mail message[`MailMessage`](../).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *fileName* is null. |

### Examples

The following example shows how to load a Message with Load Options.

```csharp
[C#]

	// Load Eml, html, mhtml, msg and dat file 
	MailMessage.Load("Message.eml", new EmlLoadOptions());
        MailMessage.Load("description.html", new HtmlLoadOptions());
        MailMessage.Load("Message.mhtml", new MhtmlLoadOptions());
        MailMessage.Load("Message.msg", new MsgLoadOptions());

        // loading with custom options
        var emlLoadOptions = new EmlLoadOptions
        {
            PreferredTextEncoding = Encoding.UTF8,
            PreserveTnefAttachments = true
        };

        MailMessage.Load("description.html", emlLoadOptions);

        var htmlLoadOptions = new HtmlLoadOptions
        {
            PreferredTextEncoding = Encoding.UTF8,
            ShouldAddPlainTextView = true,
            PathToResources = htmlImagesFolder
        };

        MailMessage.Load("description.html", htmlLoadOptions);
```

```csharp
[VB.NET]

	' Load Eml, html, mhtml, msg and dat file
	Dim mailMessage As MailMessage = MailMessage.Load("Message.eml", New EmlLoadOptions())
	MailMessage.Load("description.html", New HtmlLoadOptions())
	MailMessage.Load("Message.mhtml", New MhtmlLoadOptions())
	MailMessage.Load("Message.msg", New MsgLoadOptions())

	' loading with custom options
	Dim emlLoadOptions As EmlLoadOptions = New EmlLoadOptions With {
	  .PrefferedTextEncoding = Encoding.UTF8,
		.PreserveTnefAttachments = True
	}

	MailMessage.Load("description.html", emlLoadOptions)
	
	Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions With {
		.PrefferedTextEncoding = Encoding.UTF8,
			.ShouldAddPlainTextView = True,
				.PathToResources = htmlImagesFolder
	}
					
	MailMessage.Load("description.html", emlLoadOptions)
```

### See Also

* class [LoadOptions](../../loadoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Load message from stream with additional options.

```csharp
public static MailMessage Load(Stream stream, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source streamStream. |
| options | LoadOptions | Additional options [`LoadOptions`](../../loadoptions/). |

### Return Value

Mail message[`MailMessage`](../).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *stream* is null. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


