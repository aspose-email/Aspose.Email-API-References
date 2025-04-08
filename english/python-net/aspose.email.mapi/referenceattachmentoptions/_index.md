---
title: ReferenceAttachmentOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 810
url: /python-net/aspose.email.mapi/referenceattachmentoptions/
---

## ReferenceAttachmentOptions class

Represents configuration options for adding a reference attachment to a MAPI message.

The ReferenceAttachmentOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ReferenceAttachmentOptions(shared_link, url, provider_name)|Initializes a new instance of the ReferenceAttachmentOptions class|
## Properties
| Name | Description |
| :- | :- |
|shared_link|Gets or sets the shared link of the reference attachment.<br/>            This is the URL to the shared resource, such as a file on a cloud storage provider.|
|url|Gets or sets the direct URL for accessing the reference attachment.<br/>            This may point to the specific resource within the provider's interface.|
|provider_name|Gets or sets the name of the provider for the reference attachment.<br/>            Examples include "GoogleDrive", "OneDrive", etc.|
|permission_type|Gets or sets the permission type for the reference attachment.<br/>            Indicates the level of access granted.<br/>            The default value is AnyoneCanEdit.|
|original_permission_type|Gets or sets the original permission type for the reference attachment.<br/>            Used to specify the original permission level before any modifications.<br/>            The default value is None.|
|is_folder|Gets or sets a value indicating whether the reference attachment is a folder.<br/>            The default value is false.|
|provider_endpoint_url|Gets or sets the provider endpoint URL.<br/>            Typically used for specifying the base URL of the cloud provider API.<br/>            The default value is Empty.|
|preview_url|Gets or sets the preview URL of the reference attachment.<br/>            This URL can be used to generate a preview of the resource, if supported by the provider.<br/>            The default value is Empty.|
|thumbnail_url|Gets or sets the thumbnail URL of the reference attachment.<br/>            The URL points to a thumbnail image of the resource for visual representation.<br/>            The default value is Empty.|

### See Also

* namespace [aspose.email.mapi](/email/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/email/python-net/)

