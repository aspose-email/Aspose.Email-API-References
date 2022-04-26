---
title: MailQuery
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery constructor (1 of 2)

Initializes a new instance of the [`MailQuery`](../../mailquery) class.

```csharp
public MailQuery(string queryString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryString | String | The query string. |

### Remarks

The query string should have the following view.

The example of a simple expression:

'&lt;Field name&gt;' &lt;Comparison operator&gt; '&lt;Field value&gt;',

where &lt;Field Name&gt; - the name of a message field through which filtering is made, &lt;Comparison operator&gt; - comparison operators, as their name implies, allow to compare message field and specified value, &lt;Field value&gt; - value to be compared with a message field.

The number of simple expressions can make a compound one, ex.: (&lt;Simple expression 1&gt; &amp; &lt;Simple expression 2&gt;) &#x7C; &lt;Simple expression 3&gt;,

where "&amp;" - logical-AND operator, "&#x7C;" - logical-OR operator

At present the following values are allowed as a field name (&lt;Field name&gt;):

"To" - represents a TO field of message, "Text" - represents string in the header or body of the message, "Bcc" - represents a BCC field of message, "Body" - represents a string in the body of message, "Cc" - represents a CC field of message, "From" - represents a From field of message, "Subject" - represents a string in the subject of message, "InternalDate" - represents an internal date of message, "SentDate" - represents a sent date of message

Additionally, the following field names are allowed for IMAP-protocol:

"Answered" - represents an /Answered flag of message "Seen" - represents a /Seen flag of message "Flagged" - represents a /Flagged flag of message "Draft" - represents a /Draft flag of message "Deleted" - represents a Deleted/ flag of message "Recent" - represents a Deleted/ flag of message "MessageSize" - represents a size (in bytes) of message

Additionally, the following field names are allowed for Exchange:

"IsRead" - Indicates whether the message has been read "HasAttachment" - Indicates whether or not the message has attachments "IsSubmitted" - Indicates whether the message has been submitted to the Outbox "ContentClass" - represents a content class of item

Additionally, the following field names are allowed for pst/ost files:

"MessageClass" - Represents a message class "ContainerClass" - Represents a folder container class "Importance" - Represents a message importance "MessageSize" - represents a size (in bytes) of message "FolderName" - represents a folder name "ContentsCount" - represents a total number of items in the folder "UnreadContentsCount" - represents the number of unread items in the folder. "Subfolders" - Indicates whether or not the folder has subfolders "Read" - the message is marked as having been read "HasAttachment" - the message has at least one attachment "Unsent" - the message is still being composed "Unmodified" - the message has not been modified since it was first saved (if unsent) or it was delivered (if sent) "FromMe" - the user receiving the message was also the user who sent the message "Resend" - the message includes a request for a resend operation with a non-delivery report "NotifyRead" - the user who sent the message has requested notification when a recipient first reads it "NotifyUnread" - the user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires "EverRead" - the message has been read at least once

The field value (&lt;Field value&gt;) can take the following values: For text fields - any string, For date type fields - the string of "d-MMM-yyy" format, ex. "10-Feb-2009", For flags (fields of boolean type) - either "True", or "False"

### Examples

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### See Also

* class [MailQuery](../../mailquery)
* namespace [Aspose.Email.Tools.Search](../../mailquery)
* assembly [Aspose.Email](../../../)

---

## MailQuery constructor (2 of 2)

Initializes a new instance of the [`MailQuery`](../../mailquery) class.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Remarks

The sort query string should have the following view.

The example of a simple expression:

'&lt;Field name&gt;' OrderBy ['ASC'&#x7C;'DESC'],

where &lt;Field Name&gt; - the name of a message field through which sorting is made, ['ASC'&#x7C;'DESC'] - sorting operators, allow to sort Ascending or Descending,

The number of simple expressions can make a compound one, ex.: (&lt;Simple expression 1&gt; &amp; &lt;Simple expression 2&gt;),

### Examples

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### See Also

* class [MailQuery](../../mailquery)
* namespace [Aspose.Email.Tools.Search](../../mailquery)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
