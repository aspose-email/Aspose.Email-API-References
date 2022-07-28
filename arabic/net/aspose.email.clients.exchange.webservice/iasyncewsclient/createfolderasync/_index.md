---
title: CreateFolderAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: ينشئ المجلد الجديد
type: docs
weight: 100
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createfolderasync/
---
## IAsyncEwsClient.CreateFolderAsync method

ينشئ المجلد الجديد

```csharp
public Task<ExchangeFolderInfo> CreateFolderAsync(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions = null, string folderClass = null, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| parentFolderUri | String | URI للمجلد الأصل |
| name | String | اسم المجلد الجديد |
| permissions | ExchangeFolderPermissionCollection | إذن على مجلد جديد |
| folderClass | String | فئة المجلد الجديد |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

إرجاع معلومات المجلد

### أنظر أيضا

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->