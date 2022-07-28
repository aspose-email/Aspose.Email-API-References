---
title: PropertyDataType
second_title: Aspose.Email per riferimento all'API .NET
description: MS-OXCDATA Strutture dati
type: docs
weight: 19000
url: /it/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Strutture dati

```csharp
public enum PropertyDataType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Unspecified | `0` | Qualsiasi: questo valore del tipo di proprietà corrisponde a qualsiasi tipo; un server DEVE restituire il tipo effettivo nella sua risposta. I server NON DEVONO restituire questo tipo in risposta a una richiesta del client diversa da NspiGetIDsFromNames o dalla richiesta ROP RopGetPropertyIdsFromNames ([MS-OXCROPS] sezione 2.2.8.1). Nome della specifica: PtypUnspecified; Nomi alternativi: PT_UNSPECIFIED; |
| Null | `1` | Nessuno: questa proprietà è un segnaposto. Nome della specifica: PtypNull; Nomi alternativi: PT_NULL; |
| Integer16 | `2` | 2 byte; un intero a 16 bit Nome della specifica: PtypInteger16; Nomi alternativi: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 byte; un intero a 32 bit Nome della specifica: PtypInteger32; Nomi alternativi: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 byte; un numero in virgola mobile a 32 bit Nome della specifica: PtypFloating32; Nomi alternativi: PT_FLOAT, PT_R4, float, r4; |
| Floating64 | `5` | 8 byte; un numero in virgola mobile a 64 bit Nome della specifica: PtypFloating64; Nomi alternativi: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 byte; una rappresentazione intera scalata con segno a 64 bit di un valore di valuta decimale, con quattro cifre a destra del punto decimale Nome della specifica: PtypCurrency; Nomi alternativi: PT_CURRENCY, fixed.14.4; |
| FloatingTime | `7` | 8 byte; un numero in virgola mobile a 64 bit in cui la parte del numero intero rappresenta il numero di giorni dal 30 dicembre 1899, e la parte frazionaria rappresenta la frazione di giorno dalla mezzanotte Nome della specifica: PtypFloatingTime; Nomi alternativi: PT_APPTIME; Le informazioni sulla data sono rappresentate da incrementi di numeri interi, a partire dalla mezzanotte del 30 dicembre 1899 come ora zero. Le informazioni sull'ora sono rappresentate dalla frazione di giorno dalla mezzanotte precedente. Ad esempio, le 6:00 del 4 gennaio 1900 sarebbero rappresentate dal valore 5,25 (5 e 1/4 di giorno dopo il 30 dicembre 1899). |
| ErrorCode | `10` | 4 byte; informazioni sull'errore di codifica di un intero a 32 bit Nome della specifica: PtypErrorCode; Nomi alternativi: PT_ERROR; |
| Boolean | `11` | 1 byte; limitato a 1 o 0 Nome della specifica: PtypBoolean; Nomi alternativi: PT_BOOLEAN. bolo; |
| Integer64 | `20` | 8 byte; un intero a 64 bit Nome della specifica: PtypInteger64; Nomi alternativi: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Dimensione variabile; una stringa di caratteri Unicode con codifica in formato UTF-16LE con carattere null finale (0x0000). Nome della specifica: PtypString; Nomi alternativi: PT_UNICODE, stringa; |
| String8 | `30` | Dimensione variabile; una stringa di caratteri multibyte nella codifica specificata esternamente con carattere nullo finale (singolo 0 byte). Nome della specifica: PtypString8; Nomi alternativi: PT_STRING8; |
| Time | `64` | 8 byte; un numero intero a 64 bit che rappresenta il numero di intervalli di 100 nanosecondi dal 1 gennaio 1601 Nome della specifica: PtypTime; Nomi alternativi: PT_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| Guid | `72` | 16 byte; un GUID con campi Data1, Data2 e Data3 in formato little-endian Nome della specifica: PtypGuid; Nomi alternativi: PT_CLSID, UUID; |
| ServerId | `251` | Dimensione variabile; un campo COUNT a 16 bit seguito da una struttura Nome della specifica: PtypServerId; Nomi alternativi: PT_SVREID; |
| Restriction | `253` | Dimensione variabile; una matrice di byte che rappresenta una o più strutture di restrizione Nome della specifica: PtypRestriction; Nomi alternativi: PT_SRESTRICT; |
| RuleAction | `254` | Dimensione variabile; un campo COUNT a 16 bit seguito da altrettante strutture di azioni della regola Nome della specifica: PtypRuleAction; Nomi alternativi: PT_ACTIONS; |
| Binary | `258` | Dimensione variabile; un campo COUNT seguito da quel numero di byte. Nome della specifica: PtypBinary; Nomi alternativi: PT_BINARY; |
| MultipleInteger16 | `4098` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypInteger16. Nome della specifica: PtypMultipleInteger16; Nomi alternativi: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypInteger32. Nome della specifica: PtypMultipleInteger32; Nomi alternativi: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypFloating32. Nome della specifica: PtypMultipleFloating32; Nomi alternativi: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypFloating64. Nome della specifica: PtypMultipleFloating64; Nomi alternativi: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypCurrency. Nome della specifica: PtypMultipleCurrency; Nomi alternativi: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypFloatingTime. Nome della specifica: PtypMultipleFloatingTime; Nomi alternativi: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypBoolean. Nome della specifica: PtypMultipleBoolean; Nomi alternativi: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypInteger64. Nome della specifica: PtypMultipleInteger64; Nomi alternativi: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypString. Nome della specifica: PtypMultipleString; Nomi alternativi: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypString8. Nome della specifica: PtypMultipleString8; Nomi alternativi: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypTime. Nome della specifica: PtypMultipleTime; Nomi alternativi: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypGuid. Nome della specifica: PtypMultipleGuid; Nomi alternativi: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Dimensione variabile; un campo COUNT seguito da tanti valori PtypBinary. Nome della specifica: PtypMultipleBinary; Nomi alternativi: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | Il valore della proprietà è un oggetto COM (Component Object Model). Nome della specifica: PtypObject o PtypEmbeddedTable; Nomi alternativi: PT_OBJECT; |

### Guarda anche

* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
