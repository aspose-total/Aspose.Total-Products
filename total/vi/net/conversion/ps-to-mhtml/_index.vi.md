---
title: API C# để xuất PS sang MHTML
description: Chuyển đổi PS sang MHTML mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MHTML
otherformats: DOTM OTT RTF DOTX FLATOPC DOT WORDML ODT MARKDOWN PCL MHTML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang MHTML qua .NET" h2=".NET API để xuất PS sang MHTML trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi PS sang MHTML" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS thành Doc bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng MHTML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Mhtml thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp PS bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi PS thành MHTML, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở PS bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang MHTML theo chương trình: Các trường hợp sử dụng" %}}
Định dạng file Portable Document Format (PDF) được sử dụng để lưu trữ thông tin hình ảnh tĩnh, khiến nó trở nên lý tưởng để tạo các ấn phẩm và tài liệu. Tuy nhiên, khi làm việc với dữ liệu động, ứng dụng web như Internet Explorer trở nên cần thiết cho việc hiển thị và phân tích dữ liệu.

Chuyển đổi file PDF thành định dạng MHTML là 必不可少 if you want to unlock the full potential of your data visualization and analysis capabilities. This conversion enables you:

**Ứng trường hợp:**

*   **Phân tích dữ liệu website thương mại điện tử**: Chuyển file PDF để phân tích dữ liệu website thương mại điện tử, theo dõi các xu hướng bán hàng và nhận biết các biểu hiện hành vi của khách hàng.
*   **Đọc lại và so sánh tài liệu**: Sử dụng MHTML để đọc lại và so sánh các tài liệu,跟踪 các thay đổi và đo lường độ chính xác của các tài liệu.
*   **Tạo cơ sở kiến thức hỗ trợ kỹ thuật**: Chuyển file PDF để tạo các cơ sở kiến thức hỗ trợ kỹ thuật tương tác, mô phỏng trải nghiệm người dùng và xác định các概念 trong tài liệu.
*   **Chính sách công bố nghiên cứu**: Sử dụng MHTML để hiển thị dữ liệu nghiên cứu phức tạp như các mẫu 3D, kết quả phân tích và dữ liệu thực nghiệm trong một format có thể công bố.
*   **Báo cáo tuân thủ và tạo biểu đồ interactives**: Chuyển file PDF để tạo các biểu đồ interactiv và báo cáo, giúp tuân thủ pháp lý và làm cho quyết định tốt hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}