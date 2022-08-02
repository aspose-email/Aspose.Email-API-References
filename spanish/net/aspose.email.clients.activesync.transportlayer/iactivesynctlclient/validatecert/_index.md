---
title: ValidateCert
second_title: Referencia de la API de Aspose.Email para .NET
description: El cliente utiliza el comando ValidateCert para validar un certificado que se ha recibido a través de un correo S/MIME.
type: docs
weight: 250
url: /es/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

El cliente utiliza el comando ValidateCert para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate | Certificado que tiene que ser validado. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate | Certificado que tiene que ser validado. |
| checkCrl | Boolean | Especifica si el servidor DEBE ignorar un estado de revocación no verificable. El estado de revocación de un certificado no se puede verificar cuando las listas de revocación de certificados (CRL) no se pueden recuperar. Cuando el valor CheckCRL se establece en VERDADERO, el servidor NO DEBE ignorar un estado de revocación no verificable. Cuando el valor CheckCRL se establece en FALSO, el servidor DEBE ignorar un estado de revocación no verificable. El valor por defecto es FALSO. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate | Certificado que tiene que ser validado. |
| certificateChains | IEnumerable`1 | Lista de certificados a validar. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificate | X509Certificate | Certificado que tiene que ser validado. |
| certificateChains | IEnumerable`1 | Lista de certificados que tienen que ser validados. |
| checkCrl | Boolean | Especifica si el servidor DEBE ignorar un estado de revocación no verificable. El estado de revocación de un certificado no se puede verificar cuando las listas de revocación de certificados (CRL) no se pueden recuperar. Cuando el valor CheckCRL se establece en VERDADERO, el servidor NO DEBE ignorar un estado de revocación no verificable. Cuando el valor CheckCRL se establece en FALSO, el servidor DEBE ignorar un estado de revocación no verificable. El valor por defecto es FALSO. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |
| checkCrl | Boolean | Especifica si el servidor DEBE ignorar un estado de revocación no verificable. El estado de revocación de un certificado no se puede verificar cuando las listas de revocación de certificados (CRL) no se pueden recuperar. Cuando el valor CheckCRL se establece en VERDADERO, el servidor NO DEBE ignorar un estado de revocación no verificable. Cuando el valor CheckCRL se establece en FALSO, el servidor DEBE ignorar un estado de revocación no verificable. El valor por defecto es FALSO. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |
| certificateChains | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

ValidateCert lo utiliza el cliente para validar un certificado que se ha recibido a través de un correo S/MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| certificates | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |
| certificateChains | IEnumerable`1 | Enumeración de certificados que tienen que ser validados. |
| checkCrl | Boolean | Especifica si el servidor DEBE ignorar un estado de revocación no verificable. El estado de revocación de un certificado no se puede verificar cuando las listas de revocación de certificados (CRL) no se pueden recuperar. Cuando el valor CheckCRL se establece en VERDADERO, el servidor NO DEBE ignorar un estado de revocación no verificable. Cuando el valor CheckCRL se establece en FALSO, el servidor DEBE ignorar un estado de revocación no verificable. El valor por defecto es FALSO. |

### Valor_devuelto

Lista de estados de certificados de validación

### Ver también

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
