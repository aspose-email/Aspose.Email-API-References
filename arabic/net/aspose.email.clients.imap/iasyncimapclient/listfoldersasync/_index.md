---
title: ListFoldersAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: الحصول على قائمة المجلدات الفرعية في المجلد المحدد
type: docs
weight: 220
url: /ar/net/aspose.email.clients.imap/iasyncimapclient/listfoldersasync/
---
## IAsyncImapClient.ListFoldersAsync method

الحصول على قائمة المجلدات الفرعية في المجلد المحدد

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder = null, 
    bool loadFullInfo = false, ListFoldersOptions options = ListFoldersOptions.None, 
    ListFoldersReturnOptions returnOptions = ListFoldersReturnOptions.None, 
    IConnection connection = null, CancellationToken token = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| parentFolder | String | اسم المجلد |
| loadFullInfo | Boolean | إذا كانت القيمة true تشير إلى أنه يجب استرداد معلومات المجلد من الخادم تمامًا ، وإلا فسيتم استرداد أسماء المجلدات فقط. |
| options | ListFoldersOptions | خيارات للتشغيل |
| returnOptions | ListFoldersReturnOptions | خيارات العودة للعملية |
| connection | IConnection | الاتصال بالخادم |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->