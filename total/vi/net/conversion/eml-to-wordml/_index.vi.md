---
title: API C# để xuất EML sang WORDML
description: Chuyển đổi EML thành WORDML mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORDML
otherformats: FLATOPC ODT RTF DOT WORDML DOTX PCL TIFF XPS SVG JPEG MD DOCM OTT DOC DOTM PNG DOCX EPUB EMF TEXT PS PDF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EML sang WORDML qua .NET" h2=".NET API để hiển thị EML thành WORDML trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EML sang WORDML bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EML sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EML thành WORDML" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng WORDML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Wordml làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EML qua .NET" %}}
Trước khi chuyển đổi EML thành WORDML, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng eml, bạn có thể tải tài liệu EML, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra eml của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu WORDML qua .NET" %}}
Trong khi lưu tài liệu từ EML vào WORDML, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EML sang WORDML theo chương trình: Các trường hợp sử dụng" %}}
Tập tin EML (Electronic Mail) được sử dụng để lưu trữ thông điệp văn bản nhạt, khiến chúng trở nên lý tưởng cho việc giao tiếp email đơn giản. Tuy nhiên, khi làm việc với dữ liệu dựa trên tài liệu, ngôn ngữ markup WordML trở nên quan trọng để định dạng và tô màu.

Chuyển đổi các file EML thành các format WordML là cần thiết để khai thác được đầy đủ khả năng biên soạn và phát hành tài liệu của bạn. Chuyển đổi này cho phép bạn:

**Những用途:**

*   **Biên soạn và Phát hành Tài liệu**: Chuyển các file EML sang để biên soạn và phát hành tài liệu, đảm bảo tính nhất quán trong định dạng và phong cách.
*   **Mẫu email và CV**: Sử dụng WordML để tạo các mẫu email chuyên nghiệp và CV, thể hiện kỹ năng và kinh nghiệm của bạn.
*   **Tạo báo cáo và Phát hành**: Chuyển các file EML sang để tạo báo cáo và ấn phẩm, bao gồm các bài viết, báo cáo trắng và nhiều hơn nữa.
*   **Vật liệu Marketing**: Sử dụng WordML để tạo các vật liệu marketing như brochure, flyer và nội dung social media.
*   **Viết học thuật và Nghiên cứu**: Chuyển các file EML sang để định dạng các bài论文, luận văn và luận술, đảm bảo việc dẫn nguồn đúng và chú thích chính xác.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}