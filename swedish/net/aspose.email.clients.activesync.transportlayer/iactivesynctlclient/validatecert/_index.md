---
title: ValidateCert
second_title: Aspose.Email för .NET API-referens
description: Kommandot ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.
type: docs
weight: 250
url: /sv/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

Kommandot ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate | Certifikat som måste valideras. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate | Certifikat som måste valideras. |
| checkCrl | Boolean | Anger om servern SKA ignorera en ej verifierbar återkallelsestatus. Återkallelsestatusen för ett certifikat kan inte verifieras när listorna för återkallelse av certifikat (CRLs) inte kan hämtas. När CheckCRL-värdet är satt till TRUE, FÅR servern INTE ignorera en ej verifierbar återkallelsestatus. När CheckCRL-värdet är inställt på FALSE BÖR servern ignorera en ej verifierbar återkallelsestatus. Standardvärdet är FALSE. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate | Certifikat som måste valideras. |
| certificateChains | IEnumerable`1 | Lista över certifikat som ska valideras. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | X509Certificate | Certifikat som måste valideras. |
| certificateChains | IEnumerable`1 | Lista över certifikat som måste valideras. |
| checkCrl | Boolean | Anger om servern SKA ignorera en ej verifierbar återkallelsestatus. Återkallelsestatusen för ett certifikat kan inte verifieras när listorna för återkallelse av certifikat (CRLs) inte kan hämtas. När CheckCRL-värdet är satt till TRUE, FÅR servern INTE ignorera en ej verifierbar återkallelsestatus. När CheckCRL-värdet är inställt på FALSE BÖR servern ignorera en ej verifierbar återkallelsestatus. Standardvärdet är FALSE. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificates | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificates | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |
| checkCrl | Boolean | Anger om servern SKA ignorera en ej verifierbar återkallelsestatus. Återkallelsestatusen för ett certifikat kan inte verifieras när listorna för återkallelse av certifikat (CRLs) inte kan hämtas. När CheckCRL-värdet är satt till TRUE, FÅR servern INTE ignorera en ej verifierbar återkallelsestatus. När CheckCRL-värdet är inställt på FALSE BÖR servern ignorera en ej verifierbar återkallelsestatus. Standardvärdet är FALSE. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificates | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |
| certificateChains | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert används av klienten för att validera ett certifikat som har tagits emot via en S/MIME-post.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificates | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |
| certificateChains | IEnumerable`1 | Uppräkning av certifikat som måste valideras. |
| checkCrl | Boolean | Anger om servern SKA ignorera en ej verifierbar återkallelsestatus. Återkallelsestatusen för ett certifikat kan inte verifieras när listorna för återkallelse av certifikat (CRLs) inte kan hämtas. När CheckCRL-värdet är satt till TRUE, FÅR servern INTE ignorera en ej verifierbar återkallelsestatus. När CheckCRL-värdet är inställt på FALSE BÖR servern ignorera en ej verifierbar återkallelsestatus. Standardvärdet är FALSE. |

### Returvärde

Lista över status för valideringscertifikat

### Se även

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
