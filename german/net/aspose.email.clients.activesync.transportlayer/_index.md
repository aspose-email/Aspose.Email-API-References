---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email für .NET-API-Referenz
description: 
type: docs
weight: 80
url: /de/net/aspose.email.clients.activesync.transportlayer/
---


## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AccountInformation](./accountinformation) | Enthält Kontoinformationen des Benutzers. |
| [ActiveSyncTLClient](./activesynctlclient) | Basisklasse für ActiveSync-Client-Implementierungen |
| [AutodiscoverResult](./autodiscoverresult) | Ergebnis des AutoErmittlungsvorgangs |
| [Body](./body) | Gibt ein Freiform-Datenfeld variabler Länge an, das einem gespeicherten Element auf dem Server zugeordnet ist. |
| [BodyPart](./bodypart) | Gibt Details zum Nachrichtenteil einer E-Mail in einer Antwort an. Das BodyPart-Element MUSS in einer Befehlsantwort enthalten sein, wenn die BodyPartPreference in einer Anfrage angegeben wird. |
| [BodyPreference](./bodypreference) | Enthält Präferenzinformationen in Bezug auf Art und Größe der Informationen, die beim Suchen, Synchronisieren oder Abrufen zurückgegeben werden. |
| [CertificateStatuses](./certificatestatuses) | Gibt an, ob das Zertifikat erfolgreich validiert wurde. |
| [DataContainer](./datacontainer) | Enthält Daten für ein bestimmtes Objekt, z. B. einen Kontakt, eine E-Mail-Nachricht, einen Kalendertermin oder ein Aufgabenelement. Der DataContainer kann verwendet werden, um Elemente zu ändern, Elemente hinzuzufügen oder Elemente auf dem Clientgerät oder Server abzurufen. |
| [DeviceInformation](./deviceinformation) | Anforderung, die zum Senden der Eigenschaften des Clientgeräts an den Server verwendet wird. |
| [DevicePasswordRequest](./devicepasswordrequest) | Gibt die Anforderung zum Festlegen des Wiederherstellungskennworts des Clientgeräts durch den Server an. Um ein vorhandenes Wiederherstellungskennwort zu löschen, MUSS der Client ein leeres Kennwort senden. |
| [EASProvisionDoc](./easprovisiondoc) | Gibt die Sammlung von Sicherheitseinstellungen für die Gerätebereitstellung an. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Enthält eine Anforderung zum Löschen des Inhalts eines Ordners. EmptyFolderContents unterstützt ein einzelnes untergeordnetes Element des Options-Elements, DeleteSubFolders, das bestimmt, ob im Ordner enthaltene Unterordner gelöscht werden. Wenn die DeleteSubFolders-Option nicht in der Anforderung enthalten ist, werden die Unterordner der angegebenen CollectionId nicht gelöscht. |
| [FolderInfo](./folderinfo) | FolderInfo-Klasse enthält Ordnerinformationen |
| [FolderSyncResult](./foldersyncresult) | Enthält Änderungen an der Ordnerhierarchie. |
| [ItemEstimate](./itemestimate) | Enthält eine Bewertung zum angeforderten Ordner |
| [ItemEstimateOptions](./itemestimateoptions) | Enthält Elemente, die die Ergebnisse der GetItemEstimate-Operation filtern. |
| [ItemEstimateRequest](./itemestimaterequest) | Enthält ItemEstimate-Anforderungsparameter |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifiziert den Hauptteil der Antwort als den Vorgang enthaltend, der den Inhalt eines Ordners löscht. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Enthält die Eigenschaften, die für Elemente in der Antwort zurückgegeben werden. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Enthält eine Anfrage zum Abrufen eines Elements vom Server. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Enthält eine Antwort zum Abrufen eines Elements vom Server. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Enthält die Anfrage zum Verschieben einer Konversation in einen bestimmten Ordner. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifiziert den Hauptteil der Antwort als den Vorgang enthaltend, der eine bestimmte Konversation bewegt. |
| [ItemOperationsRequest](./itemoperationsrequest) | Enthält ItemOperations-Anfrage. |
| [ItemOperationsResponse](./itemoperationsresponse) | Enthält ItemOperations-Antwort. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Enthält die Optionen für die Operation ItemOperations.EmptyFolderContents |
| [ItOpFetchOptions](./itopfetchoptions) | Enthält die Optionen für die Operation ItemOperations.Fetch. |
| [ItOpMoveOptions](./itopmoveoptions) | Enthält die Optionen für die Operation ItemOperations.Move. |
| [MeetingResponseRequest](./meetingresponserequest) | Gibt die Besprechungsanfrage an, auf die geantwortet wird, die Antwort auf diese Besprechungsanfrage und den Ordner auf dem Server, in dem sich die Besprechungsanfrage befindet. |
| [MeetingResponseResult](./meetingresponseresult) | Besprechungsantwortergebnis Objekt |
| [MoveItemData](./moveitemdata) | Enthält Informationen zum Verschieben von Artikeln |
| [MoveItemResponse](./moveitemresponse) | Enthält Informationen, die die verschobenen Elemente beschreiben. |
| [OOFMessage](./oofmessage) | Gibt die Abwesenheitsnachricht für eine bestimmte Zielgruppe an. Exchange 2007, Exchange 2010 und Exchange 2013 erfordern, dass die Antwortnachricht für unbekannte externe und bekannte externe Zielgruppen identisch ist. Die Eigenschaft unterstützt die folgenden drei Zielgruppen für eine Abwesenheitsnachricht: Intern – Ein Benutzer, der sich in derselben Organisation wie der sendende Benutzer befindet. Bekannter externer – Ein Benutzer, der sich außerhalb der Organisation des sendenden Benutzers befindet, aber in den Kontakten des sendenden Benutzers vertreten ist. Unbekannt extern – Ein Benutzer, der sich außerhalb der Organisation des sendenden Benutzers befindet Organisation und ist nicht in den Kontakten des sendenden Benutzers vertreten. |
| [OOFReqParametrs](./oofreqparametrs) | Ruft OOF-Informationseinstellungen vom Server ab. |
| [OOFRequest](./oofrequest) | Gibt eine Klasse zum Abrufen und Festlegen von Abwesenheitsinformationen (OOF) an. |
| [OOFResponse](./oofresponse) | Gibt eine Klasse zum Abrufen und Festlegen von Abwesenheitsinformationen (OOF) an. |
| [OOFSettings](./oofsettings) | OOF-Informationseinstellungen. |
| [PictureRequest](./picturerequest) | Gibt an, dass der Client anfordert, dass Fotos in der Serverantwort zurückgegeben werden. Das Bild wird nicht unterstützt, wenn die Protokollversion 12.1 oder 14.0 ist. Enthält die Daten zur Fotoanforderung. |
| [PictureRespose](./picturerespose) | Enthält die Daten zu den Kontaktfotos. Das Bild wird nicht unterstützt, wenn die Protokollversion 12.1 oder 14.0 ist. |
| [PingParameter](./pingparameter) | Enthält die Ping-Befehlsparameter |
| [ProvisionPolicy](./provisionpolicy) | Gibt eine Sicherheitsrichtlinie an. |
| [ProvisionPolicyData](./provisionpolicydata) | Gibt die Einstellungen für eine Richtlinie an. |
| [ProvisionRequest](./provisionrequest) | Enthält Anforderungsinformationen für Bereitstellungsbefehl |
| [ProvisionResponse](./provisionresponse) | Enthält Antwortinformationen für Bereitstellungsbefehl |
| [QueryType](./querytype) | Gibt die Schlüsselwörter an, die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück, die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach „John“ mit „John Frum“ oder „Barry Johnson“ übereinstimmen, aber nicht mit „James Littlejohn“. Alle nicht leeren Texteigenschaften in der GAL, die mithilfe von ANR indiziert werden, werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form: LinkId == Wert, wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt: - Ordner können auf folgende Weise angegeben werden: Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner, einschließlich Entwurf, Posteingang und Unterordner, Postausgang und Gesendete Elemente – Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen: Der Basisoperator: And (Abschnitt 2.2.3.10) Ein dateTime-Filter, der mithilfe von GreaterThan (Abschnitt 2.2.3.78) und LessThan angegeben wird Elemente (Abschnitt 2.2.3.87) FreeText-Elemente (Abschnitt 2.2.3.73), die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt. |
| [Recipient](./recipient) | Stellt einen einzelnen Empfänger dar, der aufgelöst wurde. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Zeigt dem Server an, dass Frei/Gebucht-Daten vom Client angefordert werden, und identifiziert die Start- und Endzeit der abzurufenden Frei/Gebucht-Daten. Die Verfügbarkeit wird nicht unterstützt, wenn die Protokollversion 12.1 ist. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifiziert den Status und die Frei/Gebucht-Daten der Benutzer oder Verteilerlisten, die in der Anfrage für die durch StartTime und EndTime identifizierte Zeit identifiziert wurden. Wenn die Verfügbarkeit in einer ResolveRecipients-Anfrage enthalten ist, ruft der Server Frei/Gebucht-Informationen für die identifizierten Benutzer ab in den in der Anforderung enthaltenen To-Elementen und gibt die Frei/Gebucht-Informationen in MergedFreeBusy in der Antwort zurück. Wenn der Server die Anfrage parst, löst der Server zuerst die durch die To-Elemente identifizierten Empfänger auf und bestimmt dann die Frei/Gebucht-Informationen des Benutzers für die angegebene Zeitspanne, bevor er die Frei/Gebucht-Daten in MergedFreeBusy zurückgibt. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Enthält Informationen zu den Zertifikaten für einen Empfänger. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Enthält die Optionen zum Auflösen der Empfängerliste. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Enthält Informationen zum Auflösen von Empfängern. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Enthält Informationen darüber, ob der Empfänger aufgelöst wurde. Wenn der Empfänger aufgelöst wurde, enthält es auch den Empfängertyp, die E-Mail-Adresse, zu der der Empfänger aufgelöst wurde, und optional das S/MIME-Zertifikat für den Empfänger. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Enthält Einstellungen für Rechteverwaltungsinformationen, die vom Server abgerufen wurden. |
| [RightsManagementLicense](./rightsmanagementlicense) | Enthält die Rechterichtlinienvorlageneinstellungen für die Vorlage, die auf die zu synchronisierende E-Mail-Nachricht angewendet wird. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Enthält die Vorlagenkennung, den Namen und die Beschreibung einer auf dem Client verfügbaren Rechterichtlinienvorlage. |
| [SearchCondition](./searchcondition) | Gibt eine Bedingung für Suchanfragen an |
| [SearchOptions](./searchoptions) | Enthält die Suchoptionen. Der Benutzername und das Kennwort können in der Anfrage nur gesendet werden, nachdem ein Statuswert von 14 empfangen wurde. Der Server benötigt diese Anmeldeinformationen, um auf die angeforderten Ressourcen zuzugreifen. Der Client DARF diese nur über eine sichere oder vertrauenswürdige Verbindung senden und nur als Antwort auf einen Statuswert von 14. Die unterstützten Optionen variieren je nach durchsuchtem Geschäft. Die folgende Tabelle listet die gültigen Optionen für jeden Speicher auf. GAL: Range, UserName, Password, Picture Mailbox: Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Range, UserName, Password Die BodyPartPreference ist nur in der Suche gültig Befehlsanfragen, die eine ConversationId. enthalten |
| [SearchQuery](./searchquery) | Gibt die Schlüsselwörter an, die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück, die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach „John“ mit „John Frum“ oder „Barry Johnson“ übereinstimmen, aber nicht mit „James Littlejohn“. Alle nicht leeren Texteigenschaften in der GAL, die mithilfe von ANR indiziert werden, werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form: LinkId == Wert, wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt: - Ordner können auf folgende Weise angegeben werden: Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner, einschließlich Entwurf, Posteingang und Unterordner, Postausgang und Gesendete Elemente – Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen: Der Basisoperator: And (Abschnitt 2.2.3.10) Ein dateTime-Filter, der mithilfe von GreaterThan (Abschnitt 2.2.3.78) und LessThan angegeben wird Elemente (Abschnitt 2.2.3.87) FreeText-Elemente (Abschnitt 2.2.3.73), die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt. |
| [SearchRequest](./searchrequest) | Enthält Informationen zu Suchanfragen |
| [SearchRequestStore](./searchrequeststore) | Geben Sie den Namen, die Abfrage und Optionen für die Suche an. |
| [SearchResponse](./searchresponse) | Enthält Suchantwortinformationen |
| [SearchResponseStore](./searchresponsestore) | Enthält die Elemente Status, Ergebnis, Bereich und Summe für die zurückgegebenen Postfacheinträge. |
| [SearchResult](./searchresult) | Container für ein einzelnes übereinstimmendes Postfachelement. Wenn der durchsuchte Speicher das Postfach ist: – Es gibt ein Ergebniselement für jede Übereinstimmung, die im Postfach gefunden wird. Wenn keine Übereinstimmungen gefunden werden, ist ein leeres Ergebniselement im Store-Containerelement der Antwort-XML vorhanden. - Im Ergebniselement enthält das Properties-Element eine Liste der angeforderten Eigenschaften für das Postfachelement. Wenn der Store das ist Durchsucht wird die Dokumentbibliothek: – Das erste Ergebnis, das in der Suchantwort zurückgegeben wird, sind die Metadaten für den Stammordner oder das Element, auf das der LinkId-Wert zeigt. Der Client kann diesen Eintrag ignorieren, wenn er nicht erforderlich ist. - Wenn der documentlibrary:LinkId-Elementwert in der Anforderung auf einen Ordner verweist, werden die Metadateneigenschaften des Ordners als erstes Element und der Inhalt zurückgegeben der Ordner werden als nachfolgende Ergebnisse zurückgegeben. Der Bereich gilt für diese Ergebnisse ohne Unterschied; Beispielsweise würde der Index 0 immer für das Stammelement stehen, auf das der Link zeigt. - Wenn der documentlibrary:LinkId-Elementwert in der Anfrage auf ein Element zeigt, wird nur ein Ergebnis zurückgegeben: die Metadaten für das Element. - Innerhalb des Elements „Result“ enthält das Element „Properties“ eine Liste der angeforderten Eigenschaften für das Postfachelement. |
| [SearchResultProperties](./searchresultproperties) | Die Antworteigenschaften des Suchbefehls sind ein Container für Eigenschaften, die für einen einzelnen Eintrag gelten, der mit der Suchzeichenfolge des Abfrageelements übereinstimmt. Beispielsweise enthält das Element Properties ein Element für jede nicht leere GAL-Eigenschaft mit Textwert, die dem übereinstimmenden GAL-Eintrag zugeordnet ist. Nur die Eigenschaften, die dem bestimmten GAL-Eintrag zugeordnet sind, werden zurückgegeben; Daher können im Antwort-XML für verschiedene übereinstimmende GAL-Einträge unterschiedliche Eigenschaftensätze zurückgegeben werden. Jedes Element im Eigenschaftencontainer ist auf den entsprechenden Namespace beschränkt, der im Suchelement der obersten Ebene angegeben ist. |
| [ServerInfo](./serverinfo) | Servereinstellungen im AutoErmittlungsvorgang |
| [SettingsRequest](./settingsrequest) | Der Befehl „Settings“ unterstützt Get- und Set-Vorgänge für globale Eigenschaften und Abwesenheitseinstellungen für den Benutzer. Der Befehl „Settings“ sendet auch Geräteinformationen an den Server, implementiert die Wiederherstellung des Gerätekennworts/der persönlichen Identifikationsnummer (PIN) und ruft eine Liste der E-Mail-Adressen des Benutzers ab. |
| [SettingsResponse](./settingsresponse) | Gibt eine Antwort mit Abwesenheitseinstellungen und einer Liste der Benutzerkonten an. |
| [SmartRequest](./smartrequest) | Enthält Smart-Request-Informationen |
| [SmartRequestSource](./smartrequestsource) | Enthält Informationen über die Quellnachricht. |
| [Status](./status) | Zeigt das Ergebnis einer Operation an. |
| [SyncAddClientOperation](./syncaddclientoperation) | Erstellt ein neues Objekt in einer Sammlung auf dem Client. |
| [SyncAddResponse](./syncaddresponse) | Zeigt an, dass ein neues Objekt in einer Sammlung erstellt werden muss. |
| [SyncAddServerOperation](./syncaddserveroperation) | Erstellt ein neues Objekt in einer Sammlung auf dem Server. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Enthält Eigenschaften eines vorhandenen Objekts auf dem Clientgerät, die geändert wurden. Das geänderte Objekt wird durch sein ServerId-Element identifiziert. |
| [SyncChangeResponse](./syncchangeresponse) | Zeigt an, dass ein Objekt geändert wurde. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Enthält Eigenschaften eines vorhandenen Objekts auf dem Server, die geändert wurden. Das geänderte Objekt wird durch sein ServerId-Element identifiziert. |
| [SyncCollectionRequest](./synccollectionrequest) | Klasse enthält Befehle und Optionen, die für eine bestimmte Sammlung gelten. |
| [SyncCollectionResponse](./synccollectionresponse) | Klasse enthält Befehle und Optionen, die für eine Sync-Antwort gelten. |
| [SyncCommandsRequest](./synccommandsrequest) | Enthält Vorgänge, die für eine Sammlung gelten. Verfügbare Operationen sind Hinzufügen, Löschen, Ändern, Abrufen und SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Enthält Vorgänge, die für eine Sammlung gelten. Verfügbare Operationen sind Hinzufügen, Löschen, Ändern, Abrufen und SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Löscht ein Objekt auf dem Clientgerät oder dem Server. Das Objekt wird durch seine ServerId. identifiziert. |
| [SyncFetchResponse](./syncfetchresponse) | Fordert die Anwendungsdaten eines Elements an, das in einer Synchronisierungsantwort vom Server abgeschnitten wurde. |
| [SyncOperationResponse](./syncoperationresponse) | Abstrakte Basisklasse für Antworten auf Synchronisierungsvorgänge |
| [SyncOperationsResponse](./syncoperationsresponse) | Enthält Antworten auf Operationen wie Add, Fetch, Change, die vom Server verarbeitet werden. Die Antwort enthält je nach Vorgang einen Statuscode und weitere Informationen. |
| [SyncOptions](./syncoptions) | Gibt Optionen an, die bestimmte Aspekte der Durchführung der Synchronisierung steuern. |
| [SyncRequest](./syncrequest) | Enthält Synchronisierungsanforderungsparameter |
| [UserInformationResponse](./userinformationresponse) | Enthält den Status der Anfrage und eine Liste mit Kontoinformationen (E-Mail-Adressen) eines Benutzers. |
| [ValueConverter](./valueconverter) | Die Klasse konvertiert die ActiveSync-Protokollversion von der Zeichenfolgendarstellung in eine Aufzählung und zurück. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | ActiveSync-Client-Schnittstelle |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Basis-ActiveSync-Client-Schnittstelle |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum gibt Art der Authentifizierung an |
| [AirSync](./airsync) | AirSync-Namespace des ActiveSync-Protokolls |
| [AirSyncBase](./airsyncbase) | AirSyncBase-Namespace des ActiveSync-Protokolls |
| [AirsyncClass](./airsyncclass) | Identifiziert die Klasse des Elements. Die folgenden Klassen werden für Postfachsuchen unterstützt, wenn die Protokollversion 12.1 ist: - E-Mail - Kalender - Kontakte - Aufgaben Die Klassen SMS und Notizen sind nur verfügbar, wenn die Protokollversion 14.0 oder 14.1 ist. |
| [AirsyncFilterType](./airsyncfiltertype) | Gibt ein optionales Zeitfenster für die Objekte an |
| [AllowBluetooth](./allowbluetooth) | Gibt die Verwendung von Bluetooth auf dem Gerät an. |
| [ASProtocolVersions](./asprotocolversions) | Die ASProtocolVersions gibt die Versionen des ActiveSync-Protokolls an. |
| [BehaviorReplacement](./behaviorreplacement) | Gibt an, wie der Konflikt gelöst wird, der auftritt, wenn ein Objekt sowohl auf dem Client als auch auf dem Server geändert wurde. Der Wert gibt an, welches Objekt – das Client-Objekt oder das Server-Objekt – bei einem Konflikt beibehalten werden soll. |
| [BodyType](./bodytype) | Gibt den Formattyp des Textinhalts des Elements an. |
| [Calendar](./calendar) | Kalendernamensraum des ActiveSync-Protokolls |
| [CertificateRetrieval](./certificateretrieval) | Gibt an, ob S/MIME-Zertifikate vom Server für jeden aufgelösten Empfänger zurückgegeben werden SOLLTEN. |
| [CommandCodes](./commandcodes) | Die folgende Tabelle enthält die numerischen Codes, die den ActiveSync-Befehlen entsprechen. Der numerische Code wird im Feld Befehlscode des base64-codierten URI verwendet, um den Befehl anzugeben. |
| [CommandParameters](./commandparameters) | Befehlsparameter. |
| [ComposeMail](./composemail) | ComposeMail-Namespace des ActiveSync-Protokolls |
| [Contacts](./contacts) | Kontakte-Namespace des ActiveSync-Protokolls |
| [Contacts2](./contacts2) | Contacts2-Namespace des ActiveSync-Protokolls |
| [DocumentLibrary](./documentlibrary) | DocumentLibrary-Namespace des ActiveSync-Protokolls |
| [Email](./email) | E-Mail-Namensraum des ActiveSync-Protokolls |
| [Email2](./email2) | Email2-Namespace des ActiveSync-Protokolls |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Gibt den Algorithmus an, der beim Verschlüsseln von S/MIME-Nachrichten verwendet wird. |
| [FolderClass](./folderclass) | Gibt die Inhaltsklasse des zu überwachenden Ordners an. |
| [FolderHierarchy](./folderhierarchy) | FolderHierarchy Namespace des ActiveSync-Protokolls |
| [FolderTypes](./foldertypes) | Gibt den Typ des Ordners an, der aktualisiert (umbenannt oder verschoben) oder auf dem Server hinzugefügt wurde. |
| [GAL](./gal) | GAL-Namespace des ActiveSync-Protokolls |
| [GetItemEstimate](./getitemestimate) | GetItemEstimate-Namespace des ActiveSync-Protokolls |
| [ItemOperations](./itemoperations) | ItemOperations-Namespace des ActiveSync-Protokolls |
| [MaxAgeFilter](./maxagefilter) | Gibt die maximale Anzahl von Kalendertagen an, die synchronisiert werden können. |
| [MeetingResponse](./meetingresponse) | MeetingResponse-Namespace des ActiveSync-Protokolls |
| [MergedFreeBusy](./mergedfreebusy) | Gibt die Frei/Gebucht-Informationen für die Benutzer oder die Verteilerliste an. |
| [MIMESupport](./mimesupport) | Aktiviert die MIME-Unterstützung für E-Mail-Elemente, die vom Server an den Client gesendet werden. |
| [MIMETruncation](./mimetruncation) | Gibt an, ob die MIME-Daten des E-Mail-Elements abgeschnitten werden SOLLTEN, wenn es vom Server an den Client gesendet wird. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Gibt den erforderlichen Komplexitätsgrad des Clientkennworts an. Beispiel: Wenn der Wert von MinDevicePasswordComplexCharacters 2 ist, wäre ein Kennwort mit Groß- und Kleinbuchstaben ausreichend, ebenso wie ein Kennwort mit Kleinbuchstaben und zahlen. |
| [Move](./move) | Namensraum des ActiveSync-Protokolls verschieben |
| [Namespace](./namespace) | ActiveSync-Codepages |
| [Notes](./notes) | Notes-Namespace des ActiveSync-Protokolls |
| [OofState](./oofstate) | Gibt die Verfügbarkeit der Oof-Eigenschaft an. |
| [Ping](./ping) | Ping-Namespace des ActiveSync-Protokolls |
| [Provision](./provision) | Namespace des ActiveSync-Protokolls bereitstellen |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | Der Wert gibt an, ob der Client erfolgreich oder fehlgeschlagen ist, um die vom Server abgerufenen Richtlinieneinstellungen anzuwenden. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | Der Wert gibt den Erfolg oder Misserfolg eines Remote-Löschvorgangs auf dem Client an. |
| [RecipientType](./recipienttype) | Gibt den Empfängertyp an. |
| [ResolveRecipients](./resolverecipients) | ResolveRecipients-Namespace des ActiveSync-Protokolls |
| [RightsManagement](./rightsmanagement) | RightsManagement-Namespace des ActiveSync-Protokolls |
| [Search](./search) | Namensraum des ActiveSync-Protokolls suchen |
| [ServerType](./servertype) | Gibt den Servertyp an |
| [Settings](./settings) | Namensraum der Einstellungen des ActiveSync-Protokolls |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Gibt den Algorithmus an, der beim Signieren von S/MIME-Nachrichten verwendet wird. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Steuert die Aushandlung des Verschlüsselungsalgorithmus. |
| [StoreType](./storetype) | Enthält Informationen, die den Standort für die Operationen angeben. |
| [Tasks](./tasks) | Aufgaben-Namespace des ActiveSync-Protokolls |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Gibt den Typ des zu erstellenden Ordners an. |
| [UserResponse](./userresponse) | Gibt an, ob die Besprechung angenommen, vorläufig angenommen oder abgelehnt wird. |
| [ValidateCert](./validatecert) | ValidateCert-Namespace des ActiveSync-Protokolls |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
