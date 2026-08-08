---
title: AmpMessage
second_title: Aspose.Email for Android via Java API Reference
description: Сообщение, позволяющее отправителям включать AMP‑компоненты в электронные письма.
type: docs
weight: 22
url: /ru/androidjava/com.aspose.email/ampmessage/
---

**Inheritance:**
java.lang.Object, com.aspose.email.IPreferredTextEncodingProviderInternal, [com.aspose.email.MailMessage](../../com.aspose.email/mailmessage)
```
public class AmpMessage extends MailMessage
```

Сообщение, позволяющее отправителям включать AMP‑компоненты в электронные письма.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpMessage()](#AmpMessage--) | Инициализирует новый экземпляр класса [MailMessage](../../com.aspose.email/mailmessage) |
## Methods

| Method | Описание |
| --- | --- |
| [addAlternateView(AlternateView view)](#addAlternateView-com.aspose.email.AlternateView-) | Добавить альтернативный просмотр к сообщению |
| [addAmpComponent(AmpComponent component)](#addAmpComponent-com.aspose.email.AmpComponent-) | Добавить компонент Amp к этому сообщению. |
| [addAttachment(Attachment attachment)](#addAttachment-com.aspose.email.Attachment-) | Добавить вложение к сообщению. |
| [attachSignature(byte[] certificateRawData, String certificatePassword)](#attachSignature-byte---java.lang.String-) | Создаёт подписанное сообщение. |
| [attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)](#attachSignature-byte---java.lang.String-boolean-) | Создаёт подписанное сообщение. |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)](#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Создаёт подписанное сообщение. |
| [checkBounced()](#checkBounced--) | Проверяет, может ли это сообщение рассматриваться как сообщение‑отскок. |
| [checkSignature()](#checkSignature--) | Проверка подписи существующего MailMessage. |
| [checkSignature(InputStream stream)](#checkSignature-java.io.InputStream-) | Проверяет подпись указанного сообщения eml. |
| [checkSignature(String fileName)](#checkSignature-java.lang.String-) | Проверяет подпись указанного файла eml. |
| [checkSignatureCert()](#checkSignatureCert--) | Проверка подписи существующего MailMessage. |
| [close()](#close--) |  |
| [createReadReceipt(String from, String bodyText)](#createReadReceipt-java.lang.String-java.lang.String-) | Создаёт уведомление о прочтении. |
| [dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)](#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-) | Подписывает это сообщение с использованием подписи DKIM (DomainKeys Identified Mail). |
| [decrypt()](#decrypt--) | Расшифровывает это сообщение. |
| [decrypt(byte[] certificateRawData, String certificatePassword)](#decrypt-byte---java.lang.String-) | Расшифровывает это сообщение. |
| [decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые объектом MailMessage. |
| [encrypt(byte[] certificateRawData, String certificatePassword)](#encrypt-byte---java.lang.String-) | Шифрует это сообщение. |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) |  |
| [encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)](#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---) | Шифрует это сообщение. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему Object. |
| [getAlternateViews()](#getAlternateViews--) | Получает коллекцию альтернативных представлений сообщения. |
| [getAmpHtmlBody()](#getAmpHtmlBody--) | Получает представление AmpHtml тела сообщения. |
| [getAttachments()](#getAttachments--) | Получает коллекцию вложений сообщения |
| [getBcc()](#getBcc--) | Получает или задает коллекцию адресов, содержащую получателей BCC сообщения |
| [getBody()](#getBody--) | Получает или задает представление тела сообщения в виде простого текста. |
| [getBodyEncoding()](#getBodyEncoding--) | Получает или задает кодировку тела |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getCC()](#getCC--) | Получает или задает коллекцию адресов, содержащую получателей CC |
| [getCc()](#getCc--) | Получает получателей CC |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Получает или задает дату сообщения. Указывает дату и время, когда создатель сообщения указал, что сообщение завершено и готово к передаче в систему доставки почты. |
| [getDeliveryNotificationOptions()](#getDeliveryNotificationOptions--) | Получает или задает уведомления о доставке |
| [getEpilogue()](#getEpilogue--) | Получает или задает текст эпилога. |
| [getFrom()](#getFrom--) | Получает или задает адрес отправителя |
| [getHeaders()](#getHeaders--) | Получает коллекцию заголовков сообщения |
| [getHtmlBody()](#getHtmlBody--) | Получает или задает HTML‑тело |
| [getHtmlBodyText()](#getHtmlBodyText--) | Получает HTML‑тело сообщения в виде простого текста. |
| [getHtmlBodyText(boolean showUrl)](#getHtmlBodyText-boolean-) | Получает HTML‑тело сообщения в виде простого текста. |
| [getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)](#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-) | Получает HTML‑тело сообщения в виде простого текста. |
| [getItemId()](#getItemId--) | Представляет идентификационную информацию о сообщении в почтовом ящике. |
| [getLinkedResources()](#getLinkedResources--) | Получает коллекцию связанных ресурсов сообщения |
| [getLocalDate()](#getLocalDate--) | Получает локальную дату сообщения |
| [getMessageId()](#getMessageId--) | Получает или задает идентификатор сообщения |
| [getOriginalIsTnef()](#getOriginalIsTnef--) | Получает значение, указывающее, находится ли оригинальное сообщение EML в формате TNEF. |
| [getPreamble()](#getPreamble--) | Получает или задает текст преамбулы. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Получает или задает предпочтительную кодировку для всех текстовых свойств |
| [getPriority()](#getPriority--) | Получает или задает приоритет сообщения |
| [getReadReceiptTo()](#getReadReceiptTo--) | Получает или задает адрес уведомления о прочтении. |
| [getReplyToList()](#getReplyToList--) | Получает или задает список адресов для ответа на почтовое сообщение |
| [getReversePath()](#getReversePath--) | Получает или задает адрес ReversePath |
| [getSender()](#getSender--) | Получает или задает адрес отправителя |
| [getSensitivity()](#getSensitivity--) | Получает или задает чувствительность сообщения |
| [getSubject()](#getSubject--) | Получает или задает строку темы |
| [getSubjectEncoding()](#getSubjectEncoding--) | Получает или задает кодировку темы |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
| [getTo()](#getTo--) | Получает или задает коллекцию адресов, содержащую получателей сообщения |
| [getXMailer()](#getXMailer--) | Получает или задает X-Mailer — программное обеспечение, создавшее электронное сообщение |
| [hashCode()](#hashCode--) | Возвращает хеш-код объекта |
| [importMessage(InputStream stream)](#importMessage-java.io.InputStream-) | Импортирует сообщение из потока |
| [isBodyHtml()](#isBodyHtml--) | Получает или задает значение, указывающее, находится ли тело сообщения в формате HTML |
| [isBodyHtml(boolean value)](#isBodyHtml-boolean-) | Получает или задает значение, указывающее, находится ли тело сообщения в формате HTML |
| [isDraft()](#isDraft--) | Получает или задает значение, указывающее, было ли сообщение отправлено. |
| [isDraft(boolean value)](#isDraft-boolean-) | Получает или задает значение, указывающее, было ли сообщение отправлено. |
| [isEncrypted()](#isEncrypted--) | Получает значение, указывающее, зашифровано ли сообщение. |
| [isLocalDate()](#isLocalDate--) | Определяет, является ли дата локальной |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступно ли сообщение только для чтения |
| [isSigned()](#isSigned--) | Получает значение, указывающее, подписано ли сообщение. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает сообщение из потока |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Загружает сообщение из потока с дополнительными параметрами. |
| [load(String fileName)](#load-java.lang.String-) | Загружает сообщение из файла |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Загружает сообщение из файла с дополнительными параметрами. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recomposeTnefContent()](#recomposeTnefContent--) | Создаёт содержимое TNEF. |
| [removeSignature()](#removeSignature--) | Удалить подпись |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет сообщение как поток |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Сохраняет сообщение как поток |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет сообщение как файл |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Сохраняет сообщение как файл с дополнительными параметрами. |
| [setAmpHtmlBody(String value)](#setAmpHtmlBody-java.lang.String-) | Получает представление AmpHtml тела сообщения. |
| [setBcc(MailAddressCollection value)](#setBcc-com.aspose.email.MailAddressCollection-) | Получает или задает коллекцию адресов, содержащую получателей BCC сообщения |
| [setBody(String value)](#setBody-java.lang.String-) | Получает или задает представление тела сообщения в виде простого текста. |
| [setBodyEncoding(Charset value)](#setBodyEncoding-java.nio.charset.Charset-) | Получает или задает кодировку тела |
| [setCC(MailAddressCollection value)](#setCC-com.aspose.email.MailAddressCollection-) | Получает или задает коллекцию адресов, содержащую получателей CC |
| [setDate(Date value)](#setDate-java.util.Date-) | Получает или задает дату сообщения |
| [setDeliveryNotificationOptions(int value)](#setDeliveryNotificationOptions-int-) | Получает или задает уведомления о доставке |
| [setEpilogue(String value)](#setEpilogue-java.lang.String-) | Получает или задает текст эпилога. |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Устанавливает адрес отправителя |
| [setFrom(MailAddress value)](#setFrom-com.aspose.email.MailAddress-) | Получает или задает адрес отправителя |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Получает или задает HTML‑тело |
| [setHtmlBody(String value, boolean detectEncoding)](#setHtmlBody-java.lang.String-boolean-) | Устанавливает HTML‑тело. |
| [setMessageId(String value)](#setMessageId-java.lang.String-) | Получает или задает идентификатор сообщения |
| [setPreamble(String value)](#setPreamble-java.lang.String-) | Получает или задает текст преамбулы. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Получает или задает предпочтительную кодировку для всех текстовых свойств |
| [setPriority(MailPriority value)](#setPriority-com.aspose.email.MailPriority-) | Получает или задает приоритет сообщения |
| [setReadReceiptTo(MailAddressCollection value)](#setReadReceiptTo-com.aspose.email.MailAddressCollection-) | Получает или задает адрес уведомления о прочтении. |
| [setReplyToList(MailAddressCollection value)](#setReplyToList-com.aspose.email.MailAddressCollection-) | Получает или задает список адресов для ответа на почтовое сообщение |
| [setReversePath(MailAddress value)](#setReversePath-com.aspose.email.MailAddress-) | Получает или задает адрес ReversePath |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Получает или задает адрес отправителя |
| [setSensitivity(MailSensitivity value)](#setSensitivity-com.aspose.email.MailSensitivity-) | Получает или задает чувствительность сообщения |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает строку темы |
| [setSubjectEncoding(Charset value)](#setSubjectEncoding-java.nio.charset.Charset-) | Получает или задает кодировку темы |
| [setTimeZoneOffset(double value)](#setTimeZoneOffset-double-) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
| [setTo(MailAddressCollection value)](#setTo-com.aspose.email.MailAddressCollection-) | Получает или задает коллекцию адресов, содержащую получателей сообщения |
| [setXMailer(String value)](#setXMailer-java.lang.String-) | Получает или задает X-Mailer — программное обеспечение, создавшее электронное сообщение |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [validateMessage(InputStream stream)](#validateMessage-java.io.InputStream-) | Проверьте сообщение eml на соответствие спецификации mime. |
| [validateMessage(String fileName)](#validateMessage-java.lang.String-) | Проверьте сообщение eml на соответствие спецификации mime. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpMessage() {#AmpMessage--}
```
public AmpMessage()
```


Инициализирует новый экземпляр класса [MailMessage](../../com.aspose.email/mailmessage)

### addAlternateView(AlternateView view) {#addAlternateView-com.aspose.email.AlternateView-}
```
public void addAlternateView(AlternateView view)
```


Добавить альтернативный просмотр к сообщению

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| view | [AlternateView](../../com.aspose.email/alternateview) | Альтернативный вид для добавления |

### addAmpComponent(AmpComponent component) {#addAmpComponent-com.aspose.email.AmpComponent-}
```
public final void addAmpComponent(AmpComponent component)
```


Добавить компонент Amp к этому сообщению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| component | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### addAttachment(Attachment attachment) {#addAttachment-com.aspose.email.Attachment-}
```
public void addAttachment(Attachment attachment)
```


Добавить вложение к сообщению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| attachment | [Attachment](../../com.aspose.email/attachment) | Вложение для добавления |

### attachSignature(byte[] certificateRawData, String certificatePassword) {#attachSignature-byte---java.lang.String-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword)
```


Создаёт подписанное сообщение. Создаёт только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificateRawData | byte[] | Сертификат X.509. |
| certificatePassword | java.lang.String | Пароль, необходимый для доступа к данным сертификата X.509 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached) {#attachSignature-byte---java.lang.String-boolean-}
```
public MailMessage attachSignature(byte[] certificateRawData, String certificatePassword, boolean detached)
```


Создаёт подписанное сообщение. Создаёт только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificateRawData | byte[] | Сертификат X.509. |
| certificatePassword | java.lang.String | Пароль, необходимый для доступа к данным сертификата X.509 |
| detached | boolean | .Если detached равно true, подпись отделена.Если detached равно false (по умолчанию), подпись не отделена. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - The signed MailMessage.
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached) {#attachSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
```
public MailMessage attachSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, boolean detached)
```


Создаёт подписанное сообщение. Создаёт только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | Сертификат X.509. |
| detached | boolean | .Если detached равно true, подпись отделена.Если detached равно false (по умолчанию), подпись не отделена. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### checkBounced() {#checkBounced--}
```
public BounceResult checkBounced()
```


Проверяет, может ли это сообщение рассматриваться как сообщение‑отскок.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### checkSignature() {#checkSignature--}
```
public String[] checkSignature()
```


Проверка подписи существующего MailMessage.

**Returns:**
java.lang.String[] — сертификаты подписантов X.509
### checkSignature(InputStream stream) {#checkSignature-java.io.InputStream-}
```
public static boolean checkSignature(InputStream stream)
```


Проверяет подпись указанного сообщения eml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий сообщение в формате eml. |

**Returns:**
boolean — True, если подпись действительна; иначе — false.
### checkSignature(String fileName) {#checkSignature-java.lang.String-}
```
public static boolean checkSignature(String fileName)
```


Проверяет подпись указанного файла eml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла (eml). |

**Returns:**
boolean — True, если подпись действительна; иначе — false.
### checkSignatureCert() {#checkSignatureCert--}
```
public System.Security.Cryptography.X509Certificates.X509Certificate2[] checkSignatureCert()
```


Проверка подписи существующего MailMessage.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] — сертификаты подписантов X.509
### close() {#close--}
```
public void close()
```




### createReadReceipt(String from, String bodyText) {#createReadReceipt-java.lang.String-java.lang.String-}
```
public final MailMessage createReadReceipt(String from, String bodyText)
```


Создаёт уведомление о прочтении.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| from | java.lang.String | String, представляющая адрес отправителя. |
| bodyText | java.lang.String | Текст тела сообщения. Текст тела сообщения по умолчанию будет применён, если этот параметр равен null или пуст. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A newly created [MailMessage](../../com.aspose.email/mailmessage) that represents the read receipt.
### dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo) {#dKIMSign-com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider-com.aspose.email.DKIMSignatureInfo-}
```
public MailMessage dKIMSign(System.Security.Cryptography.RSACryptoServiceProvider rsa, DKIMSignatureInfo signatureInfo)
```


Подписывает это сообщение с использованием подписи DKIM (DomainKeys Identified Mail).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| rsa | com.aspose.ms.System.Security.Cryptography.RSACryptoServiceProvider | Класс RSA, содержащий закрытый ключ, используемый для подписи. |
| signatureInfo | [DKIMSignatureInfo](../../com.aspose.email/dkimsignatureinfo) | Информация о подписи DKIM. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - 
### decrypt() {#decrypt--}
```
public MailMessage decrypt()
```


Расшифровывает это сообщение.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(byte[] certificateRawData, String certificatePassword) {#decrypt-byte---java.lang.String-}
```
public MailMessage decrypt(byte[] certificateRawData, String certificatePassword)
```


Расшифровывает это сообщение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificateRawData | byte[] | System.Security.Cryptography.X509Certificates.X509Certificate2 |
| certificatePassword | java.lang.String | Пароль, необходимый для доступа к данным сертификата X.509 |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#decrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage decrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### deepClone() {#deepClone--}
```
public MailMessage deepClone()
```


Клонирует этот экземпляр.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - MailMessage that is a copy of the current instance
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает все ресурсы, используемые объектом MailMessage.

### encrypt(byte[] certificateRawData, String certificatePassword) {#encrypt-byte---java.lang.String-}
```
public MailMessage encrypt(byte[] certificateRawData, String certificatePassword)
```


Шифрует это сообщение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificateRawData | byte[] | X509 сертификат для шифрования сообщения |
| certificatePassword | java.lang.String |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 |  |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates) {#encrypt-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2---}
```
public MailMessage encrypt(System.Security.Cryptography.X509Certificates.X509Certificate2[] certificates)
```


Шифрует это сообщение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| сертификаты | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2[] | Массив X509 сертификатов для шифрования сообщения |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Encrypted email message
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### getAlternateViews() {#getAlternateViews--}
```
public AlternateViewCollection getAlternateViews()
```


Получает коллекцию альтернативных представлений сообщения.

**Returns:**
[AlternateViewCollection](../../com.aspose.email/alternateviewcollection)
### getAmpHtmlBody() {#getAmpHtmlBody--}
```
public String getAmpHtmlBody()
```


Получает представление AmpHtml тела сообщения.

**Returns:**
java.lang.String
### getAttachments() {#getAttachments--}
```
public AttachmentCollection getAttachments()
```


Получает коллекцию вложений сообщения

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


Получает или задает коллекцию адресов, содержащую получателей BCC сообщения

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBody() {#getBody--}
```
public String getBody()
```


Получает или задает текстовое представление тела сообщения. Если в сообщении присутствует часть text/plain, свойство возвращает её текстовые данные. В противном случае свойство возвращает текстовое содержимое свойства HtmlBody без HTML-разметки.

**Returns:**
java.lang.String
### getBodyEncoding() {#getBodyEncoding--}
```
public Charset getBodyEncoding()
```


Получает или задает кодировку тела

**Returns:**
java.nio.charset.Charset
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Получает тип тела.

**Returns:**
int
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


Получает или задает коллекцию адресов, содержащую получателей CC

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getCc() {#getCc--}
```
public final System.Collections.Generic.IGenericCollection<MailAddress> getCc()
```


Получает получателей CC

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public Date getDate()
```


Получает или задает дату сообщения. Указывает дату и время, когда создатель сообщения указал, что сообщение завершено и готово к передаче в систему доставки почты.

**Returns:**
java.util.Date
### getDeliveryNotificationOptions() {#getDeliveryNotificationOptions--}
```
public int getDeliveryNotificationOptions()
```


Получает или задает уведомления о доставке

**Returns:**
int
### getEpilogue() {#getEpilogue--}
```
public final String getEpilogue()
```


Получает или задает текст эпилога. Он располагается после последней границы.

Значение: строковое значение, представляющее эпилог.

**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public MailAddress getFrom()
```


Получает или задает адрес отправителя

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Получает коллекцию заголовков сообщения

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getHtmlBody() {#getHtmlBody--}
```
public String getHtmlBody()
```


Получает или задает HTML‑тело

**Returns:**
java.lang.String
### getHtmlBodyText() {#getHtmlBodyText--}
```
public final String getHtmlBodyText()
```


Получает HTML‑тело сообщения в виде простого текста.

**Returns:**
java.lang.String
### getHtmlBodyText(boolean showUrl) {#getHtmlBodyText-boolean-}
```
public String getHtmlBodyText(boolean showUrl)
```


Получает HTML‑тело сообщения в виде обычного текста. Этот метод разбирает свойство HtmlBody и возвращает текстовое содержимое, игнорируя HTML‑разметку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| showUrl | boolean | Определяет необходимость отображения URL в тексте. |

**Returns:**
java.lang.String
### getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback) {#getHtmlBodyText-com.aspose.email.HyperlinkRenderingCallback-}
```
public String getHtmlBodyText(HyperlinkRenderingCallback hyperlinkRenderingCallback)
```


Получает HTML‑тело сообщения в виде простого текста.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| hyperlinkRenderingCallback | [HyperlinkRenderingCallback](../../com.aspose.email/hyperlinkrenderingcallback) | Ссылка на пользовательский метод обработки отображения гиперссылки. |

**Returns:**
java.lang.String — результирующая строка пользовательской обработки отображения гиперссылки.
### getItemId() {#getItemId--}
```
public MailboxInfo getItemId()
```


Представляет идентификационную информацию о сообщении в почтовом ящике.

**Returns:**
[MailboxInfo](../../com.aspose.email/mailboxinfo)
### getLinkedResources() {#getLinkedResources--}
```
public LinkedResourceCollection getLinkedResources()
```


Получает коллекцию связанных ресурсов сообщения

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
### getLocalDate() {#getLocalDate--}
```
public Date getLocalDate()
```


Получает локальную дату сообщения

**Returns:**
java.util.Date — локальная дата сообщения
### getMessageId() {#getMessageId--}
```
public String getMessageId()
```


Получает или задает идентификатор сообщения

**Returns:**
java.lang.String
### getOriginalIsTnef() {#getOriginalIsTnef--}
```
public boolean getOriginalIsTnef()
```


Получает значение, указывающее, находится ли оригинальное сообщение EML в формате TNEF.

**Returns:**
boolean
### getPreamble() {#getPreamble--}
```
public final String getPreamble()
```


Получает или задает текст преамбулы. Он располагается перед первой границей и обычно включает пояснительную заметку для читателей, не поддерживающих MIME.

Значение: строковое значение, представляющее преамбулу.

**Returns:**
java.lang.String
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Получает или задает предпочтительную кодировку для всех текстовых свойств

**Returns:**
java.nio.charset.Charset
### getPriority() {#getPriority--}
```
public MailPriority getPriority()
```


Получает или задает приоритет сообщения

**Returns:**
[MailPriority](../../com.aspose.email/mailpriority)
### getReadReceiptTo() {#getReadReceiptTo--}
```
public final MailAddressCollection getReadReceiptTo()
```


Получает или задает адрес уведомления о прочтении.

Значение: [MailAddressCollection](../../com.aspose.email/mailaddresscollection), который представляет

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReplyToList() {#getReplyToList--}
```
public MailAddressCollection getReplyToList()
```


Получает или задает список адресов для ответа на почтовое сообщение

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReversePath() {#getReversePath--}
```
public MailAddress getReversePath()
```


Получает или задает адрес ReversePath

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSender() {#getSender--}
```
public MailAddress getSender()
```


Получает или задает адрес отправителя

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSensitivity() {#getSensitivity--}
```
public MailSensitivity getSensitivity()
```


Получает или задает чувствительность сообщения

**Returns:**
[MailSensitivity](../../com.aspose.email/mailsensitivity)
### getSubject() {#getSubject--}
```
public String getSubject()
```


Получает или задает строку темы

**Returns:**
java.lang.String
### getSubjectEncoding() {#getSubjectEncoding--}
```
public Charset getSubjectEncoding()
```


Получает или задает кодировку темы

**Returns:**
java.nio.charset.Charset
### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final double getTimeZoneOffset()
```


Получает или задает смещение от всемирного координированного времени (UTC) для дат сообщений. Это свойство определяет разницу часового пояса между локальным временем и UTC.

**Returns:**
double — количество миллисекунд.
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


Получает или задает коллекцию адресов, содержащую получателей сообщения

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getXMailer() {#getXMailer--}
```
public String getXMailer()
```


Получает или задает X-Mailer — программное обеспечение, создавшее электронное сообщение

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код объекта

**Returns:**
int -
### importMessage(InputStream stream) {#importMessage-java.io.InputStream-}
```
public void importMessage(InputStream stream)
```


Импортирует сообщение из потока

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream |

### isBodyHtml() {#isBodyHtml--}
```
public boolean isBodyHtml()
```


Получает или задает значение, указывающее, находится ли тело сообщения в формате HTML

**Returns:**
boolean
### isBodyHtml(boolean value) {#isBodyHtml-boolean-}
```
public void isBodyHtml(boolean value)
```


Получает или задает значение, указывающее, находится ли тело сообщения в формате HTML

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### isDraft() {#isDraft--}
```
public boolean isDraft()
```


Получает или задает значение, указывающее, было ли сообщение отправлено.

**Returns:**
boolean
### isDraft(boolean value) {#isDraft-boolean-}
```
public void isDraft(boolean value)
```


Получает или задает значение, указывающее, было ли сообщение отправлено.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Получает значение, указывающее, зашифровано ли сообщение.

**Returns:**
boolean
### isLocalDate() {#isLocalDate--}
```
public boolean isLocalDate()
```


Определяет, является ли дата локальной

**Returns:**
boolean — true, если дата является локальной датой
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступно ли сообщение только для чтения

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Получает значение, указывающее, подписано ли сообщение.

**Returns:**
boolean
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<MailMessage> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.MailMessage> — объект IEnumerator, который можно использовать для перебора элементов коллекции.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MailMessage load(InputStream stream)
```


Загружает сообщение из потока

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, представляющий сообщение в формате eml или msg |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MailMessage load(InputStream stream, LoadOptions options)
```


Загружает сообщение из потока с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток java.io.InputStream. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Дополнительные параметры [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### load(String fileName) {#load-java.lang.String-}
```
public static MailMessage load(String fileName)
```


Загружает сообщение из файла

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла сообщения. Файл сообщения должен быть в формате eml или msg. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MailMessage load(String fileName, LoadOptions options)
```


Загружает сообщение из файла с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Исходный путь к файлу pathString. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Дополнительные параметры [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Mail message[MailMessage](../../com.aspose.email/mailmessage).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recomposeTnefContent() {#recomposeTnefContent--}
```
public final void recomposeTnefContent()
```


Создаёт содержимое TNEF. Обратите внимание, что вложение tnef создаётся, если сообщение изначально содержало TNEF и было загружено без флага FileCompatibilityMode.PreserveTnefAttachments. То есть этот метод не создаёт tnef‑сообщение из обычного.

### removeSignature() {#removeSignature--}
```
public MailMessage removeSignature()
```


Удалить подпись

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - E-mail message
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет сообщение как поток

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняется сообщение |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Сохраняет сообщение как поток

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняется сообщение |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Дополнительные параметры для сохранения[SaveOptions](../../com.aspose.email/saveoptions). |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Сохраняет сообщение как файл

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла для сохранения сообщения. |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Сохраняет сообщение как файл с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Поток, в который сохраняется сообщение. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Дополнительные параметры для сохранения[SaveOptions](../../com.aspose.email/saveoptions). |

### setAmpHtmlBody(String value) {#setAmpHtmlBody-java.lang.String-}
```
public void setAmpHtmlBody(String value)
```


Получает представление AmpHtml тела сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBcc(MailAddressCollection value) {#setBcc-com.aspose.email.MailAddressCollection-}
```
public void setBcc(MailAddressCollection value)
```


Получает или задает коллекцию адресов, содержащую получателей BCC сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Получает или задает текстовое представление тела сообщения. Если в сообщении присутствует часть text/plain, свойство возвращает её текстовые данные. В противном случае свойство возвращает текстовое содержимое свойства HtmlBody без HTML-разметки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyEncoding(Charset value) {#setBodyEncoding-java.nio.charset.Charset-}
```
public void setBodyEncoding(Charset value)
```


Получает или задает кодировку тела

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setCC(MailAddressCollection value) {#setCC-com.aspose.email.MailAddressCollection-}
```
public void setCC(MailAddressCollection value)
```


Получает или задает коллекцию адресов, содержащую получателей CC

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Получает или задает дату сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDeliveryNotificationOptions(int value) {#setDeliveryNotificationOptions-int-}
```
public void setDeliveryNotificationOptions(int value)
```


Получает или задает уведомления о доставке

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setEpilogue(String value) {#setEpilogue-java.lang.String-}
```
public final void setEpilogue(String value)
```


Получает или задает текст эпилога. Он располагается после последней границы.

Значение: строковое значение, представляющее эпилог.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public final void setFrom(IMailAddress value)
```


Устанавливает адрес отправителя

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) | Адрес отправителя |

### setFrom(MailAddress value) {#setFrom-com.aspose.email.MailAddress-}
```
public void setFrom(MailAddress value)
```


Получает или задает адрес отправителя

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public void setHtmlBody(String value)
```


Получает или задает HTML‑тело

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setHtmlBody(String value, boolean detectEncoding) {#setHtmlBody-java.lang.String-boolean-}
```
public void setHtmlBody(String value, boolean detectEncoding)
```


Устанавливает HTML‑тело.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Текст содержимого HtmlBody. |
| detectEncoding | boolean | Определять кодировку тела, если кодировка не указана для MailMessage. |

### setMessageId(String value) {#setMessageId-java.lang.String-}
```
public void setMessageId(String value)
```


Получает или задает идентификатор сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreamble(String value) {#setPreamble-java.lang.String-}
```
public final void setPreamble(String value)
```


Получает или задает текст преамбулы. Он располагается перед первой границей и обычно включает пояснительную заметку для читателей, не поддерживающих MIME.

Значение: строковое значение, представляющее преамбулу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Получает или задает предпочтительную кодировку для всех текстовых свойств

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPriority(MailPriority value) {#setPriority-com.aspose.email.MailPriority-}
```
public void setPriority(MailPriority value)
```


Получает или задает приоритет сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailPriority](../../com.aspose.email/mailpriority) |  |

### setReadReceiptTo(MailAddressCollection value) {#setReadReceiptTo-com.aspose.email.MailAddressCollection-}
```
public final void setReadReceiptTo(MailAddressCollection value)
```


Получает или задает адрес уведомления о прочтении.

Значение: [MailAddressCollection](../../com.aspose.email/mailaddresscollection), который представляет

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReplyToList(MailAddressCollection value) {#setReplyToList-com.aspose.email.MailAddressCollection-}
```
public void setReplyToList(MailAddressCollection value)
```


Получает или задает список адресов для ответа на почтовое сообщение

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setReversePath(MailAddress value) {#setReversePath-com.aspose.email.MailAddress-}
```
public void setReversePath(MailAddress value)
```


Получает или задает адрес ReversePath

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public void setSender(MailAddress value)
```


Получает или задает адрес отправителя

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setSensitivity(MailSensitivity value) {#setSensitivity-com.aspose.email.MailSensitivity-}
```
public void setSensitivity(MailSensitivity value)
```


Получает или задает чувствительность сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailSensitivity](../../com.aspose.email/mailsensitivity) |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Получает или задает строку темы

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubjectEncoding(Charset value) {#setSubjectEncoding-java.nio.charset.Charset-}
```
public void setSubjectEncoding(Charset value)
```


Получает или задает кодировку темы

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setTimeZoneOffset(double value) {#setTimeZoneOffset-double-}
```
public final void setTimeZoneOffset(double value)
```


Получает или задает смещение от всемирного координированного времени (UTC) для дат сообщений. Это свойство определяет разницу часового пояса между локальным временем и UTC.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | double | Количество миллисекунд. |

### setTo(MailAddressCollection value) {#setTo-com.aspose.email.MailAddressCollection-}
```
public void setTo(MailAddressCollection value)
```


Получает или задает коллекцию адресов, содержащую получателей сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setXMailer(String value) {#setXMailer-java.lang.String-}
```
public void setXMailer(String value)
```


Получает или задает X-Mailer — программное обеспечение, создавшее электронное сообщение

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
### validateMessage(InputStream stream) {#validateMessage-java.io.InputStream-}
```
public static EmlValidationErrorCollection validateMessage(InputStream stream)
```


Проверьте сообщение eml на соответствие спецификации mime.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий сообщение в формате eml. |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
### validateMessage(String fileName) {#validateMessage-java.lang.String-}
```
public static EmlValidationErrorCollection validateMessage(String fileName)
```


Проверьте сообщение eml на соответствие спецификации mime.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла (eml). |

**Returns:**
[EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) - A [EmlValidationErrorCollection](../../com.aspose.email/emlvalidationerrorcollection) containing the found validation error messages.
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

