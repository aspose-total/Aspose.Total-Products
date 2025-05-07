---
title: Xuất PS sang XAML qua C# API
description: .NET API để chuyển đổi PS sang XAML mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kết xuất PS sang XAML qua .NET" h2=".NET API để xuất PS sang XAML trên Windows, macOS và Linux mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng gói API tự động hóa định dạng tệp mạnh mẽ [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng kết xuất PS sang XAML trong hai bước đơn giản. Bằng cách sử dụng API xử lý PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể chuyển đổi định dạng tệp PS thành PPTX. Sau đó, bằng cách sử dụng API xử lý bản trình bày [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX thành XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi PS sang XAML" %}}
1. Mở tệp PS bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PS sang PPTX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tệp PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng XAML bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) và đặt `Xaml` thành SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP từ tệp PS qua .NET" %}}
Trong khi chuyển đổi PS sang XAML, bạn có thể cần thêm thông tin siêu dữ liệu XMP để ưu tiên quá trình chuyển đổi hàng loạt của mình. Ví dụ: bạn có thể lấy và sắp xếp các tài liệu chuyển đổi của mình dựa trên ngày tạo và xử lý tài liệu cho phù hợp. [Aspose.PDF dành for .NET](https://products.aspose.com/pdf/net/) cho phép bạn truy cập siêu dữ liệu XMP của tệp PS. Để nhận siêu dữ liệu của tệp PS, bạn có thể tạo đối tượng [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và mở tệp PS đầu vào. Sau đó, bạn có thể lấy siêu dữ liệu của tệp bằng thuộc tính [Siêu dữ liệu](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo tệp XAML chỉ đọc qua .NET" %}}
Bằng cách sử dụng API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể nâng cao hơn nữa các tính năng của ứng dụng chuyển đổi của mình. Một trong những tính năng có thể là tạo tệp đầu ra của bạn chỉ đọc để tăng tính bảo mật. API cho phép bạn đặt tệp XAML của mình thành Chỉ đọc, có nghĩa là người dùng (sau khi họ mở bản trình bày) xem đề xuất Chỉ đọc. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang XAML theo chương trình: Các trường hợp sử dụng" %}}
Tài liệu PSD (Portable Document Format) được sử dụng để lưu thông tin về các vector graphics, giúp chúng trở nên lý tưởng để tạo các hình ảnh tĩnh, logo và minh họa. Tuy nhiên, khi làm việc với dữ liệu động, ngôn ngữ markup XAML (Extensible Application Markup Language) trở nên quan trọng trong việc xây dựng giao diện người dùng và ứng dụng.

Chuyển đổi các file PSD sang các định dạng XAML là cần thiết để khai thác được đầy đủ khả năng trong sự phát triển của ứng dụng. Đây là một quá trình chuyển đổi quan trọng, giúp bạn:

**Những用途:**

*   **Làm ứng dụng di động**: Chuyển các file PSD thành các ứng dụng di động gốc với giao diện người dùng trực quan, tận hưởng sức mạnh của XAML để có trải nghiệm người dùng mượt mà.
*   **Làm ứng dụng desktop**: Sử dụng XAML để xây dựng các ứng dụng desktop mạnh mẽ và dễ mở rộng, lợi dụng các ưu điểm của ngôn ngữ này trong binding dữ liệu, animation và templating.
*   **Thư viện component UI**: Chuyển các file PSD thành các component UI có thể sử dụng lại, như nút bấm, trường văn bản và menu, bằng XAML để có một thiết kế hiệu quả và dễ bảo trì.
*   **Kỹ thuật 3D và animation**: Sử dụng XAML để đưa các graphics 3D và animation vào ứng dụng của bạn, kết hợp sức mạnh của vector graphics với tính linh hoạt của ngôn ngữ markup.
*   **Trung gian và tùy chỉnh**: Chuyển các file PSD thành các phần tử UI có thể truy cập và tùy chỉnh, đảm bảo rằng ứng dụng của bạn đáp ứng được nhu cầu và sở thích của người dùng đa dạng.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}