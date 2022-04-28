---
title: API C# để xuất OFT sang PCL
description: Chuyển đổi OFT thành PCL mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url: /vi/net/conversion/oft-to-pcl/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PCL
otherformats: FLATOPC ODT PDF RTF TIFF WORDML PNG DOT MD JPEG GIF DOCX EMF PCL DOTX PS DOC SVG EPUB XPS DOCM OTT DOTM TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất OFT sang PCL qua .NET" h2=".NET API để hiển thị OFT thành PCL trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi OFT sang PCL bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Cells for .NET](https://products.aspose.com/oft/net/), bạn có thể chuyển đổi định dạng tệp OFT sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi OFT thành PCL" %}}
1. Mở tệp OFT bằng lớp [MailMessage](https://apireference.aspose.com/oft/net/aspose.oft/mailmessage)
2. Chuyển đổi OFT sang HTML bằng phương pháp [Save](https://apireference.aspose.com/oft/net/aspose.oft.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng PCL bằng phương pháp [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Pcl làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.oft");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp OFT qua .NET" %}}
Trước khi chuyển đổi OFT thành PCL, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng oft, bạn có thể tải tài liệu OFT, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage) của [Aspose.Cells for .NET](https://products.aspose.com/oft/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra oft của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu PCL qua .NET" %}}
Trong khi lưu tài liệu từ OFT vào PCL, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://apireference.aspose. com/words/net/ aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-pcl/" name="Bột ngọt VÀO PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-pdf/" name="MSG TO PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dot/" name="Bột ngọt" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-flatopc/" name="Bột ngọt TO FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-jpeg/" name="Bột ngọt thành JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-png/" name="Bột ngọt TO PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-rtf/" name="Bột ngọt ĐẾN RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-tiff/" name="Bột ngọt TO TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-docm/" name="Bột ngọt TO DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-ps/" name="Bột ngọt để PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-gif/" name="Bột ngọt ĐẾN GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-xps/" name="Bột ngọt ĐẾN XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-odt/" name="MSG TO ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-docx/" name="MSG TO DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-doc/" name="MSG TO DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-wordml/" name="MSG TO WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-svg/" name="MSG TO SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-epub/" name="MSG TO EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-md/" name="MSG TO MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-emf/" name="Bột ngọt ĐẾN EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dotm/" name="Bột ngọt" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-ott/" name="MSG TO OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-dotx/" name="Bột ngọt ĐỂ DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/msg-to-text/" name="Bột ngọt VÀO VĂN BẢN" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}