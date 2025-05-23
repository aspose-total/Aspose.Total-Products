---
title: Chuyển đổi CGM sang PSD thông qua API C#
description: Xuất CGM sang PSD trong các ứng dụng .NET của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi tệp CGM sang PSD qua C#" h2="Xuất CGM sang PSD trong các ứng dụng .NET mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader hoặc bất kỳ ứng dụng bên thứ ba nào khác" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng xuất CGM sang ảnh PSD trong bất kỳ ứng dụng .NET nào bằng hai bước đơn giản. Trước hết, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), bạn có thể chuyển đổi JPEG thành PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang PSD qua .NET" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Khởi tạo đối tượng lớp [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) và kết xuất CGM thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/net/ aspose.pdf.devices.pagedevice/process/methods/1) method
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Lưu tài liệu sang định dạng PSD bằng phương pháp [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang PSD trong một tệp duy nhất qua C#" %}}
Sử dụng API, bạn cũng có thể chuyển đổi tệp CGM sang PSD thành một tệp hình ảnh duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu CGM của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang PSD. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể lấy một hình ảnh TIFF duy nhất bằng phương pháp [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) của phương thức [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) lớp. Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image)
và lưu nó ở định dạng PSD bằng phương pháp [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay Tệp CGM sang PSD qua C#" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh PSD đầu ra theo nhu cầu của mình. Phương thức Image.RotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng phương pháp gốc được hiển thị bởi lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image) và gọi Hình ảnh Phương thức .RotateFlip trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) thích hợp. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang PSD theo chương trình: Các trường hợp sử dụng" %}}
Tập tin CGM (Computer Graphics Metafile) được dùng để lưu thông tin về đồ họa vector, nên chúng là lựa chọn hoàn hảo để tạo các hình ảnh静态 và minh họa. Tuy nhiên, khi làm việc với dữ liệu động, các phần mềm biên dịch hình ảnh như Photoshop trở nên quan trọng để hiển thị và sửa đổi hình ảnh.

Chuyển đổi các file CGM thành format PSD là cần thiết để khai thác được đầy đủ khả năng trong thiết kế đồ họa. Chuyển đổi này cho phép bạn:

**Ứng dụng:**

*   **Thiết kế logo**: Chuyển file CGM thành vector scalable để tạo logo có thể điều chỉnh kích thước, sử dụng trên các phương tiện như business card, bảng quảng cáo và website.
*   **Branding và Identity**: Sử dụng PSD để hình상 hóa quy định brand, tạo danh mục hình ảnh một cách nhất quán và duy trì sự nhất quán trong tất cả các tài liệu marketing.
*   **Minh họa và nghệ thuật**: Chuyển file CGM để tạo minh họa phức tạp, sửa đổi vector artwork và hoàn thiện ý tưởng thiết kế.
*   **Thiết kế in ấn**: Sử dụng PSD để hình상 hóa designs in ấn, điều chỉnh layout và đảm bảo chất lượng hình ảnh cao khi in.
*   **Tài nguyên thiết kế đồ họa**: Chuyển file CGM thành tài nguyên editable có thể sử dụng lại trong nhiều dự án, tiết kiệm thời gian và công sức.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}