---
title: Aspose.Email.Clients.Imap
second_title: Справочник по Aspose.Email для .NET API
description: Пространство имен Aspose.Email.Clients.Imap предоставляет доступ к классам и управлять сообщениями с помощью протокола доступа к сообщениям в Интернете IMAP.
type: docs
weight: 220
url: /ru/net/aspose.email.clients.imap/
---
Пространство имен **Aspose.Email.Clients.Imap** предоставляет доступ к классам и управлять сообщениями с помощью протокола доступа к сообщениям в Интернете (IMAP).

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Содержит результат работы с сообщениями |
| [BackupSettings](./backupsettings) | Класс содержит опции для операции резервного копирования |
| [BaseSearchConditions](./basesearchconditions) | Предоставляет базовый класс для условий поиска. |
| [ESearchOptions](./esearchoptions) | Параметры результата ESEARCH Этот метод работает, только если сервер поддерживает расширение ESEARCH. Подробнее https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Представляет исключение, которое возникает, когда сообщение не может быть прочитано в течение заданного времени. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Представляет информацию о вложении. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Представляет коллекцию[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Позволяет приложениям получать доступ и управлять сообщениями с помощью протокола доступа к сообщениям в Интернете (IMAP). |
| [ImapFolderInfo](./imapfolderinfo) | Представляет папку IMAP. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Предоставляет контейнер для коллекции объектов ImapFolderInfo. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Представляет класс-контейнер с идентификационной информацией для обмена между почтовым клиентом и сервером. Пожалуйста, прочитайте больше rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Содержит набор почтовых ящиков специального назначения |
| [ImapMessageFlags](./imapmessageflags) | Представляет флаги, связанные с сообщением. |
| [ImapMessageInfo](./imapmessageinfo) | Представляет объект сообщения Imap. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Предоставляет контейнер для коллекции объектов[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | Класс содержит данные об ошибках мониторинга. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Представляет метод, который будет обрабатывать событие ошибки мониторинга imap |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | Класс содержит данные о событиях мониторинга. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Представляет метод, который будет обрабатывать событие мониторинга imap |
| [ImapNamespace](./imapnamespace) | Представляет пространство имен IMAP Подробнее:https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Содержит информацию о полученной странице при использовании методов пейджинга. |
| [ImapQueryBuilder](./imapquerybuilder) | Представляет построитель поискового выражения , используемого протоколом IMAP. |
| [ImapQuota](./imapquota) | Содержит информацию о квоте ресурса почтового ящика. |
| [ImapQuotaRoot](./imapquotaroot) | Содержит информацию о корневой квоте для ресурса почтового ящика. |
| [MessageThreadResult](./messagethreadresult) | Содержит результат для методов SORT или THREAD Подробнее:https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Определяет набор значений для выбранного поля для поиска. |
| [PageSettings](./pagesettings) | Настройки для метода ImapClient.ListMessagesByPage |
| [PageSettingsAsync](./pagesettingsasync) | Настройки асинхронного метода ImapClient.BeginListMessagesByPage. |
| [RangeSeqSet](./rangeseqset) | Контейнер с диапазоном значений для поиска. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Представляет исключение, которое возникает, когда ответ от сервера не может быть прочитан в течение заданного времени. |
| [RestoreSettings](./restoresettings) | Настройки метода ImapClient.Restore |
| [RestoreSettingsAsync](./restoresettingsasync) | Настройки асинхронного метода ImapClient.Restore. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Базовый класс для различных контейнеров для значений для поиска. |
| [SequenceSetField](./sequencesetfield) | Определяет набор значений для выбранного поля для поиска. |
| [SimpleSeqSet](./simpleseqset) | Простой контейнер для значения для поиска. |
| [SortConditions](./sortconditions) | Предоставляет условия поиска для расширения SORT. Совместимость с расширением SORT IMAP, описанным в https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Предоставляет условия поиска для извлечения ветки электронной почты. Совместимость с расширением THREAD IMAP, описанным в https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Предоставляет условия поиска для извлечения ветки электронной почты. Совместимость с расширением IMAP X-GM-EXT-1, описанным на странице https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Позволяет приложениям получать доступ и управлять сообщениями с помощью протокола доступа к сообщениям в Интернете (IMAP). |
| [IImapMonitoringState](./iimapmonitoringstate) | Содержит состояние мониторинга папки. Это можно использовать для возобновления мониторинга папок с места , где оно было остановлено при возникновении ошибки. Используйте[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring)метод. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Перечисляет результаты команды imap. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Поля, которые можно получить с сервера |
| [ImapNamespaceType](./imapnamespacetype) | Представляет тип пространства имен IMAP Подробнее:https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Представляет перечисление почтовых ящиков специального назначения Подробнее см. в RFC6154 http://tools.ietf.org /html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Представляет ответы о состоянии. |
| [ListFoldersOptions](./listfoldersoptions) | Опции выбора списка папок Обратите внимание, что эти опции поддерживаются в случае, если сервер поддерживает RFC 5258 "IMAP LIST Command Extensions" Подробнее см. https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Параметры возврата для операции ListFolders Обратите внимание, что эти параметры поддерживаются в случае, если сервер поддерживает RFC 5258 "Расширения команд IMAP LIST" Подробнее см. https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Критерии сортировки для команды "СОРТИРОВКА" Подробнее:https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
