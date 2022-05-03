---
title: API C# để xuất PCL sang DOTM
description: Chuyển đổi PCL sang DOTM mà không cần sử dụng Microsoft Word
url: /vi/net/conversion/pcl-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: DOTM
otherformats: RTF XAMLFLOW FLATOPC PS DOTM MARKDOWN WORDML DOTX ODT DOT MHTML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PCL sang DOTM qua .NET" h2=".NET API để xuất PCL sang DOTM trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PCL thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi PCL sang DOTM" %}}
1. Mở tệp PCL bằng lớp [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PCL thành Doc bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Document](https://apireference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng DOTM bằng phương pháp [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Dotm thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pcl");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotm", SaveFormat.Dotm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp PCL bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi PCL thành DOTM, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) và mở PCL bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.pcl", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo ReadOnly DOTM- Tệp qua .NET" %}}
Để bảo vệ DOTM của bạn khỏi chỉnh sửa và ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn, bạn cũng có thể đặt bảo vệ tài liệu bằng cách sử dụng API. Bạn có thể giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động với nó. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Nó cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-ott/" name="PCL Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-mhtml/" name="PCL Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-wordml/" name="PCL Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-dot/" name="PCL Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-odt/" name="PCL Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-rtf/" name="PCL Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-ps/" name="PCL Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-flatopc/" name="PCL Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-pcl/" name="PCL Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-markdown/" name="PCL Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-xamlflow/" name="PCL Đến XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pcl-to-dotx/" name="PCL Đến DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}