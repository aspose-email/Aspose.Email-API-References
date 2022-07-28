---
title: ValidateCert
second_title: Aspose.Email für .NET-API-Referenz
description: Der Befehl ValidateCert wird vom Client verwendet um ein Zertifikat zu validieren das über eine S/MIME-Mail empfangen wurde.
type: docs
weight: 250
url: /de/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

Der Befehl ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate | Zertifikat, das validiert werden muss. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate | Zertifikat, das validiert werden muss. |
| checkCrl | Boolean | Gibt an, ob der Server einen nicht verifizierbaren Widerrufsstatus ignorieren SOLLTE. Der Widerrufsstatus eines Zertifikats kann nicht überprüft werden, wenn die Zertifikatssperrlisten (CRLs) nicht abgerufen werden können. Wenn der CheckCRL-Wert auf TRUE gesetzt ist, DARF der Server einen nicht überprüfbarer Widerrufsstatus. Wenn der CheckCRL-Wert auf FALSE gesetzt ist, SOLLTE der Server einen nicht verifizierbaren Sperrstatus ignorieren. Der Standardwert ist FALSE. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate | Zertifikat, das validiert werden muss. |
| certificateChains | IEnumerable`1 | Liste der zu validierenden Zertifikate. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate | Zertifikat, das validiert werden muss. |
| certificateChains | IEnumerable`1 | Liste der zu validierenden Zertifikate. |
| checkCrl | Boolean | Gibt an, ob der Server einen nicht verifizierbaren Widerrufsstatus ignorieren SOLLTE. Der Widerrufsstatus eines Zertifikats kann nicht überprüft werden, wenn die Zertifikatssperrlisten (CRLs) nicht abgerufen werden können. Wenn der CheckCRL-Wert auf TRUE gesetzt ist, DARF der Server einen nicht überprüfbarer Widerrufsstatus. Wenn der CheckCRL-Wert auf FALSE gesetzt ist, SOLLTE der Server einen nicht verifizierbaren Sperrstatus ignorieren. Der Standardwert ist FALSE. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificates | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificates | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |
| checkCrl | Boolean | Gibt an, ob der Server einen nicht verifizierbaren Widerrufsstatus ignorieren SOLLTE. Der Widerrufsstatus eines Zertifikats kann nicht überprüft werden, wenn die Zertifikatssperrlisten (CRLs) nicht abgerufen werden können. Wenn der CheckCRL-Wert auf TRUE gesetzt ist, DARF der Server einen nicht überprüfbarer Widerrufsstatus. Wenn der CheckCRL-Wert auf FALSE gesetzt ist, SOLLTE der Server einen nicht verifizierbaren Sperrstatus ignorieren. Der Standardwert ist FALSE. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificates | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |
| certificateChains | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

Das ValidateCert wird vom Client verwendet, um ein Zertifikat zu validieren, das über eine S/MIME-Mail empfangen wurde.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificates | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |
| certificateChains | IEnumerable`1 | Aufzählung der zu validierenden Zertifikate. |
| checkCrl | Boolean | Gibt an, ob der Server einen nicht verifizierbaren Widerrufsstatus ignorieren SOLLTE. Der Widerrufsstatus eines Zertifikats kann nicht überprüft werden, wenn die Zertifikatssperrlisten (CRLs) nicht abgerufen werden können. Wenn der CheckCRL-Wert auf TRUE gesetzt ist, DARF der Server einen nicht überprüfbarer Widerrufsstatus. Wenn der CheckCRL-Wert auf FALSE gesetzt ist, SOLLTE der Server einen nicht verifizierbaren Sperrstatus ignorieren. Der Standardwert ist FALSE. |

### Rückgabewert

Liste der Validierungszertifikatstatus

### Siehe auch

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
