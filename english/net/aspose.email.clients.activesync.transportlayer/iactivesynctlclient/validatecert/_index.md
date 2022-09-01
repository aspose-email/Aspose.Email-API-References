---
title: ValidateCert
second_title: Aspose.Email for .NET API Reference
description: The ValidateCert command is used by the client to validate a certificate that has been received via an S/MIME mail.
type: docs
weight: 250
url: /net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

The ValidateCert command is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate | Certificate that has to be validated. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate | Certificate that has to be validated. |
| checkCrl | Boolean | Specifies whether the server SHOULD ignore an unverifiable revocation status. The revocation status of a certificate cannot be verified when the certificate revocation lists (CRLs) cannot be retrieved. When the CheckCRL value is set to TRUE, the server MUST NOT ignore an unverifiable revocation status. When the CheckCRL value is set to FALSE, the server SHOULD ignore an unverifiable revocation status. The default value is FALSE. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate | Certificate that has to be validated. |
| certificateChains | IEnumerable`1 | List of certificates to be validated. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate | Certificate that has to be validated. |
| certificateChains | IEnumerable`1 | List of certificates that have to be validated. |
| checkCrl | Boolean | Specifies whether the server SHOULD ignore an unverifiable revocation status. The revocation status of a certificate cannot be verified when the certificate revocation lists (CRLs) cannot be retrieved. When the CheckCRL value is set to TRUE, the server MUST NOT ignore an unverifiable revocation status. When the CheckCRL value is set to FALSE, the server SHOULD ignore an unverifiable revocation status. The default value is FALSE. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeration of certificates that have to be validated. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeration of certificates that have to be validated. |
| checkCrl | Boolean | Specifies whether the server SHOULD ignore an unverifiable revocation status. The revocation status of a certificate cannot be verified when the certificate revocation lists (CRLs) cannot be retrieved. When the CheckCRL value is set to TRUE, the server MUST NOT ignore an unverifiable revocation status. When the CheckCRL value is set to FALSE, the server SHOULD ignore an unverifiable revocation status. The default value is FALSE. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeration of certificates that have to be validated. |
| certificateChains | IEnumerable`1 | Enumeration of certificates that have to be validated. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

The ValidateCert is used by the client to validate a certificate that has been received via an S/MIME mail.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeration of certificates that have to be validated. |
| certificateChains | IEnumerable`1 | Enumeration of certificates that have to be validated. |
| checkCrl | Boolean | Specifies whether the server SHOULD ignore an unverifiable revocation status. The revocation status of a certificate cannot be verified when the certificate revocation lists (CRLs) cannot be retrieved. When the CheckCRL value is set to TRUE, the server MUST NOT ignore an unverifiable revocation status. When the CheckCRL value is set to FALSE, the server SHOULD ignore an unverifiable revocation status. The default value is FALSE. |

### Return Value

List of validation certificate statuses

### See Also

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
