---
title: MaxPictures
second_title: Aspose.Email for .NET API 参考
description: 限制服务器响应中返回的联系人照片数量 协议版本为 12.1 或 14.0 时不支持 MaxPictures 服务器返回前 N 个有联系人照片的结果其中 N 是 MaxPictures 的值 达到MaxPictures限制后如果联系人没有照片服务器返回状态值173NoPicture如果联系人的照片太大服务器返回状态值174PictureTooLarge如果联系人有照片服务器返回状态值175PictureLimitReached照片但已达到 MaxPictures 限制 请注意MaxPictures 标识每个查询返回的联系人照片数量 因此如果客户端包含三个要解析的收件人并在 ResolveRecipients 命令请求中将 MaxPictures 值设置为 3则最多可以返回 9 个联系人照片
type: docs
weight: 20
url: /zh/net/aspose.email.clients.activesync.transportlayer/picturerequest/maxpictures/
---
## PictureRequest.MaxPictures property

限制服务器响应中返回的联系人照片数量。 协议版本为 12.1 或 14.0 时不支持 MaxPictures。 服务器返回前 N 个有联系人照片的结果，其中 N 是 MaxPictures 的值。 达到MaxPictures限制后，如果联系人没有照片，服务器返回状态值173（NoPicture），如果联系人的照片太大，服务器返回状态值174（PictureTooLarge），如果联系人有照片，服务器返回状态值175（PictureLimitReached）照片但已达到 MaxPictures 限制。 请注意，MaxPictures 标识每个查询返回的联系人照片数量。 因此，如果客户端包含三个要解析的收件人，并在 ResolveRecipients 命令请求中将 MaxPictures 值设置为 3，则最多可以返回 9 个联系人照片。

```csharp
public int? MaxPictures { get; set; }
```

### 也可以看看

* class [PictureRequest](../../picturerequest)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../picturerequest)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
