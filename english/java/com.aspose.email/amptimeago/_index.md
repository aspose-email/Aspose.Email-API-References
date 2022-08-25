---
title: AmpTimeago
second_title: Aspose.Email for Java API Reference
description:  Provides fuzzy timestamps by formatting dates as X time ago
type: docs
weight: 27
url: /java/com.aspose.email/amptimeago/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpTimeago extends AmpComponent
```

Provides fuzzy timestamps by formatting dates as "X time ago"
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpTimeago(Date dateTime)](#AmpTimeago-java.util.Date-) | Create instance of AmpTimeago. |
| [AmpTimeago(Date dateTime, int width, int height)](#AmpTimeago-java.util.Date-int-int-) | Create instance of AmpTimeago. |
## Methods

| Method | Description |
| --- | --- |
| [getDateTime()](#getDateTime--) | A datetime. |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | A datetime. |
| [getLocale()](#getLocale--) | By default, the local is set to en; however, you can specify other locales. |
| [setLocale(String value)](#setLocale-java.lang.String-) | By default, the local is set to en; however, you can specify other locales. |
| [getCutoff()](#getCutoff--) | Display the original date if time distance is older than cutoff (seconds). |
| [setCutoff(int value)](#setCutoff-int-) | Display the original date if time distance is older than cutoff (seconds). |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
### AmpTimeago(Date dateTime) {#AmpTimeago-java.util.Date-}
```
public AmpTimeago(Date dateTime)
```


Create instance of AmpTimeago.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date |  |

### AmpTimeago(Date dateTime, int width, int height) {#AmpTimeago-java.util.Date-int-int-}
```
public AmpTimeago(Date dateTime, int width, int height)
```


Create instance of AmpTimeago.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date |  |
| width | int |  |
| height | int |  |

### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


A datetime.

**Returns:**
java.util.Date
### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


A datetime.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLocale() {#getLocale--}
```
public final String getLocale()
```


By default, the local is set to en; however, you can specify other locales. See full list of supported locales https://amp.dev/documentation/components/amp-timeago/?format=email

**Returns:**
java.lang.String
### setLocale(String value) {#setLocale-java.lang.String-}
```
public final void setLocale(String value)
```


By default, the local is set to en; however, you can specify other locales. See full list of supported locales https://amp.dev/documentation/components/amp-timeago/?format=email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCutoff() {#getCutoff--}
```
public final int getCutoff()
```


Display the original date if time distance is older than cutoff (seconds).

**Returns:**
int
### setCutoff(int value) {#setCutoff-int-}
```
public final void setCutoff(int value)
```


Display the original date if time distance is older than cutoff (seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


Required script that muct be added to head section.

**Returns:**
java.lang.String
### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


Represents amp html version of component.

**Returns:**
java.lang.String - 
### toHtml() {#toHtml--}
```
public String toHtml()
```


Represents html version of component.

**Returns:**
java.lang.String - 
