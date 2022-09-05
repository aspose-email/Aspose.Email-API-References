---
title: GetMessageTrackingReportOptions
second_title: Aspose.Email for Java API Reference
description:  Represents options for GetMessageTrackingReport operation
type: docs
weight: 273
url: /java/com.aspose.email/getmessagetrackingreportoptions/
---
**Inheritance:**
java.lang.Object
```
public final class GetMessageTrackingReportOptions
```

Represents options for GetMessageTrackingReport operation
## Constructors

| Constructor | Description |
| --- | --- |
| [GetMessageTrackingReportOptions(String scope, String messageTrackingReportId)](#GetMessageTrackingReportOptions-java.lang.String-java.lang.String-) | Initializes a new instance of the [GetMessageTrackingReportOptions](../../com.aspose.email/getmessagetrackingreportoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [getScope()](#getScope--) | Gets or sets the search scope (non-empty string) |
| [setScope(String value)](#setScope-java.lang.String-) | Gets or sets the search scope (non-empty string) |
| [getReportTemplate()](#getReportTemplate--) | Gets or sets the type of report to get. |
| [setReportTemplate(int value)](#setReportTemplate-int-) | Gets or sets the type of report to get. |
| [getRecipientFilter()](#getRecipientFilter--) | Gets or sets a recipient address to use with the specified report. |
| [setRecipientFilter(MailAddress value)](#setRecipientFilter-com.aspose.email.MailAddress-) | Gets or sets a recipient address to use with the specified report. |
| [getMessageTrackingReportId()](#getMessageTrackingReportId--) | Gets or sets an identity string that was obtained from the FindMessageTrackingReport operation (non-empty string) |
| [setMessageTrackingReportId(String value)](#setMessageTrackingReportId-java.lang.String-) | Gets or sets an identity string that was obtained from the FindMessageTrackingReport operation (non-empty string) |
| [getReturnQueueEvents()](#getReturnQueueEvents--) | Gets or sets a value indicating whether the person who is running the task is in a privileged role. |
| [setReturnQueueEvents(boolean value)](#setReturnQueueEvents-boolean-) | Gets or sets a value indicating whether the person who is running the task is in a privileged role. |
| [getDiagnosticsLevel()](#getDiagnosticsLevel--) | Gets or sets a timing and performance information that will be used to derive the report. |
| [setDiagnosticsLevel(String value)](#setDiagnosticsLevel-java.lang.String-) | Gets or sets a timing and performance information that will be used to derive the report. |
### GetMessageTrackingReportOptions(String scope, String messageTrackingReportId) {#GetMessageTrackingReportOptions-java.lang.String-java.lang.String-}
```
public GetMessageTrackingReportOptions(String scope, String messageTrackingReportId)
```


Initializes a new instance of the [GetMessageTrackingReportOptions](../../com.aspose.email/getmessagetrackingreportoptions) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scope | java.lang.String | Specifies where to perform the search |
| messageTrackingReportId | java.lang.String | Specifies an identity string that was obtained from the FindMessageTrackingReport operation |

### getScope() {#getScope--}
```
public final String getScope()
```


Gets or sets the search scope (non-empty string)

**Returns:**
java.lang.String
### setScope(String value) {#setScope-java.lang.String-}
```
public final void setScope(String value)
```


Gets or sets the search scope (non-empty string)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReportTemplate() {#getReportTemplate--}
```
public final int getReportTemplate()
```


Gets or sets the type of report to get.

**Returns:**
int
### setReportTemplate(int value) {#setReportTemplate-int-}
```
public final void setReportTemplate(int value)
```


Gets or sets the type of report to get.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRecipientFilter() {#getRecipientFilter--}
```
public final MailAddress getRecipientFilter()
```


Gets or sets a recipient address to use with the specified report.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setRecipientFilter(MailAddress value) {#setRecipientFilter-com.aspose.email.MailAddress-}
```
public final void setRecipientFilter(MailAddress value)
```


Gets or sets a recipient address to use with the specified report.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getMessageTrackingReportId() {#getMessageTrackingReportId--}
```
public final String getMessageTrackingReportId()
```


Gets or sets an identity string that was obtained from the FindMessageTrackingReport operation (non-empty string)

**Returns:**
java.lang.String
### setMessageTrackingReportId(String value) {#setMessageTrackingReportId-java.lang.String-}
```
public final void setMessageTrackingReportId(String value)
```


Gets or sets an identity string that was obtained from the FindMessageTrackingReport operation (non-empty string)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReturnQueueEvents() {#getReturnQueueEvents--}
```
public final boolean getReturnQueueEvents()
```


Gets or sets a value indicating whether the person who is running the task is in a privileged role.

**Returns:**
boolean
### setReturnQueueEvents(boolean value) {#setReturnQueueEvents-boolean-}
```
public final void setReturnQueueEvents(boolean value)
```


Gets or sets a value indicating whether the person who is running the task is in a privileged role.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDiagnosticsLevel() {#getDiagnosticsLevel--}
```
public final String getDiagnosticsLevel()
```


Gets or sets a timing and performance information that will be used to derive the report.

**Returns:**
java.lang.String
### setDiagnosticsLevel(String value) {#setDiagnosticsLevel-java.lang.String-}
```
public final void setDiagnosticsLevel(String value)
```


Gets or sets a timing and performance information that will be used to derive the report.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

