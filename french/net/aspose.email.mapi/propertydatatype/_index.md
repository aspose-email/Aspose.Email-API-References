---
title: PropertyDataType
second_title: Référence de l'API Aspose.Email pour .NET
description: MS-OXCDATA  Structures de données
type: docs
weight: 19000
url: /fr/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA] : Structures de données

```csharp
public enum PropertyDataType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Unspecified | `0` | Any : cette valeur de type de propriété correspond à n'importe quel type ; un serveur DOIT renvoyer le type réel dans sa réponse. Les serveurs NE DOIVENT PAS renvoyer ce type en réponse à une demande client autre que NspiGetIDsFromNames ou la demande RopGetPropertyIdsFromNames ([MS-OXCROPS] section 2.2.8.1). Nom de spécification : PtypUnspecified ; Noms alternatifs : PT_UNSPECIFIED; |
| Null | `1` | Aucun : cette propriété est un espace réservé. Nom de la spécification : PtypNull ; Noms alternatifs : PT_NULL ; |
| Integer16 | `2` | 2 octets ; un entier 16 bits Nom de la spécification : PtypInteger16 ; Noms alternatifs : PT_SHORT, PT_I2, i2, ui2; |
| Integer32 | `3` | 4 octets ; un entier 32 bits Nom de la spécification : PtypInteger32 ; Noms alternatifs : PT_LONG, PT_I4, int, ui4; |
| Floating32 | `4` | 4 octets ; un nombre à virgule flottante 32 bits Nom de la spécification : PtypFloating32 ; Noms alternatifs : PT_FLOAT, PT_R4, float, r4 ; |
| Floating64 | `5` | 8 octets ; un nombre à virgule flottante 64 bits Nom de la spécification : PtypFloating64 ; Noms alternatifs : PT_DOUBLE, PT_R8, r8; |
| Currency | `6` | 8 octets ; une représentation entière 64 bits signée et mise à l'échelle d'une valeur monétaire décimale, avec quatre chiffres à droite de la virgule décimale Nom de la spécification : PtypCurrency ; Noms alternatifs : PT_CURRENCY, fixe.14.4 ; |
| FloatingTime | `7` | 8 octets ; un nombre à virgule flottante 64 bits dans lequel la partie entière représente le nombre de jours depuis le 30 décembre 1899, et la partie fractionnaire représente la fraction de jour depuis minuit Nom de la spécification : PtypFloatingTime ; Autres noms : PT_APPTIME ; Les informations de date sont représentées par des incréments de nombres entiers, en commençant par le 30 décembre 1899 à minuit comme heure zéro. L'information temporelle est représentée par la fraction de jour depuis le minuit précédent. Par exemple, 6h00 le 4 janvier 1900 serait représenté par la valeur 5,25 (5 et 1/4 de jour après le 30 décembre 1899). |
| ErrorCode | `10` | 4 octets ; une information d'erreur de codage d'entier 32 bits Nom de la spécification : PtypErrorCode ; Noms alternatifs : PT_ERROR; |
| Boolean | `11` | 1 octet ; limité à 1 ou 0 Nom de la spécification : PtypBoolean ; Noms alternatifs : PT_BOOLEAN. bool; |
| Integer64 | `20` | 8 octets ; un entier 64 bits Nom de la spécification : PtypInteger64 ; Noms alternatifs : PT_LONGLONG, PT_I8, i8, ui8; |
| String | `31` | Taille variable ; une chaîne de caractères Unicode au format UTF-16LE avec un caractère nul de fin (0x0000). Nom de la spécification : PtypString ; Noms alternatifs : PT_UNICODE, chaîne ; |
| String8 | `30` | Taille variable ; une chaîne de caractères multi-octets dans un codage spécifié en externe avec un caractère nul de fin (un seul octet 0). Nom de la spécification : PtypString8 ; Noms alternatifs : PT_STRING8; |
| Time | `64` | 8 octets ; un entier 64 bits représentant le nombre d'intervalles de 100 nanosecondes depuis le 1er janvier 1601 Nom de la spécification : PtypTime ; Noms alternatifs : PT_SYSTIME, heure, dateheure, dateheure.tz, dateheure.rfc1123, Date, heure, heure.tz; |
| Guid | `72` | 16 octets ; un GUID avec les champs Data1, Data2 et Data3 au format little-endian Nom de la spécification : PtypGuid ; Noms alternatifs : PT_CLSID, UUID ; |
| ServerId | `251` | Taille variable ; un champ COUNT 16 bits suivi d'une structure Nom de spécification : PtypServerId ; Noms alternatifs : PT_SVREID ; |
| Restriction | `253` | Taille variable ; un tableau d'octets représentant une ou plusieurs structures de restriction Nom de la spécification : PtypRestriction ; Noms alternatifs : PT_SRESTRICT ; |
| RuleAction | `254` | Taille variable ; un champ COUNT de 16 bits suivi de ce nombre de structures d'action de règle Nom de la spécification : PtypRuleAction ; Noms alternatifs : PT_ACTIONS ; |
| Binary | `258` | Taille variable ; un champ COUNT suivi de ce nombre d'octets. Nom de la spécification : PtypBinary ; Noms alternatifs : PT_BINARY; |
| MultipleInteger16 | `4098` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypInteger16. Nom de la spécification : PtypMultipleInteger16 ; Noms alternatifs : PT_MV_SHORT, PT_MV_I2, mv.i2 ; |
| MultipleInteger32 | `4099` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypInteger32. Nom de la spécification : PtypMultipleInteger32 ; Noms alternatifs : PT_MV_LONG, PT_MV_I4, mv.i4 ; |
| MultipleFloating32 | `4100` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypFloating32. Nom de la spécification : PtypMultipleFloating32 ; Noms alternatifs : PT_MV_FLOAT, PT_MV_R4, mv.float; |
| MultipleFloating64 | `4101` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypFloating64. Nom de la spécification : PtypMultipleFloating64 ; Noms alternatifs : PT_MV_DOUBLE, PT_MV_R8 ; |
| MultipleCurrency | `4102` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypCurrency. Nom de la spécification : PtypMultipleCurrency ; Noms alternatifs : PT_MV_CURRENCY, mv.fixed.14.4 ; |
| MultipleFloatingTime | `4103` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypFloatingTime. Nom de la spécification : PtypMultipleFloatingTime ; Noms alternatifs : PT_MV_APPTIME ; |
| MultipleBoolean | `4107` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypBoolean. Nom de la spécification : PtypMultipleBoolean ; Noms alternatifs : PT_MV_BOOLEAN ; |
| MultipleInteger64 | `4116` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypInteger64. Nom de la spécification : PtypMultipleInteger64 ; Noms alternatifs : PT_MV_I8, PT_MV_LONGLONG ; |
| MultipleString | `4127` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypString. Nom de la spécification : PtypMultipleString ; Noms alternatifs : PT_MV_UNICODE ; |
| MultipleString8 | `4126` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypString8. Nom de la spécification : PtypMultipleString8 ; Noms alternatifs : PT_MV_STRING8, mv.string; |
| MultipleTime | `4160` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypTime. Nom de la spécification : PtypMultipleTime ; Noms alternatifs : PT_MV_SYSTIME ; |
| MultipleGuid | `4168` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypGuid. Nom de la spécification : PtypMultipleGuid ; Noms alternatifs : PT_MV_CLSID, mv.uuid; |
| MultipleBinary | `4354` | Taille variable ; un champ COUNT suivi de ce nombre de valeurs PtypBinary. Nom de la spécification : PtypMultipleBinary ; Noms alternatifs : PT_MV_BINARY, mv.bin.hex; |
| Object | `13` | La valeur de la propriété est un objet COM (Component Object Model). Nom de la spécification : PtypObject ou PtypEmbeddedTable ; Noms alternatifs : PT_OBJECT ; |

### Voir également

* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
