---
title: HeaderType
second_title: Справочник по Aspose.Email для .NET API
description: Представляет стандарты Интернета а RFC определяют поля заголовков которые могут встречаться в сообщениях электронной почты Интернета.
type: docs
weight: 17510
url: /ru/net/aspose.email/headertype/
---
## HeaderType class

Представляет стандарты Интернета, а RFC определяют поля заголовков, которые могут встречаться в сообщениях электронной почты Интернета.

```csharp
public sealed class HeaderType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto) { get; } | Вставляется при отправке электронной почты, когда в исходном сообщении нет получателя «Кому:». Это приводит к тому, что получатели, полученные из конверта, будут перечислены в заголовке сообщения. Такое поведение не совсем правильно, агенты передачи сообщений не должны изменять заголовки (кроме вставки строк Received), и в некоторых случаях это может привести к тому, что получатели скрытой копии будут ошибочно разглашены получателям без скрытой копии. Пример: Видимо-Кому: кто-то@somedomain.com Нестандартный заголовок, который не рекомендуется использовать, упомянутый в RFC1211. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby) { get; } | Имя модератора списка рассылки, которому отправлено это сообщение; необходимо в сообщении, отправленном в модерируемый список рассылки, чтобы разрешить его распространение среди членов списка. Пример: Утверждено кем-то@somedomain.com Нестандартно для использования в электронной почте. Определено в RFC1036. |
| static [Bcc](../../aspose.email/headertype/bcc) { get; } | Копия сообщения электронной почты, отправленная одному или нескольким получателям без ведома основных получателей. Основные получатели перечислены в строках Кому: и Копия:. Это полезно, если вы хотите скопировать сообщение многим людям, чтобы каждый из них не видел других получателей. Если вы видите этот заголовок во входящей почте, что-то не так, потому что он не отображается в заголовках. |
| static [CC](../../aspose.email/headertype/cc) { get; } | Этот заголовок можно рассматривать как расширение поля «Кому:», поскольку он используется для указания дополнительных получателей. В этом случае копия сообщения электронной почты, отправленного получателю, содержит адрес получателя, указанный в сообщении. Это полезно, если вы хотите скопировать сообщение многим людям, чтобы каждый из них видел, кто другие получатели; в отличие от Bcc выше. Этот заголовок появляется во входящей электронной почте. Пример: Копия: gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments) { get; } | Это поле заголовка произвольной формы, определенное в RFC2822. Заголовок используется для размещения пояснительного текста в заголовке сообщения электронной почты. Поле может содержать произвольный текст. Пример: Комментарии: Аутентифицированный отправитель — Someone@somedonmain.com. |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding) { get; } | Третий из заголовков, связанных с MIME. Указывает метод кодирования, используемый в теле сообщения MIME. Не имеет прямого отношения к доставке электронной почты, но влияет на то, как почтовые программы, совместимые с MIME, интерпретируют содержимое сообщения. Определено в RFC2045. Content-Transfer-Encoding: 8bit Content-Transfer-Encoding: 7BIT Content-Transfer-Encoding: 7bit Content-Transfer-Encoding: base64 Content-Transfer-Encoding: quoted-printable |
| static [ContentType](../../aspose.email/headertype/contenttype) { get; } | «Content-Type» определяет формат содержимого (набор символов и т. д.). Обратите внимание, что значения для этого заголовка определяются по-разному в RFC1049 и MIME (RFC2045). Найдите заголовок MIME-version:, чтобы понять, следует ли интерпретировать Content-Type в соответствии с RFC1049 или в соответствии с MIME (RFC2045). Определение MIME следует использовать при создании почты. Исторически поле Content-Type было предложено в RFC1049. В нем Content-Type не различает тип и подтип, как это делает RFC2045. Пример: Content-Type: text/plain; charset="us-ascii" Тип контента: текстовый/обычный; charset=US-ASCII Content-Type: text/plain; charset="iso-8859-1" Content-Type: text/plain; charset=koi8-r Content-Type: text/plain; кодировка = неизвестно-8bit |
| static [Date](../../aspose.email/headertype/date) { get; } | Этот заголовок указывает дату (и время), обычно дату составления и отправки сообщения. В почтовых системах X.400 - время отправки сообщения. Некоторые почтовые системы Интернета также используют дату отправки сообщения. Если этот заголовок опущен компьютером отправителя, он вполне может быть добавлен почтовым сервером или даже какой-либо другой машиной на маршруте. Возможно, вы не знаете, что информация в строке «Дата:» представлена временем на компьютере отправителя, которое может быть установлено правильно, а может и нет. Кроме того, заголовок «Дата:» обычно не указывает, когда сообщение было отправлено, а только когда оно было составлено. Дата указывается в виде 3-символьного дня недели (вс-сб), номера дня (1-31) дд, 3-символьного названия месяца, 4-значного года гггг, за которым следует время (в 24-часовом формате) чч :mm:ss и формат зоны zzz. Часовой пояс (zzz) — это либо трехзначный часовой пояс, либо местная разница в часах и минутах, смещенная от UTC (универсальное скоординированное время — старое среднее время по Гринвичу). «-» указывает на запад, а «+» указывает на восток от UTC. Кажется, не существует стандартных определений часовых поясов. Многие версии UNIX понимают большое количество сокращений, но наиболее исчерпывающий список, который я нашел, — это пункт часового пояса руководства GNU tar и документация для модуля Perl для работы с датами TIMEZONES. Пример: Дата: Вт, 9 января 2001 г. 23:40:00 -0800 Дата: Вс, 1 апреля 2001 г. 22:52:04 EDT Дата: Пн, 2 апреля 2001 г. 16:02:19 +0200_x0,00d_ Дата: Пт 30 марта 2001 г. 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto) { get; } | Когда установлено поле DispositionNotificationTo, выполняется запрос MDN (уведомление о доставке сообщения). Программа электронной почты получателя (Outlook, Eudora и т. д.) может молча игнорировать запрос или запросить у пользователя разрешение на отправку MDN. Гарантии "возврат-получение" нет. Поле DispositionNotificationTo является стандартом де-факто для запроса уведомлений о возврате (т. е. MDN или уведомлений о доставке сообщений). |
| static [FollowupTo](../../aspose.email/headertype/followupto) { get; } | Используется в новостях Usenet, чтобы указать, что будущие обсуждения (= продолжение) статьи должны проходить в другом наборе групп новостей, чем статья, на которую ответили. Чаще всего используется, когда статья размещается в нескольких группах новостей, а дальнейшее обсуждение должно проходить только в одной из них. Определено в RFC 1036: 2.2.3, не стандартизировано для использования в электронной почте. |
| static [From](../../aspose.email/headertype/from) { get; } | Это поле содержит личность человека (лиц), которые хотели, чтобы это сообщение было отправлено. Процесс создания сообщения должен по умолчанию указывать в этом поле один аутентифицированный адрес машины, указывающий АГЕНТА (человека, систему или процесс), создавшего сообщение. Если этого не сделать, ДОЛЖНО присутствовать поле «Отправитель:». Если поле «От:» установлено по умолчанию таким образом, поле «Отправитель:» является необязательным и дублирует поле «От:». Пример: From: "Mr. Some One" Someone@somedomain.com |
| static [Importance](../../aspose.email/headertype/importance) { get; } | Получает важность. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto) { get; } | Ссылка на сообщение, на которое это сообщение является ответом. |
| static [MessageID](../../aspose.email/headertype/messageid) { get; } | Уникальный идентификатор этого сообщения. Определено в RFC 822: 4.6.1, RFC 1036: 2.1.5. |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion) { get; } | Индикатор того, что это сообщение отформатировано в соответствии со стандартом MIME, и указание используемой версии MIME. Определено в RFC 2045 |
| static [Newsgroups](../../aspose.email/headertype/newsgroups) { get; } | В новостях Usenet: группы, в которых была размещена эта статья. Некоторые системы предоставляют это поле заголовка также в электронной почте, хотя там оно не стандартизировано. К сожалению, поле заголовка может появляться в электронной почте с тремя различными и противоречащими друг другу значениями: (a) Указание получателя группы новостей статьи/сообщения, отправляемого получателям как электронной почты, так и новостей Usenet. (b) В сообщении, адресованном некоторым почтовым шлюзам новостей, указывает группы новостей, в которые должно быть отправлено сообщение. (c) В личном ответе на статью в группе новостей с указанием группы новостей, в которой началось это обсуждение. Определено в RFC 1036: 2.1.3, не стандартизировано и противоречиво для использования в электронной почте. |
| static [Received](../../aspose.email/headertype/received) { get; } | Трассировка MTA, через которые прошло сообщение. Определено в RFC 822 |
| static [References](../../aspose.email/headertype/references) { get; } | Ссылка на другие связанные сообщения. |
| static [ReplyTo](../../aspose.email/headertype/replyto) { get; } | Это поле заголовка предназначено для указания того, куда отправитель хочет направлять ответы. К сожалению, это неоднозначно, так как существуют разные виды ответов, которые отправитель может захотеть отправить на разные адреса. В частности, есть личные ответы, предназначенные только для одного человека, и групповые ответы, предназначенные для всей группы людей, прочитавших ответное сообщение (часто список рассылки, имя группы новостей не может отображаться здесь из-за различного синтаксиса, см. " Следить за".). |
| static [ReturnPath](../../aspose.email/headertype/returnpath) { get; } | Используется для передачи информации из атрибута конверта MAIL FROM при окончательной доставке, когда сообщение покидает среду SMTP, в которой используется «MAIL FROM». /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto) { get; } | Отправитель может запросить уведомление о возврате, включив это поле заголовка. Уведомление о возврате отправляется на адрес Return-Path электронного письма, а не на адрес, указанный в поле заголовка Return-Receipt-To. Этот заголовок нестандартен и в большинстве случаев не поддерживается. Вместо этого используйте Disposition-Notification-To. Даже если поддерживается, нет гарантии отправки квитанции. |
| static [Sender](../../aspose.email/headertype/sender) { get; } | Лицо или агент, отправляющий сообщение в сеть, если он не указан в поле заголовка From:. Должна пройти аутентификацию, согласно RFC 822, но какая именно аутентификация, не ясно. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity) { get; } | Получает чувствительность. |
| static [Subject](../../aspose.email/headertype/subject) { get; } | Название, заголовок, тема. Часто используется в качестве индикатора цепочек для сообщений, отвечающих на другие сообщения или комментирующих их. |
| static [To](../../aspose.email/headertype/to) { get; } | Основные получатели. Пример: Кому: Someone@somedomain.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto) { get; } | Этот заголовок запрашивает уведомление об автоматическом подтверждении, когда сообщение получено или прочитано. Обычно его игнорируют; предположительно какое-то программное обеспечение действует на него. |
| static [XMailer](../../aspose.email/headertype/xmailer) { get; } | Информация о клиентском ПО оригинатора. Пример: X-Mailer: Aspose.Email |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals)(object) | Возвращает логическое значение, указывающее, равен ли переданный объект obj этому значению. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode)() | Служит хеш-функцией для определенного типа. |
| override [ToString](../../aspose.email/headertype/tostring)() | ВозвращаетString который представляет текущийObject . |
| [implicit operator](../../aspose.email/headertype/op_implicit) | Выполняет неявное преобразование из[`HeaderType`](../headertype) кString . |

### Смотрите также

* пространство имен [Aspose.Email](../../aspose.email)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
