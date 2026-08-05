---
title: "Aspose::Email::Tools::Search::MailQueryBuilder class"
linktitle: "MailQueryBuilder"
articleTitle: "MailQueryBuilder"
second_title: "Aspose.Email for C++"
description: "Represents the builder of search expression."
type: docs
weight: 10
url: /cpp/aspose.email.tools.search/mailquerybuilder/
---

## MailQueryBuilder class

Represents the builder of search expression.

Note: By default, the result is the intersection (AND function) of all the messages that match those keys. To join keys by OR function, please, use Or() method of this class

## Constructors

| Name | Description |
| --- | --- |
| [MailQueryBuilder (2 overloads)](./mailquerybuilder/) | Initializes a new instance of the MailQueryBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [Clear](./clear/) | Clears query. |
| [get_Bcc](./get_bcc/) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [get_Body](./get_body/) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [get_Cc](./get_cc/) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [get_DefaultEncoding](./get_defaultencoding/) | Gets default encoding (charset) for query builder |
| [get_From](./get_from/) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [get_InternalDate](./get_internaldate/) | Gets the field that allows to find messages by internal date. |
| [get_KeyCollection](./get_keycollection/) | Gets the key collection. |
| [get_OrderByCollection](./get_orderbycollection/) | Gets the key collection. |
| [get_SentDate](./get_sentdate/) | Gets the field that allows to find messages by sent date. |
| [get_Subject](./get_subject/) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [get_Text](./get_text/) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [get_To](./get_to/) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [GetOptions](./getoptions/) |  |
| [GetQuery](./getquery/) | Gets the query. |
| [Or](./or/) | Search messages that match either search key. Provides disjunction between two expressions (OR). |

