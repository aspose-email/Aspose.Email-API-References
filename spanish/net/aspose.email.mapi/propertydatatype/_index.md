---
title: PropertyDataType
second_title: Referencia de la API de Aspose.Email para .NET
description: MS-OXCDATA Estructuras de datos
type: docs
weight: 19000
url: /es/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Estructuras de datos

```csharp
public enum PropertyDataType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Unspecified | `0` | Cualquiera: el valor de este tipo de propiedad coincide con cualquier tipo; un servidor DEBE devolver el tipo real en su respuesta. Los servidores NO DEBEN devolver este tipo en respuesta a una solicitud del cliente que no sea NspiGetIDsFromNames o la solicitud ROP RopGetPropertyIdsFromNames ([MS-OXCROPS] sección 2.2.8.1). Nombre de la especificación: PtypUnspecified; Nombres alternativos: PT_UNSPECIFIED; |
| Null | `1` | Ninguno: esta propiedad es un marcador de posición. Nombre de la especificación: PtypNull; Nombres alternativos: PT_NULL; |
| Integer16 | `2` | 2 bytes; un entero de 16 bits Nombre de la especificación: PtypInteger16; Nombres alternativos: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 bytes; un entero de 32 bits Nombre de la especificación: PtypInteger32; Nombres alternativos: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 bytes; un número de coma flotante de 32 bits Nombre de la especificación: PtypFloating32; Nombres alternativos: PT_FLOAT, PT_R4, float, r4; |
| Floating64 | `5` | 8 bytes; un número de punto flotante de 64 bits Nombre de la especificación: PtypFloating64; Nombres alternativos: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 bytes; una representación de entero escalado con signo de 64 bits de un valor de moneda decimal, con cuatro lugares a la derecha del punto decimal Nombre de la especificación: PtypCurrency; Nombres alternativos: PT_CURRENCY, fixed.14.4; |
| FloatingTime | `7` | 8 bytes; un número de punto flotante de 64 bits en el que la parte entera representa el número de días desde el 30 de diciembre de 1899, y la parte fraccionaria representa la fracción de un día desde la medianoche Nombre de la especificación: PtypFloatingTime; Nombres alternativos: PT_APPTIME; La información de la fecha se representa mediante incrementos de números enteros, comenzando con la medianoche del 30 de diciembre de 1899 como hora cero. La información de tiempo está representada por la fracción de un día desde la medianoche anterior. Por ejemplo, las 6:00 a. m. del 4 de enero de 1900 estarían representadas por el valor 5,25 (5 y 1/4 de un día después del 30 de diciembre de 1899). |
| ErrorCode | `10` | 4 bytes; una información de error de codificación de entero de 32 bits Nombre de la especificación: PtypErrorCode; Nombres alternativos: PT_ERROR; |
| Boolean | `11` | 1 byte; restringido a 1 o 0 Nombre de la especificación: PtypBoolean; Nombres alternativos: PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 bytes; un entero de 64 bits Nombre de la especificación: PtypInteger64; Nombres alternativos: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Tamaño variable; una cadena de caracteres Unicode en codificación de formato UTF-16LE con un carácter nulo de terminación (0x0000). Nombre de la especificación: PtypString; Nombres alternativos: PT_UNICODE, cadena; |
| String8 | `30` | Tamaño variable; una cadena de caracteres de varios bytes en una codificación especificada externamente con un carácter nulo de terminación (un solo 0 byte). Nombre de la especificación: PtypString8; Nombres alternativos: PT_STRING8; |
| Time | `64` | 8 bytes; un entero de 64 bits que representa el número de intervalos de 100 nanosegundos desde el 1 de enero de 1601 Nombre de la especificación: PtypTime; Nombres alternativos: PT_SYSTIME, hora, fechahora, fechahora.tz, fechahora.rfc1123, Fecha, hora, hora.tz; |
| Guid | `72` | 16 bytes; un GUID con campos Data1, Data2 y Data3 en formato little-endian Nombre de la especificación: PtypGuid; Nombres alternativos: PT_CLSID, UUID; |
| ServerId | `251` | Tamaño variable; un campo COUNT de 16 bits seguido de una estructura Nombre de la especificación: PtypServerId; Nombres alternativos: PT_SVREID; |
| Restriction | `253` | Tamaño variable; una matriz de bytes que representa una o más estructuras de restricción Nombre de la especificación: PtypRestriction; Nombres alternativos: PT_SRESTRICT; |
| RuleAction | `254` | Tamaño variable; un campo COUNT de 16 bits seguido de tantas estructuras de acción de regla Nombre de la especificación: PtypRuleAction; Nombres alternativos: PT_ACTIONS; |
| Binary | `258` | Tamaño variable; un campo COUNT seguido de esa cantidad de bytes. Nombre de la especificación: PtypBinary; Nombres alternativos: PT_BINARY; |
| MultipleInteger16 | `4098` | Tamaño variable; un campo COUNT seguido de tantos valores PtypInteger16. Nombre de la especificación: PtypMultipleInteger16; Nombres alternativos: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Tamaño variable; un campo COUNT seguido de tantos valores PtypInteger32. Nombre de la especificación: PtypMultipleInteger32; Nombres alternativos: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Tamaño variable; un campo COUNT seguido de tantos valores PtypFloating32. Nombre de la especificación: PtypMultipleFloating32; Nombres alternativos: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Tamaño variable; un campo COUNT seguido de tantos valores PtypFloating64. Nombre de la especificación: PtypMultipleFloating64; Nombres alternativos: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Tamaño variable; un campo COUNT seguido de tantos valores de PtypCurrency. Nombre de la especificación: PtypMultipleCurrency; Nombres alternativos: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Tamaño variable; un campo COUNT seguido de tantos valores de PtypFloatingTime. Nombre de la especificación: PtypMultipleFloatingTime; Nombres alternativos: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Tamaño variable; un campo COUNT seguido de tantos valores PtypBoolean. Nombre de la especificación: PtypMultipleBoolean; Nombres alternativos: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Tamaño variable; un campo COUNT seguido de tantos valores PtypInteger64. Nombre de la especificación: PtypMultipleInteger64; Nombres alternativos: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Tamaño variable; un campo COUNT seguido de tantos valores de PtypString. Nombre de la especificación: PtypMultipleString; Nombres alternativos: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Tamaño variable; un campo COUNT seguido de tantos valores PtypString8. Nombre de la especificación: PtypMultipleString8; Nombres alternativos: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Tamaño variable; un campo COUNT seguido de tantos valores de PtypTime. Nombre de la especificación: PtypMultipleTime; Nombres alternativos: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Tamaño variable; un campo COUNT seguido de tantos valores PtypGuid. Nombre de la especificación: PtypMultipleGuid; Nombres alternativos: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Tamaño variable; un campo COUNT seguido de tantos valores PtypBinary. Nombre de la especificación: PtypMultipleBinary; Nombres alternativos: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | El valor de la propiedad es un objeto del Modelo de objetos componentes (COM). Nombre de la especificación: PtypObject o PtypEmbeddedTable; Nombres alternativos: PT_OBJECT; |

### Ver también

* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
