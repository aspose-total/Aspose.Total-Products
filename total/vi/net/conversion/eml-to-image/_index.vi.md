---
title: API C# để xuất EML sang IMAGE
description: Chuyển đổi EML thành IMAGE mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/eml-to-image/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EMF WORDML PDF ODT MD TEXT DOTM DOC DOCX DOT DOCM IMAGE SVG EPUB JPEG RTF PNG XPS GIF PCL PS TIFF DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EML sang IMAGE qua .NET" h2=".NET API để hiển thị EML thành IMAGE trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EML sang IMAGE bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EML sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EML thành IMAGE" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng IMAGE bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Image làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EML qua .NET" %}}
Trước khi chuyển đổi EML thành IMAGE, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng eml, bạn có thể tải tài liệu EML, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra eml của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu IMAGE qua .NET" %}}
Trong khi lưu tài liệu từ EML vào IMAGE, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EML sang IMAGE theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu email điện tử (EML) được sử dụng để lưu trữ nội dung邮件文字, nên chúng là lựa chọn hoàn hảo để tạo nội dung email静态. Tuy nhiên, khi làm việc với hình ảnh và biểu tượng động, các định dạng như JPEG hoặc PNG trở nên quan trọng trong việc truyền đạt thông tin视觉.

Chuyển đổi tài liệu email điện tử thành các định dạng hình ảnh là cần thiết để khai thác được đầy đủ khả năng truyền đạt thông tin视觉 của bạn. Đây là cách bạn có thể:

**Ứng dụng:**

*   **Tạo nội dung social media hấp dẫn**: Chuyển tài liệu email điện tử thành các bài đăng, hình ảnh và biểu tượng social media để吸引 sự chú ý của người dùng.
*   **Hiển thị thông tin sản phẩm trong thương mại điện tử**: Sử dụng các định dạng hình ảnh để hiển thị thông tin sản phẩm, đặc điểm và lợi ích một cách hấp dẫn.
*   **Chương trình marketing kỹ thuật số**: Chuyển tài liệu email điện tử thành các chiến dịch email marketing eye-catching, vật phẩm quảng cáo và trang bán hàng.
*   **Ilustration trong bài viết và文章**: Sử dụng các định dạng hình ảnh để ilustrieren các bài viết phức tạp, article và báo cáo trắng.

*   **Tạo tài liệu kỹ thuật số**: Chuyển tài liệu email điện tử thành các tài liệu kỹ thuật số có nội dung视觉 hấp dẫn như hướng dẫn người dùng và tài liệu技术.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}