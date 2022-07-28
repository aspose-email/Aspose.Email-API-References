---
title: SearchResult
second_title: Aspose.Email für .NET-API-Referenz
description: Container für ein einzelnes übereinstimmendes Postfachelement. Wenn der durchsuchte Speicher das Postfach ist  Es gibt ein Ergebniselement für jede Übereinstimmung die im Postfach gefunden wird. Wenn keine Übereinstimmungen gefunden werden ist ein leeres Ergebniselement im Store-Containerelement der Antwort-XML vorhanden. - Im Ergebniselement enthält das Properties-Element eine Liste der angeforderten Eigenschaften für das Postfachelement. Wenn der Store das ist Durchsucht wird die Dokumentbibliothek  Das erste Ergebnis das in der Suchantwort zurückgegeben wird sind die Metadaten für den Stammordner oder das Element auf das der LinkId-Wert zeigt. Der Client kann diesen Eintrag ignorieren wenn er nicht erforderlich ist. - Wenn der documentlibraryLinkId-Elementwert in der Anforderung auf einen Ordner verweist werden die Metadateneigenschaften des Ordners als erstes Element und der Inhalt zurückgegeben der Ordner werden als nachfolgende Ergebnisse zurückgegeben. Der Bereich gilt für diese Ergebnisse ohne Unterschied Beispielsweise würde der Index 0 immer für das Stammelement stehen auf das der Link zeigt. - Wenn der documentlibraryLinkId-Elementwert in der Anfrage auf ein Element zeigt wird nur ein Ergebnis zurückgegeben die Metadaten für das Element. - Innerhalb des Elements Result enthält das Element Properties eine Liste der angeforderten Eigenschaften für das Postfachelement.
type: docs
weight: 2010
url: /de/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

Container für ein einzelnes übereinstimmendes Postfachelement. Wenn der durchsuchte Speicher das Postfach ist: – Es gibt ein Ergebniselement für jede Übereinstimmung, die im Postfach gefunden wird. Wenn keine Übereinstimmungen gefunden werden, ist ein leeres Ergebniselement im Store-Containerelement der Antwort-XML vorhanden. - Im Ergebniselement enthält das Properties-Element eine Liste der angeforderten Eigenschaften für das Postfachelement. Wenn der Store das ist Durchsucht wird die Dokumentbibliothek: – Das erste Ergebnis, das in der Suchantwort zurückgegeben wird, sind die Metadaten für den Stammordner oder das Element, auf das der LinkId-Wert zeigt. Der Client kann diesen Eintrag ignorieren, wenn er nicht erforderlich ist. - Wenn der documentlibrary:LinkId-Elementwert in der Anforderung auf einen Ordner verweist, werden die Metadateneigenschaften des Ordners als erstes Element und der Inhalt zurückgegeben der Ordner werden als nachfolgende Ergebnisse zurückgegeben. Der Bereich gilt für diese Ergebnisse ohne Unterschied; Beispielsweise würde der Index 0 immer für das Stammelement stehen, auf das der Link zeigt. - Wenn der documentlibrary:LinkId-Elementwert in der Anfrage auf ein Element zeigt, wird nur ein Ergebnis zurückgegeben: die Metadaten für das Element. - Innerhalb des Elements „Result“ enthält das Element „Properties“ eine Liste der angeforderten Eigenschaften für das Postfachelement.

```csharp
public class SearchResult
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SearchResult](searchresult)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | Identifiziert die Klasse des Artikels. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | Gibt die Ordner an, in denen das Element gefunden wurde. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | Gibt eine eindeutige Kennung an, die vom Server jedem zurückgegebenen Ergebnissatz zugewiesen wird. Der Wert der LongId kann als lange ID verwendet werden, die in der ItemOperations-Befehlsanforderung, der SmartReply-Befehlsanforderung, der SmartForward-Befehlsanforderung oder angegeben ist die MeetingResponse-Befehlsanforderung, auf die Ergebnismenge zu verweisen. Der Client MUSS den Wert von LongId als undurchsichtige Zeichenfolge mit bis zu 256 Zeichen speichern. |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | Die Antworteigenschaften des Suchbefehls sind ein Container für Eigenschaften, die für einen einzelnen Eintrag gelten, der mit der Suchzeichenfolge des Abfrageelements übereinstimmt. Beispielsweise enthält das Element Properties ein Element für jede nicht leere GAL-Eigenschaft mit Textwert, die dem übereinstimmenden GAL-Eintrag zugeordnet ist. Nur die Eigenschaften, die dem bestimmten GAL-Eintrag zugeordnet sind, werden zurückgegeben; Daher können im Antwort-XML für verschiedene übereinstimmende GAL-Einträge unterschiedliche Eigenschaftensätze zurückgegeben werden. Jedes Element im Eigenschaftencontainer ist auf den entsprechenden Namespace beschränkt, der im Suchelement der obersten Ebene angegeben ist. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
