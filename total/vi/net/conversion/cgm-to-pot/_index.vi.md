---
title: Xuất CGM sang POT qua C# API
description: .NET API để chuyển đổi CGM sang POT mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/cgm-to-pot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POT
otherformats: PPS POWERPOINT POTX PPT POT XAML OTP PPSX POTM PPSM SWF PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất CGM sang POT qua .NET" h2=".NET API để xuất CGM sang POT trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất CGM sang POT trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp CGM thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành POT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang POT" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng POT bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Pot` thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP từ tệp CGM qua .NET" %}}
Trong khi chuyển đổi CGM sang POT, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp CGM. Để nhận siêu dữ liệu của tệp CGM, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp CGM đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp POT chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp POT của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang POT theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM (Computer Graphics Metafile) thành các định dạng POT (Plain Old Text) là cần thiết để khơi mở được tiềm năng đầy đủ của khả năng hiển thị và phân tích dữ liệu của bạn. Chuyển đổi này cho phép bạn:

**Những用途:**

*   **Phân tích dữ liệu lịch sử**: Chuyển file CGM để phân tích dữ liệu lịch sử, theo dõi các xu hướng và nhận biết các mẫu hình trong dữ liệu.
*   **Tạo tài liệu kỹ thuật**: Sử dụng POT để tạo tài liệu kỹ thuật từ các biểu tượng phức tạp của CGM, giúp các nhà phát triển và kĩ sư dễ hiểu và thực hiện các thiết kế hơn.
*   **Thực hiện các tính năng truy cập**: Chuyển file CGM để tạo các tính năng truy cập cho người dùng có khuyết tật, như mô tả hình ảnh và text thay thế cho các phần tử hiển thị.
*   **Bày tỏ và thiết kế nghệ thuật**: Sử dụng POT để lấy các phần tử thiết kế cụ thể từ file CGM, giúp các nhà艺术 và thiết kế tái sử dụng và sửa đổi chúng trong các dự án sáng tạo mới.
*   **Phân tích và phát triển nghiên cứu**: Chuyển file CGM để hiển thị dữ liệu nghiên cứu, mô phỏng các thí nghiệm và xác định các giả设, giúp các nhà khoa học và nhà nghiên cứu sâu入 kiến thức hơn về công việc của họ.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}