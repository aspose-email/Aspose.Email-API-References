---
title: ExchangeFolderType
second_title: Aspose.Email for Java API Reference
description: Enumerates the distinguished folder types.
type: docs
weight: 216
url: /java/com.aspose.email/exchangefoldertype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExchangeFolderType extends System.Enum
```

Enumerates the distinguished folder types. This values also contained in PidTagContainerClass property.
## Fields

| Field | Description |
| --- | --- |
| [Appointment](#Appointment) | This value represents the 'appointment' folder type ("IPF.Appointment"). |
| [Contact](#Contact) | This value represents the 'contacts' folder type ("IPF.Contact"). |
| [DocumentLibraries](#DocumentLibraries) | This value represents the 'documents' folder type ("IPF.ShortcutFolder"). |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ImContactsList](#ImContactsList) | This value represents the folder type for instant messaging contacts ("IPF.Contact.MOC.ImContactList"). |
| [Imap](#Imap) | This value represents the 'imap' folder type ("IPF.IMAP"). |
| [Journal](#Journal) | This value represents the 'Journal' folder type ("IPF.Journal"). |
| [Note](#Note) | This value represents the e-mail Message folder type ("IPF.Note"). |
| [QuickContacts](#QuickContacts) | This value represents the folder type for favorite contacts ("IPF.Contact.MOC.QuickContacts"). |
| [RSSFeeds](#RSSFeeds) | This value represents the RSS Message folder type ("IPF.Note.OutlookHomepage"). |
| [StickyNote](#StickyNote) | This value represents the 'notes' folder type ("IPF.StickyNote"). |
| [Task](#Task) | This value represents the 'Task' folder type ("IPF.Task"). |
| [Undefined](#Undefined) | Folder type is not set. |
| [Unknown](#Unknown) | Folder type is unknown. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Appointment {#Appointment}
```
public static final int Appointment
```


This value represents the 'appointment' folder type ("IPF.Appointment"). Value is used with following well known folders: Calendar - Contains Calendar objects, such as appointments.

### Contact {#Contact}
```
public static final int Contact
```


This value represents the 'contacts' folder type ("IPF.Contact"). Value is used with following well known folders: Contacts - Contains Contact objects. Suggested Contacts - Contains Contact objects that are created when a recipient is not in an address book. Contacts Search - Search folder that displays a list of contacts that fit search criteria.

### DocumentLibraries {#DocumentLibraries}
```
public static final int DocumentLibraries
```


This value represents the 'documents' folder type ("IPF.ShortcutFolder"). Value is used with following well known folders: Document Libraries - Contains documents to be uploaded to a shared location.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ImContactsList {#ImContactsList}
```
public static final int ImContactsList
```


This value represents the folder type for instant messaging contacts ("IPF.Contact.MOC.ImContactList"). Value is used with following well known folders: IM Contacts List - Contains Personal Distribution List objects of favorite contacts and instant messaging contacts.

### Imap {#Imap}
```
public static final int Imap
```


This value represents the 'imap' folder type ("IPF.IMAP"). Used to migrate from IMAP profile to Exchange.

### Journal {#Journal}
```
public static final int Journal
```


This value represents the 'Journal' folder type ("IPF.Journal"). Value is used with following well known folders: Journal - Contains Journal objects.

### Note {#Note}
```
public static final int Note
```


This value represents the e-mail Message folder type ("IPF.Note"). Value is used with following well known folders: Deleted Items - The default location for objects that have been deleted. Outbox - Outgoing e-mail Message objects are placed in this folder when the Message object is sent. Sent Items - The default location in which copies of e-mail Message objects are placed after they have been submitted (sent). Inbox - The default location for incoming (received) e-mail Message objects. Drafts - The default location for composed e-mail Message objects that have been saved but not sent. Junk E-mail - Default location for e-mail Message objects determined to be junk e-mail by a Junk E-mail rule. Sync Issues - Contains folders that contain messages that indicate particular issues encountered during synchronization between client and server. This is the parent folder of the Conflicts, Local Failures, and Server Failures folders. Conflicts - Contains Message objects that indicate synchronization conflicts between client and server. Local Failures - Contains messages that indicate client-side synchronization failures. Server Failures - Contains messages that indicate server-side synchronization failures. Tracked Mail Processing - Search folder that contains flagged objects. Spooler Queue - Contains E-mail objects that have been sent or received.

### QuickContacts {#QuickContacts}
```
public static final int QuickContacts
```


This value represents the folder type for favorite contacts ("IPF.Contact.MOC.QuickContacts"). Value is used with following well known folders: Quick Contacts - Contains Contact objects for the user's favorite contacts and instant messaging contacts.

### RSSFeeds {#RSSFeeds}
```
public static final int RSSFeeds
```


This value represents the RSS Message folder type ("IPF.Note.OutlookHomepage"). Value is used with following well known folders: RSS Feeds - Contains Really Simple Syndication (RSS) feed messages.

### StickyNote {#StickyNote}
```
public static final int StickyNote
```


This value represents the 'notes' folder type ("IPF.StickyNote"). Value is used with following well known folders: Notes - Contains Note objects.

### Task {#Task}
```
public static final int Task
```


This value represents the 'Task' folder type ("IPF.Task"). Value is used with following well known folders: To-Do - Search folder used for tracking Task objects. Tasks - Contains Task objects.

### Undefined {#Undefined}
```
public static final int Undefined
```


Folder type is not set. Value is used with following well known folders: Root - The message store hierarchy's top-level folder, which contains all other Folder objects in that message store. Finder - Contains the default search folders. FreeBusy Data - Contains the free/busy data of the mailbox's owner. Top of Personal Folders - The top folder of the interpersonal message hierarchy, which contains user data folders, including most special folders such as the Inbox folder. Common Views - Contains the data for default views that are standard for the message store and that can be used by any user of a client accessing the message store. Personal Views - Contains the data for views defined by a particular user. Deferred Action - Contains any Deferred Action Message (DAM) or Deferred Error Message (DEM) that results from the execution of client-side rules.

### Unknown {#Unknown}
```
public static final int Unknown
```


Folder type is unknown.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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

