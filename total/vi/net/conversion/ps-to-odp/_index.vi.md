---
title: Xuất PS sang ODP qua C# API
description: .NET API để chuyển đổi PS sang ODP mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-odp/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODP
otherformats: POTM XAML POTX PPSM PPSX POWERPOINT PPT POT PPTM OTP PPS SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang ODP qua .NET" h2=".NET API để xuất PS sang ODP trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất PS sang ODP trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi PS sang ODP" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng ODP bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Odp` thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP từ tệp PS qua .NET" %}}
Trong khi chuyển đổi PS sang ODP, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp PS. Để nhận siêu dữ liệu của tệp PS, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp PS đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp ODP chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp ODP của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang ODP theo chương trình: Các trường hợp sử dụng" %}}
Định dạng tài liệu di động (PDF) được sử dụng để lưu trữ các tài liệu với định dạng cố định, khiến chúng trở nên lý tưởng để tạo ấn phẩm và trình diễn. Tuy nhiên, khi làm việc với dữ liệu hiển thị interactives, bảng tính như Excel trở nên quan trọng để phân tích và báo cáo.

Chuyển đổi các file PDF thành các định dạng Excel là cần thiết để mở khóa tiềm năng đầy đủ của khả năng hiển thị dữ liệu và phân tích của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Phân tích hiệu suất bán hàng**: Chuyển file PDF để phân tích hiệu suất bán hàng, theo dõi các chỉ số quan trọng và nhận biết các xu hướng trong dữ liệu.
*   **Phân tích nghiên cứu thị trường**: Sử dụng Excel để hiển thị dữ liệu nghiên cứu thị trường, phân tích hành vi của người tiêu dùng và tìm hiểu các nguyện vọng của khách hàng.
*   **Tạo tài liệu sản phẩm và bảo trì**: Chuyển file PDF để tạo các tài liệu interactives về sản phẩm, theo dõi các kỷ lục bảo trì và cập nhật tài liệu một cách nhanh chóng.
*   **Tạo nội dung giáo dục**: Sử dụng Excel để tạo nội dung giáo dục hấp dẫn, như các mô phỏng interactives, câu hỏi trắc nghiệm và đánh giá.
*   **Quyết định dựa trên dữ liệu**: Chuyển file PDF để tạo các báo cáo interactives, bảng điều khiển và hiển thị dữ liệu, giúp các bên liên quan làm quyết định tốt hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}