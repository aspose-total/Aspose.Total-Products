---
title: API C# để xuất EMAIL sang WORDML
description: Chuyển đổi EMAIL thành WORDML mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORDML
otherformats: MD TIFF OTT DOCM EMF DOTM PNG SVG DOT TEXT DOTX DOCX PDF DOC WORDML GIF FLATOPC EPUB ODT JPEG XPS RTF PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMAIL sang WORDML qua .NET" h2=".NET API để hiển thị EMAIL thành WORDML trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMAIL sang WORDML bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMAIL sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMAIL thành WORDML" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMAIL qua .NET" %}}
Trước khi chuyển đổi EMAIL thành WORDML, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng email, bạn có thể tải tài liệu EMAIL, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra email của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu WORDML qua .NET" %}}
Trong khi lưu tài liệu từ EMAIL vào WORDML, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMAIL sang WORDML theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu email được sử dụng để lưu trữ thông tin giao tiếp dựa trên văn bản, khiến chúng trở nên lý tưởng để gửi thông điệp cho người nhận. Tuy nhiên, khi làm việc với dữ liệu trình diễn (như các presentation), tệp WordML (Word Markup Language) trở nên quan trọng để tạo các tài liệu và presentation chuyên nghiệp.

Chuyển đổi từ tài liệu email sang các định dạng WordML là cần thiết để khai thác đầy đủ khả năng trong việc tạo tài liệu và设计 presentation. Chuyển đổi này cho phép bạn:

**Khoảng cách:**

*   **Giao tiếp kinh doanh**: Chuyển tệp email thành các báo cáo kinh doanh正式, đề xuất và phút họp.
*   **Thiết kế presentation**: Sử dụng WordML để thiết kế presentations吸引人, thêm các phần tử multimedia và đặc tính tương tác.
*   **Mẫu tài liệu**: Chuyển tệp email thành các mẫu tài liệu có thể tái sử dụng cho các tài liệu thường dùng, như hợp đồng và chính sách.
*   **Hợp tác nghiên cứu**: Sử dụng WordML để chia sẻ kết quả nghiên cứu, hợp tác với đồng nghiệp và theo dõi tiến trình.
*   **Tạo nội dung marketing**: Chuyển tệp email thành các vật phẩm quảng cáo, post social media và bài viết blog.

Bằng cách chuyển đổi các email của bạn sang định dạng WordML, bạn có thể mở rộng khả năng trong việc tạo tài liệu, thiết kế presentation và hợp tác.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}