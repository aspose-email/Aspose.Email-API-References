---
title: Class HeaderCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mime.HeaderCollection class. Defines the collection of header fields
type: docs
weight: 17940
url: /net/aspose.email.mime/headercollection/
---
## HeaderCollection class

Defines the collection of header fields

```csharp
public class HeaderCollection : ICollection<string>
```

## Constructors

| Name | Description |
| --- | --- |
| [HeaderCollection](headercollection/#constructor)() | Initializes a new instance of the `HeaderCollection` class. |
| [HeaderCollection](headercollection/#constructor_1)(HeaderCollection) | Initializes a new instance of the `HeaderCollection` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AllKeys](../../aspose.email.mime/headercollection/allkeys/) { get; } | Gets an array of strings containing all header keys in collections |
| virtual [Count](../../aspose.email.mime/headercollection/count/) { get; } | Gets a count of headers |
| [IsReadOnly](../../aspose.email.mime/headercollection/isreadonly/) { get; } | Is collection readonly |
| [Item](../../aspose.email.mime/headercollection/item/) { get; } | Gets a value from collection by the index. |
| [Item](../../aspose.email.mime/headercollection/item/) { get; set; } | Gets a value from collection by the name. |
| virtual [Keys](../../aspose.email.mime/headercollection/keys/) { get; } | Gets a ReadOnlyCollection containing all header keys in collections |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.mime/headercollection/add/#add)(HeaderCollection) | Adds a header to collection. |
| [Add](../../aspose.email.mime/headercollection/add/#add_1)(string) | Adds the header without value |
| [Add](../../aspose.email.mime/headercollection/add/#add_2)(string, string) | Adds the header. |
| virtual [Add_](../../aspose.email.mime/headercollection/add_/)(string, string) | Adds the header. |
| virtual [Clear](../../aspose.email.mime/headercollection/clear/)() | Clears all headers. |
| [Contains](../../aspose.email.mime/headercollection/contains/)(string) | Gets a value indicating whether the specified header is contained in the collection |
| [CopyTo](../../aspose.email.mime/headercollection/copyto/)(string[], int) | Copies all the elements of the current collection to the specified string array starting at the specified destination index. |
| virtual [Get](../../aspose.email.mime/headercollection/get/#get)(int) | Gets the value at the specified index. |
| [Get](../../aspose.email.mime/headercollection/get/#get_1)(string) | Gets the header value by a given header name. |
| [GetDecodedValue](../../aspose.email.mime/headercollection/getdecodedvalue/)(string) | Gets the header value. |
| [GetEnumerator](../../aspose.email.mime/headercollection/getenumerator/)() | Returns an enumerator that iterates through a collection. |
| virtual [GetKey](../../aspose.email.mime/headercollection/getkey/)(int) | Gets the key at the specified index of the collection. |
| [GetValues](../../aspose.email.mime/headercollection/getvalues/)(string) | Gets the header values. |
| [HasKeys](../../aspose.email.mime/headercollection/haskeys/)() | Gets a value indicating whether the collection contains keys. |
| [Insert](../../aspose.email.mime/headercollection/insert/)(string, string) | Inserts the header in collection. If collection contains headers with the same name this header will be inserted before other headers with the same name. |
| [Remove](../../aspose.email.mime/headercollection/remove/)(string) | Removes the header from collection by a given header name. |
| [Set](../../aspose.email.mime/headercollection/set/)(string, string) | Sets the header. |

### See Also

* namespace [Aspose.Email.Mime](../../aspose.email.mime/)
* assembly [Aspose.Email](../../)


