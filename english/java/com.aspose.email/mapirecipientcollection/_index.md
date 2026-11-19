---
title: MapiRecipientCollection
second_title: Aspose.Email for Java API Reference
description: The recipients of an Outlook item.
type: docs
weight: 488
url: /java/com.aspose.email/mapirecipientcollection/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection
```
public class MapiRecipientCollection extends System.Collections.ObjectModel.Collection<MapiRecipient>
```

The recipients of an Outlook item.

This example adds To, CC and BCC recipients to a message.

```

 try (MapiMessage msg = new MapiMessage("from@domain.com", "to@domain.com", "Report", "The report is attached.")) {
     msg.getRecipients().add("cc@domain.com", "Copy Recipient", MapiRecipientType.MAPI_CC);
     msg.getRecipients().add("bcc@domain.com", "Hidden Recipient", MapiRecipientType.MAPI_BCC);

     for (MapiRecipient recipient : msg.getRecipients()) {
         System.out.println(recipient.getRecipientType() + ": " + recipient.getDisplayName()
                 + " <" + recipient.getEmailAddress() + ">");
     }

     msg.save("report.msg");
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiRecipientCollection()](#MapiRecipientCollection--) | Initializes a new instance of the [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) class. |
## Methods

| Method | Description |
| --- | --- |
| [add(String address, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-int-) | Adds a recipient. |
| [add(String address, String addressType, String displayName, int recipientType)](#add-java.lang.String-java.lang.String-java.lang.String-int-) | Adds a recipient with an address of the specified type. |
| [addItem(T arg0)](#addItem-T-) |  |
| [addMapiRecipient(MapiRecipient item)](#addMapiRecipient-com.aspose.email.MapiRecipient-) | Adds an existing recipient to the end of the collection. |
| [clear()](#clear--) |  |
| [containsItem(T arg0)](#containsItem-T-) |  |
| [copyToTArray(T[] arg0, int arg1)](#copyToTArray-T---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getICollection()](#getICollection--) |  |
| [getIList()](#getIList--) |  |
| [getSyncRoot()](#getSyncRoot--) |  |
| [get_Item(int arg0)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOfItem(T arg0)](#indexOfItem-T-) |  |
| [insertItem(int arg0, T arg1)](#insertItem-int-T-) |  |
| [insertMapiRecipient(int index, MapiRecipient item)](#insertMapiRecipient-int-com.aspose.email.MapiRecipient-) | Inserts a recipient at the specified position. |
| [isReadOnly()](#isReadOnly--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int arg0)](#removeAt-int-) |  |
| [removeItem(T arg0)](#removeItem-T-) |  |
| [set_Item(int arg0, T arg1)](#set-Item-int-T-) |  |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiRecipientCollection() {#MapiRecipientCollection--}
```
public MapiRecipientCollection()
```


Initializes a new instance of the [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) class.

### add(String address, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-int-}
```
public final MapiRecipient add(String address, String displayName, int recipientType)
```


Adds a recipient.

Adding a recipient also updates [MapiMessage.getDisplayTo()](../../com.aspose.email/mapimessage\#getDisplayTo--), [MapiMessage.getDisplayCc()](../../com.aspose.email/mapimessage\#getDisplayCc--) or [MapiMessage.getDisplayBcc()](../../com.aspose.email/mapimessage\#getDisplayBcc--) of the message, depending on the type of the recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The e-mail address. |
| displayName | java.lang.String | The display name. |
| recipientType | int | The type: To, CC or BCC. |

**Returns:**
[MapiRecipient](../../com.aspose.email/mapirecipient) - The new [MapiRecipient](../../com.aspose.email/mapirecipient).
### add(String address, String addressType, String displayName, int recipientType) {#add-java.lang.String-java.lang.String-java.lang.String-int-}
```
public final MapiRecipient add(String address, String addressType, String displayName, int recipientType)
```


Adds a recipient with an address of the specified type.

Adding a recipient also updates [MapiMessage.getDisplayTo()](../../com.aspose.email/mapimessage\#getDisplayTo--), [MapiMessage.getDisplayCc()](../../com.aspose.email/mapimessage\#getDisplayCc--) or [MapiMessage.getDisplayBcc()](../../com.aspose.email/mapimessage\#getDisplayBcc--) of the message, depending on the type of the recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| address | java.lang.String | The address. |
| addressType | java.lang.String | The type of the address, such as  SMTP  or  EX . |
| displayName | java.lang.String | The display name. |
| recipientType | int | The type: To, CC or BCC. |

**Returns:**
[MapiRecipient](../../com.aspose.email/mapirecipient) - The new [MapiRecipient](../../com.aspose.email/mapirecipient).
### addItem(T arg0) {#addItem-T-}
```
public void addItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### addMapiRecipient(MapiRecipient item) {#addMapiRecipient-com.aspose.email.MapiRecipient-}
```
public final void addMapiRecipient(MapiRecipient item)
```


Adds an existing recipient to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | The recipient to add. |

### clear() {#clear--}
```
public void clear()
```




### containsItem(T arg0) {#containsItem-T-}
```
public boolean containsItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### copyToTArray(T[] arg0, int arg1) {#copyToTArray-T---int-}
```
public void copyToTArray(T[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T[] |  |
| arg1 | int |  |

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
### getICollection() {#getICollection--}
```
public System.Collections.ICollection getICollection()
```




**Returns:**
com.aspose.ms.System.Collections.ICollection
### getIList() {#getIList--}
```
public System.Collections.IList getIList()
```




**Returns:**
com.aspose.ms.System.Collections.IList
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### get_Item(int arg0) {#get-Item-int-}
```
public T get_Item(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
T
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOfItem(T arg0) {#indexOfItem-T-}
```
public int indexOfItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
int
### insertItem(int arg0, T arg1) {#insertItem-int-T-}
```
public void insertItem(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### insertMapiRecipient(int index, MapiRecipient item) {#insertMapiRecipient-int-com.aspose.email.MapiRecipient-}
```
public final void insertMapiRecipient(int index, MapiRecipient item)
```


Inserts a recipient at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based position to insert at. |
| item | [MapiRecipient](../../com.aspose.email/mapirecipient) | The recipient to insert. |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<T> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<T>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int arg0) {#removeAt-int-}
```
public void removeAt(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### removeItem(T arg0) {#removeItem-T-}
```
public boolean removeItem(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

**Returns:**
boolean
### set_Item(int arg0, T arg1) {#set-Item-int-T-}
```
public void set_Item(int arg0, T arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |
| arg1 | T |  |

### size() {#size--}
```
public int size()
```




**Returns:**
int
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

