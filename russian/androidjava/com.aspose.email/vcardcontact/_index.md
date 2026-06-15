---
title: VCardContact
second_title: Aspose.Email for Android via Java API Reference
description: Представляет контакт vCard
type: docs
weight: 415
url: /ru/androidjava/com.aspose.email/vcardcontact/
---

**Inheritance:**
java.lang.Object
```
public final class VCardContact
```

Представляет контакт vCard
## Constructors

| Constructor | Описание |
| --- | --- |
| [VCardContact()](#VCardContact--) | Инициализирует новый экземпляр класса [VCardContact](../../com.aspose.email/vcardcontact). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeliveryAddresses()](#getDeliveryAddresses--) | Получает или задает адрес доставки. |
| [getEmails()](#getEmails--) | Получает или задает адреса электронной почты контакта. |
| [getExplanatoryInfo()](#getExplanatoryInfo--) | Получает или задает пояснительную информацию vCard. |
| [getExtendedProperties()](#getExtendedProperties--) | Получает или задает расширенные свойства. |
| [getGeo()](#getGeo--) | Получает или задает глобальное позиционирование. |
| [getIdentificationInfo()](#getIdentificationInfo--) | Получает или задает свойства идентификации. |
| [getLabels()](#getLabels--) | Получает или задает адрес доставки. |
| [getMailer()](#getMailer--) | Получает или задает почтовый клиент. |
| [getOrganization()](#getOrganization--) | Получает или задает информацию об организации. |
| [getSecurity()](#getSecurity--) | Получает или задает свойства безопасности. |
| [getTelephoneNumbers()](#getTelephoneNumbers--) | Получает или задает телефонные номера контакта. |
| [getTimeZone()](#getTimeZone--) | Получает или задает часовой пояс. |
| [hashCode()](#hashCode--) |  |
| [isMultiContacts(InputStream stream)](#isMultiContacts-java.io.InputStream-) | Проверяет, содержит ли исходный поток несколько контактов. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного потока, содержащего vCard. |
| [load(InputStream stream, Charset encoding)](#load-java.io.InputStream-java.nio.charset.Charset-) | Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного потока, содержащего vCard. |
| [load(String filePath)](#load-java.lang.String-) | Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0. |
| [load(String filePath, Charset encoding)](#load-java.lang.String-java.nio.charset.Charset-) | Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0. |
| [loadAsMultiple(InputStream stream, Charset encoding)](#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-) | Загружает список контактов из потока с несколькими контактами. |
| [loadAsMultiple(String filePath, Charset encoding)](#loadAsMultiple-java.lang.String-java.nio.charset.Charset-) | Загружает список контактов из файла с несколькими контактами. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате vCard. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток, используя заданные параметры сохранения. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате, используя параметры по умолчанию. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл vCard с параметрами по умолчанию. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл, используя заданные параметры сохранения. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный файл в формате, используя параметры по умолчанию. |
| [setDeliveryAddresses(VCardDeliveryAddressCollection value)](#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-) | Получает или задает адрес доставки. |
| [setEmails(VCardEmailCollection value)](#setEmails-com.aspose.email.VCardEmailCollection-) | Получает или задает адреса электронной почты контакта. |
| [setExplanatoryInfo(VCardExplanatoryInfo value)](#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-) | Получает или задает пояснительную информацию vCard. |
| [setExtendedProperties(System.Collections.Specialized.StringCollection value)](#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Получает или задает расширенные свойства. |
| [setGeo(VCardGeo value)](#setGeo-com.aspose.email.VCardGeo-) | Получает или задает глобальное позиционирование. |
| [setIdentificationInfo(VCardIdentificationInfo value)](#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-) | Получает или задает свойства идентификации. |
| [setLabels(VCardLabelCollection value)](#setLabels-com.aspose.email.VCardLabelCollection-) | Получает или задает адрес доставки. |
| [setMailer(String value)](#setMailer-java.lang.String-) | Получает или задает почтовый клиент. |
| [setOrganization(VCardOrganization value)](#setOrganization-com.aspose.email.VCardOrganization-) | Получает или задает информацию об организации. |
| [setSecurity(VCardSecurity value)](#setSecurity-com.aspose.email.VCardSecurity-) | Получает или задает свойства безопасности. |
| [setTelephoneNumbers(VCardTelephoneNumberCollection value)](#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-) | Получает или задает телефонные номера контакта. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | Получает или задает часовой пояс. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VCardContact() {#VCardContact--}
```
public VCardContact()
```


Инициализирует новый экземпляр класса [VCardContact](../../com.aspose.email/vcardcontact).

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
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


Получает или задает адрес доставки.

**Returns:**
[VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection)
### getEmails() {#getEmails--}
```
public final VCardEmailCollection getEmails()
```


Получает или задает адреса электронной почты контакта.

**Returns:**
[VCardEmailCollection](../../com.aspose.email/vcardemailcollection)
### getExplanatoryInfo() {#getExplanatoryInfo--}
```
public final VCardExplanatoryInfo getExplanatoryInfo()
```


Получает или задает пояснительную информацию vCard.

**Returns:**
[VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo)
### getExtendedProperties() {#getExtendedProperties--}
```
public final System.Collections.Specialized.StringCollection getExtendedProperties()
```


Получает или задает расширенные свойства.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getGeo() {#getGeo--}
```
public final VCardGeo getGeo()
```


Получает или задает глобальное позиционирование.

**Returns:**
[VCardGeo](../../com.aspose.email/vcardgeo)
### getIdentificationInfo() {#getIdentificationInfo--}
```
public final VCardIdentificationInfo getIdentificationInfo()
```


Получает или задает свойства идентификации.

**Returns:**
[VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo)
### getLabels() {#getLabels--}
```
public final VCardLabelCollection getLabels()
```


Получает или задает адрес доставки.

**Returns:**
[VCardLabelCollection](../../com.aspose.email/vcardlabelcollection)
### getMailer() {#getMailer--}
```
public final String getMailer()
```


Получает или задает почтовый клиент.

**Returns:**
java.lang.String
### getOrganization() {#getOrganization--}
```
public final VCardOrganization getOrganization()
```


Получает или задает информацию об организации.

**Returns:**
[VCardOrganization](../../com.aspose.email/vcardorganization)
### getSecurity() {#getSecurity--}
```
public final VCardSecurity getSecurity()
```


Получает или задает свойства безопасности.

**Returns:**
[VCardSecurity](../../com.aspose.email/vcardsecurity)
### getTelephoneNumbers() {#getTelephoneNumbers--}
```
public final VCardTelephoneNumberCollection getTelephoneNumbers()
```


Получает или задает телефонные номера контакта.

**Returns:**
[VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection)
### getTimeZone() {#getTimeZone--}
```
public final String getTimeZone()
```


Получает или задает часовой пояс.

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


Проверяет, содержит ли исходный поток несколько контактов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток |

**Returns:**
boolean — True, если несколько контактов, иначе false.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static VCardContact load(InputStream stream)
```


Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного потока, содержащего vCard. Поддерживаемые версии vCard: 2.1 и 3.0.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для чтения |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(InputStream stream, Charset encoding) {#load-java.io.InputStream-java.nio.charset.Charset-}
```
public static VCardContact load(InputStream stream, Charset encoding)
```


Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного потока, содержащего vCard. Поддерживаемые версии vCard: 2.1 и 3.0.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для чтения |
| кодировка | java.nio.charset.Charset | Кодировка данных потока |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(String filePath) {#load-java.lang.String-}
```
public static VCardContact load(String filePath)
```


Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла для чтения |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(String filePath, Charset encoding) {#load-java.lang.String-java.nio.charset.Charset-}
```
public static VCardContact load(String filePath, Charset encoding)
```


Читает [VCardContact](../../com.aspose.email/vcardcontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла для чтения |
| кодировка | java.nio.charset.Charset | Кодировка файла |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### loadAsMultiple(InputStream stream, Charset encoding) {#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(InputStream stream, Charset encoding)
```


Загружает список контактов из потока с несколькими контактами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток |
| кодировка | java.nio.charset.Charset | Кодировка данных потока, если null, будет использована UTF8. |

**Returns:**
java.util.List<com.aspose.email.VCardContact> — список контактов
### loadAsMultiple(String filePath, Charset encoding) {#loadAsMultiple-java.lang.String-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(String filePath, Charset encoding)
```


Загружает список контактов из файла с несколькими контактами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Исходный файл |
| кодировка | java.nio.charset.Charset | Кодировка данных файла, если null, будет использована UTF8. |

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


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате vCard. Поддерживаемая версия vCard: 2.1.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(OutputStream stream, ContactSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-}
```
public final void save(OutputStream stream, ContactSaveOptions saveOptions)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток, используя указанные параметры сохранения. Поддерживаемый параметр сохранения — [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | Параметры сохранения |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате, используя параметры по умолчанию. Поддерживаемый формат сохранения — vCard.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveFormat | int | Формат сохранения |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл vCard с параметрами по умолчанию. Поддерживаемая версия vCard — 2.1.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |

### save(String filePath, ContactSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.ContactSaveOptions-}
```
public final void save(String filePath, ContactSaveOptions saveOptions)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл, используя указанные параметры сохранения. Поддерживаемый параметр сохранения — [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | Параметры сохранения |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный файл в формате, используя параметры по умолчанию. Поддерживаемый формат сохранения — vCard.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |
| saveFormat | int | Формат сохранения |

### setDeliveryAddresses(VCardDeliveryAddressCollection value) {#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-}
```
public final void setDeliveryAddresses(VCardDeliveryAddressCollection value)
```


Получает или задает адрес доставки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection) |  |

### setEmails(VCardEmailCollection value) {#setEmails-com.aspose.email.VCardEmailCollection-}
```
public final void setEmails(VCardEmailCollection value)
```


Получает или задает адреса электронной почты контакта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardEmailCollection](../../com.aspose.email/vcardemailcollection) |  |

### setExplanatoryInfo(VCardExplanatoryInfo value) {#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-}
```
public final void setExplanatoryInfo(VCardExplanatoryInfo value)
```


Получает или задает пояснительную информацию vCard.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo) |  |

### setExtendedProperties(System.Collections.Specialized.StringCollection value) {#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setExtendedProperties(System.Collections.Specialized.StringCollection value)
```


Получает или задает расширенные свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setGeo(VCardGeo value) {#setGeo-com.aspose.email.VCardGeo-}
```
public final void setGeo(VCardGeo value)
```


Получает или задает глобальное позиционирование.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardGeo](../../com.aspose.email/vcardgeo) |  |

### setIdentificationInfo(VCardIdentificationInfo value) {#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-}
```
public final void setIdentificationInfo(VCardIdentificationInfo value)
```


Получает или задает свойства идентификации.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo) |  |

### setLabels(VCardLabelCollection value) {#setLabels-com.aspose.email.VCardLabelCollection-}
```
public final void setLabels(VCardLabelCollection value)
```


Получает или задает адрес доставки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardLabelCollection](../../com.aspose.email/vcardlabelcollection) |  |

### setMailer(String value) {#setMailer-java.lang.String-}
```
public final void setMailer(String value)
```


Получает или задает почтовый клиент.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrganization(VCardOrganization value) {#setOrganization-com.aspose.email.VCardOrganization-}
```
public final void setOrganization(VCardOrganization value)
```


Получает или задает информацию об организации.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardOrganization](../../com.aspose.email/vcardorganization) |  |

### setSecurity(VCardSecurity value) {#setSecurity-com.aspose.email.VCardSecurity-}
```
public final void setSecurity(VCardSecurity value)
```


Получает или задает свойства безопасности.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardSecurity](../../com.aspose.email/vcardsecurity) |  |

### setTelephoneNumbers(VCardTelephoneNumberCollection value) {#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-}
```
public final void setTelephoneNumbers(VCardTelephoneNumberCollection value)
```


Получает или задает телефонные номера контакта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection) |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String value)
```


Получает или задает часовой пояс.

**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

