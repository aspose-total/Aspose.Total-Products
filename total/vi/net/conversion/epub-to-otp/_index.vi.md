---
title: Xuất EPUB sang OTP qua C# API
description: .NET API để chuyển đổi EPUB sang OTP mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất EPUB sang OTP qua .NET" h2=".NET API để xuất EPUB sang OTP trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất EPUB sang OTP trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp EPUB thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi EPUB sang OTP" %}}
1. Mở tệp EPUB bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi EPUB sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng OTP bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Otp` thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP từ tệp EPUB qua .NET" %}}
Trong khi chuyển đổi EPUB sang OTP, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp EPUB. Để nhận siêu dữ liệu của tệp EPUB, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp EPUB đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp OTP chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp OTP của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp EPUB sang OTP theo chương trình: Các trường hợp sử dụng" %}}
Tập tin (tờ trình) e-book (sách điện tử) được sử dụng để lưu trữ nội dung kỹ thuật số, khiến chúng trở nên lý tưởng nhất cho việc tạo ra nội dung động và trải nghiệm tương tác. Tuy nhiên, khi làm việc với dữ liệu ngoại tuyến, tập tin văn bản trở nên quan trọng hơn để mục đích lưu trữ lâu dài và lưu trữ档案.

Chuyển đổi các file e-book thành Tập tin Văn bản Ngoại Trả (Offline Text files) là cần thiết để khai thác được tiềm năng đầy đủ của các thư viện và kho dữ liệu của bạn. Chuyển đổi này cho phép bạn:

**Những用途:**

*   **Bảo trữ kỹ thuật số**: Chuyển file e-book thành các档案 vĩnh cửu, đảm bảo nội dung kỹ thuật số vẫn có thể tiếp cận trong thời gian dài hơn.
*   **Đọc và chia sẻ ngoại tuyến**: Sử dụng Tập tin Văn bản Ngoại Trả để phân phối nội dung không cần phải dựa trên kết nối internet, lý tưởng nhất cho các vùng có truy cập hạn chế hoặc trường hợp không có Wi-Fi.
*   **Quản lý thư viện và sắp xếp**: Chuyển file e-book thành một bộ sưu tập văn bản có tổ chức và cấu trúc, giúp tìm kiếm, phân loại và lấy thông tin cụ thể.
*   **Lưu trữ kỹ thuật số và phục hồi**: Sử dụng Tập tin Văn bản Ngoại Trả để lưu trữ cácartifact kỹ thuật số và phục hồi nội dung bị损坏, đảm bảo thông tin có giá trị vẫn được giữ nguyên cho các thế hệ sau.
*   **Tạo nội dung và biên tập ngoại tuyến**: Chuyển file e-book thành nội dung có thể sửa đổi không cần dựa trên kết nối internet, lý tưởng nhất cho các tác giả, nhà văn và Nhà xuất bản cần làm việc trong isolation hoặc với truy cập hạn chế đến nguồn lực online.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}