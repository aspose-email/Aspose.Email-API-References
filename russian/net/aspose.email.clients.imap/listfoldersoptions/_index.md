---
title: ListFoldersOptions
second_title: Справочник по Aspose.Email для .NET API
description: Параметры выбора списка папок Обратите внимание что эти параметры поддерживаются в случае если сервер поддерживает RFC 5258 Расширения команд IMAP LIST Подробнее см. https//tools.ietf.org/html/rfc5258
type: docs
weight: 16510
url: /ru/net/aspose.email.clients.imap/listfoldersoptions/
---
## ListFoldersOptions enumeration

Параметры выбора списка папок Обратите внимание, что эти параметры поддерживаются в случае, если сервер поддерживает RFC 5258 «Расширения команд IMAP LIST» Подробнее см. https://tools.ietf.org/html/rfc5258

```csharp
[Flags]
public enum ListFoldersOptions
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Не определено |
| Subscribed | `1` | SUBSCRIBED — заставляет команду LIST отображать список подписанных имен, , а не существующих почтовых ящиков. Часто это подмножество реальных почтовых ящиков. Этот список также может содержать имена несуществующих почтовых ящиков. В любом случае список ДОЛЖЕН включать именно те имена почтовых ящиков, которые соответствуют шаблону канонического списка и на которые подписаны. Этот параметр предназначен для дополнения команды LSUB. Особо следует отметить атрибуты почтового ящика, возвращаемые этой опцией, по сравнению с тем, что возвращает LSUB. В последнем случае возвращаемые атрибуты могут не отражать фактическое состояние атрибута в имени почтового ящика, и атрибут \NoSelect имеет второе специальное значение (он указывает, что этот почтовый ящик сам по себе не подписан, но что у него есть дочерние почтовые ящики). которые). При описанной здесь опции выбора SUBSCRIBED атрибуты являются точными и полными и не имеют особого значения. «LSUB» и «LIST (SUBSCRIBED)», таким образом, не одно и то же, и некоторые серверы должны выполнять значительную дополнительную работу, чтобы ответить на «LIST (SUBSCRIBED)». Из-за этого клиентам СЛЕДУЕТ продолжать использовать «LSUB», если они специально не хотят получать дополнительную информацию, предлагаемую «LIST (SUBSCRIBED)». подписан на. Атрибут "\Subscribed" ДОЛЖЕН поддерживаться и ДОЛЖЕН быть точно рассчитан, когда указана опция выбора SUBSCRIBED. Обратите внимание, что опция выбора SUBSCRIBED подразумевает опцию возврата SUBSCRIBED (см. ниже). |
| Remote | `2` | REMOTE — заставляет команду LIST отображать удаленные почтовые ящики так же, как и локальные, как описано в [MBRef]. Этот параметр предназначен для замены команды RLIST и, в сочетании с параметром выбора SUBSCRIBED, команды RLSUB. Атрибут \Remote ДОЛЖЕН быть точно рассчитан, когда указана опция REMOTE. Параметр выбора REMOTE не взаимодействует с другими параметрами. дополнение к местным. В частности, он не взаимодействует с RECURSIVEMATCH (см. ниже). Запрос (REMOTE RECURSIVEMATCH) недействителен, так как недействителен запрос (RECURSIVEMATCH). Запрос (REMOTE RECURSIVEMATCH SUBSCRIBED) запрашивает все подписанные почтовые ящики, как локальные, так и удаленные. |
| RecursiveMatch | `4` | RECURSIVEMATCH — этот параметр заставляет сервер возвращать информацию о родительских почтовых ящиках, которые не соответствуют другим параметрам выбора, но имеют некоторые подпочтовые ящики, которые соответствуют. Информация о детях возвращается в элементе расширенных данных CHILDINFO. Примечание 1: Чтобы родительский почтовый ящик был возвращен, он все равно должен соответствовать каноническому шаблону LIST. шаблон. Опция RECURSIVEMATCH НЕ ДОЛЖНА использоваться как единственная опция выбора (или только с REMOTE), так как она имеет смысл только тогда, когда также используются другие опции выбора. В таком случае сервер ДОЛЖЕН вернуть ответ с тегом BAD. Обратите внимание, что даже если указана опция RECURSIVEMATCH, клиент ДОЛЖЕН иметь возможность обрабатывать случай, когда возвращается элемент расширенных данных CHILDINFO и нет подпочтовых ящиков , соответствующих критериям выбора последующей команды LIST, , поскольку они могут быть удалены/переименованы после отправки ответа LIST, но до того, как клиент получил к ним доступ. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
