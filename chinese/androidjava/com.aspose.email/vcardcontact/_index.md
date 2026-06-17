---
title: VCardContact
second_title: Aspose.Email for Android via Java API 参考
description: 表示 vCard 联系人
type: docs
weight: 415
url: /zh/androidjava/com.aspose.email/vcardcontact/
---

**Inheritance:**
java.lang.Object
```
public final class VCardContact
```

表示 vCard 联系人
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VCardContact()](#VCardContact--) | 初始化 [VCardContact](../../com.aspose.email/vcardcontact) 类的新实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeliveryAddresses()](#getDeliveryAddresses--) | 获取或设置投递地址 |
| [getEmails()](#getEmails--) | 获取或设置联系人的电子邮件地址 |
| [getExplanatoryInfo()](#getExplanatoryInfo--) | 获取或设置 vCard 说明信息 |
| [getExtendedProperties()](#getExtendedProperties--) | 获取或设置扩展属性 |
| [getGeo()](#getGeo--) | 获取或设置全局定位 |
| [getIdentificationInfo()](#getIdentificationInfo--) | 获取或设置标识属性 |
| [getLabels()](#getLabels--) | 获取或设置投递地址 |
| [getMailer()](#getMailer--) | 获取或设置邮件程序 |
| [getOrganization()](#getOrganization--) | 获取或设置组织信息 |
| [getSecurity()](#getSecurity--) | 获取或设置安全属性 |
| [getTelephoneNumbers()](#getTelephoneNumbers--) | 获取或设置联系人的电话号码 |
| [getTimeZone()](#getTimeZone--) | 获取或设置时区 |
| [hashCode()](#hashCode--) |  |
| [isMultiContacts(InputStream stream)](#isMultiContacts-java.io.InputStream-) | 检查源流是否包含多个联系人。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从包含 vCard 的指定流中读取 [VCardContact](../../com.aspose.email/vcardcontact)。 |
| [load(InputStream stream, Charset encoding)](#load-java.io.InputStream-java.nio.charset.Charset-) | 从包含 vCard 的指定流中读取 [VCardContact](../../com.aspose.email/vcardcontact)。 |
| [load(String filePath)](#load-java.lang.String-) | 从指定的 vCard 文件读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0 |
| [load(String filePath, Charset encoding)](#load-java.lang.String-java.nio.charset.Charset-) | 从指定的 vCard 文件读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0 |
| [loadAsMultiple(InputStream stream, Charset encoding)](#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-) | 从多联系人流加载联系人列表。 |
| [loadAsMultiple(String filePath, Charset encoding)](#loadAsMultiple-java.lang.String-java.nio.charset.Charset-) | 从多联系人文件加载联系人列表。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将此 [MapiContact](../../com.aspose.email/mapicontact) 以 vCard 格式保存到给定流中。 |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | 使用指定的保存选项将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到给定流中。 |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | 使用默认选项将此 [MapiContact](../../com.aspose.email/mapicontact) 以默认格式保存到给定流中。 |
| [save(String filePath)](#save-java.lang.String-) | 使用默认选项将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到 vCard 文件中。 |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | 使用指定的保存选项将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到文件中。 |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | 将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到指定文件，使用默认选项的格式。 |
| [setDeliveryAddresses(VCardDeliveryAddressCollection value)](#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-) | 获取或设置投递地址 |
| [setEmails(VCardEmailCollection value)](#setEmails-com.aspose.email.VCardEmailCollection-) | 获取或设置联系人的电子邮件地址 |
| [setExplanatoryInfo(VCardExplanatoryInfo value)](#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-) | 获取或设置 vCard 说明信息 |
| [setExtendedProperties(System.Collections.Specialized.StringCollection value)](#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-) | 获取或设置扩展属性 |
| [setGeo(VCardGeo value)](#setGeo-com.aspose.email.VCardGeo-) | 获取或设置全局定位 |
| [setIdentificationInfo(VCardIdentificationInfo value)](#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-) | 获取或设置标识属性 |
| [setLabels(VCardLabelCollection value)](#setLabels-com.aspose.email.VCardLabelCollection-) | 获取或设置投递地址 |
| [setMailer(String value)](#setMailer-java.lang.String-) | 获取或设置邮件程序 |
| [setOrganization(VCardOrganization value)](#setOrganization-com.aspose.email.VCardOrganization-) | 获取或设置组织信息 |
| [setSecurity(VCardSecurity value)](#setSecurity-com.aspose.email.VCardSecurity-) | 获取或设置安全属性 |
| [setTelephoneNumbers(VCardTelephoneNumberCollection value)](#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-) | 获取或设置联系人的电话号码 |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | 获取或设置时区 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VCardContact() {#VCardContact--}
```
public VCardContact()
```


初始化 [VCardContact](../../com.aspose.email/vcardcontact) 类的新实例

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeliveryAddresses() {#getDeliveryAddresses--}
```
public final VCardDeliveryAddressCollection getDeliveryAddresses()
```


获取或设置投递地址

**Returns:**
[VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection)
### getEmails() {#getEmails--}
```
public final VCardEmailCollection getEmails()
```


获取或设置联系人的电子邮件地址

**Returns:**
[VCardEmailCollection](../../com.aspose.email/vcardemailcollection)
### getExplanatoryInfo() {#getExplanatoryInfo--}
```
public final VCardExplanatoryInfo getExplanatoryInfo()
```


获取或设置 vCard 说明信息

**Returns:**
[VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo)
### getExtendedProperties() {#getExtendedProperties--}
```
public final System.Collections.Specialized.StringCollection getExtendedProperties()
```


获取或设置扩展属性

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getGeo() {#getGeo--}
```
public final VCardGeo getGeo()
```


获取或设置全局定位

**Returns:**
[VCardGeo](../../com.aspose.email/vcardgeo)
### getIdentificationInfo() {#getIdentificationInfo--}
```
public final VCardIdentificationInfo getIdentificationInfo()
```


获取或设置标识属性

**Returns:**
[VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo)
### getLabels() {#getLabels--}
```
public final VCardLabelCollection getLabels()
```


获取或设置投递地址

**Returns:**
[VCardLabelCollection](../../com.aspose.email/vcardlabelcollection)
### getMailer() {#getMailer--}
```
public final String getMailer()
```


获取或设置邮件程序

**Returns:**
java.lang.String
### getOrganization() {#getOrganization--}
```
public final VCardOrganization getOrganization()
```


获取或设置组织信息

**Returns:**
[VCardOrganization](../../com.aspose.email/vcardorganization)
### getSecurity() {#getSecurity--}
```
public final VCardSecurity getSecurity()
```


获取或设置安全属性

**Returns:**
[VCardSecurity](../../com.aspose.email/vcardsecurity)
### getTelephoneNumbers() {#getTelephoneNumbers--}
```
public final VCardTelephoneNumberCollection getTelephoneNumbers()
```


获取或设置联系人的电话号码

**Returns:**
[VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection)
### getTimeZone() {#getTimeZone--}
```
public final String getTimeZone()
```


获取或设置时区

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMultiContacts(InputStream stream) {#isMultiContacts-java.io.InputStream-}
```
public static boolean isMultiContacts(InputStream stream)
```


检查源流是否包含多个联系人。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流 |

**Returns:**
布尔型 - 如果是多个联系人则为 True，否则为 false。
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static VCardContact load(InputStream stream)
```


从包含 vCard 的指定流中读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于读取的流 |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(InputStream stream, Charset encoding) {#load-java.io.InputStream-java.nio.charset.Charset-}
```
public static VCardContact load(InputStream stream, Charset encoding)
```


从包含 vCard 的指定流中读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于读取的流 |
| 编码 | java.nio.charset.Charset | 流数据编码 |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(String filePath) {#load-java.lang.String-}
```
public static VCardContact load(String filePath)
```


从指定的 vCard 文件读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于读取的文件名 |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(String filePath, Charset encoding) {#load-java.lang.String-java.nio.charset.Charset-}
```
public static VCardContact load(String filePath, Charset encoding)
```


从指定的 vCard 文件读取 [VCardContact](../../com.aspose.email/vcardcontact)。支持的 vCard 版本为 2.1 和 3.0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于读取的文件名 |
| 编码 | java.nio.charset.Charset | 文件编码 |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### loadAsMultiple(InputStream stream, Charset encoding) {#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(InputStream stream, Charset encoding)
```


从多联系人流加载联系人列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 源流 |
| 编码 | java.nio.charset.Charset | 流数据编码，如果为 null 则使用 UTF8。 |

**Returns:**
java.util.List<com.aspose.email.VCardContact> - 联系人列表
### loadAsMultiple(String filePath, Charset encoding) {#loadAsMultiple-java.lang.String-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(String filePath, Charset encoding)
```


从多联系人文件加载联系人列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 源文件 |
| 编码 | java.nio.charset.Charset | 文件数据编码，如果为 null 则使用 UTF8。 |

**Returns:**
java.util.List<com.aspose.email.VCardContact> -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 以 vCard 格式保存到给定流中。支持的 vCard 版本为 2.1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |

### save(OutputStream stream, ContactSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-}
```
public final void save(OutputStream stream, ContactSaveOptions saveOptions)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到给定流中，使用指定的保存选项。支持的保存选项为 [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | 保存选项 |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到给定流中，使用默认选项的格式。支持的保存格式为 vCard。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存的流 |
| saveFormat | int | 保存格式 |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到 vCard 文件，使用默认选项。支持的 vCard 版本为 2.1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | vCard 文件名 |

### save(String filePath, ContactSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.ContactSaveOptions-}
```
public final void save(String filePath, ContactSaveOptions saveOptions)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到文件中，使用指定的保存选项。支持的保存选项为 [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | vCard 文件名 |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | 保存选项 |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


将此 [MapiContact](../../com.aspose.email/mapicontact) 保存到指定文件，使用默认选项的格式。支持的保存格式为 vCard。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | vCard 文件名 |
| saveFormat | int | 保存格式 |

### setDeliveryAddresses(VCardDeliveryAddressCollection value) {#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-}
```
public final void setDeliveryAddresses(VCardDeliveryAddressCollection value)
```


获取或设置投递地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection) |  |

### setEmails(VCardEmailCollection value) {#setEmails-com.aspose.email.VCardEmailCollection-}
```
public final void setEmails(VCardEmailCollection value)
```


获取或设置联系人的电子邮件地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardEmailCollection](../../com.aspose.email/vcardemailcollection) |  |

### setExplanatoryInfo(VCardExplanatoryInfo value) {#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-}
```
public final void setExplanatoryInfo(VCardExplanatoryInfo value)
```


获取或设置 vCard 说明信息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo) |  |

### setExtendedProperties(System.Collections.Specialized.StringCollection value) {#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setExtendedProperties(System.Collections.Specialized.StringCollection value)
```


获取或设置扩展属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setGeo(VCardGeo value) {#setGeo-com.aspose.email.VCardGeo-}
```
public final void setGeo(VCardGeo value)
```


获取或设置全局定位

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardGeo](../../com.aspose.email/vcardgeo) |  |

### setIdentificationInfo(VCardIdentificationInfo value) {#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-}
```
public final void setIdentificationInfo(VCardIdentificationInfo value)
```


获取或设置标识属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo) |  |

### setLabels(VCardLabelCollection value) {#setLabels-com.aspose.email.VCardLabelCollection-}
```
public final void setLabels(VCardLabelCollection value)
```


获取或设置投递地址

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardLabelCollection](../../com.aspose.email/vcardlabelcollection) |  |

### setMailer(String value) {#setMailer-java.lang.String-}
```
public final void setMailer(String value)
```


获取或设置邮件程序

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrganization(VCardOrganization value) {#setOrganization-com.aspose.email.VCardOrganization-}
```
public final void setOrganization(VCardOrganization value)
```


获取或设置组织信息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardOrganization](../../com.aspose.email/vcardorganization) |  |

### setSecurity(VCardSecurity value) {#setSecurity-com.aspose.email.VCardSecurity-}
```
public final void setSecurity(VCardSecurity value)
```


获取或设置安全属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardSecurity](../../com.aspose.email/vcardsecurity) |  |

### setTelephoneNumbers(VCardTelephoneNumberCollection value) {#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-}
```
public final void setTelephoneNumbers(VCardTelephoneNumberCollection value)
```


获取或设置联系人的电话号码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection) |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String value)
```


获取或设置时区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

