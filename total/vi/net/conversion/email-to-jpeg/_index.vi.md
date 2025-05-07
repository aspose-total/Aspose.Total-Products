---
title: API C# để xuất EMAIL sang JPEG
description: Chuyển đổi EMAIL thành JPEG mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMAIL sang JPEG qua .NET" h2=".NET API để hiển thị EMAIL thành JPEG trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMAIL sang JPEG bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMAIL sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMAIL thành JPEG" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng JPEG bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Jpeg làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMAIL qua .NET" %}}
Trước khi chuyển đổi EMAIL thành JPEG, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng email, bạn có thể tải tài liệu EMAIL, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra email của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu JPEG qua .NET" %}}
Trong khi lưu tài liệu từ EMAIL vào JPEG, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMAIL sang JPEG theo chương trình: Các trường hợp sử dụng" %}}
Chuyển file email thành hình ảnh JPEG là một sự cần thiết để khai thác tiềm năng视觉. Những file email chứa dữ liệu giao tiếp quan trọng có thể được chuyển đổi hiệu quả thành các hình ảnh JPEG, trở nên lý tưởng cho việc hiển thị tĩnh và chia sẻ. Tuy nhiên, khi làm việc với nội dung động, các nền tảng xã hội như Instagram trở nên thiết yếu để kể chuyện视觉 và tương tác.

Chuyển file email thành các định dạng JPEG là một sự cần thiết để khai thác được tiềm năng đầy đủ của nội dung视觉 và khả năng chia sẻ. Việc này cho phép bạn:

**Những ứng dụng:**

*   **Chia sẻ trên mạng xã hội**: Chuyển file email thành các hình ảnh JPEG để tạo ra những nội dung吸引 người xem, có thể chia sẻ trên nhiều nền tảng xã hội, giúp tiếp cận được một số lượng khán giả rộng rãi hơn.
*   **Xây dựng hình ảnh sản phẩm trong thương mại điện tử**: Sử dụng các hình ảnh JPEG để hiển thị chi tiết, đặc điểm và tính năng của sản phẩm, làm nên trải nghiệm mua sắm online tốt hơn.
*   **Kế hoạch quảng cáo và quảng bá sự kiện**: Chuyển file email thành các hình ảnh JPEG để quảng cáo các sự kiện, sản phẩm hoặc dịch vụ, thu hút sự chú ý và tạo quan tâm.
*   **Biểu đồ thông tin và vi hóa dữ liệu**: Sử dụng các hình ảnh JPEG để hiển thị dữ liệu, thống kê và thông tin, tạo ra nội dung có tính chất both informative and engaging for various audiences.
*   **Chương trình marketing kỹ thuật số**: Chuyển file email thành các hình ảnh JPEG để tạo ra những visual hấp dẫn cho các chiến dịch marketing, quảng cáo và tài liệu quảng bá.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}