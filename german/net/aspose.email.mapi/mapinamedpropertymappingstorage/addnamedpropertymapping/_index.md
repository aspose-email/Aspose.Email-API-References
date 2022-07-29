---
title: AddNamedPropertyMapping
second_title: Aspose.Email für .NET-API-Referenz
description: Fügt die benannte Eigenschaftszuordnung für die numerische benannte Eigenschaft hinzu.
type: docs
weight: 40
url: /de/net/aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping/
---
## AddNamedPropertyMapping(MapiProperty, long, Guid) {#addnamedpropertymapping}

Fügt die benannte Eigenschaftszuordnung für die numerische benannte Eigenschaft hinzu.

```csharp
public void AddNamedPropertyMapping(MapiProperty property, long nameId, Guid guid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| property | MapiProperty | Die Eigenschaft, für die eine Zuordnung hinzugefügt werden soll. |
| nameId | Int64 | Die Namens-ID. |
| guid | Guid | Die GUID, die den Eigenschaftssatz identifiziert. |

### Bemerkungen

*property* sollte eine gültige ID für benannte Eigenschaft haben,[`GetNextAvailablePropertyId`](../getnextavailablepropertyid) kann verwendet werden, um eine zu generieren. Andernfalls wird eine Ausnahme ausgelöst.

### Siehe auch

* class [MapiProperty](../../mapiproperty)
* class [MapiNamedPropertyMappingStorage](../../mapinamedpropertymappingstorage)
* namensraum [Aspose.Email.Mapi](../../mapinamedpropertymappingstorage)
* Montage [Aspose.Email](../../../)

---

## AddNamedPropertyMapping(MapiProperty, string, Guid) {#addnamedpropertymapping_1}

Fügt die benannte Eigenschaftszuordnung für die Zeichenfolge namens Eigenschaft hinzu.

```csharp
public void AddNamedPropertyMapping(MapiProperty property, string nameId, Guid guid)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| property | MapiProperty | Die Eigenschaft, für die eine Zuordnung hinzugefügt werden soll. |
| nameId | String | Die Namens-ID. |
| guid | Guid | Die GUID, die den Eigenschaftssatz identifiziert. |

### Bemerkungen

*property* sollte eine gültige ID für benannte Eigenschaft haben,[`GetNextAvailablePropertyId`](../getnextavailablepropertyid) kann verwendet werden, um eine zu generieren. Andernfalls wird eine Ausnahme ausgelöst.

### Siehe auch

* class [MapiProperty](../../mapiproperty)
* class [MapiNamedPropertyMappingStorage](../../mapinamedpropertymappingstorage)
* namensraum [Aspose.Email.Mapi](../../mapinamedpropertymappingstorage)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->