---
title: ContactQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression that used by Exchange protocol.
type: docs
weight: 122
url: /java/com.aspose.email/contactquerybuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ContactQueryBuilder extends MailQueryBuilder
```

Represents the builder of search expression that used by Exchange protocol.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContactQueryBuilder()](#ContactQueryBuilder--) | Initializes a new instance of the  ContactQueryBuilder  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCreationTime()](#getCreationTime--) | Gets the field that allows to find items with a specified CreationTime. |
| [getDisplayName()](#getDisplayName--) | Gets the field that allows to find Contact that contain the specified string in the DisplayName field. |
| [getContactCreationTime()](#getContactCreationTime--) | Gets the field that allows to find items with a specified CreationTime. |
| [getContactDisplayName()](#getContactDisplayName--) | Gets the field that allows to find Contact that contain the specified string in the DisplayName field. |
### ContactQueryBuilder() {#ContactQueryBuilder--}
```
public ContactQueryBuilder()
```


Initializes a new instance of the  ContactQueryBuilder  class.

### getCreationTime() {#getCreationTime--}
```
public final DateComparisonField getCreationTime()
```


Gets the field that allows to find items with a specified CreationTime.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getDisplayName() {#getDisplayName--}
```
public final StringComparisonField getDisplayName()
```


Gets the field that allows to find Contact that contain the specified string in the DisplayName field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContactCreationTime() {#getContactCreationTime--}
```
public DateComparisonField getContactCreationTime()
```


Gets the field that allows to find items with a specified CreationTime.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getContactDisplayName() {#getContactDisplayName--}
```
public StringComparisonField getContactDisplayName()
```


Gets the field that allows to find Contact that contain the specified string in the DisplayName field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
