---
title: API C# để xuất EML sang DOCX
description: Chuyển đổi EML thành DOCX mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/eml-to-docx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: PCL PDF TEXT RTF DOTM DOCM DOT MD DOTX TIFF DOCX FLATOPC WORDML EMF XPS PS EPUB OTT GIF ODT PNG JPEG DOC SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EML sang DOCX qua .NET" h2=".NET API để hiển thị EML thành DOCX trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EML sang DOCX bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EML sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành DOCX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EML thành DOCX" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng DOCX bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Docx làm SaveFormat
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
Trước khi chuyển đổi EML thành DOCX, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng eml, bạn có thể tải tài liệu EML, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra eml của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu DOCX qua .NET" %}}
Trong khi lưu tài liệu từ EML vào DOCX, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EML sang DOCX theo chương trình: Các trường hợp sử dụng" %}}
Tệ tin EML (Electronic Mail) được sử dụng để lưu trữ thông điệp dạng văn bản, nên chúng là lựa chọn hoàn hảo để gửi và nhận email. Tuy nhiên, khi làm việc với các tài liệu cần có định dạng và trình bày, tệp .docx của Microsoft Word thường được ưa dùng hơn.

Chuyển đổi các file EML thành các định dạng .docx là cần thiết để khai thác đầy đủ khả năng chỉnh sửa tài liệu của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Giao thông tin trong lĩnh vực kinh doanh**: Chuyển các file EML thành các tài liệu có vẻ chuyên nghiệp, như ghi chú họpmeeting notes, cập nhật dự ánproject updates, và đề xuất kinh doanhbusiness proposals.
*   ** Correspondence cá nhân**: Sử dụng Word để định dạng và chỉnh sửa email, thư từ, và thông điệp cá nhân, đảm bảo tone văn bản được làm sạch và dễ đọc.
*   **Ghi chú họp và biên bản**: Chuyển các file EML thành các ghi chú họp và biên bản chi tiết, giúp việc giữ hộ và theo dõi hành động chính xác hơn.
*   **Viết đề xuất và hợp đồng**: Sử dụng Word để soạn thảo và chỉnh sửa đề xuất, hợp đồng, và thỏa thuận, đảm bảo rõ ràng, ngắn gọn, và chuyên nghiệp.
*   **Việc nghiên cứu và viết学术**: Chuyển các file EML thành các bài论文, bài báo, và luận văn, giúp việc chỉnh sửa và合作 dễ dàng hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}