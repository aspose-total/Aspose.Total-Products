---
title: Xuất PS sang PPSM qua C# API
description: .NET API để chuyển đổi PS sang PPSM mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPSM
otherformats: PPSX POTX PPTM POWERPOINT SWF POTM PPSM PPS OTP PPT POT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang PPSM qua .NET" h2=".NET API để xuất PS sang PPSM trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất PS sang PPSM trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi PS sang PPSM" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng PPSM bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Ppsm` thành SaveFormat
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
Trong khi chuyển đổi PS sang PPSM, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp PS. Để nhận siêu dữ liệu của tệp PS, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp PS đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp PPSM chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp PPSM của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang PPSM theo chương trình: Các trường hợp sử dụng" %}}
**Hướng dẫn chuyển đổi file**

Files PDF (Portable Document Format) được sử dụng để lưu trữ các tài liệu, khiến chúng trở nên lý tưởng để in và chia sẻ. Tuy nhiên, khi làm việc với nội dung có thể sửa đổi, các định dạng Microsoft Office trở nên quan trọng trong việc chỉnh sửa và hợp tác.

Chuyển đổi các file PDF thành các định dạng PPSM (PowerPoint Slide Master) là cần thiết để khai thác được đầy đủ khả năng thiết kế và điều chỉnh layouts trình diễn của bạn. Việc này cho phép bạn:

**Ứng trường hợp:**

*   **Thiết kế trình diễn doanh nghiệp**: Chuyển file PDF để tạo các thương hiệu doanh nghiệp một cách nhất quán, logo và typography trên tất cả các trình diễn.
*   **Tạo vật liệu marketing**: Sử dụng PPSM để thiết kế và sửa đổi các tài liệu marketing như brochure, poster và flyer.
*   **Xây dựng tài liệu đào tạo**: Chuyển file PDF để tạo các tài liệu đào tạo tương tác, mô phỏng và hướng dẫn.
*   **Thiết kế và điều chỉnh layouts xuất bản**: Sử dụng PPSM để thiết kế và sửa đổi layouts của các tạp chí, báo và sách.
*   **Tạo template PowerPoint tùy chỉnh**: Chuyển file PDF để tạo các template PowerPoint tùy chỉnh, tiết kiệm thời gian và công sức cho nhà thiết kế và người trình diễn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}