---
title: ExchangeFolderType
second_title: Aspose.Email for Java API Reference
description:  Enumerates the distinguished folder types.
type: docs
weight: 214
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
| [Undefined](#Undefined) | Folder type is not set. |
| [Note](#Note) | This value represents the e-mail Message folder type ("IPF.Note"). |
| [RSSFeeds](#RSSFeeds) | This value represents the RSS Message folder type ("IPF.Note.OutlookHomepage"). |
| [Appointment](#Appointment) | This value represents the 'appointment' folder type ("IPF.Appointment"). |
| [Contact](#Contact) | This value represents the 'contacts' folder type ("IPF.Contact"). |
| [QuickContacts](#QuickContacts) | This value represents the folder type for favorite contacts ("IPF.Contact.MOC.QuickContacts"). |
| [ImContactsList](#ImContactsList) | This value represents the folder type for instant messaging contacts ("IPF.Contact.MOC.ImContactList"). |
| [DocumentLibraries](#DocumentLibraries) | This value represents the 'documents' folder type ("IPF.ShortcutFolder"). |
| [Journal](#Journal) | This value represents the 'Journal' folder type ("IPF.Journal"). |
| [StickyNote](#StickyNote) | This value represents the 'notes' folder type ("IPF.StickyNote"). |
| [Task](#Task) | This value represents the 'Task' folder type ("IPF.Task"). |
| [Imap](#Imap) | This value represents the 'imap' folder type ("IPF.IMAP"). |
| [Unknown](#Unknown) | Folder type is unknown. |
### Undefined {#Undefined}
```
public static final int Undefined
```


Folder type is not set. Value is used with following well known folders: Root - The message store hierarchy's top-level folder, which contains all other Folder objects in that message store. Finder - Contains the default search folders. FreeBusy Data - Contains the free/busy data of the mailbox's owner. Top of Personal Folders - The top folder of the interpersonal message hierarchy, which contains user data folders, including most special folders such as the Inbox folder. Common Views - Contains the data for default views that are standard for the message store and that can be used by any user of a client accessing the message store. Personal Views - Contains the data for views defined by a particular user. Deferred Action - Contains any Deferred Action Message (DAM) or Deferred Error Message (DEM) that results from the execution of client-side rules.

### Note {#Note}
```
public static final int Note
```


This value represents the e-mail Message folder type ("IPF.Note"). Value is used with following well known folders: Deleted Items - The default location for objects that have been deleted. Outbox - Outgoing e-mail Message objects are placed in this folder when the Message object is sent. Sent Items - The default location in which copies of e-mail Message objects are placed after they have been submitted (sent). Inbox - The default location for incoming (received) e-mail Message objects. Drafts - The default location for composed e-mail Message objects that have been saved but not sent. Junk E-mail - Default location for e-mail Message objects determined to be junk e-mail by a Junk E-mail rule. Sync Issues - Contains folders that contain messages that indicate particular issues encountered during synchronization between client and server. This is the parent folder of the Conflicts, Local Failures, and Server Failures folders. Conflicts - Contains Message objects that indicate synchronization conflicts between client and server. Local Failures - Contains messages that indicate client-side synchronization failures. Server Failures - Contains messages that indicate server-side synchronization failures. Tracked Mail Processing - Search folder that contains flagged objects. Spooler Queue - Contains E-mail objects that have been sent or received.

### RSSFeeds {#RSSFeeds}
```
public static final int RSSFeeds
```


This value represents the RSS Message folder type ("IPF.Note.OutlookHomepage"). Value is used with following well known folders: RSS Feeds - Contains Really Simple Syndication (RSS) feed messages.

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

### QuickContacts {#QuickContacts}
```
public static final int QuickContacts
```


This value represents the folder type for favorite contacts ("IPF.Contact.MOC.QuickContacts"). Value is used with following well known folders: Quick Contacts - Contains Contact objects for the user's favorite contacts and instant messaging contacts.

### ImContactsList {#ImContactsList}
```
public static final int ImContactsList
```


This value represents the folder type for instant messaging contacts ("IPF.Contact.MOC.ImContactList"). Value is used with following well known folders: IM Contacts List - Contains Personal Distribution List objects of favorite contacts and instant messaging contacts.

### DocumentLibraries {#DocumentLibraries}
```
public static final int DocumentLibraries
```


This value represents the 'documents' folder type ("IPF.ShortcutFolder"). Value is used with following well known folders: Document Libraries - Contains documents to be uploaded to a shared location.

### Journal {#Journal}
```
public static final int Journal
```


This value represents the 'Journal' folder type ("IPF.Journal"). Value is used with following well known folders: Journal - Contains Journal objects.

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

### Imap {#Imap}
```
public static final int Imap
```


This value represents the 'imap' folder type ("IPF.IMAP"). Used to migrate from IMAP profile to Exchange.

### Unknown {#Unknown}
```
public static final int Unknown
```


Folder type is unknown.

