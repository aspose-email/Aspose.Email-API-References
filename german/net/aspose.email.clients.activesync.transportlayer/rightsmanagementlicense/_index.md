---
title: RightsManagementLicense
second_title: Aspose.Email für .NET-API-Referenz
description: Enthält die Rechterichtlinienvorlageneinstellungen für die Vorlage die auf die zu synchronisierende E-Mail-Nachricht angewendet wird.
type: docs
weight: 1900
url: /de/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Enthält die Rechterichtlinienvorlageneinstellungen für die Vorlage, die auf die zu synchronisierende E-Mail-Nachricht angewendet wird.

```csharp
public class RightsManagementLicense
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Gibt das Ablaufdatum für die Lizenz an. Das ContentExpiryDate-Element wird auf „9999-12-30T23:59:59.999Z“ gesetzt, wenn für die Rechteverwaltungslizenz kein Ablaufdatum festgelegt ist. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Gibt an, ob der Inhalt der ursprünglichen E-Mail vom Benutzer geändert werden kann, wenn der Benutzer die E-Mail-Nachricht weiterleitet, beantwortet oder vollständig beantwortet. Der Wert ist TRUE, wenn die E-Mail vom Benutzer geändert werden kann; andernfalls FALSE. Der Wert FALSE erfordert, dass der Client die ursprüngliche rechteverwaltete E-Mail-Nachricht von der SmartForward- oder SmartReply-Anforderung ausschließen MUSS. Folglich sind Inline-Antworten nicht zulässig, wenn das EditAllowed-Element auf FALSE gesetzt ist. Wenn EditAllowed auf FALSE gesetzt ist und ReplaceMime in einer SmartForward- oder SmartReply-Anforderung nicht vorhanden ist, fügt der Server die ursprüngliche E-Mail-Nachricht mit verwalteten Rechten als Anlage zur neuen Nachricht hinzu. Umgekehrt, wenn ReplaceMime vorhanden ist, hängt der Server die ursprüngliche rechteverwaltete E-Mail-Nachricht nicht als Anhang an. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Gibt an, ob der Inhalt der ursprünglichen E-Mail vom Benutzer geändert werden kann, wenn der Benutzer die E-Mail-Nachricht weiterleitet, beantwortet oder vollständig beantwortet. Der Wert ist TRUE, wenn die E-Mail vom Benutzer geändert werden kann; andernfalls FALSE. Der Wert FALSE erfordert, dass der Client die ursprüngliche rechteverwaltete E-Mail-Nachricht von der SmartForward- oder SmartReply-Anforderung ausschließen MUSS. Folglich sind Inline-Antworten nicht zulässig, wenn das EditAllowed-Element auf FALSE gesetzt ist. Wenn EditAllowed auf FALSE gesetzt ist und ReplaceMime in einer SmartForward- oder SmartReply-Anforderung nicht vorhanden ist, fügt der Server die ursprüngliche E-Mail-Nachricht mit verwalteten Rechten als Anlage zur neuen Nachricht hinzu. Umgekehrt, wenn composemail:ReplaceMime vorhanden ist, hängt der Server die ursprüngliche rechteverwaltete E-Mail-Nachricht nicht als Anlage an. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | Gibt an, ob der IRM-Schutz der E-Mail-Nachricht vom Benutzer entfernt werden kann. Der Wert ist TRUE, wenn der Benutzer den IRM-Schutz entfernen kann, wenn der Benutzer die E-Mail-Nachricht weiterleitet, beantwortet oder vollständig beantwortet; andernfalls FALSE. Wenn eine E-Mail-Nachricht mit verwalteten Rechten mithilfe des SmartForward- oder SmartReply-Befehls weitergeleitet oder beantwortet wird, werden die folgenden Bedingungen ausgewertet: – Bei der ursprünglichen Rechterichtlinienvorlage ist das ExportAllowed-Element auf TRUE gesetzt – Die Vorlagen-ID auf der neuen Nachricht ist auf die Vorlage "Keine Einschränkung" festgelegt (Vorlagen-ID-Wert "00000000-0000-0000-0000-000000000000") Wenn beide Bedingungen erfüllt sind, wird der IRM-Schutz von der ausgehenden Nachricht entfernt. Die ursprüngliche Nachricht behält ihren IRM-Schutz. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Gibt an, ob der Benutzer Inhalt aus der E-Mail-Nachricht kopieren kann. Der Wert ist TRUE, wenn der Inhalt der E-Mail-Nachricht ausgeschnitten, kopiert oder ein Screenshot des Inhalts gemacht werden kann; andernfalls FALSE. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Gibt an, ob der Benutzer die E-Mail-Nachricht weiterleiten kann. Der Wert ist TRUE, wenn der Benutzer die E-Mail-Nachricht weiterleiten kann; andernfalls FALSE. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Gibt an, ob der Benutzer die Empfängerliste ändern kann, wenn der Benutzer die E-Mail-Nachricht weiterleitet oder beantwortet. Der Wert ist TRUE, wenn der Benutzer die Empfängerliste (1) ändern kann; andernfalls FALSE. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Gibt an, ob der Benutzer der Besitzer der E-Mail-Nachricht ist. Der Wert ist TRUE, wenn der Benutzer der Besitzer der E-Mail-Nachricht ist; andernfalls FALSCH. Der Wert TRUE gibt an, dass der authentifizierte Benutzer Eigentümerrechte für diese Nachricht hat. Dieses Element dient nur der Informationsdarstellung. Die Allowed-Elemente (EditAllowed, ReplyAllowed usw.) werden verwendet, um auszuwerten, ob eine bestimmte Aktion erlaubt oder eingeschränkt ist. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | Gibt an, ob die E-Mail vom Benutzer gedruckt werden kann. Dieses Element gibt keine Clientunterstützung zum Drucken einer E-Mail-Nachricht an; es gibt nur an, ob die E-Mail-Nachricht gedruckt werden kann, wenn der Client das Drucken unterstützt. Der Wert ist TRUE, wenn die E-Mail vom Benutzer gedruckt werden kann; andernfalls FALSE. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | Gibt an, ob Anwendungen von Drittanbietern programmgesteuert auf den Inhalt der E-Mail-Nachricht zugreifen können. Der Wert ist TRUE, wenn Anwendungen von Drittanbietern programmgesteuert auf den Inhalt der E-Mail-Nachricht zugreifen können; andernfalls FALSCH. Der Wert TRUE gibt an, ob der geschützte Inhalt für andere Anwendungen zugänglich ist. Geschützter Inhalt besteht aus dem Nachrichtentext und Anhängen. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Gibt an, ob der Benutzer allen Empfängern (1) der ursprünglichen E-Mail-Nachricht antworten kann. Der Wert ist TRUE, wenn der Benutzer allen Empfängern der E-Mail-Nachricht antworten kann; andernfalls FALSE. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Gibt an, ob der Benutzer auf die E-Mail-Nachricht antworten darf. Der Wert ist TRUE, wenn der Benutzer auf die E-Mail-Nachricht antworten kann; andernfalls FALSE. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Enthält eine Beschreibung der Rechterichtlinienvorlage, die durch das übergeordnete RightsManagementLicense-Element dargestellt wird. Dieses Element wird nur zu Informationszwecken verwendet. Die maximale Länge des TemplateDescription-Elements beträgt 10240 Zeichen. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Enthält eine Zeichenfolge, die die Rechterichtlinienvorlage identifiziert, die durch das übergeordnete RightsManagementLicense-Element dargestellt wird. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Gibt den Namen der Rechterichtlinienvorlage an, die durch das übergeordnete RightsManagementLicense-Element dargestellt wird. Dieses Element wird nur zu Informationszwecken verwendet. Die maximale Länge des TemplateName-Elements beträgt 256 Zeichen. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
