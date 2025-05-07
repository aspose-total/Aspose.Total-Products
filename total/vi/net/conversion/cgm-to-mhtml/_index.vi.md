---
title: API C# để xuất CGM sang MHTML
description: Chuyển đổi CGM sang MHTML mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: WORDML MHTML DOTX MARKDOWN DOT FLATOPC XAMLFLOW RTF PCL ODT PS DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất CGM sang MHTML qua .NET" h2=".NET API để xuất CGM sang MHTML trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp CGM thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi CGM sang MHTML" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM thành Doc bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng MHTML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Mhtml thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp CGM bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi CGM thành MHTML, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở CGM bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo ReadOnly MHTML- Tệp qua .NET" %}}
Để bảo vệ MHTML của bạn khỏi chỉnh sửa và ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn, bạn cũng có thể đặt bảo vệ tài liệu bằng cách sử dụng API. Bạn có thể giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động với nó. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Nó cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang MHTML theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM thành MHTML: Mở khóa nội dung tương tác

Tập tin CGM (Computer Graphics Metafile) được sử dụng để lưu thông tin về đồ họa vector, nên chúng là lựa chọn hoàn hảo để tạo các minh họa静态 và đồ họa. Tuy nhiên, khi làm việc với nội dung động, các nền tảng dựa trên HTML trở nên quan trọng để tạo trải nghiệm tương tác. Chuyển đổi các file CGM thành định dạng MHTML sẽ mở khóa tiềm năng của nội dung tương tác của bạn, giúp bạn có thể:

**Ứng dụng trường hợp:**

*   **Trả lời hỏi đáp tương tác**: Chuyển đổi các file CGM để tạo trình diễn tương tác thu hút sự chú ý và sự tham gia của khán giả.
*   **Minh họa dựa trên web**: Sử dụng MHTML để nhúng đồ họa vector vào các trang web, nâng cao trải nghiệm người dùng và vẻ đẹp视觉.
*   **Chuyển đổi nội dung động vào ứng dụng HTML**: Chuyển các file CGM thành định dạng MHTML để tích hợp nội dung động vào ứng dụng dựa trên HTML, như các nền tảng e-learning hoặc mạng xã hội.
*   **Chuyển PDF thành HTML**: Sử dụng MHTML để chuyển các file PDF chứa đồ họa vector thành tài liệu HTML tương tác, lý tưởng cho việc xuất bản và chia sẻ online.
*   **Cải thiện tính khả dụng**: Chuyển các file CGM thành định dạng HTML để cải thiện tính khả dụng bằng cách hỗ trợ các công nghệ đọc màn hình và các công cụ trợ năng khác.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}