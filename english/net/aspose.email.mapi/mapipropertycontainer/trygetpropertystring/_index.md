---
title: MapiPropertyContainer.TryGetPropertyString
second_title: Aspose.Email for .NET API Reference
description: MapiPropertyContainer method. Try to get a property data as string with specified tag and code page
type: docs
weight: 170
url: /net/aspose.email.mapi/mapipropertycontainer/trygetpropertystring/
---
## TryGetPropertyString(long, int) {#trygetpropertystring_3}

Try to get a property data as string with specified tag and code page.

```csharp
public string TryGetPropertyString(long tag, int codepage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The property tag key. |
| codepage | Int32 | The code page. |

### Return Value

String that contains the contents of property data.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long) {#trygetpropertystring_2}

Try to get a property data as string with specified tag.

```csharp
public string TryGetPropertyString(long tag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The property tag key. |

### Return Value

String that contains the contents of property data.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string, int) {#trygetpropertystring_1}

Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

```csharp
public bool TryGetPropertyString(long tag, ref string value, int codepage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The MAPI property tag. |
| value | String& | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |
| codepage | Int32 | The specified codepage used to get string value. |

### Return Value

true if s was converted successfully; otherwise, false.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string) {#trygetpropertystring}

Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

```csharp
public bool TryGetPropertyString(long tag, ref string value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Int64 | The MAPI property tag. |
| value | String& | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

### Return Value

true if s was converted successfully; otherwise, false.

### See Also

* class [MapiPropertyContainer](../)
* namespace [Aspose.Email.Mapi](../../mapipropertycontainer/)
* assembly [Aspose.Email](../../../)


