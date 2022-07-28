---
title: PropertyDataType
second_title: Aspose.Email för .NET API-referens
description: MS-OXCDATA Data Structures
type: docs
weight: 19000
url: /sv/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Data Structures

```csharp
public enum PropertyDataType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Unspecified | `0` | Alla: den här egenskapstypens värde matchar vilken typ som helst; en server MÅSTE returnera den faktiska typen i sitt svar. Servrar FÅR INTE returnera denna typ som svar på en klientförfrågan annan än NspiGetIDsFromNames eller RopGetPropertyIdsFromNames ROP-begäran ([MS-OXCROPS] avsnitt 2.2.8.1). Specifikationsnamn: PtypUn Alternativa namn: PT_UNSPECIFIED; |
| Null | `1` | Ingen: Den här egenskapen är en platshållare. Specifikationsnamn: PtypNull; Alternativa namn: PT_NULL; |
| Integer16 | `2` | 2 byte; ett 16-bitars heltal Specifikationsnamn: PtypInteger16; Alternativa namn: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 byte; ett 32-bitars heltal Specifikationsnamn: PtypInteger32; Alternativa namn: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 byte; ett 32-bitars flyttal number Specifikationsnamn: PtypFloating32; Alternativa namn: PT_FLOAT, PT_R4, float, r4; |
| Floating64 | `5` | 8 byte; ett 64-bitars flyttal nummer Specifikationsnamn: PtypFloating64; Alternativa namn: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 byte; en 64-bitars signerad, skalad heltalsrepresentation av ett decimalt valutavärde, med fyra ställen till höger om decimalpunkten Specifikationsnamn: PtypCurrency; Alternativa namn: PT_CURRENCY, fixed.14.4; |
| FloatingTime | `7` | 8 byte; ett 64-bitars flyttal där hela taldelen representerar antalet dagar sedan 30 december 1899, och bråkdelen representerar bråkdelen av en dag sedan midnight Specifikationsnamn: PtypFloatingTime; Alternativa namn: PT_APPTIME; Datuminformationen representeras av helnummersteg, med början den 30 december 1899 midnatt som tid noll. Tidsinformationen representeras av bråkdelen av en dag sedan föregående midnatt. Till exempel skulle kl. 06.00 den 4 januari 1900 representeras av värdet 5,25 (5 och 1/4 av en dag efter den 30 december 1899). |
| ErrorCode | `10` | 4 byte; en 32-bitars heltalskodningsfelinformation Specifikationsnamn: PtypErrorCode; Alternativa namn: PT_ERROR; |
| Boolean | `11` | 1 byte; begränsad till 1 eller 0 Specifikationsnamn: PtypBoolean; Alternativa namn: PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 byte; ett 64-bitars heltal Specifikationsnamn: PtypInteger64; Alternativa namn: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Variabel storlek; en sträng av Unicode-tecken i UTF-16LE-format som kodar med ett avslutande nolltecken (0x0000). Specifikationsnamn: PtypString; Alternativa namn: PT_UNICODE, string; |
| String8 | `30` | Variabel storlek; en sträng av multibyte-tecken i externt specificerad kodning med avslutande null-tecken (enkel 0 byte). Specifikationsnamn: PtypString8; Alternativa namn: PT_STRING8; |
| Time | `64` | 8 byte; ett 64-bitars heltal som representerar antalet 100-nanosekundersintervaller sedan 1 januari 1601 Specifikationsnamn: PtypTime; Alternativa namn: PT_SYSTIME, tid, datetime, datetime.tz, datetime.rfc1123, Datum, tid, time.tz; |
| Guid | `72` | 16 byte; en GUID med fälten Data1, Data2 och Data3 i little-endian format Specifikationsnamn: PtypGuid; Alternativa namn: PT_CLSID, UUID; |
| ServerId | `251` | Variabel storlek; ett 16-bitars COUNT-fält följt av en struktur Specifikationsnamn: PtypServerId; Alternativa namn: PT_SVREID; |
| Restriction | `253` | Variabel storlek; en byte-array som representerar en eller flera restriktionsstrukturer Specifikationsnamn: PtypRestriction; Alternativa namn: PT_SRESTRICT; |
| RuleAction | `254` | Variabel storlek; ett 16-bitars COUNT-fält följt av så många regelåtgärdsstrukturer Specifikationsnamn: PtypRuleAction; Alternativa namn: PT_ACTIONS; |
| Binary | `258` | Variabel storlek; ett COUNT-fält följt av så många byte. Specifikationsnamn: PtypBinary; Alternativa namn: PT_BINARY; |
| MultipleInteger16 | `4098` | Variabel storlek; ett COUNT-fält följt av så många PtypInteger16-värden. Specifikationsnamn: PtypMultipleInteger16; Alternativa namn: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Variabel storlek; ett COUNT-fält följt av så många PtypInteger32-värden. Specifikationsnamn: PtypMultipleInteger32; Alternativa namn: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Variabel storlek; ett COUNT-fält följt av så många PtypFloating32-värden. Specifikationsnamn: PtypMultipleFloating32; Alternativa namn: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Variabel storlek; ett COUNT-fält följt av så många PtypFloating64-värden. Specifikationsnamn: PtypMultipleFloating64; Alternativa namn: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Variabel storlek; ett COUNT-fält följt av så många PtypCurrency-värden. Specifikationsnamn: PtypMultipleCurrency; Alternativa namn: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Variabel storlek; ett COUNT-fält följt av så många PtypFloatingTime-värden. Specifikationsnamn: PtypMultipleFloatingTime; Alternativa namn: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Variabel storlek; ett COUNT-fält följt av så många PtypBoolean-värden. Specifikationsnamn: PtypMultipleBoolean; Alternativa namn: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Variabel storlek; ett COUNT-fält följt av så många PtypInteger64-värden. Specifikationsnamn: PtypMultipleInteger64; Alternativa namn: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Variabel storlek; ett COUNT-fält följt av så många PtypString-värden. Specifikationsnamn: PtypMultipleString; Alternativa namn: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Variabel storlek; ett COUNT-fält följt av så många PtypString8-värden. Specifikationsnamn: PtypMultipleString8; Alternativa namn: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Variabel storlek; ett COUNT-fält följt av så många PtypTime-värden. Specifikationsnamn: PtypMultipleTime; Alternativa namn: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Variabel storlek; ett COUNT-fält följt av så många PtypGuid-värden. Specifikationsnamn: PtypMultipleGuid; Alternativa namn: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Variabel storlek; ett COUNT-fält följt av så många PtypBinary-värden. Specifikationsnamn: PtypMultipleBinary; Alternativa namn: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | Egenskapsvärdet är ett COM-objekt (Component Object Model). Specifikationsnamn: PtypObject eller PtypEmbeddedTable; Alternativa namn: PT_OBJECT; |

### Se även

* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
