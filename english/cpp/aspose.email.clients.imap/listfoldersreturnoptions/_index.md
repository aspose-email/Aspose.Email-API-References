---
title: "ListFoldersReturnOptions Enum"
linktitle: "ListFoldersReturnOptions"
articleTitle: "ListFoldersReturnOptions"
second_title: "Aspose.Email for C++"
description: "Return options for ListFolders operation Please note, this options are supported in case if server supports RFC 5258 \"IMAP LIST Command Extensions\" See more det"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/listfoldersreturnoptions/
---

## ListFoldersReturnOptions enumeration (3 values)

Return options for ListFolders operation Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258

| Value | Description |
| --- | --- |
| None | Not defined |
| Subscribed | SUBSCRIBED - causes the LIST command to return subscription state for all matching mailbox names. The "\Subscribed" attribute MUST be supported and MUST be accurately computed when the SUBSCRIBED return option is specified. Further, all mailbox flags MUST be accurately computed (this differs from the behavior of the LSUB command). |
| Children | CHILDREN - requests mailbox child information. This option MUST be supported by all servers. |

