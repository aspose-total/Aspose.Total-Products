---
title: API C# để xuất EMLX sang EPUB
description: Chuyển đổi EMLX thành EPUB mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMLX sang EPUB qua .NET" h2=".NET API để hiển thị EMLX thành EPUB trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMLX sang EPUB bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMLX sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMLX thành EPUB" %}}
1. Mở tệp EMLX bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMLX sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng EPUB bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Epub làm SaveFormat
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMLX qua .NET" %}}
Trước khi chuyển đổi EMLX thành EPUB, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng emlx, bạn có thể tải tài liệu EMLX, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra emlx của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu EPUB qua .NET" %}}
Trong khi lưu tài liệu từ EMLX vào EPUB, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMLX sang EPUB theo chương trình: Các trường hợp sử dụng" %}}
Tập tin EMLX (Electronic Mail with X-Based Headers) được sử dụng để lưu trữ thông tin email, làm cho chúng trở nên lý tưởng để tạo các email静态 và档案 tin nhắn. Tuy nhiên, khi làm việc với nội dung động, các định dạng ePUB trở nên quan trọng trong xuất bản kỹ thuật số và phân phối nội dung online.

Chuyển đổi các tập tin EMLX thành các định dạng ePUB là cần thiết để khai thác đầy đủ khả năng trong xuất bản kỹ thuật số và phân phối nội dung online của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng trường hợp:**

* **Xuất bản kỹ thuật số**: Chuyển các tập tin EMLX thành các tạp chí,报纸, hoặc sách điện tử có interactivity, dễ dàng truy cập trên các thiết bị khác nhau.
* **Phân phối nội dung e-learning**: Sử dụng định dạng ePUB để xuất bản các khóa học online, hướng dẫn, và tài liệu giáo dục, làm giàu trải nghiệm học tập cho sinh viên và chuyên gia.
* **Xuất bản bài viết online**: Chuyển các tập tin EMLX thành các bài viết có hình ảnh đẹp, câu chuyện, và bài đăng blog, tăng sự tham gia và hài lòng của người đọc.
* **Tập chí và小说 điện tử**: Sử dụng định dạng ePUB để bảo tồn và phân phối các comic, novel, và loại hình kể chuyện interactivity khác, cung cấp cho người đọc một trải nghiệm đọc độc đáo.
* **Phân phối nội dung website**: Chuyển các tập tin EMLX thành nội dung web động, như bài viết, mô tả sản phẩm, và đánh giá của khách hàng, cải thiện sự tham gia và tỷ lệ chuyển đổi của người dùng website.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}