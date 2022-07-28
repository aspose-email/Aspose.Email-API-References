---
title: IAsyncImapClient
second_title: Aspose.Email für .NET-API-Referenz
description: Ermöglicht Anwendungen den Zugriff auf und die Bearbeitung von Nachrichten mithilfe des Internet Message Access Protocol IMAP.
type: docs
weight: 16240
url: /de/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Ermöglicht Anwendungen den Zugriff auf und die Bearbeitung von Nachrichten mithilfe des Internet Message Access Protocol (IMAP).

```csharp
public interface IAsyncImapClient
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | Fügt die Flags zur Nachricht hinzu |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Lädt die E-Mail-Nachricht in den angegebenen Ordner hoch |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Lädt die E-Mail-Nachrichten in den aktuellen Ordner hoch |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Sichert den Inhalt der angegebenen Ordner |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Sichert den Inhalt der angegebenen Ordner |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | Ändert die Flags der Nachricht |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Benachrichtigt den Server, welche Erweiterungen vom Client unterstützt werden. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC5161 unterstützt. Weitere Informationen finden Sie unter https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Übernehmen Sie die Löschungen |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | Kopiert die Nachricht |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Kopiert die Nachricht. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Nachrichten kopieren. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Erstellt einen Ordner mit dem angegebenen Namen. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Löscht einen angegebenen Ordner. Diese Methode stellt den Befehl IMAP DELETE dar. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Markiert eine Nachricht mit der angegebenen eindeutigen Kennung als gelöscht und schreibt die Löschungen fest, wenn der Benutzer dies angibt. Diese Methode funktioniert nur, wenn der Server die UIDPLUS-Erweiterung unterstützt. Bitte lesen Sie mehr https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Überprüfen Sie, ob dieser Ordner existiert |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Ruft den angegebenen Anhang ab. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | Ruft die Nachrichten asynchron ab |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | Gibt Informationen über den angegebenen Ordner zurück, ohne ihn auszuwählen |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | Nachrichten-Threads abrufen. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Ruft Namespaces ab, die auf einem Server verfügbar sind. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Ruft Kontingentinformationen ab |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | Ruft Kontingentstamminformationen für mailbox ab |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | Leitet Client-Informationen an einen Server weiter. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Ruft die Liste der Unterordner im angegebenen Ordner ab |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ruft Informationen zu einer Nachricht ab. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ruft Informationen zu einer Nachricht ab. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Ruft die Liste der Nachrichten im aktuellen Ordner ab. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Ruft die Liste der Nachrichten im angegebenen Ordner ab |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Ruft die Liste der Nachrichten ab |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Ruft die Liste der Nachrichten ab |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Verschiebt den angegebenen Ordner und seine Unterordner an einen neuen Speicherort. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Verschiebt die Nachrichten. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | Befehl „Keine Operation“ |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | Entfernt die Flags der Nachricht |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Benennt einen bestimmten Ordner in einen neuen Namen um |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Fordert einen Prüfpunkt des aktuell ausgewählten Postfachs an. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Beginnt mit der Wiederherstellung von imap-Ordnern aus dem angegebenen persönlichen Speicher. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Nimmt die Überwachung von Nachrichtenänderungen für den angegebenen Ordner wieder auf. Im Gegensatz zur StartMonitoring-Methode findet sie alle fehlenden Postfachänderungen und ruft den Rückruf für sie auf. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Wählt den angegebenen Ordner aus |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Legt Kontingentinformationen fest |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | Nachrichten-Threads sortieren. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Startet die Überwachung von Nachrichtenänderungen für den angegebenen Ordner. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Beendet die Überwachung von Nachrichtenänderungen für den angegebenen Ordner. Beendet die Überwachung aller Ordner, wenn folderName null ist. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Den SUBSCRIBE-Befehl gesendet, der den angegebenen Postfachnamen zu den "aktiven" Postfächern des Servers hinzufügt. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Markiert eine Nachricht mit der angegebenen Sequenznummer als nicht gelöscht |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Markiert eine Nachricht mit der angegebenen Sequenznummer als nicht gelöscht. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Hebt die Auswahl der aktuell ausgewählten Ordner auf. Wenn die Eigenschaft doNotExpunge wahr ist, werden alle Nachrichten als gelöscht markiert und entfernt, andernfalls wird das Löschen abgebrochen. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC3691 unterstützt Weitere Informationen finden Sie unter https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Den UNSUBSCRIBE-Befehl gesendet, der den angegebenen Postfachnamen aus der Gruppe der "aktiven" Postfächer des Servers entfernt |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Führt die Validierung der Anmeldeinformationen aus |

### Siehe auch

* namensraum [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
