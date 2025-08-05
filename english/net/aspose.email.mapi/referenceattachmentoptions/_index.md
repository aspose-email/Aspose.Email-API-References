---
title: Class ReferenceAttachmentOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.ReferenceAttachmentOptions class. Represents configuration options for adding a reference attachment to a MAPI message
type: docs
weight: 17780
url: /net/aspose.email.mapi/referenceattachmentoptions/
---
## ReferenceAttachmentOptions class

Represents configuration options for adding a reference attachment to a MAPI message.

```csharp
public class ReferenceAttachmentOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ReferenceAttachmentOptions](referenceattachmentoptions/)(string, string, string) | Initializes a new instance of the `ReferenceAttachmentOptions` class with the specified shared link, URL, and provider name. |

## Properties

| Name | Description |
| --- | --- |
| [IsFolder](../../aspose.email.mapi/referenceattachmentoptions/isfolder/) { get; set; } | Gets or sets a value indicating whether the reference attachment is a folder. The default value is **false**. |
| [OriginalPermissionType](../../aspose.email.mapi/referenceattachmentoptions/originalpermissiontype/) { get; set; } | Gets or sets the original permission type for the reference attachment. Used to specify the original permission level before any modifications. The default value is **None**. |
| [PermissionType](../../aspose.email.mapi/referenceattachmentoptions/permissiontype/) { get; set; } | Gets or sets the permission type for the reference attachment. Indicates the level of access granted. The default value is **AnyoneCanEdit**. |
| [PreviewUrl](../../aspose.email.mapi/referenceattachmentoptions/previewurl/) { get; set; } | Gets or sets the preview URL of the reference attachment. This URL can be used to generate a preview of the resource, if supported by the provider. The default value is **Empty**. |
| [ProviderEndpointUrl](../../aspose.email.mapi/referenceattachmentoptions/providerendpointurl/) { get; set; } | Gets or sets the provider endpoint URL. Typically used for specifying the base URL of the cloud provider API. The default value is **Empty**. |
| [ProviderName](../../aspose.email.mapi/referenceattachmentoptions/providername/) { get; set; } | Gets or sets the name of the provider for the reference attachment. Examples include "GoogleDrive", "OneDrive", etc. |
| [SharedLink](../../aspose.email.mapi/referenceattachmentoptions/sharedlink/) { get; set; } | Gets or sets the shared link of the reference attachment. This is the URL to the shared resource, such as a file on a cloud storage provider. |
| [ThumbnailUrl](../../aspose.email.mapi/referenceattachmentoptions/thumbnailurl/) { get; set; } | Gets or sets the thumbnail URL of the reference attachment. The URL points to a thumbnail image of the resource for visual representation. The default value is **Empty**. |
| [Url](../../aspose.email.mapi/referenceattachmentoptions/url/) { get; set; } | Gets or sets the direct URL for accessing the reference attachment. This may point to the specific resource within the provider's interface. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


