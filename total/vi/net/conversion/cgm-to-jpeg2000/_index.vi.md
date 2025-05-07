---
title: Chuyển đổi CGM sang JPEG2000 thông qua API C#
description: Xuất CGM sang JPEG2000 trong các ứng dụng .NET của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi tệp CGM sang JPEG2000 qua C#" h2="Xuất CGM sang JPEG2000 trong các ứng dụng .NET mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader hoặc bất kỳ ứng dụng bên thứ ba nào khác" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng xuất CGM sang ảnh JPEG2000 trong bất kỳ ứng dụng .NET nào bằng hai bước đơn giản. Trước hết, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), bạn có thể chuyển đổi JPEG thành JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang JPEG2000 qua .NET" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Khởi tạo đối tượng lớp [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) và kết xuất CGM thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/net/ aspose.pdf.devices.pagedevice/process/methods/1) method
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Lưu tài liệu sang định dạng JPEG2000 bằng phương pháp [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang JPEG2000 trong một tệp duy nhất qua C#" %}}
Sử dụng API, bạn cũng có thể chuyển đổi tệp CGM sang JPEG2000 thành một tệp hình ảnh duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu CGM của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang JPEG2000. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể lấy một hình ảnh TIFF duy nhất bằng phương pháp [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) của phương thức [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) lớp. Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image)
và lưu nó ở định dạng JPEG2000 bằng phương pháp [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay Tệp CGM sang JPEG2000 qua C#" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh JPEG2000 đầu ra theo nhu cầu của mình. Phương thức Image.RotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng phương pháp gốc được hiển thị bởi lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image) và gọi Hình ảnh Phương thức .RotateFlip trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) thích hợp. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang JPEG2000 theo chương trình: Các trường hợp sử dụng" %}}
Tập tin CGM (Computer Graphics Metafile) được dùng để lưu trữ thông tin về hình ảnh vector, khiến chúng trở nên lý tưởng để tạo ra các hình ảnh tĩnh và minh họa. Tuy nhiên, khi làm việc với dữ liệu động, hình ảnh như JPEG 2000 trở nên quan trọng hơn để đảm bảo tỷ lệ nén và chất lượng cao nhất.

Chuyển đổi tập tin CGM thành các định dạng JPEG 2000 là cần thiết để khai thác đầy đủ tiềm năng của khả năng nén và chất lượng hình ảnh của bạn. Chuyển đổi này cho phép bạn:

**Ứng dụng cụ thể:**

*   **Chỉnh sửa hình ảnh với chất lượng cao**: Chuyển tập tin CGM thành các hình ảnh cao质量, tối ưu hóa các biểu tượng để sử dụng trên web và đảm bảo sự nhất quán trong branding của tất cả các tài liệu marketing.
*   **Ứng dụng trong Lưu trữ và Bảo tồn**: Sử dụng JPEG 2000 để nén và lưu trữ các dataset hình ảnh lớn, đảm bảo việc bảo tồn lâu dài và truy cập được cho nội dung hình ảnh có giá trị quan trọng.
*   **Y tế và Diagnostics**: Chuyển tập tin CGM thành các hình ảnh y tế chi tiết và cao质量 để mục đích chẩn đoán, giảm số lỗi và cải thiện kết quả đối với bệnh nhân.
*   **Công việc nghiên cứu khoa học và xuất bản**: Sử dụng JPEG 2000 để nén và phát hành các dataset hình ảnh lớn trong nghiên cứu khoa học, giúp hợp tác toàn cầu và chia sẻ kiến thức.
*   **Thư viện kỹ thuật và Bảo tồn**: Chuyển tập tin CGM thành các thư viện số có thể mở rộng, bảo tồn di tích văn hóa và hiện vật lịch sử cho các thế hệ sau.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}