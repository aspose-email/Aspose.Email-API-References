---
title: FileAsMapping
second_title: Aspose.Email for Android via Java API Reference
description:  Specifies how to generate and recompute the value of the dispidFileAs property when other contact name properties change.
type: docs
weight: 133
url: /java/com.aspose.email/fileasmapping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileAsMapping extends System.Enum
```

Specifies how to generate and recompute the value of the dispidFileAs property when other contact name properties change. Coincides MS-OXPROPS revision 16.2 from 7/31/2014
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Empty value. |
| [DisplayName](#DisplayName) | DisplayName |
| [FirstName](#FirstName) | GivenName |
| [LastName](#LastName) | Surname |
| [Organization](#Organization) | CompanyName |
| [FirstMiddleLastGen](#FirstMiddleLastGen) | GivenName MiddleName Surname Generation |
| [LastFirstMiddle](#LastFirstMiddle) | Surname, GivenName MiddleName |
| [LastFirstMiddle2](#LastFirstMiddle2) | SurnameGivenName MiddleName |
| [LastFirstMiddle3](#LastFirstMiddle3) | Surname GivenName MiddleName |
| [OrgLastFirstMiddle](#OrgLastFirstMiddle) | CompanyName\\r\\nSurname, GivenName MiddleName |
| [OrgLastFirstMiddle2](#OrgLastFirstMiddle2) | CompanyName\\r\\nSurnameGivenName MiddleName |
| [OrgLastFirstMiddle3](#OrgLastFirstMiddle3) | CompanyName\\r\\nSurname GivenName MiddleName |
| [LastFirstMiddleOrg](#LastFirstMiddleOrg) | Surname, GivenName MiddleName\\r\\nCompanyName |
| [LastFirstMiddleOrg2](#LastFirstMiddleOrg2) | SurnameGivenName MiddleName\\r\\nCompanyName |
| [LastFirstMiddleOrg3](#LastFirstMiddleOrg3) | Surname GivenName PidTagMiddleName\\r\\nCompanyName |
| [LastFirstMiddleGen](#LastFirstMiddleGen) | Surname GivenName MiddleName Generation |
| [LastFirstMiddleGen2](#LastFirstMiddleGen2) | SurnameGivenName MiddleName Generation |
| [BestMatch](#BestMatch) | Specifies that, when displaying the contact, the application should attempt to use the current value of dispidFileUnder and other contact properties to find a "best match" for dispidFileUnderId to one of the previous values in this table. |
| [AccordingToLocale](#AccordingToLocale) | Specifies that, when displaying the contact, the application should choose the appropriate default values (according to the language locale) for dispidFileUnderId and update dispidFileUnder to match the choice. |
| [None](#None) | Specifies that, FileUnder is a user-provided, and should not be changed when another contact name property changes. |
### Empty {#Empty}
```
public static final long Empty
```


Empty value.

### DisplayName {#DisplayName}
```
public static final long DisplayName
```


DisplayName

### FirstName {#FirstName}
```
public static final long FirstName
```


GivenName

### LastName {#LastName}
```
public static final long LastName
```


Surname

### Organization {#Organization}
```
public static final long Organization
```


CompanyName

### FirstMiddleLastGen {#FirstMiddleLastGen}
```
public static final long FirstMiddleLastGen
```


GivenName MiddleName Surname Generation

### LastFirstMiddle {#LastFirstMiddle}
```
public static final long LastFirstMiddle
```


Surname, GivenName MiddleName

### LastFirstMiddle2 {#LastFirstMiddle2}
```
public static final long LastFirstMiddle2
```


SurnameGivenName MiddleName

### LastFirstMiddle3 {#LastFirstMiddle3}
```
public static final long LastFirstMiddle3
```


Surname GivenName MiddleName

### OrgLastFirstMiddle {#OrgLastFirstMiddle}
```
public static final long OrgLastFirstMiddle
```


CompanyName\\r\\nSurname, GivenName MiddleName

### OrgLastFirstMiddle2 {#OrgLastFirstMiddle2}
```
public static final long OrgLastFirstMiddle2
```


CompanyName\\r\\nSurnameGivenName MiddleName

### OrgLastFirstMiddle3 {#OrgLastFirstMiddle3}
```
public static final long OrgLastFirstMiddle3
```


CompanyName\\r\\nSurname GivenName MiddleName

### LastFirstMiddleOrg {#LastFirstMiddleOrg}
```
public static final long LastFirstMiddleOrg
```


Surname, GivenName MiddleName\\r\\nCompanyName

### LastFirstMiddleOrg2 {#LastFirstMiddleOrg2}
```
public static final long LastFirstMiddleOrg2
```


SurnameGivenName MiddleName\\r\\nCompanyName

### LastFirstMiddleOrg3 {#LastFirstMiddleOrg3}
```
public static final long LastFirstMiddleOrg3
```


Surname GivenName PidTagMiddleName\\r\\nCompanyName

### LastFirstMiddleGen {#LastFirstMiddleGen}
```
public static final long LastFirstMiddleGen
```


Surname GivenName MiddleName Generation

### LastFirstMiddleGen2 {#LastFirstMiddleGen2}
```
public static final long LastFirstMiddleGen2
```


SurnameGivenName MiddleName Generation

### BestMatch {#BestMatch}
```
public static final long BestMatch
```


Specifies that, when displaying the contact, the application should attempt to use the current value of dispidFileUnder and other contact properties to find a "best match" for dispidFileUnderId to one of the previous values in this table.

### AccordingToLocale {#AccordingToLocale}
```
public static final long AccordingToLocale
```


Specifies that, when displaying the contact, the application should choose the appropriate default values (according to the language locale) for dispidFileUnderId and update dispidFileUnder to match the choice.

### None {#None}
```
public static final long None
```


Specifies that, FileUnder is a user-provided, and should not be changed when another contact name property changes. I.e. value of FileUnder is not constructed from other properties.

