---
title: PropertyDataType
second_title: Aspose.Email für .NET-API-Referenz
description: MS-OXCDATA Datenstrukturen
type: docs
weight: 19000
url: /de/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Datenstrukturen

```csharp
public enum PropertyDataType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Unspecified | `0` | Beliebig: Dieser Eigenschaftstypwert stimmt mit jedem Typ überein; ein Server MUSS den tatsächlichen Typ in seiner Antwort zurückgeben. Server DÜRFEN diesen Typ NICHT als Antwort auf eine andere Clientanforderung als NspiGetIDsFromNames oder die RopGetPropertyIdsFromNames ROP-Anforderung ([MS-OXCROPS] Abschnitt 2.2.8.1) zurückgeben. Spezifikationsname: PtypUnspecified; Alternative Namen: PT_UNSPECIFIED; |
| Null | `1` | Keine: Diese Eigenschaft ist ein Platzhalter. Spezifikationsname: PtypNull; Alternative Namen: PT_NULL; |
| Integer16 | `2` | 2 Byte; eine 16-Bit-Ganzzahl Spezifikationsname: PtypInteger16; Alternative Namen: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 Bytes; eine 32-Bit-Ganzzahl Spezifikationsname: PtypInteger32; Alternative Namen: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 Bytes; eine 32-Bit-Gleitkommazahl Spezifikationsname: PtypFloating32; Alternative Namen: PT_FLOAT, PT_R4, Float, r4; |
| Floating64 | `5` | 8 Byte; eine 64-Bit-Gleitkommazahl Spezifikationsname: PtypFloating64; Alternative Namen: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 Byte; eine 64-Bit vorzeichenbehaftete, skalierte ganzzahlige Darstellung eines dezimalen Währungswerts, mit vier Stellen rechts vom Dezimalkomma Spezifikationsname: PtypCurrency; Alternative Namen: PT_CURRENCY, behoben.14.4; |
| FloatingTime | `7` | 8 Byte; eine 64-Bit-Gleitkommazahl, bei der der ganzzahlige Teil die Anzahl der Tage seit dem 30. Dezember 1899 und der Bruchteil den Bruchteil eines Tages seit Mitternacht darstellt Spezifikationsname: PtypFloatingTime; Alternative Namen: PT_APPTIME; Die Datumsinformationen werden durch ganzzahlige Inkremente dargestellt, beginnend mit dem 30. Dezember 1899 Mitternacht als Zeit Null. Die Zeitinformation wird durch den Bruchteil eines Tages seit der vorhergehenden Mitternacht dargestellt. Beispielsweise würde 6:00 Uhr am 4. Januar 1900 durch den Wert 5,25 dargestellt (5 und 1/4 eines Tages nach dem 30. Dezember 1899). |
| ErrorCode | `10` | 4 Byte; eine 32-Bit-Integer-Codierungsfehlerinformation Spezifikationsname: PtypErrorCode; Alternative Namen: PT_ERROR; |
| Boolean | `11` | 1 Byte; auf 1 oder 0 beschränkt Spezifikationsname: PtypBoolean; Alternative Namen: PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 Bytes; eine 64-Bit-Ganzzahl Spezifikationsname: PtypInteger64; Alternative Namen: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Variable Größe; eine Zeichenfolge aus Unicode-Zeichen im UTF-16LE-Format mit abschließendem Nullzeichen (0x0000). Spezifikationsname: PtypString; Alternative Namen: PT_UNICODE, string; |
| String8 | `30` | Variable Größe; eine Folge von Multibyte-Zeichen in extern spezifizierter Codierung mit abschließendem Nullzeichen (einzelnes 0-Byte). Spezifikationsname: PtypString8; Alternative Namen: PT_STRING8; |
| Time | `64` | 8 Byte; eine 64-Bit-Ganzzahl, die die Anzahl der 100-Nanosekunden-Intervalle seit dem 1. Januar 1601 darstellt Spezifikationsname: PtypTime; Alternative Namen: PT_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| Guid | `72` | 16 Byte; eine GUID mit den Feldern Data1, Data2 und Data3 im Little-Endian-Format Spezifikationsname: PtypGuid; Alternative Namen: PT_CLSID, UUID; |
| ServerId | `251` | Variable Größe; ein 16-Bit-COUNT-Feld gefolgt von einer Struktur Spezifikationsname: PtypServerId; Alternative Namen: PT_SVREID; |
| Restriction | `253` | Variable Größe; ein Byte-Array, das eine oder mehrere Beschränkungsstrukturen darstellt Spezifikationsname: PtypRestriction; Alternative Namen: PT_SRESTRICT; |
| RuleAction | `254` | Variable Größe; ein 16-Bit-COUNT-Feld, gefolgt von so vielen Regelaktionsstrukturen Spezifikationsname: PtypRuleAction; Alternative Namen: PT_ACTIONS; |
| Binary | `258` | Variable Größe; ein COUNT-Feld gefolgt von so vielen Bytes. Spezifikationsname: PtypBinary; Alternative Namen: PT_BINARY; |
| MultipleInteger16 | `4098` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypInteger16-Werten. Spezifikationsname: PtypMultipleInteger16; Alternative Namen: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypInteger32-Werten. Spezifikationsname: PtypMultipleInteger32; Alternative Namen: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypFloating32-Werten. Spezifikationsname: PtypMultipleFloating32; Alternative Namen: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypFloating64-Werten. Spezifikationsname: PtypMultipleFloating64; Alternative Namen: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypCurrency-Werten. Spezifikationsname: PtypMultipleCurrency; Alternative Namen: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypFloatingTime-Werten. Spezifikationsname: PtypMultipleFloatingTime; Alternative Namen: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypBoolean-Werten. Spezifikationsname: PtypMultipleBoolean; Alternative Namen: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypInteger64-Werten. Spezifikationsname: PtypMultipleInteger64; Alternative Namen: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypString-Werten. Spezifikationsname: PtypMultipleString; Alternative Namen: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypString8-Werten. Spezifikationsname: PtypMultipleString8; Alternative Namen: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypTime-Werten. Spezifikationsname: PtypMultipleTime; Alternative Namen: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypGuid-Werten. Spezifikationsname: PtypMultipleGuid; Alternative Namen: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Variable Größe; ein COUNT-Feld, gefolgt von so vielen PtypBinary-Werten. Spezifikationsname: PtypMultipleBinary; Alternative Namen: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | Der Eigenschaftswert ist ein COM-Objekt (Component Object Model). Spezifikationsname: PtypObject oder PtypEmbeddedTable; Alternative Namen: PT_OBJECT; |

### Siehe auch

* namensraum [Aspose.Email.Mapi](../../aspose.email.mapi)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
