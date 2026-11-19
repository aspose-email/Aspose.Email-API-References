---
title: MapiContactElectronicAddressPropertySet
second_title: Aspose.Email for Java API Reference
description: The e-mail addresses Email1 Email2 Email3 and fax numbers primary business home of a contact.
type: docs
weight: 441
url: /java/com.aspose.email/mapicontactelectronicaddresspropertyset/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiContactPropertySet](../../com.aspose.email/mapicontactpropertyset)
```
public final class MapiContactElectronicAddressPropertySet extends MapiContactPropertySet
```

The e-mail addresses (Email1, Email2, Email3) and fax numbers (primary, business, home) of a contact.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiContactElectronicAddressPropertySet()](#MapiContactElectronicAddressPropertySet--) | Initializes a new instance of the [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) class. |
| [MapiContactElectronicAddressPropertySet(MapiPropertyCollection properties)](#MapiContactElectronicAddressPropertySet-com.aspose.email.MapiPropertyCollection-) | Initializes a new instance of the [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) class from contact properties. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBusinessFax()](#getBusinessFax--) | Gets the business fax number. |
| [getClass()](#getClass--) |  |
| [getDefaultEmailAddress()](#getDefaultEmailAddress--) | Gets the address used as \#getEmail1().getEmail1() when the contact has no address and \#getUseAutocomplete().getUseAutocomplete() is  true . |
| [getEmail1()](#getEmail1--) | Gets the first e-mail address. |
| [getEmail2()](#getEmail2--) | Gets the second e-mail address. |
| [getEmail3()](#getEmail3--) | Gets the third e-mail address. |
| [getHomeFax()](#getHomeFax--) | Gets the home fax number. |
| [getPrimaryFax()](#getPrimaryFax--) | Gets the primary fax number. |
| [getUseAutocomplete()](#getUseAutocomplete--) | Gets a value indicating whether \#getDefaultEmailAddress().getDefaultEmailAddress() is used when the contact has no address. |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether no address is set. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBusinessFax(MapiContactElectronicAddress value)](#setBusinessFax-com.aspose.email.MapiContactElectronicAddress-) | Sets the business fax number. |
| [setDefaultEmailAddress(MapiContactElectronicAddress value)](#setDefaultEmailAddress-com.aspose.email.MapiContactElectronicAddress-) | Sets the address used as \#getEmail1().getEmail1() when the contact has no address and \#getUseAutocomplete().getUseAutocomplete() is  true . |
| [setEmail1(MapiContactElectronicAddress value)](#setEmail1-com.aspose.email.MapiContactElectronicAddress-) | Sets the first e-mail address. |
| [setEmail2(MapiContactElectronicAddress value)](#setEmail2-com.aspose.email.MapiContactElectronicAddress-) | Sets the second e-mail address. |
| [setEmail3(MapiContactElectronicAddress value)](#setEmail3-com.aspose.email.MapiContactElectronicAddress-) | Sets the third e-mail address. |
| [setHomeFax(MapiContactElectronicAddress value)](#setHomeFax-com.aspose.email.MapiContactElectronicAddress-) | Sets the home fax number. |
| [setPrimaryFax(MapiContactElectronicAddress value)](#setPrimaryFax-com.aspose.email.MapiContactElectronicAddress-) | Sets the primary fax number. |
| [setUseAutocomplete(boolean value)](#setUseAutocomplete-boolean-) | Sets a value indicating whether \#getDefaultEmailAddress().getDefaultEmailAddress() is used when the contact has no address. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiContactElectronicAddressPropertySet() {#MapiContactElectronicAddressPropertySet--}
```
public MapiContactElectronicAddressPropertySet()
```


Initializes a new instance of the [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) class.

### MapiContactElectronicAddressPropertySet(MapiPropertyCollection properties) {#MapiContactElectronicAddressPropertySet-com.aspose.email.MapiPropertyCollection-}
```
public MapiContactElectronicAddressPropertySet(MapiPropertyCollection properties)
```


Initializes a new instance of the [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) class from contact properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties that contain the addresses. |

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
### getBusinessFax() {#getBusinessFax--}
```
public final MapiContactElectronicAddress getBusinessFax()
```


Gets the business fax number.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultEmailAddress() {#getDefaultEmailAddress--}
```
public final MapiContactElectronicAddress getDefaultEmailAddress()
```


Gets the address used as \#getEmail1().getEmail1() when the contact has no address and \#getUseAutocomplete().getUseAutocomplete() is  true .

Exchange Server needs an address to create a contact; this one is used when a contact without addresses is created through EWS.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getEmail1() {#getEmail1--}
```
public final MapiContactElectronicAddress getEmail1()
```


Gets the first e-mail address.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getEmail2() {#getEmail2--}
```
public final MapiContactElectronicAddress getEmail2()
```


Gets the second e-mail address.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getEmail3() {#getEmail3--}
```
public final MapiContactElectronicAddress getEmail3()
```


Gets the third e-mail address.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getHomeFax() {#getHomeFax--}
```
public final MapiContactElectronicAddress getHomeFax()
```


Gets the home fax number.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getPrimaryFax() {#getPrimaryFax--}
```
public final MapiContactElectronicAddress getPrimaryFax()
```


Gets the primary fax number.

**Returns:**
[MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)
### getUseAutocomplete() {#getUseAutocomplete--}
```
public final boolean getUseAutocomplete()
```


Gets a value indicating whether \#getDefaultEmailAddress().getDefaultEmailAddress() is used when the contact has no address. The default is  true .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Gets a value indicating whether no address is set.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBusinessFax(MapiContactElectronicAddress value) {#setBusinessFax-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setBusinessFax(MapiContactElectronicAddress value)
```


Sets the business fax number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setDefaultEmailAddress(MapiContactElectronicAddress value) {#setDefaultEmailAddress-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setDefaultEmailAddress(MapiContactElectronicAddress value)
```


Sets the address used as \#getEmail1().getEmail1() when the contact has no address and \#getUseAutocomplete().getUseAutocomplete() is  true .

Exchange Server needs an address to create a contact; this one is used when a contact without addresses is created through EWS.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setEmail1(MapiContactElectronicAddress value) {#setEmail1-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setEmail1(MapiContactElectronicAddress value)
```


Sets the first e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setEmail2(MapiContactElectronicAddress value) {#setEmail2-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setEmail2(MapiContactElectronicAddress value)
```


Sets the second e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setEmail3(MapiContactElectronicAddress value) {#setEmail3-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setEmail3(MapiContactElectronicAddress value)
```


Sets the third e-mail address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setHomeFax(MapiContactElectronicAddress value) {#setHomeFax-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setHomeFax(MapiContactElectronicAddress value)
```


Sets the home fax number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setPrimaryFax(MapiContactElectronicAddress value) {#setPrimaryFax-com.aspose.email.MapiContactElectronicAddress-}
```
public final void setPrimaryFax(MapiContactElectronicAddress value)
```


Sets the primary fax number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress) |  |

### setUseAutocomplete(boolean value) {#setUseAutocomplete-boolean-}
```
public final void setUseAutocomplete(boolean value)
```


Sets a value indicating whether \#getDefaultEmailAddress().getDefaultEmailAddress() is used when the contact has no address. The default is  true .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

