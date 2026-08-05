---
title: "Aspose::Email::Clients::Imap::ImapFolderInfo class"
linktitle: "ImapFolderInfo"
articleTitle: "ImapFolderInfo"
second_title: "Aspose.Email for C++"
description: "Represents an IMAP folder."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapfolderinfo/
---

## ImapFolderInfo class

Represents an IMAP folder.

## Constructors

| Name | Description |
| --- | --- |
| [ImapFolderInfo (2 overloads)](./imapfolderinfo/) | Initializes a new instance of ImapFolderInfo class |

## Methods

| Name | Description |
| --- | --- |
| [get_Delimiter](./get_delimiter/) | Gets a string that is used to delimit levels of hieararchy under this folder. It usually contains either '/' or '.'. This value is only set for folders returned by a call to GetFolderList methods. For GetFolderInfo method and CurrentFolder property, this will throw an exception |
| [get_Flags](./get_flags/) | Gets flags that are applicable for this mailbox |
| [get_FolderType](./get_foldertype/) | Gets information about folder purpose in case if it is used as special folder. This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154) See more: http://tools.ietf.org/html/rfc6154 |
| [get_HasChildren](./get_haschildren/) | Gets value indicating whether folder contains subfolders. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 If value is true , it indicates that the folder has child sub-folders that are accessible to the currently authenticated user, otherwise false. |
| [get_HighestModSequence](./get_highestmodsequence/) | Gets value of all messages in the mailbox. See more: https://tools.ietf.org/html/rfc7162 |
| [get_Marked](./get_marked/) | Gets a value indicating whether it is marked this folder. |
| [get_Name](./get_name/) | Gets the name of the folder. |
| [get_NewMessageCount](./get_newmessagecount/) | Gets the number of the new messages. |
| [get_NoInferiors](./get_noinferiors/) | Gets a value indicating whether this folder can have child levels. If it is True , then no child levels exist now and none can be created in the future |
| [get_NoModSeq](./get_nomodseq/) | Gets value which indicates if mailbox supports mod-sequences. This property works only if server supports CONDSTORE extension. Please, read more https://tools.ietf.org/html/rfc4551#section-3.1.2 |
| [get_NonExistent](./get_nonexistent/) | Gets value indicating whether a folder name is referred to an existing folder. See more: http://tools.ietf.org/html/rfc5258 |
| [get_PermanentFlags](./get_permanentflags/) | Gets message flags which can be changed permanently. NOTE: If this is empty, then all flags can be changed permanently. |
| [get_ReadOnly](./get_readonly/) | Gets a value indicating whether the folder is read-only. |
| [get_RecentMessageCount](./get_recentmessagecount/) | Gets the number of messages that arrived recently. |
| [get_Remote](./get_remote/) | Gets value indicating that a folder is a remote mailbox. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 |
| [get_Selectable](./get_selectable/) | Gets a value indicating whether it is possible to select this folder. |
| [get_Subscribed](./get_subscribed/) | Gets value that indicates that a folder name is subscribed to. See more: http://tools.ietf.org/html/rfc5258 |
| [get_TotalMessageCount](./get_totalmessagecount/) | Gets the number of messages in the folder. |
| [get_UIDNext](./get_uidnext/) | Gets the validity ID of the mailbox. |
| [get_UidNotSticky](./get_uidnotsticky/) | Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [get_ValidityId](./get_validityid/) | Gets the validity ID of the mailbox. |
| [set_Delimiter](./set_delimiter/) | Gets a string that is used to delimit levels of hieararchy under this folder. It usually contains either '/' or '.'. This value is only set for folders returned by a call to GetFolderList methods. For GetFolderInfo method and CurrentFolder property, this will throw an exception |
| [set_Flags](./set_flags/) | Sets flags that are applicable for this mailbox |
| [set_FolderType](./set_foldertype/) | Gets information about folder purpose in case if it is used as special folder. This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154) See more: http://tools.ietf.org/html/rfc6154 |
| [set_HasChildren](./set_haschildren/) | Gets value indicating whether folder contains subfolders. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 If value is true , it indicates that the folder has child sub-folders that are accessible to the currently authenticated user, otherwise false. |
| [set_HighestModSequence](./set_highestmodsequence/) | Gets value of all messages in the mailbox. See more: https://tools.ietf.org/html/rfc7162 |
| [set_Marked](./set_marked/) | Gets a value indicating whether it is marked this folder. |
| [set_Name](./set_name/) | Gets the name of the folder. |
| [set_NewMessageCount](./set_newmessagecount/) | Gets the number of the new messages. |
| [set_NoInferiors](./set_noinferiors/) | Gets a value indicating whether this folder can have child levels. If it is True , then no child levels exist now and none can be created in the future |
| [set_NoModSeq](./set_nomodseq/) | Gets value which indicates if mailbox supports mod-sequences. This property works only if server supports CONDSTORE extension. Please, read more https://tools.ietf.org/html/rfc4551#section-3.1.2 |
| [set_NonExistent](./set_nonexistent/) | Gets value indicating whether a folder name is referred to an existing folder. See more: http://tools.ietf.org/html/rfc5258 |
| [set_PermanentFlags](./set_permanentflags/) | Sets message flags which can be changed permanently. NOTE: If this is empty, then all flags can be changed permanently. |
| [set_ReadOnly](./set_readonly/) | Gets a value indicating whether the folder is read-only. |
| [set_RecentMessageCount](./set_recentmessagecount/) | Gets the number of messages that arrived recently. |
| [set_Remote](./set_remote/) | Gets value indicating that a folder is a remote mailbox. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 |
| [set_Selectable](./set_selectable/) | Gets a value indicating whether it is possible to select this folder. |
| [set_Subscribed](./set_subscribed/) | Gets value that indicates that a folder name is subscribed to. See more: http://tools.ietf.org/html/rfc5258 |
| [set_TotalMessageCount](./set_totalmessagecount/) | Gets the number of messages in the folder. |
| [set_UIDNext](./set_uidnext/) | Gets the validity ID of the mailbox. |
| [set_UidNotSticky](./set_uidnotsticky/) | Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [set_ValidityId](./set_validityid/) | Gets the validity ID of the mailbox. |
| [ToString](./tostring/) | Returns a string that represents the current object. |
| [Aspose::Email::Clients::Imap::Commands::AppendMessagesGrCommand](./asposeemailclientsimapcommandsappendmessagesgrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::BackupGrCommand](./asposeemailclientsimapcommandsbackupgrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::ConnectGrCommand](./asposeemailclientsimapcommandsconnectgrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::DeleteCommand](./asposeemailclientsimapcommandsdeletecommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::FetchMessageInfoCollectionCommand](./asposeemailclientsimapcommandsfetchmessageinfocollectioncommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::ListCommand](./asposeemailclientsimapcommandslistcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::ListFoldersGrCommand](./asposeemailclientsimapcommandslistfoldersgrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::ListMessagesByPageGrCommand](./asposeemailclientsimapcommandslistmessagesbypagegrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::ListMessagesGrCommand](./asposeemailclientsimapcommandslistmessagesgrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::MoveFolderGrCommand](./asposeemailclientsimapcommandsmovefoldergrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::RestoreGrCommand](./asposeemailclientsimapcommandsrestoregrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::SelectCommand](./asposeemailclientsimapcommandsselectcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::SelectFolderGrCommand](./asposeemailclientsimapcommandsselectfoldergrcommand/) |  |
| [Aspose::Email::Clients::Imap::Commands::StatusCommand](./asposeemailclientsimapcommandsstatuscommand/) |  |
| [ImapConnection](./imapconnection/) |  |
| [InBox](./inbox/) | Gets inbox name. |

