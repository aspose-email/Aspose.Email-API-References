---
title: PostalAddressCategory
second_title: Aspose.Email for Android via Java API Reference
description:  Represents category for a postal address
type: docs
weight: 350
url: /java/com.aspose.email/postaladdresscategory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class PostalAddressCategory implements System.IEquatable<PostalAddressCategory>
```

Represents category for a postal address
## Constructors

| Constructor | Description |
| --- | --- |
| [PostalAddressCategory(String description)](#PostalAddressCategory-java.lang.String-) | Initializes a new instance of the [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) class with 'Custom' category. |
## Fields

| Field | Description |
| --- | --- |
| [HOME_VALUE](#HOME-VALUE) | String value for 'Home' category |
| [WORK_VALUE](#WORK-VALUE) | String value for 'Work' category |
| [CUSTOM_VALUE](#CUSTOM-VALUE) | String value for 'Custom' category |
## Methods

| Method | Description |
| --- | --- |
| [getHome()](#getHome--) | Defines a type of an address as a home address. |
| [getWork()](#getWork--) | Defines a type of an address as a work address. |
| [getCustom()](#getCustom--) | Defines a type of an address as an address of type other. |
| [getValue()](#getValue--) | Gets category of a postal address |
| [getDescription()](#getDescription--) | Gets description for the 'Custom' category of a postal address |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [op_Equality(PostalAddressCategory a, PostalAddressCategory b)](#op-Equality-com.aspose.email.PostalAddressCategory-com.aspose.email.PostalAddressCategory-) | Determines whether the specified objects are equal. |
| [op_Inequality(PostalAddressCategory a, PostalAddressCategory b)](#op-Inequality-com.aspose.email.PostalAddressCategory-com.aspose.email.PostalAddressCategory-) | Determines whether the specified objects are not equal. |
| [equals(PostalAddressCategory other)](#equals-com.aspose.email.PostalAddressCategory-) | Determines whether the specified object is equal to the current object. |
### PostalAddressCategory(String description) {#PostalAddressCategory-java.lang.String-}
```
public PostalAddressCategory(String description)
```


Initializes a new instance of the [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) class with 'Custom' category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Description for the 'Custom' category of a postal address |

### HOME_VALUE {#HOME-VALUE}
```
public static final String HOME_VALUE
```


String value for 'Home' category

### WORK_VALUE {#WORK-VALUE}
```
public static final String WORK_VALUE
```


String value for 'Work' category

### CUSTOM_VALUE {#CUSTOM-VALUE}
```
public static final String CUSTOM_VALUE
```


String value for 'Custom' category

### getHome() {#getHome--}
```
public static PostalAddressCategory getHome()
```


Defines a type of an address as a home address.

**Returns:**
[PostalAddressCategory](../../com.aspose.email/postaladdresscategory)
### getWork() {#getWork--}
```
public static PostalAddressCategory getWork()
```


Defines a type of an address as a work address.

**Returns:**
[PostalAddressCategory](../../com.aspose.email/postaladdresscategory)
### getCustom() {#getCustom--}
```
public static PostalAddressCategory getCustom()
```


Defines a type of an address as an address of type other.

**Returns:**
[PostalAddressCategory](../../com.aspose.email/postaladdresscategory)
### getValue() {#getValue--}
```
public final String getValue()
```


Gets category of a postal address

**Returns:**
java.lang.String
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets description for the 'Custom' category of a postal address

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### op_Equality(PostalAddressCategory a, PostalAddressCategory b) {#op-Equality-com.aspose.email.PostalAddressCategory-com.aspose.email.PostalAddressCategory-}
```
public static boolean op_Equality(PostalAddressCategory a, PostalAddressCategory b)
```


Determines whether the specified objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) | First object to compare |
| b | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) | Second object to compare |

**Returns:**
boolean - Returns true if objects are equal, otherwise false.
### op_Inequality(PostalAddressCategory a, PostalAddressCategory b) {#op-Inequality-com.aspose.email.PostalAddressCategory-com.aspose.email.PostalAddressCategory-}
```
public static boolean op_Inequality(PostalAddressCategory a, PostalAddressCategory b)
```


Determines whether the specified objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) | First object to compare |
| b | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) | Second object to compare |

**Returns:**
boolean - Returns true if objects are not equal, otherwise false.
### equals(PostalAddressCategory other) {#equals-com.aspose.email.PostalAddressCategory-}
```
public boolean equals(PostalAddressCategory other)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PostalAddressCategory](../../com.aspose.email/postaladdresscategory) | The object to compare with the current object. |

**Returns:**
boolean - true if the specified object is equal to the current object; otherwise, false.
