---
title: AmpTimeago
second_title: Aspose.Email for Android via Java API Reference
description: Provides fuzzy timestamps by formatting dates as X time ago
type: docs
weight: 23
url: /androidjava/com.aspose.email/amptimeago/
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP provides a set of common attributes that are extended to many AMP components. |
| [getClass()](#getClass--) |  |
| [getCutoff()](#getCutoff--) | Display the original date if time distance is older than cutoff (seconds). |
| [getDateTime()](#getDateTime--) | A datetime. |
| [getFallback()](#getFallback--) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [getLocale()](#getLocale--) | By default, the local is set to en; however, you can specify other locales. |
| [getPlaceholder()](#getPlaceholder--) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCutoff(int value)](#setCutoff-int-) | Display the original date if time distance is older than cutoff (seconds). |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | A datetime. |
| [setFallback(String value)](#setFallback-java.lang.String-) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [setLocale(String value)](#setLocale-java.lang.String-) | By default, the local is set to en; however, you can specify other locales. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP provides a set of common attributes that are extended to many AMP components.

**Returns:**
[AmpAttributes](../../com.aspose.email/ampattributes)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCutoff() {#getCutoff--}
```
public final int getCutoff()
```


Display the original date if time distance is older than cutoff (seconds).

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


A datetime.

**Returns:**
java.util.Date
### getFallback() {#getFallback--}
```
public final String getFallback()
```


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Returns:**
java.lang.String
### getLocale() {#getLocale--}
```
public final String getLocale()
```


By default, the local is set to en; however, you can specify other locales. See full list of supported locales https://amp.dev/documentation/components/amp-timeago/?format=email

**Returns:**
java.lang.String
### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


Required script that muct be added to head section.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCutoff(int value) {#setCutoff-int-}
```
public final void setCutoff(int value)
```


Display the original date if time distance is older than cutoff (seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


A datetime.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocale(String value) {#setLocale-java.lang.String-}
```
public final void setLocale(String value)
```


By default, the local is set to en; however, you can specify other locales. See full list of supported locales https://amp.dev/documentation/components/amp-timeago/?format=email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

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
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

