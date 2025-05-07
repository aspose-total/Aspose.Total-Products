---
title: API C# để xuất EMAIL sang IMAGE
description: Chuyển đổi EMAIL thành IMAGE mà không cần sử dụng Microsoft Word hoặc Outlook trên .NET
url_ignore: /vi/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất EMAIL sang IMAGE qua .NET" h2=".NET API để hiển thị EMAIL thành IMAGE trên Windows, macOS và Linux mà không cần sử dụng Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Nếu bạn là nhà phát triển .NET đang tìm cách thêm các tính năng chuyển đổi EMAIL sang IMAGE bên trong ứng dụng của mình, thì API thao tác định dạng tệp [Aspose.Total for .NET](https://products.aspose.com/total/net/) là cách phía trước. Bằng cách sử dụng [Aspose.Email for .NET](https://products.aspose.com/email/net/), bạn có thể chuyển đổi định dạng tệp EMAIL sang HTML. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất HTML thành IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi EMAIL thành IMAGE" %}}
1. Mở tệp EMAIL bằng lớp [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Chuyển đổi EMAIL sang HTML bằng phương pháp [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMAIL qua .NET" %}}
Trước khi chuyển đổi EMAIL thành IMAGE, nếu bạn muốn đảm bảo rằng bạn đang chuyển đổi đúng email, bạn có thể tải tài liệu EMAIL, phân tích cú pháp và xem thuộc tính mong muốn của mình. Bằng cách sử dụng lớp [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) của [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, bạn có thể lấy thông tin người gửi và người nhận. Ví dụ: bạn có thể kiểm tra email của người gửi cụ thể cho việc chuyển đổi bằng cách sử dụng thuộc tính [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tài liệu IMAGE qua .NET" %}}
Trong khi lưu tài liệu từ EMAIL vào IMAGE, bạn có thể cần bảo vệ tài liệu đầu ra của mình. Đôi khi bạn có thể cần phải giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. Điều này có thể hữu ích để ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn. API [Aspose.Words for .NET](https://products.aspose.com/words/net/), cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) tham số liệt kê. Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EMAIL sang IMAGE theo chương trình: Các trường hợp sử dụng" %}}
**Chuyển Email sang Hình ảnh: Mở khóa kể chuyện hình ảnh**

Emails là một cách hiệu quả để chuyển tải thông tin, nhưng chúng thiếu sự hấp dẫn视觉 so với các format khác như hình ảnh. Chuyển email sang các định dạng hình ảnh là cần thiết để mở khóa tiềm năng của kể chuyện hình ảnh và bảo tồn nội dung cho việc tham khảo trong tương lai.

Chuyển các file email sang các định dạng hình ảnh có意义 quan trọng trong:

**Use Cases:**

*   **Bảo tồn nội dung**: Chuyển emails sang hình ảnh để bắt捉 nội dung, như ghi chú cuộc họp, thỏa thuận bán hàng, hoặc kế hoạch dự án, và làm cho chúng sẵn sàng tham khảo trong tương lai.
*   **Bảo vệ thương hiệu**: Sử dụng chuyển đổi hình ảnh để bảo tồn các yếu tố hình ảnh của công ty, như logo và các thành phần hiển thị, đảm bảo tính nhất quán trong tất cả các kênh thông tin.
*   **Khoảng giữ ảo ảo**: Chuyển emails sang hình ảnh để tạo một kho lưu trữ kỹ thuật số về lịch sử công ty, bao gồm các sự kiện quan trọng, các bước tiến và quyết định làm nên thành công.
*   **Tính khả dụng và bao gồm**: Chuyển emails sang hình ảnh để làm cho nội dung dễ dàng tiếp cận hơn cho người dùng có khuyết tật视觉 hoặc uy tín, bằng cách sử dụng text mô tả thay thế để cung cấp ngữ cảnh.
*   **An toàn và tuân thủ**: Sử dụng chuyển đổi hình ảnh để bảo vệ thông tin nhạy cảm khỏi việc bị chiếm đoạt bởi các truy cập không được phép, đáp ứng yêu cầu pháp lý về bảo vệ dữ liệu và bí mật.

Bằng cách chuyển các file email sang các định dạng hình ảnh, các tổ chức có thể mở khóa tiềm năng của kể chuyện hình ảnh, bảo tồn nội dung và đảm bảo tuân thủ các quy định.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}