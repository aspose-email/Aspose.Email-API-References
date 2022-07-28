---
title: ValidateCert
second_title: Aspose.Email for .NET API 参考
description: ValidateCert 命令被客户端用来验证通过 S/MIME 邮件收到的证书
type: docs
weight: 250
url: /zh/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

ValidateCert 命令被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate | 必须验证的证书。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate | 必须验证的证书。 |
| checkCrl | Boolean | 指定服务器是否应该忽略无法验证的吊销状态。 当无法检索证书吊销列表 (CRL) 时，无法验证证书的吊销状态。 当 CheckCRL 值设置为 TRUE 时，服务器不得忽略无法验证的撤销状态。 当 CheckCRL 值设置为 FALSE 时，服务器应该忽略无法验证的撤销状态。 默认值为 FALSE。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate | 必须验证的证书。 |
| certificateChains | IEnumerable`1 | 要验证的证书列表。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate | 必须验证的证书。 |
| certificateChains | IEnumerable`1 | 必须验证的证书列表。 |
| checkCrl | Boolean | 指定服务器是否应该忽略无法验证的吊销状态。 当无法检索证书吊销列表 (CRL) 时，无法验证证书的吊销状态。 当 CheckCRL 值设置为 TRUE 时，服务器不得忽略无法验证的撤销状态。 当 CheckCRL 值设置为 FALSE 时，服务器应该忽略无法验证的撤销状态。 默认值为 FALSE。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificates | IEnumerable`1 | 必须验证的证书的枚举。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificates | IEnumerable`1 | 必须验证的证书的枚举。 |
| checkCrl | Boolean | 指定服务器是否应该忽略无法验证的吊销状态。 当无法检索证书吊销列表 (CRL) 时，无法验证证书的吊销状态。 当 CheckCRL 值设置为 TRUE 时，服务器不得忽略无法验证的撤销状态。 当 CheckCRL 值设置为 FALSE 时，服务器应该忽略无法验证的撤销状态。 默认值为 FALSE。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificates | IEnumerable`1 | 必须验证的证书的枚举。 |
| certificateChains | IEnumerable`1 | 必须验证的证书的枚举。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert 被客户端用来验证通过 S/MIME 邮件收到的证书。

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| certificates | IEnumerable`1 | 必须验证的证书的枚举。 |
| certificateChains | IEnumerable`1 | 必须验证的证书的枚举。 |
| checkCrl | Boolean | 指定服务器是否应该忽略无法验证的吊销状态。 当无法检索证书吊销列表 (CRL) 时，无法验证证书的吊销状态。 当 CheckCRL 值设置为 TRUE 时，服务器不得忽略无法验证的撤销状态。 当 CheckCRL 值设置为 FALSE 时，服务器应该忽略无法验证的撤销状态。 默认值为 FALSE。 |

### 返回值

验证证书状态列表

### 也可以看看

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
