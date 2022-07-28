---
title: PropertyDataType
second_title: Aspose.Email for .NET API Referansı
description: MS-OXCDATA Veri Yapıları
type: docs
weight: 19000
url: /tr/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: Veri Yapıları

```csharp
public enum PropertyDataType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Unspecified | `0` | Herhangi biri: bu özellik türü değeri herhangi bir türle eşleşir; bir sunucu, yanıtında gerçek türü döndürmelidir ZORUNLU. Sunucular, NspiGetIDsFromNames veya RopGetPropertyIdsFromNames ROP isteği ([MS-OXCROPS] bölüm 2.2.8.1) dışındaki bir istemci isteğine yanıt olarak bu türü döndürmemelidir ZORUNLU. Belirtim adı: PtypUnspecified; Alternatif adlar: PT_UNSPECIFIED; |
| Null | `1` | Yok: Bu özellik bir yer tutucudur. Belirtim adı: PtypNull; Alternatif adlar: PT_NULL; |
| Integer16 | `2` | 2 bayt; 16 bitlik bir tam sayı Belirtim adı: PtypInteger16; Alternatif adlar: PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 bayt; 32 bitlik bir tam sayı Belirtim adı: PtypInteger32; Alternatif adlar: PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 bayt; 32 bitlik kayan noktalı sayı Belirtim adı: PtypFloating32; Alternatif adlar: PT_FLOAT, PT_R4, float, r4; |
| Floating64 | `5` | 8 bayt; 64 bitlik kayan noktalı sayı Belirtim adı: PtypFloating64; Alternatif adlar: PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 bayt; ondalık para birimi değerinin 64 bit işaretli, ölçekli tamsayı temsili, ondalık noktanın sağında dört basamaklı Belirtim adı: PtypCurrency; Alternatif adlar: PT_CURRENCY, sabit.14.4; |
| FloatingTime | `7` | 8 bayt; tam sayı bölümünün 30 Aralık 1899, tarihinden itibaren gün sayısını temsil ettiği ve kesirli bölümün gece yarısından itibaren bir günün kesirini temsil ettiği 64 bitlik bir kayan nokta sayısı Belirtim adı: PtypFloatingTime; Alternatif adlar: PT_APPTIME; Tarih bilgisi, sıfır zaman olarak 30 Aralık 1899 gece yarısından başlayarak tam sayı artışlarıyla temsil edilir. Zaman bilgisi, önceki gece yarısından itibaren bir günün kesriyle temsil edilir. Örneğin, 4 Ocak 1900'deki 06:00 AM, 5,25 değeriyle (30 Aralık 1899'u geçen günün 5 ve 1/4'ü) temsil edilir. |
| ErrorCode | `10` | 4 bayt; 32 bit tamsayı kodlama hatası bilgisi Belirtim adı: PtypErrorCode; Alternatif adlar: PT_ERROR; |
| Boolean | `11` | 1 bayt; 1 veya 0 ile sınırlandırılmıştır Spesifikasyon adı: PtypBoolean; Alternatif adlar: PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 bayt; 64 bitlik bir tam sayı Belirtim adı: PtypInteger64; Alternatif adlar: PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Değişken boyut; sonlandırma boş karakter (0x0000) ile kodlama UTF-16LE biçiminde bir Unicode karakter dizisi. Belirtim adı: PtypString; Alternatif adlar: PT_UNICODE, string; |
| String8 | `30` | Değişken boyut; sonlandırma boş karakterle (tek 0 bayt) harici olarak belirtilen kodlamada çok baytlı karakter dizisi. Belirtim adı: PtypString8; Alternatif adlar: PT_STRING8; |
| Time | `64` | 8 bayt; 1 Ocak 1601'den bu yana 100 nanosaniyelik aralıkların sayısını temsil eden 64 bitlik bir tam sayı Belirtim adı: PtypTime; Alternatif adlar: PT_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| Guid | `72` | 16 bayt; Küçük endian biçiminde Data1, Data2 ve Data3 alanlarını içeren bir GUID Özellik adı: PtypGuid; Alternatif adlar: PT_CLSID, UUID; |
| ServerId | `251` | Değişken boyut; 16 bitlik bir COUNT alanı ve ardından bir yapı Belirtim adı: PtypServerId; Alternatif adlar: PT_SVREID; |
| Restriction | `253` | Değişken boyut; bir veya daha fazla Kısıtlama yapısını temsil eden bir bayt dizisi Belirtim adı: PtypRestriction; Alternatif adlar: PT_SRESTRICT; |
| RuleAction | `254` | Değişken boyut; 16 bitlik bir COUNT alanı ve ardından bu kadar çok kural eylemi yapısı Belirtim adı: PtypRuleAction; Alternatif adlar: PT_ACTIONS; |
| Binary | `258` | Değişken boyut; bir COUNT alanı ve ardından bu kadar bayt. Özellik adı: PtypBinary; Alternatif adlar: PT_BINARY; |
| MultipleInteger16 | `4098` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypInteger16 değeri. Belirtim adı: PtypMultipleInteger16; Alternatif adlar: PT_MV_SHORT, PT_MV_I2, mv.i2; |
| MultipleInteger32 | `4099` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypInteger32 değeri. Belirtim adı: PtypMultipleInteger32; Alternatif adlar: PT_MV_LONG, PT_MV_I4, mv.i4; |
| MultipleFloating32 | `4100` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypFloating32 değeri. Belirtim adı: PtypMultipleFloating32; Alternatif adlar: PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypFloating64 değeri. Özellik adı: PtypMultipleFloating64; Alternatif adlar: PT_MV_DOUBLE, PT_MV_R8; |
| MultipleCurrency | `4102` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypCurrency değeri. Belirtim adı: PtypMultipleCurrency; Alternatif adlar: PT_MV_CURRENCY, mv.fixed.14.4; |
| MultipleFloatingTime | `4103` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypFloatingTime değeri. Belirtim adı: PtypMultipleFloatingTime; Alternatif adlar: PT_MV_APPTIME; |
| MultipleBoolean | `4107` | Değişken boyut; bir COUNT alanı ve ardından bu kadar çok PtypBoolean değeri. Özellik adı: PtypMultipleBoolean; Alternatif adlar: PT_MV_BOOLEAN; |
| MultipleInteger64 | `4116` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypInteger64 değeri. Belirtim adı: PtypMultipleInteger64; Alternatif adlar: PT_MV_I8, PT_MV_LONGLONG; |
| MultipleString | `4127` | Değişken boyut; bir COUNT alanı ve ardından bu kadar çok PtypString değeri. Belirtim adı: PtypMultipleString; Alternatif adlar: PT_MV_UNICODE; |
| MultipleString8 | `4126` | Değişken boyut; bir COUNT alanı ve ardından bu kadar çok PtypString8 değeri. Belirtim adı: PtypMultipleString8; Alternatif adlar: PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypTime değeri. Belirtim adı: PtypMultipleTime; Alternatif adlar: PT_MV_SYSTIME; |
| MultipleGuid | `4168` | Değişken boyut; bir COUNT alanı ve ardından bu kadar çok PtypGuid değeri. Belirtim adı: PtypMultipleGuid; Alternatif adlar: PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Değişken boyut; bir SAYI alanı ve ardından bu kadar çok PtypBinary değeri. Belirtim adı: PtypMultipleBinary; Alternatif adlar: PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | Özellik değeri, bir Bileşen Nesne Modeli (COM) nesnesidir. Belirtim adı: PtypObject veya PtypEmbeddedTable; Alternatif adlar: PT_OBJECT; |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
