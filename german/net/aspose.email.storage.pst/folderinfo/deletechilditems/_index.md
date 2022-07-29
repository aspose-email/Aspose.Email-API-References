---
title: DeleteChildItems
second_title: Aspose.Email für .NET-API-Referenz
description: Löscht die untergeordneten Nachrichten.
type: docs
weight: 220
url: /de/net/aspose.email.storage.pst/folderinfo/deletechilditems/
---
## FolderInfo.DeleteChildItems method

Löscht die untergeordneten Nachrichten.

```csharp
public void DeleteChildItems(IEnumerable<string> entryIdCollection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | Die Eintrags-ID-Sammlung. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | Die Bearbeitung der ANSI-Dateiversion ist nicht implementiert. |
| InvalidOperationException | Das PST ist nur zum Lesen geöffnet. oder Das zu löschende Element gehört nicht zu diesem Ordner. oder Der Suchordner kann nicht gelöscht werden. oder Der Ordner \Deleted Items\ kann nicht gelöscht werden. oder Die entryId ist falsch. |
| ArgumentNullException | entryId;Die entryId darf nicht null sein. |

### Siehe auch

* class [FolderInfo](../../folderinfo)
* namensraum [Aspose.Email.Storage.Pst](../../folderinfo)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->