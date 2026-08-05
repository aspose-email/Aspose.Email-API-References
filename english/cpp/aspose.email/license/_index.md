---
title: "Aspose::Email::License class"
linktitle: "License"
articleTitle: "License"
second_title: "Aspose.Email for C++"
description: "Provides methods to license the component."
type: docs
weight: 10
url: /cpp/aspose.email/license/
---

## License class

Provides methods to license the component.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains

<ms> the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```cpp
[C#]
@verbatim 
License license = new License();
license.SetLicense("MyLicense.lic");
 
 
[Visual Basic]
 
Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

</ms>

<java> the component jar file:

```cpp
License license = new License();
license.setLicense("MyLicense.lic");
```

</java>

## Constructors

| Name | Description |
| --- | --- |
| [License](./license/) | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [get_IsLicensed](./get_islicensed/) |  |
| [SetLicense (3 overloads)](./setlicense/) | Licenses the component. |

