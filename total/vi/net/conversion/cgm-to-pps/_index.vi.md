---
title: Xuất CGM sang PPS qua C# API
description: .NET API để chuyển đổi CGM sang PPS mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất CGM sang PPS qua .NET" h2=".NET API để xuất CGM sang PPS trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất CGM sang PPS trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp CGM thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang PPS" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng PPS bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Pps` thành SaveFormat
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
Trong khi chuyển đổi CGM sang PPS, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp CGM. Để nhận siêu dữ liệu của tệp CGM, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp CGM đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp PPS chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp PPS của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang PPS theo chương trình: Các trường hợp sử dụng" %}}
Tập tin CGM (Computer Graphics Metafile) được sử dụng để lưu thông tin về các hình ảnh vector, khiến chúng trở nên lý tưởng để tạo các biểu tượng静态 và tranh minh họa. Tuy nhiên, khi làm việc với dữ liệu động, các bảng tính như Excel đã trở nên thiết yếu trong việc hiển thị dữ liệu và phân tích.

Chuyển đổi tập tin CGM thành các định dạng PPS (Portable Presentation) là cần thiết để khai thác đầy đủ tiềm năng của các trình diễn và hình ảnh hóa của bạn. Đây là cách bạn có thể:

**Ứng trường hợp:**

*   **Thiết kế trình diễn**: Chuyển đổi tập tin CGM để tạo các slide, animation và transition chuyên nghiệp, hấp dẫn người xem.
*   **Training và Giáo dục**: Sử dụng PPS để tạo các vật liệu đào tạo interactives, mô phỏng và hướng dẫn, làm tăng kết quả học tập.
*   **Kinh doanh và tài vụn**: Chuyển đổi CGM để tạo các tài liệu bán hàng hấp dẫn, demo sản phẩm và materials marketing.
*   **Liên hệ nội bộ**: Sử dụng PPS để tạo các thông báo nội bộ, báo cáo và infographic, giúp chia sẻ thông tin tốt hơn.
*   **Hình ảnh hóa sự kiện và Triển lãm**: Chuyển đổi CGM để tạo các biểu tượng sự kiện hấp dẫn, thiết kế triển lãm và hiển thị tại hội chợ.

Chuyển đổi tập tin CGM thành PPS cho phép bạn tận dụng các tính năng mới nhất của phần mềm trình diễn, bao gồm animation cao cấp, transition và hiệu ứng. Đây là một bước thiết yếu trong bất kỳ dự án nào cần đến các trình diễn chuyên nghiệp.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}