---
title: API C# để xuất EMAIL sang TEXT
description: Chuyển đổi EMAIL thành TEXT mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: EPUB GIF MD RTF DOCM PCL FLATOPC JPEG PDF EMF WORDML DOTX ODT DOTM DOC DOT XPS SVG PNG DOCX OTT TIFF TEXT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMAIL sang TEXT qua .NET" h2=".NET API để hiển thị EMAIL thành TEXT trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMAIL sang TEXT bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMAIL sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMAIL thành TEXT" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng TEXT bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Text làm SaveFormat
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
Trước khi chuyển đổi EMAIL thành TEXT, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng email, bạn có thể tải tài liệu EMAIL, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra email của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu TEXT qua .NET" %}}
Trong khi lưu tài liệu từ EMAIL vào TEXT, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMAIL sang TEXT theo chương trình: Các trường hợp sử dụng" %}}
Chuyển email sang file văn bản là một quá trình cần thiết để trích xuất thông tin từ các thư điện tử, giúp chúng trở nên lý tưởng cho việc tạo lập hồ sơ viết và tóm tắt. Tuy nhiên, khi làm việc với các chuỗi email dài, các công cụ như ứng dụng email trở nên quan trọng để tổ chức và theo dõi các cuộc đối thoại.

Quá trình chuyển đổi email sang file văn bản là cần thiết để khai thác đầy đủ khả năng lưu trữ hồ sơ và tóm tắt của bạn. Quá trình này cho phép bạn:

**Ứng dụng:**  

*   **Lưu trữ email**: Chuyển email thành hồ sơ viết,存档 và tóm tắt để mục đích lịch sử.  
*   **Phân tích giao dịch khách hàng**: Sử dụng file văn bản để phân tích các cuộc đối thoại email, theo dõi vấn đề và nhận ra xu hướng trong沟通.  
*   **Lưu ý họpmeeting và tóm tắt**: Chuyển email thành ghi chú ngắn gọn về các cuộc họp, tóm tắt và mục tiêu cần thực hiện cho đội nhóm và các bên liên quan.  
*   **Theo dõi chiến dịch marketing**: Sử dụng file văn bản để theo dõi các cuộc đối thoại về chiến dịch marketing,追踪 phản hồi và đo lường mức độ tương tác.  
*   **Lưu trữ pháp lý**: Chuyển email thành hồ sơ viết chính thức, chứng cứ và biên niên bản cho mục đích pháp lý.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}