---
title: TemplateEngine
second_title: Aspose.Email for Java API Reference
description:  This class uses specified template to construct E-Mail messages.
type: docs
weight: 662
url: /java/com.aspose.email/templateengine/
---
**Inheritance:**
java.lang.Object
```
public final class TemplateEngine
```

This class uses specified template to construct E-Mail messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [TemplateEngine(String fileName)](#TemplateEngine-java.lang.String-) | Initializes a new instance of the [TemplateEngine](../../com.aspose.email/templateengine) class. |
| [TemplateEngine(MailMessage templateMessage)](#TemplateEngine-com.aspose.email.MailMessage-) | Initializes a new instance of the [TemplateEngine](../../com.aspose.email/templateengine) class. |
## Methods

| Method | Description |
| --- | --- |
| [registerRoutine(String name, TemplateRoutine routine)](#registerRoutine-java.lang.String-com.aspose.email.TemplateRoutine-) | Registers the template routine to the temaplate engine. |
| [isRoutineRegistered(String name)](#isRoutineRegistered-java.lang.String-) | Determines if a name of template routine is registered in the template engine. |
| [unregisterRoutine(String name)](#unregisterRoutine-java.lang.String-) | Unregister the template routine from the template engine by name. |
| [merge(MailMessage source)](#merge-com.aspose.email.MailMessage-) | Merge a source MailMessage with the template |
| [merge(DataRow row)](#merge-com.aspose.email.DataRow-) | Merge a source DataRow with the template. |
| [reset()](#reset--) | Resets this instance. |
| [instantiate(DataTable table, DataColumnMappingCollection mappings)](#instantiate-com.aspose.email.DataTable-com.aspose.email.DataColumnMappingCollection-) | Instantiates the template with a DataTable as datasource. |
| [instantiate(DataTable table)](#instantiate-com.aspose.email.DataTable-) | Instantiates the template with a DataTable as datasource. |
| [instantiate(DataRowCollection rows, DataColumnMappingCollection mappings)](#instantiate-com.aspose.email.DataRowCollection-com.aspose.email.DataColumnMappingCollection-) | Instantiates the template with a DataRowCollection as datasource. |
| [instantiate(DataRowCollection rows)](#instantiate-com.aspose.email.DataRowCollection-) | Instantiates the template with a DataRowCollection as datasource. |
| [instantiate(IDataReader reader)](#instantiate-com.aspose.email.IDataReader-) | Instantiates the template with a IDataReader as datasource. |
### TemplateEngine(String fileName) {#TemplateEngine-java.lang.String-}
```
public TemplateEngine(String fileName)
```


Initializes a new instance of the [TemplateEngine](../../com.aspose.email/templateengine) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### TemplateEngine(MailMessage templateMessage) {#TemplateEngine-com.aspose.email.MailMessage-}
```
public TemplateEngine(MailMessage templateMessage)
```


Initializes a new instance of the [TemplateEngine](../../com.aspose.email/templateengine) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templateMessage | [MailMessage](../../com.aspose.email/mailmessage) | The template message. |

### registerRoutine(String name, TemplateRoutine routine) {#registerRoutine-java.lang.String-com.aspose.email.TemplateRoutine-}
```
public final void registerRoutine(String name, TemplateRoutine routine)
```


Registers the template routine to the temaplate engine.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the funciton. |
| routine | [TemplateRoutine](../../com.aspose.email/templateroutine) | Delegate processing the data |

### isRoutineRegistered(String name) {#isRoutineRegistered-java.lang.String-}
```
public final boolean isRoutineRegistered(String name)
```


Determines if a name of template routine is registered in the template engine.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name that is used to register the template routine. |

**Returns:**
boolean - Returns True if the name is registered in the template engine, otherwise returns False.
### unregisterRoutine(String name) {#unregisterRoutine-java.lang.String-}
```
public final void unregisterRoutine(String name)
```


Unregister the template routine from the template engine by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name that is used to unregister the template routine. |

### merge(MailMessage source) {#merge-com.aspose.email.MailMessage-}
```
public final MailMessage merge(MailMessage source)
```


Merge a source MailMessage with the template

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [MailMessage](../../com.aspose.email/mailmessage) | The source MailMessage |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The MailMessage merged with template
### merge(DataRow row) {#merge-com.aspose.email.DataRow-}
```
public final MailMessage merge(DataRow row)
```


Merge a source DataRow with the template.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.aspose.email/datarow) | The source DataRow. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The MailMessage merged with template.
### reset() {#reset--}
```
public final void reset()
```


Resets this instance.

### instantiate(DataTable table, DataColumnMappingCollection mappings) {#instantiate-com.aspose.email.DataTable-com.aspose.email.DataColumnMappingCollection-}
```
public final MailMessageCollection instantiate(DataTable table, DataColumnMappingCollection mappings)
```


Instantiates the template with a DataTable as datasource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.aspose.email/datatable) | The DataTable, which contains the source data to instantiate the template. |
| mappings | [DataColumnMappingCollection](../../com.aspose.email/datacolumnmappingcollection) | The IColumnMappingCollection, which represents the mapping between the source column in DataTable and target field in template |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A MailMessageCollection that generated by the template and the datasource.
### instantiate(DataTable table) {#instantiate-com.aspose.email.DataTable-}
```
public final MailMessageCollection instantiate(DataTable table)
```


Instantiates the template with a DataTable as datasource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.aspose.email/datatable) | The DataTable, which contains the source data to instantiate the template. |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A MailMessageCollection that generated by the template and the datasource.
### instantiate(DataRowCollection rows, DataColumnMappingCollection mappings) {#instantiate-com.aspose.email.DataRowCollection-com.aspose.email.DataColumnMappingCollection-}
```
public final MailMessageCollection instantiate(DataRowCollection rows, DataColumnMappingCollection mappings)
```


Instantiates the template with a DataRowCollection as datasource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rows | [DataRowCollection](../../com.aspose.email/datarowcollection) | The DataRowCollection, which contains the source data to instantiate the template. |
| mappings | [DataColumnMappingCollection](../../com.aspose.email/datacolumnmappingcollection) | The IColumnMappingCollection, which represents the mapping between the source column in data source and target field in template |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A MailMessageCollection that generated by the template and the datasource.
### instantiate(DataRowCollection rows) {#instantiate-com.aspose.email.DataRowCollection-}
```
public final MailMessageCollection instantiate(DataRowCollection rows)
```


Instantiates the template with a DataRowCollection as datasource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rows | [DataRowCollection](../../com.aspose.email/datarowcollection) | The DataRowCollection, which contains the source data to instantiate the template. |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A MailMessageCollection that generated by the template and the datasource.
### instantiate(IDataReader reader) {#instantiate-com.aspose.email.IDataReader-}
```
public final MailMessageCollection instantiate(IDataReader reader)
```


Instantiates the template with a IDataReader as datasource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reader | [IDataReader](../../com.aspose.email/idatareader) | The IDataReader, which will provide the source data to instantiate the template. |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A MailMessageCollection that generated by the template and the datasource.
