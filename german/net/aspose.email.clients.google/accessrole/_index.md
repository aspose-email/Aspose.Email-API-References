---
title: AccessRole
second_title: Aspose.Email für .NET-API-Referenz
description: Die effektive Zugriffsrolle die der authentifizierte Benutzer für den Kalender hat.
type: docs
weight: 15590
url: /de/net/aspose.email.clients.google/accessrole/
---
## AccessRole enumeration

Die effektive Zugriffsrolle, die der authentifizierte Benutzer für den Kalender hat.

```csharp
public enum AccessRole
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| none | `0` | Nicht definiert |
| freeBusyReader | `1` | Bietet Lesezugriff auf Frei/Gebucht-Informationen. |
| reader | `2` | Bietet Lesezugriff auf den Kalender. Private Veranstaltungen werden Benutzern mit Lesezugriff angezeigt, aber Veranstaltungsdetails werden ausgeblendet. |
| writer | `3` | Bietet Lese- und Schreibzugriff auf den Kalender. Private Ereignisse werden Benutzern mit Schreibzugriff angezeigt, und Ereignisdetails sind sichtbar. |
| owner | `4` | Stellt den Besitz des Kalenders bereit. Diese Rolle hat alle Berechtigungen der Writer-Rolle mit der zusätzlichen Möglichkeit, ACLs zu sehen und zu manipulieren. |

### Siehe auch

* namensraum [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->