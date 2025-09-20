---
title: Chuyển đổi EPUB sang WMF qua Java
description: Xuất tệp EPUB sang WMF trong các ứng dụng Java của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/java/conversion/epub-to-wmf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: WMF
otherformats: JPEG2000  PSD WMZ SVGZ DXF TGA WMF IMAGE EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi EPUB sang WMF qua Java" h2="Xuất tệp EPUB sang WMF trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi tệp epub sang hình ảnh WMF trong Java bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất EPUB sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể kết xuất JPEG thành WMF. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xuất EPUB sang WMF qua Java" %}}
1. Mở tệp EPUB bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Khởi tạo đối tượng lớp và kết xuất EPUB thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. phương thức aspose.pdf.Page-java.io.OutputStream-)
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng WMF bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi EPUB sang WMF trong một tệp duy nhất qua Java" %}}
API cũng cho phép bạn xuất tệp EPUB sang WMF thành một tệp duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu EPUB của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang WMF. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể nhận một hình ảnh TIFF duy nhất bằng cách sử dụng [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- phương thức java.io.OutputStream-) của lớp [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và lưu nó thành định dạng WMF bằng cách sử dụng [save](https:// phương thức apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi EPUB sang WMF với Watermark qua Java" %}}
Sử dụng API, bạn cũng có thể xuất tệp EPUB sang WMF với hình mờ trong tài liệu WMF của mình. Để thêm hình mờ, trước tiên bạn có thể chuyển đổi EPUB sang JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging / Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay EPUB sang tệp WMF qua Java" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh WMF đầu ra theo nhu cầu của mình. Phương thức Image.rotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Thư viện cung cấp các phương thức đơn giản để thực hiện các hoạt động phức tạp trong khi gói gọn tất cả các chi tiết xấu xí. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và gọi Hình ảnh. phương thức xoay trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **EPUB sang WMF (Windows Metafile)** là cần thiết để tạo ra **đồ họa dựa trên vector tương thích với Windows** từ eBook. Tệp WMF cung cấp hình ảnh có thể co dãn, chất lượng cao phù hợp cho bài thuyết trình, sơ đồ và xuất bản văn phòng. Bằng cách chuyển đổi EPUB thành WMF, các nhà xuất bản, giáo viên và doanh nghiệp có thể tạo ra đồ họa chuyên nghiệp, duy trì độ phân giải độc lập và tối ưu hóa quy trình làm việc tập trung vào Windows.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}
- **Xuất bản dựa trên văn phòng** – Tích hợp hình ảnh eBook vào tài liệu Microsoft Office một cách mượt mà.
- **Tạo sơ đồ** – Chuyển nội dung văn bản và đồ họa thành sơ đồ vector có thể chỉnh sửa.
- **Đồ họa trình bày** – Tăng cường slide bằng hình ảnh có thể co dãn và chất lượng cao.
- **Quy trình lưu trữ** – Bảo quản đồ họa eBook trong một định dạng vector chuẩn.
- **Báo cáo doanh nghiệp** – Bao gồm đồ họa xuất bản trong báo cáo và bảng điều khiển chuyên nghiệp.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}
- **Các luồng công việc EPUB-sang-WMF** – Tự động hóa việc chuyển đổi eBook thành đồ họa Windows Metafile.
- **Chuyển đổi sơ đồ tự động** – Tạo ra các sơ đồ có thể co dãn từ nội dung văn bản hoặc đồ họa.
- **Tạo ra nhiều tệp metafile một cách hiệu quả** – Sản xuất nhiều đồ họa WMF từ các xuất bản một cách hiệu quả.
- **Quy trình làm việc tài liệu cấp doanh nghiệp** – Tích hợp đồ họa WMF vào các hệ thống báo cáo và xuất bản quy mô lớn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}