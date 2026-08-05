---
title: "Aspose::Email::Clients::Imap::ImapClient class"
linktitle: "ImapClient"
articleTitle: "ImapClient"
second_title: "Aspose.Email for C++"
description: "Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP)."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapclient/
---

## ImapClient class

**Inherits:** Aspose::Email::Clients::EmailClient

Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

## Constructors

| Name | Description |
| --- | --- |
| [ImapClient (19 overloads)](./imapclient/) | Initializes a new instance of the ImapClient class |

## Methods

| Name | Description |
| --- | --- |
| [AddMessageFlags (28 overloads)](./addmessageflags/) | Adds the flags to the message |
| [AppendMessage (8 overloads)](./appendmessage/) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [AppendMessages (4 overloads)](./appendmessages/) | Uploads the mail message to the current folder If current folder hasn't been specified default folder is used. |
| [Backup (4 overloads)](./backup/) | Backups the content of the specified folders |
| [BeginAddMessageFlags (84 overloads)](./beginaddmessageflags/) | Adds the flags to the message asynchronously |
| [BeginAppendMessage (16 overloads)](./beginappendmessage/) | Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used. |
| [BeginAppendMessages (16 overloads)](./beginappendmessages/) | Begins append message to the end of the specified folder If current folder hasn't been specified default folder is used. |
| [BeginBackup (12 overloads)](./beginbackup/) | Begins to backup the content of the specified folders |
| [BeginChangeMessageFlags (84 overloads)](./beginchangemessageflags/) | Changes the flags of the message |
| [BeginClientCapabilities (6 overloads)](./beginclientcapabilities/) | Notifies server which extensions are supported by client asyncronously. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [BeginCommitDeletes (28 overloads)](./begincommitdeletes/) | Begins to commit the deletions |
| [BeginCopyMessage (12 overloads)](./begincopymessage/) | Begins an asynchronous copying. |
| [BeginCopyMessages (30 overloads)](./begincopymessages/) | Begins copy operation asynchronously. |
| [BeginCreateFolder (6 overloads)](./begincreatefolder/) | Begins an asynchronous folder creation. |
| [BeginDeleteFolder (6 overloads)](./begindeletefolder/) | Begins an asynchronous folder deletion. |
| [BeginDeleteMessage (36 overloads)](./begindeletemessage/) | Marks a message with the specified sequence number as deleted asynchronously |
| [BeginDeleteMessages (96 overloads)](./begindeletemessages/) | Marks a message with the specified sequence number as deleted asynchronously |
| [BeginExistFolder (6 overloads)](./beginexistfolder/) | Check whether this folder exists |
| [BeginFetchAttachment (6 overloads)](./beginfetchattachment/) | Begins fetch an attachment. |
| [BeginFetchMessage (18 overloads)](./beginfetchmessage/) | Begins an asynchronous message fetching. |
| [BeginFetchMessages (12 overloads)](./beginfetchmessages/) | Begins FetchMessages operation asynchronously |
| [BeginGetFolderInfo (6 overloads)](./begingetfolderinfo/) | Begins an asynchronous folder listing. |
| [BeginGetMessageThreads (2 overloads)](./begingetmessagethreads/) | Begins getting message threads asynchronously. |
| [BeginGetNamespaces (6 overloads)](./begingetnamespaces/) | Begins getting namespaces that are available on a server asynchronously. |
| [BeginGetQuota (6 overloads)](./begingetquota/) | Begins getting quota information |
| [BeginGetQuotaRoot (6 overloads)](./begingetquotaroot/) | Begins getting quota root information for mailbox |
| [BeginIntroduceClient (12 overloads)](./beginintroduceclient/) | Begins introduce client information to a server asynchronously. |
| [BeginListAttachments (2 overloads)](./beginlistattachments/) |  |
| [BeginListFolders (30 overloads)](./beginlistfolders/) | Begins to get the list of folders in the mailbox |
| [BeginListMessage (24 overloads)](./beginlistmessage/) | Begins to get information about a message. |
| [BeginListMessages (44 overloads)](./beginlistmessages/) | Begins getting the list of messages asynchronously in the current folder |
| [BeginListMessagesByPage (2 overloads)](./beginlistmessagesbypage/) | Begins getting the list of messages asynchronously |
| [BeginLogin (6 overloads)](./beginlogin/) | Begins to sign in to a server |
| [BeginLogout (6 overloads)](./beginlogout/) | Begins to sign in to a server |
| [BeginMoveFolder (6 overloads)](./beginmovefolder/) | Moves specified folder and its subfolders to new location asynchronously. |
| [BeginMoveMessage (24 overloads)](./beginmovemessage/) | Begins an asynchronous moving. |
| [BeginMoveMessages (60 overloads)](./beginmovemessages/) | Begins an asynchronous moving. |
| [BeginNoop (6 overloads)](./beginnoop/) | Begins to execute 'No operation' command |
| [BeginRemoveMessageFlags (84 overloads)](./beginremovemessageflags/) | Removes the flags of the message asynchronously |
| [BeginRenameFolder (6 overloads)](./beginrenamefolder/) | Begins RenameFolder operation asynchronously |
| [BeginRequestCheckpoint (6 overloads)](./beginrequestcheckpoint/) | Begins request a checkpoint of the currently selected mailbox. |
| [BeginRestore](./beginrestore/) | Begins to restore imap folders from the given personal storage. |
| [BeginSaveMessage (24 overloads)](./beginsavemessage/) | Begins SaveMessage operation asynchronously |
| [BeginSelectFolder (8 overloads)](./beginselectfolder/) | Begins select the specified folder asynchronously. |
| [BeginSetQuota (6 overloads)](./beginsetquota/) | Begins setting quota information |
| [BeginSortMessageThreads (2 overloads)](./beginsortmessagethreads/) | Begins sorting message threads asynchronously. |
| [BeginSubscribeFolder (6 overloads)](./beginsubscribefolder/) | Begins subscribe operation that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [BeginUndeleteMessage (24 overloads)](./beginundeletemessage/) | Marks a message with the specified sequence number as not deleted. |
| [BeginUnselectFolder (12 overloads)](./beginunselectfolder/) | Begins permanently removes all messages marked as deleted for currently selected folder and removes selected-state for current folder asyncronously. |
| [BeginUnsubscribeFolder (6 overloads)](./beginunsubscribefolder/) | Begins unsubscribe operation that removes the specified mailbox name from the server's set of "active" mailboxes |
| [BeginValidateCredentials (6 overloads)](./beginvalidatecredentials/) | Begins to execute credentials validation |
| [ChangeMessageFlags (28 overloads)](./changemessageflags/) | Changes the flags of the message |
| [ClientCapabilities (2 overloads)](./clientcapabilities/) | Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [CommitDeletes (10 overloads)](./commitdeletes/) | Commit the deletions |
| [ConnectionFinalize](./connectionfinalize/) | Performs finalization operation for specified connection |
| [CopyMessage (4 overloads)](./copymessage/) | Copies the message |
| [CopyMessages (11 overloads)](./copymessages/) | Copy messages |
| [CreateFolder (2 overloads)](./createfolder/) | Creates a folder with the specified name |
| [DeleteFolder (2 overloads)](./deletefolder/) | Deletes a specified folder. This method represents IMAP DELETE command |
| [DeleteMessage (12 overloads)](./deletemessage/) | Marks a message with the specified sequence number as deleted |
| [DeleteMessages (32 overloads)](./deletemessages/) | Marks a message with the specified sequence number as deleted |
| [Dispose](./dispose/) | Finalizes all operations with a server. |
| [EndAddMessageFlags](./endaddmessageflags/) | Waits for the pending asynchronous operation to complete. |
| [EndAppendMessage](./endappendmessage/) | Waits for the pending asynchronous operation to complete. |
| [EndAppendMessages](./endappendmessages/) | Waits for the pending asynchronous operation to complete. |
| [EndBackup](./endbackup/) | Waits for the pending asynchronous operation to complete. |
| [EndChangeMessageFlags](./endchangemessageflags/) | Waits for the pending asynchronous operation to complete. |
| [EndClientCapabilities](./endclientcapabilities/) | Waits for the pending asynchronous operation to complete. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161 |
| [EndCommitDeletes](./endcommitdeletes/) | Waits for the pending asynchronous operation to complete. |
| [EndCopyMessage](./endcopymessage/) | Waits for the pending asynchronous operation to complete. |
| [EndCopyMessages](./endcopymessages/) | Waits for the pending asynchronous operation to complete. |
| [EndCreateFolder](./endcreatefolder/) | Waits for the pending asynchronous folder creation to complete. |
| [EndDeleteFolder](./enddeletefolder/) | Waits for the pending asynchronous folder deletion to complete. |
| [EndDeleteMessage](./enddeletemessage/) | Waits for the pending asynchronous message deletion to complete. |
| [EndDeleteMessages](./enddeletemessages/) | Waits for the pending asynchronous message deletion to complete. |
| [EndExistFolder (2 overloads)](./endexistfolder/) | Waits for the pending asynchronous operation to complete. |
| [EndFetchAttachment](./endfetchattachment/) | Waits for the asynchronous operation to complete. |
| [EndFetchMessage](./endfetchmessage/) | Waits for the pending asynchronous message fetching to complete. |
| [EndFetchMessages](./endfetchmessages/) | Waits for the asynchronous operation to complete. |
| [EndGetFolderInfo](./endgetfolderinfo/) | Waits for the pending asynchronous folder listing to complete. |
| [EndGetMessageThreads](./endgetmessagethreads/) | Waits for the pending asynchronous folder deletion to complete. |
| [EndGetNamespaces](./endgetnamespaces/) | Waits for the pending asynchronous operation to complete. |
| [EndGetQuota](./endgetquota/) | Waits for the pending asynchronous operation to complete. |
| [EndGetQuotaRoot](./endgetquotaroot/) | Waits for the pending asynchronous operation to complete. |
| [EndIntroduceClient](./endintroduceclient/) | Waits for the pending asynchronous operation to complete. |
| [EndListAttachments](./endlistattachments/) |  |
| [EndListFolders](./endlistfolders/) | Waits for the pending asynchronous operation to complete. |
| [EndListMessage](./endlistmessage/) | Waits for the asynchronous ListMessage operation to complete. |
| [EndListMessages](./endlistmessages/) | Waits for the asynchronous ListMessages operation to complete. |
| [EndListMessagesByPage](./endlistmessagesbypage/) | Waits for the asynchronous ListMessagesByPage operation to complete. |
| [EndLogin](./endlogin/) | Waits for the pending asynchronous operation to complete. |
| [EndLogout](./endlogout/) | Waits for the pending asynchronous operation to complete. |
| [EndMoveFolder](./endmovefolder/) | Waits for completion of the asynchronous operation. |
| [EndMoveMessage](./endmovemessage/) | Waits for the pending asynchronous operation to complete. |
| [EndMoveMessages](./endmovemessages/) | Waits for the pending asynchronous operation to complete. |
| [EndNoop](./endnoop/) | Waits for the pending asynchronous operation to complete. |
| [EndRemoveMessageFlags](./endremovemessageflags/) | Waits for the pending asynchronous operation to complete. |
| [EndRenameFolder](./endrenamefolder/) | Waits for the asynchronous operation to complete. |
| [EndRequestCheckpoint](./endrequestcheckpoint/) | Waits for the pending asynchronous operation to complete. |
| [EndRestore](./endrestore/) | Waits for the pending asynchronous operation to complete. |
| [EndSaveMessage](./endsavemessage/) | Waits for the asynchronous operation to complete. |
| [EndSelectFolder](./endselectfolder/) | Waits for the pending asynchronous message fetching to complete. |
| [EndSetQuota](./endsetquota/) | Waits for the pending asynchronous operation to complete. |
| [EndSortMessageThreads](./endsortmessagethreads/) | Waits for the pending asynchronous folder deletion to complete. |
| [EndSubscribeFolder](./endsubscribefolder/) | Waits for the pending asynchronous operation to complete. |
| [EndUndeleteMessage](./endundeletemessage/) | Waits for the pending asynchronous operation to complete. |
| [EndUnselectFolder](./endunselectfolder/) | Waits for the pending asynchronous operation to complete. |
| [EndUnsubscribeFolder](./endunsubscribefolder/) | Waits for the pending asynchronous operation to complete. |
| [EndValidateCredentials](./endvalidatecredentials/) | Waits for the pending asynchronous operation to complete. |
| [ExistFolder (4 overloads)](./existfolder/) | Check whether this folder exists |
| [FetchAttachment (2 overloads)](./fetchattachment/) | Fetches the specified attachment |
| [FetchMessage (6 overloads)](./fetchmessage/) | Fetches the message |
| [FetchMessages (4 overloads)](./fetchmessages/) | Fetches the messages |
| [get_AllowedAuthentication](./get_allowedauthentication/) | Gets enumeration of allowed by user authentication types |
| [get_AnnotateSupported](./get_annotatesupported/) | Gets information whether ANNOTATE extension is supported See more: https://tools.ietf.org/html/rfc5257 |
| [get_AutoCommit](./get_autocommit/) | Indicates, whether commit operation are executed automatically when folder is changed or before connection is closed. |
| [get_ChildrenSupported](./get_childrensupported/) | Gets information whether CHILDREN extension is supported See more: https://tools.ietf.org/html/rfc3348 |
| [get_ClientIdentificationInfo](./get_clientidentificationinfo/) | Gets client identification information See more: https://tools.ietf.org/html/rfc2971 |
| [get_CompressSupported](./get_compresssupported/) | Gets information whether COMPRESS extension is supported See more: https://tools.ietf.org/html/rfc4978 |
| [get_CondstoreSupported](./get_condstoresupported/) | Gets information whether CONDSTORE extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [get_CurrentFolder](./get_currentfolder/) | Gets the current folder |
| [get_DefaultFolder](./get_defaultfolder/) | Default folder for ImapClients |
| [get_DefaultPort](./get_defaultport/) | Gets default port for client |
| [get_Delimiter](./get_delimiter/) | Gets delimiter of folders hierarhy. |
| [get_EnableSupported](./get_enablesupported/) | Gets information whether ENABLE extension is supported See more: https://tools.ietf.org/html/rfc5161 |
| [get_ESearchSupported](./get_esearchsupported/) | Gets information whether ESEARCH extension is supported See more: https://tools.ietf.org/html/rfc4731 |
| [get_ExchangeIdAutomatically](./get_exchangeidautomatically/) | Gets value which indicates whether client should to introduce information about itself to a server automatically. See more: https://tools.ietf.org/html/rfc2971 |
| [get_ExtendedListSupported](./get_extendedlistsupported/) | Gets information whether LIST Command Extension is supported See more https://tools.ietf.org/html/rfc5258 |
| [get_GmExt1Supported](./get_gmext1supported/) | Defines if Google X-GM-EXT-1 extension is supported |
| [get_IdSupported](./get_idsupported/) | Gets information whether ID extension is supported See more: https://tools.ietf.org/html/rfc2971 |
| [get_MailboxInfo](./get_mailboxinfo/) | Gets set of special-use mailboxes See more: http://tools.ietf.org/html/rfc6154 and https://tools.ietf.org/html/rfc8457 |
| [get_MoveSupported](./get_movesupported/) | Gets information whether MOVE extension is supported See more: https://tools.ietf.org/html/rfc6851 |
| [get_NamespaceSupported](./get_namespacesupported/) | Gets information whether NAMESPACE extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| [get_Pool](./get_pool/) | Gets connection pool for the client |
| [get_QresyncSupported](./get_qresyncsupported/) | Gets information whether QRESYNC extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [get_QuotaSupported](./get_quotasupported/) | Gets information whether quota is supported |
| [get_ReadOnly](./get_readonly/) | Gets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted. |
| [get_SaslIrSupported](./get_saslirsupported/) | Gets information whether SASL Initial Client Response extension is supported See more: https://tools.ietf.org/html/rfc4959 |
| [get_SelectedCompression](./get_selectedcompression/) | Gets compression type which is used to communicate with a server. See more: https://tools.ietf.org/html/rfc4978 |
| [get_ServerIdentificationInfo](./get_serveridentificationinfo/) | Gets server identification information See more: https://tools.ietf.org/html/rfc2971 |
| [get_ServerSupportedCompression](./get_serversupportedcompression/) | Gets information which compression types are supported by a server. See more: https://tools.ietf.org/html/rfc4978 |
| [get_SortSupported](./get_sortsupported/) | Gets information whether Sort command are supported |
| [get_SpecialUseSupported](./get_specialusesupported/) | Gets information whether Special-Use Mailboxes is supported See more: https://tools.ietf.org/html/rfc6154 |
| [get_SupportedAuthentication](./get_supportedauthentication/) | Gets enumeration of supported by server authentication types |
| [get_SupportOldServer](./get_supportoldserver/) | Indicates whether the old servers need to be supported when receiving messages. |
| [get_ThreadAlgorithms](./get_threadalgorithms/) | Gets supported thread algorithms |
| [get_ThreadSupported](./get_threadsupported/) | Gets information whether Thread command are supported |
| [get_UidPlusSupported](./get_uidplussupported/) | Gets information whether UIDPLUS extension is supported See more: https://tools.ietf.org/html/rfc4315 |
| [get_UnselectSupported](./get_unselectsupported/) | Gets information whether UNSELECT extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| [GetFolderInfo (2 overloads)](./getfolderinfo/) | Returns information about the specified folder without selecting it |
| [GetMessageThreads (2 overloads)](./getmessagethreads/) | Get message threads. |
| [GetNamespaces (2 overloads)](./getnamespaces/) | Gets namespaces that are available on a server. |
| [GetQuota (2 overloads)](./getquota/) | Gets quota information |
| [GetQuotaRoot (2 overloads)](./getquotaroot/) | Gets quota root information for mailbox |
| [IntroduceClient (4 overloads)](./introduceclient/) | Introduces client information to a server. |
| [ListAttachments (2 overloads)](./listattachments/) | Gets the message attachments list. Gets an information for each attachment in message. |
| [ListFolders (10 overloads)](./listfolders/) | Gets the list of folders in the mailbox |
| [ListMessage (8 overloads)](./listmessage/) | Gets information about a message. |
| [ListMessages (27 overloads)](./listmessages/) | Gets the list of messages in the current folder |
| [ListMessagesByPage (4 overloads)](./listmessagesbypage/) | Gets the list of messages |
| [Login (2 overloads)](./login/) | Sign in to a server |
| [Logout (2 overloads)](./logout/) | Sign in to a server |
| [MoveFolder (2 overloads)](./movefolder/) | Moves specified folder and its subfolders to new location. |
| [MoveMessage (8 overloads)](./movemessage/) | Moves the message |
| [MoveMessages (20 overloads)](./movemessages/) | Moves the message |
| [NeedSupportOldServers](./needsupportoldservers/) |  |
| [Noop (3 overloads)](./noop/) | 'No operation' command |
| [RemoveMessageFlags (28 overloads)](./removemessageflags/) | Removes the flags of the message |
| [RenameFolder (2 overloads)](./renamefolder/) | Renames a specified folder to a new name |
| [RequestCheckpoint (2 overloads)](./requestcheckpoint/) | Requests a checkpoint of the currently selected mailbox. |
| [Restore](./restore/) | Begins to restore imap folders from the given personal storage. |
| [ResumeMonitoring](./resumemonitoring/) | Resumes monitoring of message changes for specified folder. Unlike the StartMonitoring method, it will find all missing mailbox changes and call the callback for them. |
| [SaveMessage (8 overloads)](./savemessage/) | Downloads the message with the specified sequence number and writes its data into a supplied stream |
| [SelectFolder (4 overloads)](./selectfolder/) | Selects the specified folder |
| [set_AllowedAuthentication](./set_allowedauthentication/) | Sets enumeration of allowed by user authentication types |
| [set_AnnotateSupported](./set_annotatesupported/) | Gets information whether ANNOTATE extension is supported See more: https://tools.ietf.org/html/rfc5257 |
| [set_AutoCommit](./set_autocommit/) | Indicates, whether commit operation are executed automatically when folder is changed or before connection is closed. |
| [set_ChildrenSupported](./set_childrensupported/) | Gets information whether CHILDREN extension is supported See more: https://tools.ietf.org/html/rfc3348 |
| [set_ClientIdentificationInfo](./set_clientidentificationinfo/) | Sets client identification information See more: https://tools.ietf.org/html/rfc2971 |
| [set_CompressSupported](./set_compresssupported/) | Gets information whether COMPRESS extension is supported See more: https://tools.ietf.org/html/rfc4978 |
| [set_CondstoreSupported](./set_condstoresupported/) | Gets information whether CONDSTORE extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [set_CurrentFolder](./set_currentfolder/) | Gets the current folder |
| [set_DefaultFolder](./set_defaultfolder/) | Default folder for ImapClients |
| [set_Delimiter](./set_delimiter/) | Sets delimiter of folders hierarhy. |
| [set_EnableSupported](./set_enablesupported/) | Gets information whether ENABLE extension is supported See more: https://tools.ietf.org/html/rfc5161 |
| [set_ESearchSupported](./set_esearchsupported/) | Gets information whether ESEARCH extension is supported See more: https://tools.ietf.org/html/rfc4731 |
| [set_ExchangeIdAutomatically](./set_exchangeidautomatically/) | Sets value which indicates whether client should to introduce information about itself to a server automatically. See more: https://tools.ietf.org/html/rfc2971 |
| [set_ExtendedListSupported](./set_extendedlistsupported/) | Gets information whether LIST Command Extension is supported See more https://tools.ietf.org/html/rfc5258 |
| [set_GmExt1Supported](./set_gmext1supported/) | Defines if Google X-GM-EXT-1 extension is supported |
| [set_IdSupported](./set_idsupported/) | Gets information whether ID extension is supported See more: https://tools.ietf.org/html/rfc2971 |
| [set_MoveSupported](./set_movesupported/) | Gets information whether MOVE extension is supported See more: https://tools.ietf.org/html/rfc6851 |
| [set_NamespaceSupported](./set_namespacesupported/) | Gets information whether NAMESPACE extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| [set_QresyncSupported](./set_qresyncsupported/) | Gets information whether QRESYNC extension is supported See more: https://tools.ietf.org/html/rfc7162 |
| [set_QuotaSupported](./set_quotasupported/) | Gets information whether quota is supported |
| [set_ReadOnly](./set_readonly/) | Sets value which indicates if changes to the permanent state of the mailbox, including per-user state, are permitted. |
| [set_SaslIrSupported](./set_saslirsupported/) | Gets information whether SASL Initial Client Response extension is supported See more: https://tools.ietf.org/html/rfc4959 |
| [set_SelectedCompression](./set_selectedcompression/) | Sets compression type which is used to communicate with a server. See more: https://tools.ietf.org/html/rfc4978 |
| [set_SortSupported](./set_sortsupported/) | Gets information whether Sort command are supported |
| [set_SpecialUseSupported](./set_specialusesupported/) | Gets information whether Special-Use Mailboxes is supported See more: https://tools.ietf.org/html/rfc6154 |
| [set_SupportOldServer](./set_supportoldserver/) | Indicates whether the old servers need to be supported when receiving messages. |
| [set_ThreadSupported](./set_threadsupported/) | Gets information whether Thread command are supported |
| [set_UidPlusSupported](./set_uidplussupported/) | Gets information whether UIDPLUS extension is supported See more: https://tools.ietf.org/html/rfc4315 |
| [set_UnselectSupported](./set_unselectsupported/) | Gets information whether UNSELECT extension is supported See more: https://tools.ietf.org/html/rfc2342 |
| [SetQuota (2 overloads)](./setquota/) | Sets quota information |
| [SortMessageThreads (2 overloads)](./sortmessagethreads/) | Get message threads. |
| [StartMonitoring](./startmonitoring/) | Starts monitoring of message changes for specified folder. |
| [StopMonitoring (2 overloads)](./stopmonitoring/) | Stops any monitoring of changes. |
| [SubscribeFolder (2 overloads)](./subscribefolder/) | Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes. |
| [UndeleteMessage (8 overloads)](./undeletemessage/) | Marks a message with the specified sequence number as not deleted |
| [UnselectFolder (4 overloads)](./unselectfolder/) | Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder. |
| [UnsubscribeFolder (2 overloads)](./unsubscribefolder/) | Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes |
| [ValidateCredentials (2 overloads)](./validatecredentials/) | Executes credentials validation |

