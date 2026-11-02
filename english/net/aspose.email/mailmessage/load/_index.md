---
title: MailMessage.Load
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Loads a message from a file. MSG is recognized automatically any other file is read as EML
type: docs
weight: 20
url: /net/aspose.email/mailmessage/load/
---
## Load(string) {#load_2}

Loads a message from a file. MSG is recognized automatically; any other file is read as EML.

```csharp
public static MailMessage Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |
| [FormatNotSupportedException](../../formatnotsupportedexception/) | The format of the data is not supported. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a message from a stream. MSG is recognized automatically; any other data is read as EML.

```csharp
public static MailMessage Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| [FormatNotSupportedException](../../formatnotsupportedexception/) | The format of the data is not supported. |

### See Also

* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Loads a message from a file in the format selected by the options.

```csharp
public static MailMessage Load(string fileName, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| options | LoadOptions | The options; their class selects the format, such as [`EmlLoadOptions`](../../emlloadoptions/) or [`MsgLoadOptions`](../../msgloadoptions/). |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null`. |
| [FormatNotSupportedException](../../formatnotsupportedexception/) | The format of the data is not supported. |

## Examples

The following example shows how to load a Message with Load Options.

[C#]

```csharp
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

[Visual Basic]

```csharp
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

Loads a message from a stream in the format selected by the options.

```csharp
public static MailMessage Load(Stream stream, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |
| options | LoadOptions | The options; their class selects the format, such as [`EmlLoadOptions`](../../emlloadoptions/) or [`MsgLoadOptions`](../../msgloadoptions/). |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| [FormatNotSupportedException](../../formatnotsupportedexception/) | The format of the data is not supported. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


