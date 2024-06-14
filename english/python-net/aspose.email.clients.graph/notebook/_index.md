---
title: Notebook
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 170
url: /python-net/aspose.email.clients.graph/notebook/
---

## Notebook class

https://docs.microsoft.com/en-us/graph/api/resources/notebook?view=graph-rest-1.0<br/>            A OneNote notebook.

The Notebook type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Notebook()|Initializes a new instance of the Notebook class|
## Properties
| Name | Description |
| :- | :- |
|created_by|Identity of the user, device, and application which created the item.<br/>            Read-only.|
|created_date_time|The date and time when the notebook was created.<br/>            The timestamp represents date and time information using ISO 8601 format and is always in UTC time.<br/>            For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. <br/>            Read-only.|
|is_created_date_time_specified|Indicates whether CreatedDateTime property is specified.|
|id|The unique identifier of the notebook. <br/>            Read-only.|
|is_default|Indicates whether this is the user's default notebook. <br/>            Read-only.|
|is_default_specified|Indicates whether IsDefault property is specified.|
|is_shared|Indicates whether the notebook is shared.<br/>            If true, the contents of the notebook can be seen by people other than the owner. <br/>            Read-only.|
|is_shared_specified|Indicates whether IsShared property is specified.|
|last_modified_by|Identity of the user, device, and application which created the item. <br/>            Read-only.|
|last_modified_date_time|The date and time when the notebook was last modified. <br/>            The timestamp represents date and time information using ISO 8601 format and is always in UTC time.<br/>            For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. <br/>            Read-only.|
|is_last_modified_date_time_specified|Indicates whether LastModifiedDateTime property is specified.|
|links|Links for opening the notebook.<br/>            The oneNoteClientURL link opens the notebook in the OneNote native client if it's installed. <br/>            The oneNoteWebURL link opens the notebook in OneNote on the web.|
|display_name|The name of the notebook.|
|section_groups_url|The URL for the sectionGroups navigation property, which returns all the section groups in the notebook. <br/>            Read-only.|
|sections_url|The URL for the sections navigation property, which returns all the sections in the notebook. <br/>            Read-only.|
|self|The endpoint where you can get details about the notebook. <br/>            Read-only.|
|user_role|Possible values are: Owner, Contributor, Reader, None.<br/>            Owner represents owner-level access to the notebook.<br/>            Contributor represents read/write access to the notebook.<br/>            Reader represents read-only access to the notebook.<br/>            Read-only.|

### See Also

* namespace [aspose.email.clients.graph](/email/python-net/aspose.email.clients.graph/)
* assembly [Aspose.Email](/email/python-net/)

