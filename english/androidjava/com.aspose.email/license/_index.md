---
title: License
second_title: Aspose.Email for Android via Java API Reference
description:   Provides methods to license the component.
type: docs
weight: 176
url: /java/com.aspose.email/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As license = New license
>  	License.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | Licenses the component. |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As license = New license
>  	License.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


Licenses the component.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>   in the folder that contains 
>   
>   ```
> 
>   the component, in the folder that contains the calling assembly,
>   in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>   
>   [C#]
>   
>  	License license = new License();
>  	license.SetLicense("MyLicense.lic");
>  	
>  	
>  	[Visual Basic]
>  	
>  	Dim license As License = New License
>  	license.SetLicense("MyLicense.lic")
>   
>   
> ```
>   
>   ```
> 
>   the component jar file:
>   
>  	License license = new License();
>  	license.setLicense("MyLicense.lic");
>   
>   
> ```
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Can be a full or short file name\`\`\`  or name of an embedded resource \`\`\`. Use an empty string to switch to evaluation mode.

--------------------

\`\`\`

Tries to find the license in the following locations:

\`\`\` \`\`\`

1. Explicit path.

\`\`\` \`\`\`

2. The folder of the component assembly.

3. The folder of the client's calling assembly.

4. The folder of the entry assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

\`\`\` \`\`\`

2. The folder of the component jar file.

\`\`\` |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenses the component.

--------------------

> ```
> ```
> 
>  [C#]
>  License license = new License();
>  license.SetLicense(myStream);
>  [Visual Basic]
>  Dim license as License = new License
>  license.SetLicense(myStream)
>  
> ```
>  ```
> 
>  License license = new License();
>  license.setLicense(myStream);
>  
> ```
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream that contains the license.

--------------------

\`\`\`

Use this method to load a license from a stream.

\`\`\`

\`\`\` void setLicense(java.io.InputStream stream) \`\`\` |

### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public final void setLicense(File licenseFile)
```


Licenses the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseFile | java.io.File | File of licenseFileInfo. |

