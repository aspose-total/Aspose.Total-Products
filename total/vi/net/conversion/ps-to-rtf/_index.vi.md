---
title: API C# để xuất PS sang RTF
description: Chuyển đổi PS sang RTF mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: DOTM ODT PCL FLATOPC OTT DOT DOTX WORDML MHTML MARKDOWN XAMLFLOW RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang RTF qua .NET" h2=".NET API để xuất PS sang RTF trên Windows, macOS và Linux mà không cần sử dụng Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) là một API mạnh mẽ để thêm các tính năng chuyển đổi và thao tác tài liệu bên trong ứng dụng .NET của bạn. Bằng cách sử dụng API xử lý PDF nâng cao [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành DOC. Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể kết xuất DOC tới RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API để chuyển đổi PS sang RTF" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS thành Doc bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp Tài liệu bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document) của Aspose.Words
4. Lưu tài liệu sang định dạng RTF bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) và đặt Rtf thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Giải mã tệp PS bằng Mật khẩu chủ sở hữu qua .NET" %}}
Trước khi chuyển đổi PS thành RTF, nếu bạn muốn giải mã tài liệu của mình, bạn có thể thực hiện bằng cách sử dụng API. Để giải mã tệp PDF, trước tiên bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở PS bằng mật khẩu của chủ sở hữu. Sau đó, bạn cần gọi phương thức [Giải mã](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) của đối tượng Document. Cuối cùng, lưu tệp đã cập nhật bằng cách sử dụng phương thức Lưu của đối tượng Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo ReadOnly RTF- Tệp qua .NET" %}}
Để bảo vệ RTF của bạn khỏi chỉnh sửa và ngăn người khác chỉnh sửa thông tin nhạy cảm và bí mật trong tài liệu của bạn, bạn cũng có thể đặt bảo vệ tài liệu bằng cách sử dụng API. Bạn có thể giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động với nó. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Nó cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Bạn có thể đặt tài liệu của mình thành chỉ đọc bằng cách sử dụng các dòng mã sau. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang RTF theo chương trình: Các trường hợp sử dụng" %}}
**Tài liệu PDF (Portable Document Format)** được sử dụng để lưu thông tin trong các tài liệu, giúp chúng trở nên chuyên nghiệp và dễ nhìn khi tạo các tài liệu hoặc trình bày trình chiếu. Tuy nhiên, khi làm việc với nội dung multimedia, các file RTF (Rich Text Format) trở nên quan trọng hơn cho việc chỉnh sửa và định dạng text.

Chuyển đổi các file PS thành các format RTF là cần thiết để khai thác được đầy đủ khả năng chỉnh sửa và định dạng text của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng:**  

*   **Chỉnh sửa tài liệu**: Chuyển file PS sang RTF để chỉnh sửa text, layout và định dạng một cách dễ dàng hơn.  
*   **Tạo PDF chuyên nghiệp**: Sử dụng RTF để tạo các tài liệu PDF có font rendering và layout chính xác, chuyên nghiệp.  
*   **Nhập nội dung lớn**: Chuyển file PS sang RTF để nhập大量 nội dung vào các ứng dụng khác cho việc chỉnh sửa hiệu quả hơn.  
*   **Bảo tồn định dạng**: Sử dụng RTF để bảo tồn formatting của tài liệu, bao gồm font, khoảng cách và căn lề, trong quá trình chia sẻ và hợp tác.  
*   **Giữ nguyên tính tương容**: Chuyển file PS sang RTF để cải thiện tính tương容 với các ứng dụng và hệ thống khác, đảm bảo việc trao đổi tài liệu dễ dàng hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}