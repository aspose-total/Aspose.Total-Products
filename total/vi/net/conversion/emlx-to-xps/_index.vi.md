---
title: API C# để xuất EMLX sang XPS
description: Chuyển đổi EMLX thành XPS mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/emlx-to-xps/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: XPS
otherformats: TEXT OTT EMF WORDML GIF XPS TIFF DOCM DOCX DOT ODT DOTM DOTX PNG RTF FLATOPC EPUB DOC PS PCL PDF JPEG SVG MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMLX sang XPS qua .NET" h2=".NET API để hiển thị EMLX thành XPS trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMLX sang XPS bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMLX sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMLX thành XPS" %}}
1. Mở tệp EMLX bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMLX sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng XPS bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Xps làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMLX qua .NET" %}}
Trước khi chuyển đổi EMLX thành XPS, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng emlx, bạn có thể tải tài liệu EMLX, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra emlx của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu XPS qua .NET" %}}
Trong khi lưu tài liệu từ EMLX vào XPS, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMLX sang XPS theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu EMLX (Electronic Messaging Layer with Extensions) được sử dụng để lưu trữ thông tin rõ ràng, nên chúng là lựa chọn hoàn hảo để gửi email và trao đổi thông báo kinh doanh. Tuy nhiên, khi làm việc với dữ liệu hình ảnh, tài liệu XPS (XML Paper Specification) trở nên quan trọng để in ấn và chia sẻ nội dung hiển thị.

Chuyển đổi các file EMLX thành các định dạng XPS là cần thiết để khơi mở tiềm năng đầy đủ của khả năng chia sẻ và in ấn. Đây là cách bạn có thể:

**Ứng dụng:**

*   **Chia sẻ tài liệu**: Chuyển các file EMLX để chia sẻ tài liệu, báo cáo và biểu trình với đồng nghiệp và khách hàng, đảm bảo trao đổi chính xác và an toàn.
*   **Tối ưu in ấn**: Sử dụng XPS để tối ưu layout in, hình ảnh và thiết kế, đảm bảo chất lượng hình ảnh tốt hơn và kích thước file nhỏ hơn.
*   **Chỉnh sửa và nâng cao hình ảnh**: Chuyển các file EMLX để chỉnh sửa và cải thiện nội dung hình ảnh, bao gồm đồ họa, ảnh và minh họa.
*   **Integrate chữ ký số**: Sử dụng XPS để tích hợp chữ ký số, đảm bảo xác nhận an toàn và đáng tin cậy của tài liệu.
*   **Tiếp cận và bao gồm**: Chuyển các file EMLX để tạo các tài liệu tiếp cận và bao gồm, tuân thủ tiêu chuẩn truy cập web để dễ đọc hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}