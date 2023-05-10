---
title: Class TemplateEngine
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Tools.Merging.TemplateEngine class. This class uses specified template to construct EMail messages
type: docs
weight: 20650
url: /net/aspose.email.tools.merging/templateengine/
---
## TemplateEngine class

This class uses specified template to construct E-Mail messages.

```csharp
public sealed class TemplateEngine
```

## Constructors

| Name | Description |
| --- | --- |
| [TemplateEngine](templateengine/#constructor)(MailMessage) | Initializes a new instance of the `TemplateEngine` class. |
| [TemplateEngine](templateengine/#constructor_1)(string) | Initializes a new instance of the `TemplateEngine` class. |

## Methods

| Name | Description |
| --- | --- |
| [GetTemplateFields](../../aspose.email.tools.merging/templateengine/gettemplatefields/)() | Get list of template field names. |
| [Instantiate](../../aspose.email.tools.merging/templateengine/instantiate/#instantiate)(DataRowCollection) | Instantiates the template with a DataRowCollection as datasource. |
| [Instantiate](../../aspose.email.tools.merging/templateengine/instantiate/#instantiate_2)(DataTable) | Instantiates the template with a DataTable as datasource. |
| [Instantiate](../../aspose.email.tools.merging/templateengine/instantiate/#instantiate_4)(IDataReader) | Instantiates the template with a IDataReader as datasource. |
| [Instantiate](../../aspose.email.tools.merging/templateengine/instantiate/#instantiate_1)(DataRowCollection, IColumnMappingCollection) | Instantiates the template with a DataRowCollection as datasource. |
| [Instantiate](../../aspose.email.tools.merging/templateengine/instantiate/#instantiate_3)(DataTable, IColumnMappingCollection) | Instantiates the template with a DataTable as datasource. |
| [IsRoutineRegistered](../../aspose.email.tools.merging/templateengine/isroutineregistered/)(string) | Determines if a name of template routine is registered in the template engine. |
| [Merge](../../aspose.email.tools.merging/templateengine/merge/#merge_1)(DataRow) | Merge a source DataRow with the template. |
| [Merge](../../aspose.email.tools.merging/templateengine/merge/#merge)(MailMessage) | Merge a source MailMessage with the template |
| [RegisterRoutine](../../aspose.email.tools.merging/templateengine/registerroutine/)(string, TemplateRoutine) | Registers the template routine to the temaplate engine. |
| [Reset](../../aspose.email.tools.merging/templateengine/reset/)() | Resets this instance. |
| [UnregisterRoutine](../../aspose.email.tools.merging/templateengine/unregisterroutine/)(string) | Unregister the template routine from the template engine by name. |

### See Also

* namespace [Aspose.Email.Tools.Merging](../../aspose.email.tools.merging/)
* assembly [Aspose.Email](../../)


