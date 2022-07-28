---
title: IAsyncPop3Client
second_title: Referencia de la API de Aspose.Email para .NET
description: Permite que las aplicaciones accedan y manipulen los mensajes mediante el Protocolo de oficina de correos versión 3 POP3.
type: docs
weight: 16850
url: /es/net/aspose.email.clients.pop3/iasyncpop3client/
---
## IAsyncPop3Client interface

Permite que las aplicaciones accedan y manipulen los mensajes mediante el Protocolo de oficina de correos versión 3 (POP3).

```csharp
public interface IAsyncPop3Client : IDisposable
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/iasyncpop3client/commitdeletesasync)(int, IConnection, CancellationToken) | Confirmar las eliminaciones |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync)(int, IConnection, CancellationToken) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessageasync#deletemessageasync_1)(string, IConnection, CancellationToken) | Borra el mensaje |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync)(IConnection, CancellationToken) | Borra todos los mensajes |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync)(int, IConnection, CancellationToken) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync#fetchmessageasync_1)(string, IConnection, CancellationToken) | Obtiene el mensaje |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync)(IEnumerable&lt;int&gt;, IConnection, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/fetchmessagesasync#fetchmessagesasync_1)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync)(bool, IConnection, CancellationToken) | Obtiene el estado del buzón info |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmailboxsizeasync)(IConnection, CancellationToken) | Obtiene el tamaño del buzón |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagecountasync)(bool, IConnection, CancellationToken) | Obtiene el mensaje count |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync)(int, IConnection, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageheadersasync#getmessageheadersasync_1)(string, IConnection, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync)(int, Pop3ListFields, IConnection, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync#getmessageinfoasync_1)(string, Pop3ListFields, IConnection, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync)(int, IConnection, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessagesizeasync#getmessagesizeasync_1)(string, IConnection, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync)(int, IConnection, CancellationToken) | Obtiene el mensaje id único |
| [ListMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/listmessagesasync)(Pop3ListFields, bool, MailQuery, IConnection, CancellationToken) | Lista los mensajes. |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/iasyncpop3client/loadmessageinfolistasync)(Pop3LoadMessageInfoList) | Carga la lista de Pop3MessageInfo |
| [NoopAsync](../../aspose.email.clients.pop3/iasyncpop3client/noopasync)(IConnection, CancellationToken) | Comando 'Sin operación' |
| [SaveMessageAsync](../../aspose.email.clients.pop3/iasyncpop3client/savemessageasync)(Pop3SaveMessage) | Obtiene y guarda el mensaje como flujo |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/iasyncpop3client/undeletemessagesasync)(IConnection, CancellationToken) | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/iasyncpop3client/validatecredentialsasync)(IConnection, CancellationToken) | Ejecuta validación de credenciales |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
