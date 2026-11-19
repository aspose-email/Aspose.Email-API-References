---
title: AppointmentFormattingOptions
second_title: Aspose.Email for Java API Reference
description: Templates that  uses to render the details of an appointment as plain text or HTML.
type: docs
weight: 38
url: /java/com.aspose.email/appointmentformattingoptions/
---

**Inheritance:**
java.lang.Object
```
public class AppointmentFormattingOptions
```

Templates that [Appointment.getAppointmentText(AppointmentFormattingOptions)](../../com.aspose.email/appointment\#getAppointmentText-AppointmentFormattingOptions-) uses to render the details of an appointment as plain text or HTML.

Each template is a composite format string in which  \{0\}  is replaced by the value, for example  Location: \{0\} . A new instance holds the plain-text templates;  createAsHtml()  returns one with HTML templates. Setting a template to  null  or an empty string keeps the current one.
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentFormattingOptions()](#AppointmentFormattingOptions--) | Initializes a new instance of the [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) class with the plain-text templates. |
## Methods

| Method | Description |
| --- | --- |
| [createAsHtml()](#createAsHtml--) | Creates formatting options with the HTML templates. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | Gets markup to add to the head of the HTML output, typically a  |
| [getDescriptionFormat()](#getDescriptionFormat--) | Gets the template for the description. |
| [getEndDateFormat()](#getEndDateFormat--) | Gets the template for the end date and time. |
| [getLocationFormat()](#getLocationFormat--) | Gets the template for the location. |
| [getOrganizerFormat()](#getOrganizerFormat--) | Gets the template for the organizer. |
| [getStartDateFormat()](#getStartDateFormat--) | Gets the template for the start date and time. |
| [getTimezoneFormat()](#getTimezoneFormat--) | Gets the template for the time zone. |
| [getTitleFormat()](#getTitleFormat--) | Gets the template for the title (the summary of the appointment). |
| [hashCode()](#hashCode--) |  |
| [isTextFormat()](#isTextFormat--) | Gets a value indicating whether the templates produce plain text rather than HTML. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Sets markup to add to the head of the HTML output, typically a  |
| [setDescriptionFormat(String value)](#setDescriptionFormat-java.lang.String-) | Sets the template for the description. |
| [setEndDateFormat(String value)](#setEndDateFormat-java.lang.String-) | Sets the template for the end date and time. |
| [setLocationFormat(String value)](#setLocationFormat-java.lang.String-) | Sets the template for the location. |
| [setOrganizerFormat(String value)](#setOrganizerFormat-java.lang.String-) | Sets the template for the organizer. |
| [setStartDateFormat(String value)](#setStartDateFormat-java.lang.String-) | Sets the template for the start date and time. |
| [setTimezoneFormat(String value)](#setTimezoneFormat-java.lang.String-) | Sets the template for the time zone. |
| [setTitleFormat(String value)](#setTitleFormat-java.lang.String-) | Sets the template for the title (the summary of the appointment). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentFormattingOptions() {#AppointmentFormattingOptions--}
```
public AppointmentFormattingOptions()
```


Initializes a new instance of the [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) class with the plain-text templates.

### createAsHtml() {#createAsHtml--}
```
public static AppointmentFormattingOptions createAsHtml()
```


Creates formatting options with the HTML templates.

**Returns:**
[AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) - Formatting options that render the appointment as HTML.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


Gets markup to add to the head of the HTML output, typically a 

**Returns:**
java.lang.String - The markup, inserted as is. It is used only with the HTML templates.
### getDescriptionFormat() {#getDescriptionFormat--}
```
public final String getDescriptionFormat()
```


Gets the template for the description.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the description.
### getEndDateFormat() {#getEndDateFormat--}
```
public final String getEndDateFormat()
```


Gets the template for the end date and time.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the end date and time. The plain-text default is  EndTime: \{0\} .
### getLocationFormat() {#getLocationFormat--}
```
public final String getLocationFormat()
```


Gets the template for the location.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the location. The plain-text default is  Location: \{0\} .
### getOrganizerFormat() {#getOrganizerFormat--}
```
public final String getOrganizerFormat()
```


Gets the template for the organizer.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the organizer. The plain-text default is  Organizer: \{0\} .
### getStartDateFormat() {#getStartDateFormat--}
```
public final String getStartDateFormat()
```


Gets the template for the start date and time.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the start date and time. The plain-text default is  StartTime: \{0\} .
### getTimezoneFormat() {#getTimezoneFormat--}
```
public final String getTimezoneFormat()
```


Gets the template for the time zone.

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the time zone. The plain-text default is  Time Zone: \{0\} .
### getTitleFormat() {#getTitleFormat--}
```
public final String getTitleFormat()
```


Gets the template for the title (the summary of the appointment).

**Returns:**
java.lang.String - A composite format string in which  \{0\}  is replaced by the title. The plain-text default is  Title: \{0\} .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTextFormat() {#isTextFormat--}
```
public final boolean isTextFormat()
```


Gets a value indicating whether the templates produce plain text rather than HTML.

**Returns:**
boolean -  true  for the plain-text templates;  false  for the HTML templates.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


Sets markup to add to the head of the HTML output, typically a 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The markup, inserted as is. It is used only with the HTML templates. |

### setDescriptionFormat(String value) {#setDescriptionFormat-java.lang.String-}
```
public final void setDescriptionFormat(String value)
```


Sets the template for the description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the description. |

### setEndDateFormat(String value) {#setEndDateFormat-java.lang.String-}
```
public final void setEndDateFormat(String value)
```


Sets the template for the end date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the end date and time. The plain-text default is  EndTime: \{0\} . |

### setLocationFormat(String value) {#setLocationFormat-java.lang.String-}
```
public final void setLocationFormat(String value)
```


Sets the template for the location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the location. The plain-text default is  Location: \{0\} . |

### setOrganizerFormat(String value) {#setOrganizerFormat-java.lang.String-}
```
public final void setOrganizerFormat(String value)
```


Sets the template for the organizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the organizer. The plain-text default is  Organizer: \{0\} . |

### setStartDateFormat(String value) {#setStartDateFormat-java.lang.String-}
```
public final void setStartDateFormat(String value)
```


Sets the template for the start date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the start date and time. The plain-text default is  StartTime: \{0\} . |

### setTimezoneFormat(String value) {#setTimezoneFormat-java.lang.String-}
```
public final void setTimezoneFormat(String value)
```


Sets the template for the time zone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the time zone. The plain-text default is  Time Zone: \{0\} . |

### setTitleFormat(String value) {#setTitleFormat-java.lang.String-}
```
public final void setTitleFormat(String value)
```


Sets the template for the title (the summary of the appointment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A composite format string in which  \{0\}  is replaced by the title. The plain-text default is  Title: \{0\} . |

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

