---
title: API C# để xuất SVG sang DOTX
description: Chuyển đổi SVG sang DOTX mà không cần sử dụng Microsoft Word
url: /vi/net/conversion/svg-to-dotx/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOTX
otherformats: DOTM PS FLATOPC WORDML DOT MARKDOWN PCL XAMLFLOW MHTML ODT DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất SVG sang DOTX qua .NET" h2=".NET API để xuất SVG sang DOTX trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp SVG thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi SVG sang DOTX" %}}
1. Mở tệp SVG bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi SVG thành Doc bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Tài liệu](https://apireference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng DOTX bằng phương pháp [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Dotx thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotx", SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp SVG bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi SVG thành DOTX, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document) và mở SVG bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo ReadOnly DOTX- Tệp qua .NET" %}}
Để bảo vệ DOTX của bạn khỏi chỉnh sửa và ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn, bạn cũng có thể đặt bảo vệ tài liệu bằng cách sử dụng API. Bạn có thể giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động với nó. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Nó cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-ott/" name="SVG Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-mhtml/" name="SVG Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-wordml/" name="SVG Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-dot/" name="SVG Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-odt/" name="SVG Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-rtf/" name="SVG Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-ps/" name="SVG Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-flatopc/" name="SVG Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-pcl/" name="SVG Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-markdown/" name="SVG Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-xamlflow/" name="SVG Đến XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/svg-to-dotx/" name="SVG Đến DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}