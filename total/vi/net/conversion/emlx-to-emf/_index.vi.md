---
title: API C# để xuất EMLX sang EMF
description: Chuyển đổi EMLX thành EMF mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/emlx-to-emf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EMF
otherformats: PS PNG XPS OTT DOC DOCM MD TIFF DOT DOCX TEXT JPEG DOTX PDF RTF GIF FLATOPC EMF WORDML ODT DOTM SVG PCL EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMLX sang EMF qua .NET" h2=".NET API để hiển thị EMLX thành EMF trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMLX sang EMF bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMLX sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMLX thành EMF" %}}
1. Mở tệp EMLX bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMLX sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng EMF bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Emf làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMLX qua .NET" %}}
Trước khi chuyển đổi EMLX thành EMF, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng emlx, bạn có thể tải tài liệu EMLX, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra emlx của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu EMF qua .NET" %}}
Trong khi lưu tài liệu từ EMLX vào EMF, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMLX sang EMF theo chương trình: Các trường hợp sử dụng" %}}
Tập tin EMF (Enhanced Metafile) được sử dụng để lưu thông tin về hình ảnh raster, khiến chúng trở nên lý tưởng để tạo các hình ảnh tĩnh và minh họa. Tuy nhiên, khi làm việc với dữ liệu động, bảng tính như Excel trở nên quan trọng để hiển thị dữ liệu và phân tích.

Chuyển đổi tập tin EMF thành các định dạng Excel là cần thiết để unlock được đầy đủ khả năng hiển thị và phân tích dữ liệu của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Chỉnh sửa hình ảnh**: Chuyển các file EMF để chỉnh sửa hình ảnh, thêm text và hình dạng, cũng như điều khiển giá trị pixel.
*   **Thiết kế giao diện người dùng (GUI)**: Sử dụng Excel để thiết kế và tạo các phần tử giao diện người dùng tương tác, như nút bấm, menu và biểu đồ.
*   **Khai thác kỹ thuật vẽ kỹ thuật**: Chuyển các file EMF để tạo các vẽ kỹ thuật chi tiết, blueprints và tài liệu dự án.
*   **Minh họa khoa học**: Sử dụng Excel để tạo các minh họa từ dữ liệu khoa học, như biểu đồ, biểu đồ và hình ảnh.
*   **Sinh艺术 và đồ họa**: Chuyển các file EMF để tạo các tác phẩm nghệ thuật số, đồ họa và thiết kế bằng kỹ thuật điều khiển pixel.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}