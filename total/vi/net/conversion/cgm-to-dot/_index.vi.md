---
title: API C# để xuất CGM sang DOT
description: Chuyển đổi CGM sang DOT mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/cgm-to-dot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOT
otherformats: PCL FLATOPC OTT WORDML ODT DOT RTF MARKDOWN XAMLFLOW DOTX PS MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất CGM sang DOT qua .NET" h2=".NET API để xuất CGM sang DOT trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp CGM thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi CGM sang DOT" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM thành Doc bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng DOT bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Dot thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp CGM bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi CGM thành DOT, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở CGM bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo ReadOnly DOT- Tệp qua .NET" %}}
Để bảo vệ DOT của bạn khỏi chỉnh sửa và ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn, bạn cũng có thể đặt bảo vệ tài liệu bằng cách sử dụng API. Bạn có thể giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động với nó. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Nó cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang DOT theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM thành định dạng DOT là một việc cần thiết để mở rộng tiềm năng tối đa trong khả năng hiển thị và sắp xếp lại của bạn đối với các biểu đồ. Đây là một quá trình chuyển đổi có mục đích:

**Những用途:**

*   **Biểu diễn Biểu đồ**: Chuyển các file CGM thành định dạng DOT để tạo các biểu đồ, sơ đồ luồng, và biểu đồ quy trình bằng cách sử dụng DOT format, đây là cách lý tưởng để minh họa các mối quan hệ phức tạp giữa các điểm dữ liệu.
*   **Tối ưu Sắp xếp lại Biểu đồ**: Sử dụng định dạng DOT để tối ưu cách sắp xếp của các nút và cạnh trong các biểu đồ của bạn, đảm bảo độ đọc dễ dàng và hiệu quả nhất có thể.
*   **Biểu đồ Quá trình Kinh doanh**: Chuyển các file CGM thành các biểu đồ quá trình kinh doanh chi tiết, chỉ ra các luồng công việc,任务, và điểm quyết định.
*   **Biểu đồ Kỹ thuật**: Sử dụng định dạng DOT để tạo các biểu đồ kỹ thuật như sơ đồ lớp lớp UML, sơ đồ luồng dữ liệu, và mô hình ER.
*   **Cấu trúc và Hiệrchế Biểu đồ**: Chuyển các file CGM thành việc xác lập các hiệrchế rõ ràng và cấu trúc trong các biểu đồ của bạn, giúp dễ dàng di chuyển và hiểu sâu hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}