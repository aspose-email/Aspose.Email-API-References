---
title: ExchangeFolderType
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die unterschiedlichen Ordnertypen auf. Diese Werte sind auch in der PidTagContainerClass-Eigenschaft enthalten.
type: docs
weight: 3340
url: /de/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Listet die unterschiedlichen Ordnertypen auf. Diese Werte sind auch in der PidTagContainerClass-Eigenschaft enthalten.

```csharp
public enum ExchangeFolderType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Undefined | `0` | Der Ordnertyp ist nicht festgelegt. Der Wert wird mit den folgenden bekannten Ordnern verwendet: Root – Der oberste Ordner der Nachrichtenspeicherhierarchie, der alle anderen Ordnerobjekte in diesem Nachrichtenspeicher enthält. Finder – Enthält die Standardsuchordner. Frei/Gebucht-Daten – Enthält die Frei/Gebucht-Daten des Postfachbesitzers. Anfang der persönlichen Ordner – Der oberste Ordner der Hierarchie zwischenmenschlicher Nachrichten, der Benutzerdatenordner enthält, einschließlich der meisten speziellen Ordner wie dem Posteingangsordner. Allgemeine Ansichten – Enthält die Daten für Standardansichten, die für den Nachrichtenspeicher standardmäßig sind und die von jedem Benutzer eines Clients verwendet werden können, der auf den Nachrichtenspeicher zugreift. Persönliche Ansichten – Enthält die Daten für Ansichten, die von einem bestimmten Benutzer definiert wurden. Deferred Action – Enthält alle verzögerten Action Message (DAM) oder Deferred Error Message (DEM), die aus der Ausführung clientseitiger Regeln resultiert. |
| Note | `1` | Dieser Wert repräsentiert den Ordnertyp für E-Mail-Nachrichten ("IPF.Note"). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Gelöschte Elemente - Der Standardspeicherort für gelöschte Objekte. Postausgang - Ausgehende E-Mail Nachrichtenobjekte werden in diesem Ordner abgelegt, wenn das Nachrichtenobjekt gesendet wird. Gesendete Elemente – Der Standardspeicherort, an dem Kopien von E-Mail-Nachrichtenobjekten abgelegt werden, nachdem sie übermittelt (gesendet) wurden. Posteingang – Der Standardspeicherort für eingehende ( erhalten) E-Mail-Nachrichtenobjekte. Entwürfe – Der Standardspeicherort für erstellte E-Mail-Nachrichtenobjekte, die gespeichert, aber nicht gesendet wurden. Junk-E-Mail – Standardspeicherort für E-Mail-Nachrichtenobjekte, die als Junk-E-Mail bestimmt wurden durch eine Junk-E-Mail-Regel. Synchronisierungsprobleme – Enthält Ordner mit Meldungen, die auf bestimmte Probleme hinweisen, die während der Synchronisierung zwischen Client und Server aufgetreten sind. Dies ist der übergeordnete Ordner der Ordner „Konflikte“, „Lokale Fehler“ und „Serverfehler“. Konflikte – Enthält Nachrichtenobjekte, die auf Synchronisierungskonflikte zwischen Client und Server hinweisen. Lokale Fehler – Enthält Nachrichten, die auf clientseitige Synchronisierungsfehler hinweisen. Serverfehler - Enthält Meldungen, die auf serverseitige Synchronisierungsfehler hinweisen. Nachverfolgte E-Mail-Verarbeitung - Suchordner, der gekennzeichnete Objekte enthält. Spooler-Warteschlange - Enthält E-Mail-Objekte, die gesendet oder empfangen wurden. |
| RSSFeeds | `2` | Dieser Wert repräsentiert den RSS-Nachrichtenordnertyp ("IPF.Note.OutlookHomepage"). Der Wert wird mit den folgenden bekannten Ordnern verwendet: RSS-Feeds - Enthält RSS-Feed-Nachrichten (Really Simple Syndication). |
| Appointment | `3` | Dieser Wert stellt den Ordnertyp „Termin“ dar („IPF.Appointment“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Kalender – Enthält Kalenderobjekte wie Termine. |
| Contact | `4` | Dieser Wert repräsentiert den Ordnertyp „Kontakte“ („IPF.Contact“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Kontakte – Enthält Kontaktobjekte. Vorgeschlagene Kontakte – Enthält Kontaktobjekte, die erstellt werden, wenn kein Empfänger vorhanden ist in einem Adressbuch. Kontaktsuche – Suchordner, der eine Liste mit Kontakten anzeigt, die den Suchkriterien entsprechen. |
| QuickContacts | `5` | Dieser Wert repräsentiert den Ordnertyp für bevorzugte Kontakte ("IPF.Contact.MOC.QuickContacts"). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Schnellkontakte - Enthält Kontaktobjekte für die bevorzugten Kontakte des Benutzers und Instant Messaging-Kontakte. |
| ImContactsList | `6` | Dieser Wert stellt den Ordnertyp für Instant Messaging-Kontakte dar („IPF.Contact.MOC.ImContactList“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: IM-Kontaktliste – Enthält persönliche Verteilerlistenobjekte von bevorzugten Kontakten und Instant Messaging-Kontakten . |
| DocumentLibraries | `7` | Dieser Wert repräsentiert den Ordnertyp „Dokumente“ („IPF.ShortcutFolder“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Dokumentbibliotheken – Enthält Dokumente, die an einen freigegebenen Speicherort hochgeladen werden sollen. |
| Journal | `8` | Dieser Wert repräsentiert den Ordnertyp „Journal“ („IPF.Journal“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Journal – Enthält Journalobjekte. |
| StickyNote | `9` | Dieser Wert repräsentiert den Ordnertyp „Notizen“ („IPF.StickyNote“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: Notizen – Enthält Notizobjekte. |
| Task | `10` | Dieser Wert repräsentiert den Ordnertyp „Aufgabe“ („IPF.Task“). Der Wert wird mit den folgenden bekannten Ordnern verwendet: To-Do – Suchordner, der zum Verfolgen von Aufgabenobjekten verwendet wird. Aufgaben – Enthält Aufgabenobjekte. |
| Imap | `11` | Dieser Wert repräsentiert den Ordnertyp „imap“ („IPF.IMAP“). Wird verwendet, um vom IMAP-Profil zu Exchange zu migrieren. |
| Unknown | `12` | Ordnertyp ist unbekannt. |

### Siehe auch

* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
