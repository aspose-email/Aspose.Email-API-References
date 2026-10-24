---
title: MapiContactAddress
second_title: Aspose.Email for Java API Reference
description: Serves as the abstract base class for contact address types in MAPI contact items.
type: docs
weight: 438
url: /java/com.aspose.email/mapicontactaddress/
---

**Inheritance:**
java.lang.Object
```
public abstract class MapiContactAddress
```

Serves as the abstract base class for contact address types in MAPI contact items. This class provides common functionality for managing electronic addresses ([MapiContactElectronicAddress](../../com.aspose.email/mapicontactelectronicaddress)) and physical addresses ([MapiContactPhysicalAddress](../../com.aspose.email/mapicontactphysicaladdress)) through shared property access methods.

--------------------

This abstract class is designed to be inherited by concrete address type implementations. It provides helper methods like [getStringProperty(Object,String)](../../com.aspose.email/mapicontactaddress\#getStringProperty-Object-String-) and \{@link MapiContactAddress\#setStringProperty(Object,String,string&)\} for accessing MAPI properties, and [setStringNamedProperty(String,int)](../../com.aspose.email/mapicontactaddress\#setStringNamedProperty-String-int-) for working with named properties in the PSETID.Address property set. Do not instantiate this class directly. Use the derived classes to work with specific address types.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiContactAddress()](#MapiContactAddress--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiContactAddress() {#MapiContactAddress--}
```
public MapiContactAddress()
```


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

