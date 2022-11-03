---
title: ListFoldersReturnOptions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 530
url: /email/python-net/aspose.email.clients.imap/listfoldersreturnoptions/
---

## ListFoldersReturnOptions enumeration

Return options for ListFolders operation<br/>            Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions"<br/>            See more details in https://tools.ietf.org/html/rfc5258

## Members
| Member name | Description |
| :- | :- |
|NONE|Not defined|
|SUBSCRIBED|SUBSCRIBED -  causes the LIST command to return subscription state for all matching mailbox names.  <br/>            The "\Subscribed" attribute MUST be supported and MUST be accurately computed when the SUBSCRIBED return option is specified.  <br/>            Further, all mailbox flags MUST be accurately computed (this differs from the behavior of the LSUB command).|
|CHILDREN|CHILDREN -  requests mailbox child information. This option MUST be supported by all servers.|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/slides/python-net/)

