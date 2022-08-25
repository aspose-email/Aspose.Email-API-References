---
title: HeadersFormattingOptions
second_title: Aspose.Email for Java API Reference
description:  Allows to specify headers formatting options when saving MailMessage to Mhtml or Html format.
type: docs
weight: 291
url: /java/com.aspose.email/headersformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public abstract class HeadersFormattingOptions extends SaveOptions
```

Allows to specify headers formatting options when saving MailMessage to Mhtml or Html format.
## Constructors

| Constructor | Description |
| --- | --- |
| [HeadersFormattingOptions()](#HeadersFormattingOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |
## Methods

| Method | Description |
| --- | --- |
| [getRenderedContactFields()](#getRenderedContactFields--) | Defines groups of Contact fields which will be included in output mhtml. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Defines groups of Contact fields which will be included in output mhtml. |
| [getCssStyles()](#getCssStyles--) | Gets or sets the additional css styles for the formatter. |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Gets or sets the additional css styles for the formatter. |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | Default page header format. |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | Default page header format. |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | Default header line format. |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | Default header line format. |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | Before headers format. |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | Before headers format. |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | After headers format. |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | After headers format. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the format templates. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Gets list of headers for rendering. |
### HeadersFormattingOptions() {#HeadersFormattingOptions--}
```
public HeadersFormattingOptions()
```


Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format.

### getRenderedContactFields() {#getRenderedContactFields--}
```
public final int getRenderedContactFields()
```


Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting.

**Returns:**
int
### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


Gets or sets the additional css styles for the formatter.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


Gets or sets the additional css styles for the formatter.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultPageHeaderFormat() {#getDefaultPageHeaderFormat--}
```
public final String getDefaultPageHeaderFormat()
```


Default page header format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### setDefaultPageHeaderFormat(String value) {#setDefaultPageHeaderFormat-java.lang.String-}
```
public final void setDefaultPageHeaderFormat(String value)
```


Default page header format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultHeaderFormat() {#getDefaultHeaderFormat--}
```
public final String getDefaultHeaderFormat()
```


Default header line format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### setDefaultHeaderFormat(String value) {#setDefaultHeaderFormat-java.lang.String-}
```
public final void setDefaultHeaderFormat(String value)
```


Default header line format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBeforeHeadersFormat() {#getBeforeHeadersFormat--}
```
public final String getBeforeHeadersFormat()
```


Before headers format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### setBeforeHeadersFormat(String value) {#setBeforeHeadersFormat-java.lang.String-}
```
public final void setBeforeHeadersFormat(String value)
```


Before headers format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAfterHeadersFormat() {#getAfterHeadersFormat--}
```
public final String getAfterHeadersFormat()
```


After headers format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### setAfterHeadersFormat(String value) {#setAfterHeadersFormat-java.lang.String-}
```
public final void setAfterHeadersFormat(String value)
```


After headers format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Gets the format templates.

Value: The format templates.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getRenderingHeaders() {#getRenderingHeaders--}
```
public final List<String> getRenderingHeaders()
```


Gets list of headers for rendering.

**Returns:**
java.util.List<java.lang.String>
