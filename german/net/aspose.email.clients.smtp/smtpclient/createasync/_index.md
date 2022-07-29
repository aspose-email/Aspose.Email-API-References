---
title: CreateAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt eine neue Instanz vonSmtpClientaspose.email.clients.smtp/smtpclient Klasse
type: docs
weight: 220
url: /de/net/aspose.email.clients.smtp/smtpclient/createasync/
---
## SmtpClient.CreateAsync method

Erstellt eine neue Instanz von[`SmtpClient`](../../smtpclient) Klasse

```csharp
public static Task<IAsyncSmtpClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 25, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | String | Der Hostname |
| port | String | Die Portnummer |
| username | IAsyncTokenProvider | Der Nutzername |
| asyncTokenProvider | Int32 | Der Zugriffstokenanbieter. |
| securityOptions | SecurityOptions | Sicherheitsmodus für einen E-Mail-Client |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Siehe auch

* interface [IAsyncSmtpClient](../../iasyncsmtpclient)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [SmtpClient](../../smtpclient)
* namensraum [Aspose.Email.Clients.Smtp](../../smtpclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->