---
title: Xuất PS sang POTX qua C# API
description: .NET API để chuyển đổi PS sang POTX mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPS SWF PPTM XAML OTP PPSX POT POWERPOINT PPSM PPT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang POTX qua .NET" h2=".NET API để xuất PS sang POTX trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất PS sang POTX trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi PS sang POTX" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng POTX bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Potx` thành SaveFormat
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
Trong khi chuyển đổi PS sang POTX, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp PS. Để nhận siêu dữ liệu của tệp PS, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp PS đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp POTX chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp POTX của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang POTX theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu PDF (Portable Document Format) được sử dụng để lưu trữ thông tin về layout, nên chúng là lựa chọn hoàn hảo để tạo các tài liệu静态 như brochure, tờ rơi và trình diễn thuyết trình. Tuy nhiên, khi làm việc với dữ liệu động, trình diễn Microsoft Office như PowerPoint trở nên quan trọng hơn để hiển thị dữ liệu và phân tích.

Chuyển đổi các file PDF thành các định dạng PowerPoint là cần thiết để khai thác được đầy đủ khả năng của trình diễn và phân tích của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Tối ưu bài trình diễn bán hàng**: Chuyển file PDF sang format PowerPoint để tối ưu các trình diễn bán hàng, sắp xếp nội dung một cách dễ dàng và tạo nên câu chuyện hấp dẫn.
*   **Xây dựng vật liệu marketing sự kiện**: Sử dụng PowerPoint để hiển thị các vật liệu marketing sự kiện, mô拟 trải nghiệm của khán giả và xác định ý tưởng thiết kế.
*   **Tạo tài liệu kỹ thuật**: Chuyển file PDF sang format PowerPoint để tạo các tài liệu kỹ thuật tương tác, mô拟 trải nghiệm người dùng và xác định nội dung documentation.
*   **Thiết kế trình diễn công ty**: Sử dụng PowerPoint để thiết kế các trình diễn công ty, điều chỉnh layout và formatting một cách hiệu quả và tăng cường hiệu ứng hình ảnh tổng thể.
*   **Hiển thị dữ liệu phân tích cho các bên liên quan**: Chuyển file PDF sang format PowerPoint để tạo các biểu đồ dữ liệu hấp dẫn cho các bên liên quan, giúp họ đưa ra quyết định tốt hơn và沟通 hiệu quả hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}