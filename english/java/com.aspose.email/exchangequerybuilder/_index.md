---
title: ExchangeQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression based on search filters that used by Exchange protocol.
type: docs
weight: 225
url: /java/com.aspose.email/exchangequerybuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ExchangeQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression based on search filters that used by Exchange protocol.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeQueryBuilder()](#ExchangeQueryBuilder--) | Initializes a new instance of the [ExchangeQueryBuilder](../../com.aspose.email/exchangequerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [getItemSize()](#getItemSize--) | Gets the field that allows to find items with a specified size. |
| [getAttachmentName()](#getAttachmentName--) | Gets the field that allows to find items with a specified attachment name. |
| [getTaskStatus()](#getTaskStatus--) | Gets the field that allows to find tasks that contains the specified status. |
| [getMessageId()](#getMessageId--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field. |
| [getContentClass()](#getContentClass--) | Gets items with an specified content class. |
| [getExtendedProperties()](#getExtendedProperties--) |  |
| [getAppointment()](#getAppointment--) | Gets object with appointment properties to create query |
| [getContact()](#getContact--) | Gets object with contact properties to create query |
| [hasFlags(int flags)](#hasFlags-int-) | Search messages with the specified flags. |
| [hasNoFlags(int flags)](#hasNoFlags-int-) | Search messages with the unspecified flags. |
### ExchangeQueryBuilder() {#ExchangeQueryBuilder--}
```
public ExchangeQueryBuilder()
```


Initializes a new instance of the [ExchangeQueryBuilder](../../com.aspose.email/exchangequerybuilder) class.

### getItemSize() {#getItemSize--}
```
public final IntComparisonField getItemSize()
```


Gets the field that allows to find items with a specified size.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getAttachmentName() {#getAttachmentName--}
```
public final StringComparisonField getAttachmentName()
```


Gets the field that allows to find items with a specified attachment name.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTaskStatus() {#getTaskStatus--}
```
public final EnumComparisonField getTaskStatus()
```


Gets the field that allows to find tasks that contains the specified status. Server compatibility: Exchange 2010 and higher

**Returns:**
[EnumComparisonField](../../com.aspose.email/enumcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents MessageId search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContentClass() {#getContentClass--}
```
public final StringComparisonField getContentClass()
```


Gets items with an specified content class.

Value: The [StringComparisonField](../../com.aspose.email/stringcomparisonfield) that represents a content class.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getExtendedProperties() {#getExtendedProperties--}
```
public final ExtendedPropertiesComparisonField getExtendedProperties()
```


Value: Gets dictionary with pairs of property descriptors and comparison field to search by extended properties.

**Returns:**
[ExtendedPropertiesComparisonField](../../com.aspose.email/extendedpropertiescomparisonfield)
### getAppointment() {#getAppointment--}
```
public final AppointmentQueryBuilder getAppointment()
```


Gets object with appointment properties to create query

**Returns:**
[AppointmentQueryBuilder](../../com.aspose.email/appointmentquerybuilder)
### getContact() {#getContact--}
```
public final ContactQueryBuilder getContact()
```


Gets object with contact properties to create query

**Returns:**
[ContactQueryBuilder](../../com.aspose.email/contactquerybuilder)
### hasFlags(int flags) {#hasFlags-int-}
```
public final MailQuery hasFlags(int flags)
```


Search messages with the specified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(int flags) {#hasNoFlags-int-}
```
public final MailQuery hasNoFlags(int flags)
```


Search messages with the unspecified flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | The flags. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
