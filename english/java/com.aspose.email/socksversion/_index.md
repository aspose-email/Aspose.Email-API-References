---
title: SocksVersion
second_title: Aspose.Email for Java API Reference
description:  Versions of the SOCKS protocol
type: docs
weight: 642
url: /java/com.aspose.email/socksversion/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SocksVersion extends System.Enum
```

Versions of the SOCKS protocol
## Fields

| Field | Description |
| --- | --- |
| [SocksV4](#SocksV4) | SOCKS4 and SOCKS4a version SOCKS4a extends the SOCKS4 protocol to allow a client to specify a destination domain name rather than an IPv4 address; this is useful when the client itself cannot resolve the destination host's domain name to an IP address. |
| [SocksV5](#SocksV5) | SOCKS5 version The SOCKS5 protocol is defined in RFC 1928. |
### SocksV4 {#SocksV4}
```
public static final byte SocksV4
```


SOCKS4 and SOCKS4a version SOCKS4a extends the SOCKS4 protocol to allow a client to specify a destination domain name rather than an IPv4 address; this is useful when the client itself cannot resolve the destination host's domain name to an IP address.

### SocksV5 {#SocksV5}
```
public static final byte SocksV5
```


SOCKS5 version The SOCKS5 protocol is defined in RFC 1928. It is an extension of the SOCKS4 protocol; it offers more choices for authentication, and adds support for IPv6 and UDP, the latter of which can be used for DNS lookups.

