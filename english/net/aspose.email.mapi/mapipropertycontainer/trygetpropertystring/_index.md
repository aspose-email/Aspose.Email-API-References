---
title: MapiPropertyContainer.TryGetPropertyString
second_title: Aspose.Email for .NET API Reference
description: MapiPropertyContainer method. Gets the value of a property as a string decoding an ANSI string with the specified code page
type: docs
weight: 170
url: /net/aspose.email.mapi/mapipropertycontainer/trygetpropertystring/
---
## TryGetPropertyString(long, int) {#trygetpropertystring_3}

Gets the value of a property as a string, decoding an ANSI string with the specified code page.

```csharp
public string TryGetPropertyString(long tag, int codepage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The tag of the property. |
| codepage | Int32 | The code page of an ANSI (8-bit) string. |

### Return Value

The value, or `null` if the property does not exist.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long) {#trygetpropertystring_2}

Gets the value of a property as a string.

```csharp
public string TryGetPropertyString(long tag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The tag of the property. |

### Return Value

The value, or `null` if the property does not exist.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string, int) {#trygetpropertystring_1}

Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

```csharp
public bool TryGetPropertyString(long tag, ref string value, int codepage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The tag of the property. |
| value | String& | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | Int32 | The code page of an ANSI (8-bit) string. |

### Return Value

`true` if the property exists; otherwise, `false`.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string) {#trygetpropertystring}

Gets the value of a property as a string, if the property exists.

```csharp
public bool TryGetPropertyString(long tag, ref string value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The tag of the property. |
| value | String& | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

### Return Value

`true` if the property exists; otherwise, `false`.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)


