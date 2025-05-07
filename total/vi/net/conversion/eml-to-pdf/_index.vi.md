---
title: API C# để xuất EML sang PDF
description: Chuyển đổi EML thành PDF mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOCX DOC SVG FLATOPC WORDML MD PNG TIFF DOTM DOT XPS TEXT EPUB DOCM JPEG GIF PS DOTX RTF PDF OTT EMF ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EML sang PDF qua .NET" h2=".NET API để hiển thị EML thành PDF trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EML sang PDF bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EML sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EML thành PDF" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng PDF bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Pdf làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EML qua .NET" %}}
Trước khi chuyển đổi EML thành PDF, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng eml, bạn có thể tải tài liệu EML, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra eml của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu PDF qua .NET" %}}
Trong khi lưu tài liệu từ EML vào PDF, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EML sang PDF theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu Email (EML) được sử dụng để lưu trữ thông tin nhắn điện tử, nên chúng là lựa chọn hoàn hảo để gửi và nhận thư điện tử. Tuy nhiên, khi cần đến các tài liệu trình bày chuyên nghiệp, PDFs trở thành công cụ không thể thiếu cho in ấn theo yêu cầu, chữ ký điện tử và lưu trữ kỹ thuật số.

Chuyển đổi từ dạng EML sang PDF là việc 必要 để khai thác đầy đủ khả năng của các tài liệu in và khả năng truy cập. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Tài liệu chuyên nghiệp**: Chuyển EML thành PDF để tạo các tài liệu trình bày chuyên nghiệp như đề xuất, hợp đồng và bài trình bày.
*   **Chữ ký điện tử và Lưu trữ kỹ thuật số**: Sử dụng PDF để thực hiện chữ ký điện tử an toàn và lưu trữ các tài liệu nhạy cảm, đảm bảo tuân thủ yêu cầu pháp lý.
*   **In ấn theo yêu cầu**: Chuyển EML thành PDF để in ấn các vật phẩm như brochure, flyer và card business cho các chiến dịch marketing và sự kiện.
*   **Truy cập và bao gồm**: Sử dụng PDF để làm cho các tài liệu dễ truy cập hơn cho người khuyết tật bằng cách chuyển đổi chúng thành text hoặc format đã định.
*   **Phân phối và hợp tác kỹ thuật số**: Chuyển EML thành PDF để chia sẻ tài liệu an toàn qua email hoặc các nền tảng hợp tác online, làm giảm các bước trong quy trình và tăng hiệu quả làm việc.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}