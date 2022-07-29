---
title: Save
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda estoMapiTaskaspose.email.mapi/mapitask al flujo dado usando el formato especificado.
type: docs
weight: 220
url: /es/net/aspose.email.mapi/mapitask/save/
---
## Save(Stream, TaskSaveFormat) {#save}

Guarda esto[`MapiTask`](../../mapitask) al flujo dado usando el formato especificado.

```csharp
public void Save(Stream stream, TaskSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar. |
| saveFormat | TaskSaveFormat | Un formato de guardado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream* es`nulo` . |
| NotSupportedException | *stream* no admite la escritura. |
| NotSupportedException | El formato especificado no es compatible. |

### Ver también

* enum [TaskSaveFormat](../../tasksaveformat)
* class [MapiTask](../../mapitask)
* espacio de nombres [Aspose.Email.Mapi](../../mapitask)
* asamblea [Aspose.Email](../../../)

---

## Save(string, TaskSaveFormat) {#save_1}

Guarda esto[`MapiTask`](../../mapitask) en el archivo usando el formato especificado.

```csharp
public void Save(string filePath, TaskSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Un nombre de archivo. |
| saveFormat | TaskSaveFormat | Un formato de guardado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío`. |
| NotSupportedException | alguna opción de guardar no es compatible |

### Ver también

* enum [TaskSaveFormat](../../tasksaveformat)
* class [MapiTask](../../mapitask)
* espacio de nombres [Aspose.Email.Mapi](../../mapitask)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->