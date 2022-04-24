---
title: Chuyển đổi PS sang PSD thông qua API C#
description: Xuất PS sang PSD trong các ứng dụng .NET của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url: /vi/net/conversion/ps-to-psd/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PSD
otherformats: JPEG2000  WMZ EMZ PSD DXF TGA WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi tệp PS sang PSD qua C#" h2="Xuất PS sang PSD trong các ứng dụng .NET mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader hoặc bất kỳ ứng dụng bên thứ ba nào khác" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total cho .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng xuất PS sang ảnh PSD trong bất kỳ ứng dụng .NET nào bằng hai bước đơn giản. Trước hết, bằng cách sử dụng [Aspose.PDF cho .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất PS sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), bạn có thể chuyển đổi JPEG thành PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp PS sang PSD qua .NET" %}}
1. Mở tệp PS bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Khởi tạo đối tượng lớp [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) và kết xuất PS thành JPEG bằng cách sử dụng [Process](https://apireference.aspose. com / pdf / net / aspose.pdf.devices.pagedevice / process / methods / 1) method
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Lưu tài liệu sang định dạng PSD bằng phương pháp [Lưu](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PS sang PSD trong một tệp duy nhất qua C#" %}}
Sử dụng API, bạn cũng có thể chuyển đổi tệp PS ](g PSD thành một tệp hình ảnh duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu PS của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang PSD. Bạn có thể mở tệp đầu vào bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể lấy một hình ảnh TIFF duy nhất bằng phương pháp [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) của phương thức [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) lớp. Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
và lưu nó ở định dạng PSD bằng phương pháp [Lưu](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay Tệp PS sang PSD qua C#" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh PSD đầu ra theo nhu cầu của mình. Phương thức Image.RotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng phương pháp gốc được hiển thị bởi lớp [Hình ảnh](https://apireference.aspose.com/imaging/net/aspose.imaging/image) và gọi Hình ảnh Phương thức .RotateFlip trong khi chỉ định [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) thích hợp. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-emz/" name="PS Đến EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-tga/" name="PS Đến TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-jpeg2000/" name="PS Đến JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-image/" name="PS Đến IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-psd/" name="PS Đến PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-wmz/" name="PS Đến WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-svgz/" name="PS Đến SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to/" name="PS Đến" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-wmf/" name="PS Đến WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-dxf/" name="PS Đến DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ps-to-dicom/" name="PS Đến DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}