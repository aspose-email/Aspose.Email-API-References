---
title: ValidateCert
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يتم استخدام الأمر ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.
type: docs
weight: 250
url: /ar/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert/
---
## ValidateCert(X509Certificate) {#validatecert_4}

يتم استخدام الأمر ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificate | X509Certificate | الشهادة التي يجب التحقق من صحتها. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, bool) {#validatecert_5}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, bool checkCrl)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificate | X509Certificate | الشهادة التي يجب التحقق من صحتها. |
| checkCrl | Boolean | يحدد ما إذا كان يجب على الخادم أن يتجاهل حالة إبطال غير قابلة للتحقق. لا يمكن التحقق من حالة إبطال الشهادة عندما يتعذر استرداد قوائم إبطال الشهادات (CRLs) . عند تعيين قيمة CheckCRL على TRUE ، يجب ألا يتجاهل الخادم حالة إبطال لا يمكن التحقق منها. عند تعيين قيمة CheckCRL على FALSE ، يجب أن يتجاهل الخادم حالة الإبطال التي لا يمكن التحقق منها. القيمة الافتراضية هي FALSE. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;) {#validatecert_6}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificate | X509Certificate | الشهادة التي يجب التحقق من صحتها. |
| certificateChains | IEnumerable`1 | قائمة الشهادات التي سيتم التحقق من صحتها. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_7}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(X509Certificate certificate, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificate | X509Certificate | الشهادة التي يجب التحقق من صحتها. |
| certificateChains | IEnumerable`1 | قائمة الشهادات التي يجب التحقق من صحتها. |
| checkCrl | Boolean | يحدد ما إذا كان يجب على الخادم أن يتجاهل حالة إبطال غير قابلة للتحقق. لا يمكن التحقق من حالة إبطال الشهادة عندما يتعذر استرداد قوائم إبطال الشهادات (CRLs) . عند تعيين قيمة CheckCRL على TRUE ، يجب ألا يتجاهل الخادم حالة إبطال لا يمكن التحقق منها. عند تعيين قيمة CheckCRL على FALSE ، يجب أن يتجاهل الخادم حالة الإبطال التي لا يمكن التحقق منها. القيمة الافتراضية هي FALSE. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;) {#validatecert}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificates | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_1}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    bool checkCrl)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificates | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |
| checkCrl | Boolean | يحدد ما إذا كان يجب على الخادم أن يتجاهل حالة إبطال غير قابلة للتحقق. لا يمكن التحقق من حالة إبطال الشهادة عندما يتعذر استرداد قوائم إبطال الشهادات (CRLs) . عند تعيين قيمة CheckCRL على TRUE ، يجب ألا يتجاهل الخادم حالة إبطال لا يمكن التحقق منها. عند تعيين قيمة CheckCRL على FALSE ، يجب أن يتجاهل الخادم حالة الإبطال التي لا يمكن التحقق منها. القيمة الافتراضية هي FALSE. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) {#validatecert_2}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificates | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |
| certificateChains | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

---

## ValidateCert(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) {#validatecert_3}

يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME.

```csharp
public List<CertificateStatuses> ValidateCert(IEnumerable<X509Certificate> certificates, 
    IEnumerable<X509Certificate> certificateChains, bool checkCrl)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| certificates | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |
| certificateChains | IEnumerable`1 | تعداد الشهادات التي يجب التحقق من صحتها. |
| checkCrl | Boolean | يحدد ما إذا كان يجب على الخادم أن يتجاهل حالة إبطال غير قابلة للتحقق. لا يمكن التحقق من حالة إبطال الشهادة عندما يتعذر استرداد قوائم إبطال الشهادات (CRLs) . عند تعيين قيمة CheckCRL على TRUE ، يجب ألا يتجاهل الخادم حالة إبطال لا يمكن التحقق منها. عند تعيين قيمة CheckCRL على FALSE ، يجب أن يتجاهل الخادم حالة الإبطال التي لا يمكن التحقق منها. القيمة الافتراضية هي FALSE. |

### قيمة الإرجاع

قائمة بحالات شهادة التحقق من الصحة

### أنظر أيضا

* class [CertificateStatuses](../../certificatestatuses)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
