---
title: SharePointAuditOperation
second_title: Aspose.Email für .NET-API-Referenz
description: SharePoint-Überwachungsvorgänge
type: docs
weight: 2760
url: /de/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

SharePoint-Überwachungsvorgänge

```csharp
public enum SharePointAuditOperation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Dieser Vorgang befindet sich in der Vorschau. Der Empfänger einer Einladung zum Anzeigen oder Bearbeiten einer freigegebenen Datei (oder eines freigegebenen Ordners) hat auf die freigegebene Datei zugegriffen, indem er auf den Link in der Einladung geklickt hat. |
| AccessInvitationCreated | `1` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer sendet eine Einladung an eine andere Person (innerhalb oder außerhalb seiner Organisation), um eine freigegebene Datei oder einen freigegebenen Ordner auf einer SharePoint- oder OneDrive for Business-Website anzuzeigen oder zu bearbeiten. Die Details des Ereigniseintrags identifizieren den Namen der freigegebenen Datei, den Benutzer, an den die Einladung gesendet wurde, und die Art der Freigabeberechtigung, die von der Person ausgewählt wurde, die die Einladung gesendet hat. |
| AccessInvitationExpired | `2` | Dieser Vorgang befindet sich in der Vorschau. Eine an einen externen Benutzer gesendete Einladung läuft ab. Standardmäßig läuft eine an einen Benutzer außerhalb Ihrer Organisation gesendete Einladung nach 7 Tagen ab, wenn die Einladung nicht angenommen wird. |
| AccessInvitationRevoked | `3` | Dieser Vorgang befindet sich in der Vorschau. Der Websiteadministrator oder Eigentümer einer Website oder eines Dokuments in SharePoint oder OneDrive for Business zieht eine Einladung zurück, die an einen Benutzer außerhalb Ihrer Organisation gesendet wurde. Eine Einladung kann nur zurückgezogen werden, bevor sie angenommen wurde. |
| AccessInvitationUpdated | `4` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer, der eine Einladung erstellt und an eine andere Person zum Anzeigen oder Bearbeiten einer freigegebenen Datei (oder eines freigegebenen Ordners) auf einer SharePoint- oder OneDrive for Business-Website gesendet hat, sendet die Einladung erneut. |
| AccessRequestApproved | `5` | Der Site-Administrator oder Eigentümer einer Site oder eines Dokuments in SharePoint oder OneDrive for Business genehmigt eine Benutzeranfrage zum Zugriff auf die Site oder das Dokument. |
| AccessRequestCreated | `6` | Der Benutzer fordert Zugriff auf eine Website oder ein Dokument in SharePoint oder OneDrive for Business an, für das er keine Zugriffsberechtigung hat. |
| AccessRequestRejected | `7` | Dieser Vorgang befindet sich in der Vorschau. Der Site-Administrator oder Eigentümer einer Site oder eines Dokuments in SharePoint lehnt eine Benutzeranfrage zum Zugriff auf die Site oder das Dokument ab. |
| ActivationEnabled | `8` | Dieser Vorgang befindet sich in der Vorschau. Benutzer können Browser-fähige Formularvorlagen aktivieren, die keinen Formularcode enthalten, volle Vertrauenswürdigkeit erfordern, die Wiedergabe auf einem mobilen Gerät aktivieren oder eine von einem Serveradministrator verwaltete Datenverbindung verwenden. |
| AdministratorAddedToTermStore | `9` | Dieser Vorgang befindet sich in der Vorschau. Term Store-Administrator hinzugefügt. |
| AdministratorDeletedFromTermStore | `10` | Dieser Vorgang befindet sich in der Vorschau. Terminologiespeicher-Administrator gelöscht. |
| AllowGroupCreationSet | `11` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer fügt einer SharePoint- oder OneDrive for Business-Website eine Berechtigungsstufe hinzu, die es einem Benutzer, dem diese Berechtigung zugewiesen wurde, ermöglicht, eine Gruppe für diese Website zu erstellen. |
| AppCatalogCreated | `12` | Dieser Vorgang befindet sich in der Vorschau. App-Katalog erstellt, um benutzerdefinierte Unternehmens-Apps für Ihre SharePoint-Umgebung verfügbar zu machen. |
| AuditPolicyRemoved | `13` | Dieser Vorgang befindet sich in der Vorschau. Document LifeCycle Policy wurde für eine Websitesammlung entfernt. |
| AuditPolicyUpdate | `14` | Dieser Vorgang befindet sich in der Vorschau. Lebenszyklusrichtlinie für Dokumente wurde für eine Websitesammlung aktualisiert. |
| AzureStreamingEnabledSet | `15` | Dieser Vorgang befindet sich in der Vorschau. Ein Videoportalbesitzer hat Videostreaming von Azure zugelassen. |
| CollaborationTypeModified | `16` | Dieser Vorgang befindet sich in der Vorschau. Die auf Sites zulässige Art der Zusammenarbeit (z. B. Intranet, Extranet oder Öffentlich) wurde geändert. |
| ConnectedSiteSettingModified | `17` | Der Benutzer hat den Link zwischen einem Projekt und einer Projektwebsite entweder erstellt, geändert oder gelöscht, oder der Benutzer ändert die Synchronisierungseinstellung für den Link in Project Web App. |
| CreateSSOApplication | `18` | Dieser Vorgang befindet sich in der Vorschau. In Secure Store Service erstellte Zielanwendung. |
| CustomFieldOrLookupTableCreated | `19` | Der Benutzer hat ein benutzerdefiniertes Feld oder eine Nachschlagetabelle/einen benutzerdefinierten Eintrag in Project Web App erstellt. |
| CustomFieldOrLookupTableDeleted | `20` | Der Benutzer hat ein benutzerdefiniertes Feld oder eine Nachschlagetabelle/einen Eintrag in Project Web App gelöscht. |
| CustomFieldOrLookupTableModified | `21` | Benutzer hat ein benutzerdefiniertes Feld oder eine Nachschlagetabelle/ein Element in Project Web App geändert. |
| CustomizeExemptUsers | `22` | Dieser Vorgang befindet sich in der Vorschau. Der globale Administrator hat die Liste der ausgenommenen Benutzeragenten im SharePoint Admin Center angepasst. Sie können angeben, welche Benutzeragenten davon ausgenommen werden sollen, eine ganze Webseite zum Indexieren zu erhalten. Das bedeutet, wenn ein Benutzeragent, den Sie als ausgenommen angegeben haben, auf ein InfoPath-Formular trifft, wird das Formular als XML-Datei und nicht als ganze Webseite zurückgegeben. Dies beschleunigt die Indizierung von InfoPath-Formularen. |
| DefaultLanguageChangedInTermStore | `23` | Dieser Vorgang befindet sich in der Vorschau. Spracheinstellung im Terminologiespeicher geändert. |
| DelegateModified | `24` | Der Benutzer hat einen Sicherheitsdelegierten in Project Web App erstellt oder geändert. |
| DelegateRemoved | `25` | Der Benutzer hat einen Sicherheitsdelegierten in Project Web App gelöscht. |
| DeleteSSOApplication | `26` | Dieser Vorgang befindet sich in der Vorschau. Eine SSO-Anwendung wurde gelöscht. |
| eDiscoveryHoldApplied | `27` | Dieser Vorgang befindet sich in der Vorschau. Für eine Inhaltsquelle wurde ein in-situ-Speicher platziert. Compliance-Speicher werden mithilfe einer eDiscovery-Websitesammlung (z. B. eDiscovery Center) in SharePoint verwaltet. |
| eDiscoveryHoldRemoved | `28` | Dieser Vorgang befindet sich in der Vorschau. Ein in-situ-Speicher wurde aus einer Inhaltsquelle entfernt. Compliance-Speicher werden mithilfe einer eDiscovery-Websitesammlung (z. B. eDiscovery Center) in SharePoint verwaltet. |
| eDiscoverySearchPerformed | `29` | Dieser Vorgang befindet sich in der Vorschau. Eine eDiscovery-Suche wurde mithilfe einer eDiscovery-Websitesammlung in SharePoint durchgeführt. |
| EngagementAccepted | `30` | Der Benutzer akzeptiert eine Ressourcenverpflichtung in Project Web App. |
| EngagementModified | `31` | Der Benutzer ändert ein Ressourcenengagement in Project Web App. |
| EngagementRejected | `32` | Der Benutzer lehnt einen Ressourceneinsatz in Project Web App ab. |
| EnterpriseCalendarModified | `33` | Benutzer kopiert, ändert oder löscht einen Unternehmenskalender in Project Web App. |
| EntityDeleted | `34` | Benutzer löscht eine Arbeitszeittabelle in Project Web App. |
| EntityForceCheckedIn | `35` | Der Benutzer erzwingt ein Einchecken in einen Kalender, ein benutzerdefiniertes Feld oder eine Nachschlagetabelle in Project Web App. |
| ExemptUserAgentSet | `36` | Dieser Vorgang befindet sich in der Vorschau. Der globale Administrator fügt einen Benutzeragenten zur Liste der ausgenommenen Benutzeragenten im SharePoint Admin Center hinzu. |
| FileAccessed | `37` | Benutzer- oder Systemkonto greift auf eine Datei auf einer SharePoint- oder OneDrive for Business-Website zu. Systemkonten können auch FileAccessed-Ereignisse generieren. |
| FileCheckOutDiscarded | `38` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer verwirft eine ausgecheckte Datei (oder macht sie rückgängig). Das bedeutet, dass alle Änderungen, die sie beim Auschecken an der Datei vorgenommen haben, verworfen und nicht in der Version des Dokuments in der Dokumentbibliothek gespeichert werden. |
| FileCheckedIn | `39` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer checkt ein Dokument ein, das er aus einer SharePoint- oder OneDrive for Business-Dokumentbibliothek ausgecheckt hat. |
| FileCheckedOut | `40` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer checkt ein Dokument aus, das sich in einer SharePoint- oder OneDrive for Business-Dokumentbibliothek befindet. Benutzer können Dokumente, die für sie freigegeben wurden, auschecken und ändern. |
| FileCopied | `41` | Der Benutzer kopiert ein Dokument von einer SharePoint- oder OneDrive for Business-Website. Die kopierte Datei kann in einem anderen Ordner auf der Website gespeichert werden. |
| FileDeleted | `42` | Benutzer löscht ein Dokument von einer SharePoint- oder OneDrive for Business-Website. |
| FileDeletedFirstStageRecycleBin | `43` | Benutzer löscht eine Datei aus dem Papierkorb auf einer SharePoint- oder OneDrive for Business-Website. |
| FileDeletedSecondStageRecycleBin | `44` | Der Benutzer löscht eine Datei aus dem Papierkorb der zweiten Stufe auf einer SharePoint- oder OneDrive for Business-Website. |
| FileDownloaded | `45` | Der Benutzer lädt ein Dokument von einer SharePoint- oder OneDrive for Business-Website herunter. |
| FileFetched | `46` | Dieses Ereignis wurde durch das FileAccessed-Ereignis ersetzt und ist veraltet. |
| FileModified | `47` | Benutzer- oder Systemkonto ändert den Inhalt oder die Eigenschaften eines Dokuments, das sich auf einer SharePoint- oder OneDrive for Business-Website befindet. |
| FileMoved | `48` | Der Benutzer verschiebt ein Dokument von seinem aktuellen Speicherort auf einer SharePoint- oder OneDrive for Business-Website an einen neuen Speicherort. |
| FilePreviewed | `49` | Benutzer zeigt eine Vorschau eines Dokuments auf einer SharePoint- oder OneDrive for Business-Website an. |
| FileRenamed | `50` | Benutzer benennt ein Dokument auf einer SharePoint- oder OneDrive for Business-Website um. |
| FileRestored | `51` | Benutzer stellt ein Dokument aus dem Papierkorb einer SharePoint- oder OneDrive for Business-Website wieder her. |
| FileSyncDownloadedFull | `52` | Der Benutzer stellt eine Synchronisierungsbeziehung her und lädt Dateien zum ersten Mal erfolgreich aus einer SharePoint- oder OneDrive for Business-Dokumentbibliothek auf seinen Computer herunter. |
| FileSyncDownloadedPartial | `53` | Der Benutzer lädt erfolgreich alle Änderungen an Dateien aus der SharePoint- oder OneDrive for Business-Dokumentbibliothek herunter. Dieses Ereignis zeigt an, dass alle Änderungen, die an Dateien in der Dokumentbibliothek vorgenommen wurden, auf den Computer des Benutzers heruntergeladen wurden. Es wurden nur Änderungen heruntergeladen, da die Dokumentbibliothek zuvor vom Benutzer heruntergeladen wurde (wie durch das FileSyncDownloadedFull-Ereignis angegeben). |
| FileSyncUploadedFull | `54` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer richtet eine Synchronisierungsbeziehung ein und lädt Dateien zum ersten Mal erfolgreich von seinem Computer in eine SharePoint- oder OneDrive for Business-Dokumentbibliothek hoch. |
| FileSyncUploadedPartial | `55` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer lädt erfolgreich Änderungen an Dateien in eine SharePoint- oder OneDrive for Business-Dokumentbibliothek hoch. Dieses Ereignis zeigt an, dass alle Änderungen, die an der lokalen Version einer Datei aus einer Dokumentbibliothek vorgenommen wurden, erfolgreich in die Dokumentbibliothek hochgeladen wurden. Nur Änderungen werden entladen, da diese Dateien zuvor vom Benutzer hochgeladen wurden (wie durch das FileSyncUploadedFull-Ereignis angegeben). |
| FileUploaded | `56` | Der Benutzer lädt ein Dokument in einen Ordner auf einer SharePoint- oder OneDrive for Business-Website hoch. |
| FileViewed | `57` | Dieses Ereignis wurde durch das FileAccessed-Ereignis ersetzt und ist veraltet. |
| FolderCopied | `58` | Der Benutzer kopiert einen Ordner von einer SharePoint- oder OneDrive for Business-Website an einen anderen Speicherort in SharePoint oder OneDrive for Business. |
| FolderCreated | `59` | Benutzer erstellt einen Ordner auf einer SharePoint- oder OneDrive for Business-Website. |
| FolderDeleted | `60` | Benutzer löscht einen Ordner von einer SharePoint- oder OneDrive for Business-Website. |
| FolderDeletedFirstStageRecycleBin | `61` | Benutzer löscht einen Ordner aus dem Papierkorb auf einer SharePoint- oder OneDrive for Business-Website . |
| FolderDeletedSecondStageRecycleBin | `62` | Der Benutzer löscht einen Ordner aus dem Papierkorb der zweiten Stufe auf einer SharePoint- oder OneDrive for Business-Website. |
| FolderModified | `63` | Der Benutzer ändert einen Ordner auf einer SharePoint- oder OneDrive for Business-Website. Dieses Ereignis umfasst Änderungen an Ordnermetadaten wie Tags und Eigenschaften. |
| FolderMoved | `64` | Der Benutzer verschiebt einen Ordner von einer SharePoint- oder OneDrive for Business-Website. |
| FolderRenamed | `65` | Benutzer benennt einen Ordner auf einer SharePoint- oder OneDrive for Business-Website um. |
| FolderRestored | `66` | Der Benutzer stellt einen Ordner aus dem Papierkorb auf einer SharePoint- oder OneDrive for Business-Website wieder her. |
| GroupAdded | `67` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer erstellt eine Gruppe für eine SharePoint- oder OneDrive for Business-Website oder führt eine Aufgabe aus, die zur Erstellung einer Gruppe führt. Wenn ein Benutzer beispielsweise zum ersten Mal einen Link zum Freigeben einer Datei erstellt, wird der OneDrive for Business-Site des Benutzers eine Systemgruppe hinzugefügt. Dieses Ereignis kann auch darauf zurückzuführen sein, dass ein Benutzer einen Link mit Bearbeitungsberechtigungen zu einer freigegebenen Datei erstellt hat. |
| GroupRemoved | `68` | Dieser Vorgang befindet sich in der Vorschau. Benutzer löscht eine Gruppe von einer SharePoint- oder OneDrive for Business-Website. |
| GroupUpdated | `69` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer ändert die Einstellungen einer Gruppe für eine SharePoint- oder OneDrive for Business-Website. Dies kann das Ändern des Gruppennamens beinhalten, wer die Gruppenmitgliedschaft anzeigen oder bearbeiten kann und wie Mitgliedschaftsanfragen gehandhabt werden. |
| LanguageAddedToTermStore | `70` | Dieser Vorgang befindet sich in der Vorschau. Sprache zum Terminologiespeicher hinzugefügt. |
| LanguageRemovedFromTermStore | `71` | Dieser Vorgang befindet sich in der Vorschau. Sprache aus dem Terminologiespeicher entfernt. |
| LegacyWorkflowEnabledSet | `72` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer fügt der Website den Inhaltstyp SharePoint-Workflowaufgabe hinzu. Globale Administratoren können im SharePoint Admin Center auch Workflows für die gesamte Organisation aktivieren. |
| LookAndFeelModified | `73` | Der Benutzer ändert einen Schnellstart, Gantt-Diagrammformate oder Gruppenformate. Oder der Benutzer erstellt, ändert oder löscht eine Ansicht in Project Web App. |
| ManagedSyncClientAllowed | `74` | Der Benutzer stellt erfolgreich eine Synchronisierungsbeziehung mit einer SharePoint- oder OneDrive for Business-Website her. Die Synchronisierungsbeziehung ist erfolgreich, da der Computer des Benutzers Mitglied einer Domäne ist, die der Liste der Domänen (als Liste sicherer Empfänger bezeichnet) hinzugefügt wurde, die auf Dokumentbibliotheken in Ihrer Organisation zugreifen können. Weitere Informationen zu dieser Funktion finden Sie unter Verwenden von Windows PowerShell-Cmdlets zum Aktivieren der OneDrive-Synchronisierung für Domänen, die auf der Liste sicherer Empfänger stehen. |
| MaxQuotaModified | `75` | Dieser Vorgang befindet sich in der Vorschau. Das maximale Kontingent für eine Site wurde geändert. |
| MaxResourceUsageModified | `76` | Dieser Vorgang befindet sich in der Vorschau. Die maximal zulässige Ressourcennutzung für eine Site wurde geändert. |
| MySitePublicEnabledSet | `77` | Dieser Vorgang befindet sich in der Vorschau. Das Flag, das es Benutzern ermöglicht, öffentliche MySites zu haben, wurde vom SharePoint-Administrator gesetzt. |
| NewsFeedEnabledSet | `78` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer aktiviert RSS-Feeds für eine SharePoint- oder OneDrive for Business-Website. Globale Administratoren können RSS-Feeds für die gesamte Organisation im SharePoint Admin Center aktivieren. |
| ODBNextUXSettings | `79` | Dieser Vorgang befindet sich in der Vorschau. Neue Benutzeroberfläche für OneDrive for Business wurde aktiviert. |
| OfficeOnDemandSet | `80` | Dieser Vorgang befindet sich in der Vorschau. Der Site-Administrator aktiviert Office on Demand, wodurch Benutzer auf die neueste Version der Office-Desktopanwendungen zugreifen können. Office on Demand ist im SharePoint Admin Center aktiviert und erfordert ein Office 365-Abonnement, das vollständige, installierte Office-Anwendungen enthält. |
| PageViewed | `81` | Benutzer zeigt eine Seite auf einer SharePoint-Website oder OneDrive for Business-Website an. Dies umfasst nicht das Anzeigen von Dokumentbibliotheksdateien von einer SharePoint-Website oder einer One Drive for Business-Website in einem Browser. |
| PeopleResultsScopeSet | `82` | Dieser Vorgang befindet sich in der Vorschau. Der Site-Administrator erstellt oder ändert die Ergebnisquelle für People Searches für eine SharePoint-Site. |
| PermissionSyncSettingModified | `83` | Der Benutzer ändert die Synchronisierungseinstellungen für Projektberechtigungen in Project Web App. |
| PermissionTemplateModified | `84` | Der Benutzer erstellt, ändert oder löscht eine Berechtigungsvorlage in Project Web App. |
| PortfolioDataAccessed | `85` | Benutzer greift auf Portfolioinhalte (Treiberbibliothek, Treiberpriorisierung, Portfolioanalysen) in Project Web App zu. |
| PortfolioDataModified | `86` | Benutzer erstellt, ändert oder löscht Portfoliodaten (Treiberbibliothek, Treiberpriorisierung, Portfolioanalysen) in Project Web App. |
| PreviewModeEnabledSet | `87` | Dieser Vorgang befindet sich in der Vorschau. Der Site-Administrator aktiviert die Dokumentvorschau für eine SharePoint-Site. |
| ProjectAccessed | `88` | Benutzer greift auf Projektinhalte in Project Web App zu. |
| ProjectCheckedIn | `89` | Der Benutzer checkt ein Projekt ein, das er aus einer Project Web App ausgecheckt hat. |
| ProjectCheckedOut | `90` | Der Benutzer checkt ein Projekt aus, das sich in einer Project Web App befindet. Benutzer können Projekte, die sie öffnen dürfen, auschecken und ändern. |
| ProjectCreated | `91` | Benutzer erstellt ein Projekt in Project Web App. |
| ProjectDeleted | `92` | Benutzer löscht ein Projekt in Project Web App. |
| ProjectForceCheckedIn | `93` | Der Benutzer erzwingt ein Einchecken in ein Projekt in Project Web App. |
| ProjectModified | `94` | Benutzer ändert ein Projekt in Project Web App. |
| ProjectPublished | `95` | Benutzer veröffentlicht ein Projekt in Project Web App. |
| ProjectWorkflowRestarted | `96` | Benutzer startet einen Workflow in Project Web App neu. |
| PWASettingsAccessed | `97` | Benutzer greifen über CSOM auf die Project Web App-Einstellungen zu. |
| PWASettingsModified | `98` | Benutzer ändert eine Project Web App-Konfiguration. |
| QueueJobStateModified | `99` | Der Benutzer bricht einen Warteschlangenauftrag in Project Web App ab oder startet ihn neu. |
| QuotaWarningEnabledModified | `100` | Dieser Vorgang befindet sich in der Vorschau. Speicherkontingentwarnung geändert. |
| RenderingEnabled | `101` | Dieser Vorgang befindet sich in der Vorschau. Browserfähige Formularvorlagen werden von InfoPath-Formulardiensten gerendert. |
| ReportingAccessed | `102` | Benutzer hat auf den Berichtsendpunkt in Project Web App zugegriffen. |
| ReportingSettingModified | `103` | Benutzer ändert die Berichterstellungskonfiguration in Project Web App. |
| ResourceAccessed | `104` | Der Benutzer greift auf einen Unternehmensressourceninhalt in Project Web App zu. |
| ResourceCheckedIn | `105` | Der Benutzer checkt eine Enterprise-Ressource ein, die er aus Project Web App ausgecheckt hat. |
| ResourceCheckedOut | `106` | Der Benutzer checkt eine Enterprise-Ressource aus, die sich in Project Web App befindet. |
| ResourceCreated | `107` | Benutzer erstellt eine Enterprise-Ressource in Project Web App. |
| ResourceDeleted | `108` | Benutzer löscht eine Enterprise-Ressource in Project Web App. |
| ResourceForceCheckedIn | `109` | Der Benutzer erzwingt das Einchecken einer Enterprise-Ressource in Project Web App. |
| ResourceModified | `110` | Benutzer ändert eine Enterprise-Ressource in Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | Benutzer checkt einen Ressourcenplan in Project Web App ein oder aus. |
| ResourcePlanModified | `112` | Benutzer ändert einen Ressourcenplan in Project Web App. |
| ResourcePlanPublished | `113` | Benutzer veröffentlicht einen Ressourcenplan in Project Web App. |
| ResourceRedacted | `114` | Der Benutzer redigiert eine Unternehmensressource und entfernt alle persönlichen Informationen in Project Web App. |
| ResourceWarningEnabledModified | `115` | Dieser Vorgang befindet sich in der Vorschau. Ressourcenkontingentwarnung geändert. |
| SSOGroupCredentialsSet | `116` | Dieser Vorgang befindet sich in der Vorschau. Gruppenanmeldeinformationen im Secure Store Service festgelegt. |
| SSOUserCredentialsSet | `117` | Dieser Vorgang befindet sich in der Vorschau. Benutzeranmeldeinformationen im Secure Store Service festgelegt. |
| SearchCenterUrlSet | `118` | Dieser Vorgang befindet sich in der Vorschau. Suchcenter-URL festgelegt. |
| SecondaryMySiteOwnerSet | `119` | Dieser Vorgang befindet sich in der Vorschau. Ein Benutzer hat seiner MySite einen sekundären Eigentümer hinzugefügt. |
| SecurityCategoryModified | `120` | Benutzer erstellt, ändert oder löscht eine Sicherheitskategorie in Project Web App. |
| SecurityGroupModified | `121` | Benutzer erstellt, ändert oder löscht eine Sicherheitsgruppe in Project Web App. |
| SendToConnectionAdded | `122` | Dieser Vorgang befindet sich in der Vorschau. Der globale Administrator erstellt eine neue Verbindung „Senden an“ auf der Seite „Datensatzverwaltung“ im SharePoint Admin Center. Eine „Senden an“-Verbindung gibt Einstellungen für ein Dokumentenrepository oder ein Datenarchiv an. Wenn Sie eine „Senden an“-Verbindung erstellen, kann ein Inhaltsorganisator Dokumente an den angegebenen Speicherort senden. |
| SendToConnectionRemoved | `123` | Dieser Vorgang befindet sich in der Vorschau. Der globale Administrator löscht eine „Senden an“-Verbindung auf der Datensatzverwaltungsseite im SharePoint Admin Center. |
| SharedLinkCreated | `124` | Der Benutzer erstellt einen Link zu einer freigegebenen Datei in SharePoint oder OneDrive for Business. Dieser Link kann an andere Personen gesendet werden, um ihnen Zugriff auf die Datei zu gewähren. Ein Benutzer kann zwei Arten von Links erstellen: einen Link, der es einem Benutzer ermöglicht, die freigegebene Datei anzuzeigen und zu bearbeiten, oder einen Link, der es dem Benutzer ermöglicht, die Datei nur anzuzeigen. |
| SharedLinkDisabled | `125` | Dieser Vorgang befindet sich in der Vorschau. Benutzer deaktiviert (dauerhaft) einen Link, der erstellt wurde, um eine Datei zu teilen. |
| SharingInvitationAccepted | `126` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer nimmt eine Einladung zur Freigabe einer Datei oder eines Ordners an. Dieses Ereignis wird protokolliert, wenn ein Benutzer eine Datei mit anderen Benutzern teilt. |
| SharingRevoked | `127` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer hebt die Freigabe einer Datei oder eines Ordners auf, der zuvor mit anderen Benutzern geteilt wurde. Dieses Ereignis wird protokolliert, wenn ein Benutzer die Freigabe einer Datei für andere Benutzer beendet. |
| SharingSet | `128` | Der Benutzer teilt eine Datei oder einen Ordner in SharePoint oder OneDrive for Business mit einem anderen Benutzer in seiner Organisation. |
| SiteAdminChangeRequest | `129` | Dieser Vorgang befindet sich in der Vorschau. Benutzer fordert an, als Websitesammlungsadministrator für eine SharePoint-Websitesammlung hinzugefügt zu werden. Websitesammlungsadministratoren haben Vollzugriffsberechtigungen für die Websitesammlung und alle Unterwebsites. |
| SiteCollectionAdminAdded | `130` | Dieser Vorgang befindet sich in der Vorschau. Websitesammlungsadministrator oder -besitzer fügt eine Person als Websitesammlungsadministrator für eine SharePoint- oder OneDrive for Business-Website hinzu. Websitesammlungsadministratoren haben Vollzugriffsberechtigungen für die Websitesammlung und alle Unterwebsites. |
| SiteCollectionCreated | `131` | Dieser Vorgang befindet sich in der Vorschau. Der globale Administrator erstellt eine neue Websitesammlung in Ihrer SharePoint-Organisation. |
| SiteRenamed | `132` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer benennt eine SharePoint- oder OneDrive for Business-Website um |
| StatusReportModified | `133` | Benutzer erstellt, ändert oder löscht einen Statusbericht in Project Web App. |
| SyncGetChanges | `134` | Dieser Vorgang befindet sich in der Vorschau. Der Benutzer klickt in SharePoint oder OneDrive for Business in der Aktionsleiste auf Synchronisieren, um alle Änderungen an Dateien in einer Dokumentbibliothek mit seinem Computer zu synchronisieren. |
| TaskStatusAccessed | `135` | Benutzer greift auf den Status einer oder mehrerer Aufgaben in Project Web App zu. |
| TaskStatusApproved | `136` | Benutzer genehmigt eine Statusaktualisierung einer oder mehrerer Aufgaben in Project Web App. |
| TaskStatusRejected | `137` | Benutzer lehnt eine Statusaktualisierung einer oder mehrerer Aufgaben in Project Web App ab. |
| TaskStatusSaved | `138` | Benutzer speichert eine Statusaktualisierung einer oder mehrerer Aufgaben in Project Web App. |
| TaskStatusSubmitted | `139` | Der Benutzer übermittelt eine Statusaktualisierung einer oder mehrerer Aufgaben in Project Web App. |
| TimesheetAccessed | `140` | Benutzer greift auf eine Arbeitszeittabelle in Project Web App zu. |
| TimesheetApproved | `141` | Benutzer genehmigt Arbeitszeittabelle in Project Web App. |
| TimesheetRejected | `142` | Benutzer lehnt eine Arbeitszeittabelle in Project Web App ab. |
| TimesheetSaved | `143` | Benutzer speichert eine Arbeitszeittabelle in Project Web App. |
| TimesheetSubmitted | `144` | Der Benutzer sendet eine Status-Arbeitszeittabelle in Project Web App. |
| UnmanagedSyncClientBlocked | `145` | Der Benutzer versucht, eine Synchronisierungsbeziehung mit einer SharePoint- oder OneDrive for Business-Website von einem Computer herzustellen, der kein Mitglied der Domäne Ihrer Organisation ist oder Mitglied einer Domäne ist, die nicht zur Liste der Domänen hinzugefügt wurde ( Liste sicherer Empfänger genannt), die auf Dokumentbibliotheken in Ihrer Organisation zugreifen können. Die Synchronisierungsbeziehung ist nicht zulässig, und der Computer des Benutzers wird daran gehindert, Dateien in einer Dokumentbibliothek zu synchronisieren, herunterzuladen oder hochzuladen. Informationen zu dieser Funktion finden Sie unter Verwenden von Windows PowerShell-Cmdlets zum Aktivieren der OneDrive-Synchronisierung für Domänen, die auf der Liste sicherer Empfänger stehen. |
| UpdateSSOApplication | `146` | Dieser Vorgang befindet sich in der Vorschau. Zielanwendung in Secure Store Service aktualisiert. |
| UserAddedToGroup | `147` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer fügt eine Person zu einer Gruppe auf einer SharePoint- oder OneDrive for Business-Website hinzu. Das Hinzufügen einer Person zu einer Gruppe gewährt dem Benutzer die Berechtigungen, die der Gruppe zugewiesen wurden. |
| UserRemovedFromGroup | `148` | Dieser Vorgang befindet sich in der Vorschau. Websiteadministrator oder -besitzer entfernt eine Person aus einer Gruppe auf einer SharePoint- oder OneDrive for Business-Website. Nachdem die Person entfernt wurde, erhält sie nicht mehr die Berechtigungen, die der Gruppe zugewiesen wurden. |
| WorkflowModified | `149` | Der Benutzer erstellt, ändert oder löscht einen Enterprise-Projekttyp oder Workflow-Phasen oder -Stufen in Project Web App. |

### Siehe auch

* namensraum [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
