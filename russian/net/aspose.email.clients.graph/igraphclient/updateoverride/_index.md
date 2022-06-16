---
title: UpdateOverride
second_title: Справочник по Aspose.Email для .NET API
description: Измените поле classifyAs переопределения как указано. Этот метод нельзя использовать для изменения каких-либо других полей в экземпляре ClassificationOverride. Если для отправителя существует переопределение и отправитель меняет свое отображаемое имя вы можете использовать CreateOrUpdateOverride чтобы принудительно обновить поле имени в существующем переопределении. Если для отправителя существует переопределение и отправитель меняет свой SMTP-адрес удаление существующего переопределения и создание нового с новым SMTP-адресом является единственным способом обновить переопределение для этого отправителя. Разрешения Для вызова этого API требуется одно из следующих разрешений. Чтобы узнать больше в том числе о том как выбрать разрешения см. Разрешения. Делегировано рабочая или учебная учетная запись Mail.ReadWrite Делегировано личная учетная запись Microsoft Mail.ReadWrite Application Mail.ReadWrite
type: docs
weight: 410
url: /ru/net/aspose.email.clients.graph/igraphclient/updateoverride/
---
## IGraphClient.UpdateOverride method

Измените поле classifyAs переопределения, как указано. Этот метод нельзя использовать для изменения каких-либо других полей в экземпляре ClassificationOverride. Если для отправителя существует переопределение, и отправитель меняет свое отображаемое имя, вы можете использовать CreateOrUpdateOverride, чтобы принудительно обновить поле имени в существующем переопределении. Если для отправителя существует переопределение, и отправитель меняет свой SMTP-адрес, удаление существующего переопределения и создание нового с новым SMTP-адресом является единственным способом «обновить» переопределение для этого отправителя. Разрешения: Для вызова этого API требуется одно из следующих разрешений. Чтобы узнать больше, в том числе о том, как выбрать разрешения, см. Разрешения. Делегировано (рабочая или учебная учетная запись) Mail.ReadWrite Делегировано (личная учетная запись Microsoft) Mail.ReadWrite Application Mail.ReadWrite

```csharp
public ClassificationOverride UpdateOverride(ClassificationOverride classificationOverride)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classificationOverride | ClassificationOverride | Переопределение классификации для обновления |

### Смотрите также

* class [ClassificationOverride](../../classificationoverride)
* interface [IGraphClient](../../igraphclient)
* пространство имен [Aspose.Email.Clients.Graph](../../igraphclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->