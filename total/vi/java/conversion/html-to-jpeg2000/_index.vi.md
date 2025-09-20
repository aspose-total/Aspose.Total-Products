---
title: Chuyển đổi HTML sang JPEG2000 qua Java
description: Xuất tệp HTML sang JPEG2000 trong các ứng dụng Java của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/java/conversion/html-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: JPEG2000
otherformats: WMF DXF EMZ  PSD IMAGE SVGZ WMZ JPEG2000 TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi HTML sang JPEG2000 qua Java" h2="Xuất tệp HTML sang JPEG2000 trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi tệp html sang hình ảnh JPEG2000 trong Java bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất HTML sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể kết xuất JPEG thành JPEG2000. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xuất HTML sang JPEG2000 qua Java" %}}
1. Mở tệp HTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Khởi tạo đối tượng lớp và kết xuất HTML thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. phương thức aspose.pdf.Page-java.io.OutputStream-)
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng JPEG2000 bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang JPEG2000 trong một tệp duy nhất qua Java" %}}
API cũng cho phép bạn xuất tệp HTML sang JPEG2000 thành một tệp duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu HTML của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang JPEG2000. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể nhận một hình ảnh TIFF duy nhất bằng cách sử dụng [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- phương thức java.io.OutputStream-) của lớp [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và lưu nó thành định dạng JPEG2000 bằng cách sử dụng [save](https:// phương thức apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang JPEG2000 với Watermark qua Java" %}}
Sử dụng API, bạn cũng có thể xuất tệp HTML sang JPEG2000 với hình mờ trong tài liệu JPEG2000 của mình. Để thêm hình mờ, trước tiên bạn có thể chuyển đổi HTML sang JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging / Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng JPEG2000. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay HTML sang tệp JPEG2000 qua Java" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh JPEG2000 đầu ra theo nhu cầu của mình. Phương thức Image.rotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Thư viện cung cấp các phương thức đơn giản để thực hiện các hoạt động phức tạp trong khi gói gọn tất cả các chi tiết xấu xí. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và gọi Hình ảnh. phương thức xoay trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **HTML sang JPEG2000** là rất quan trọng để tạo ra **hình ảnh chất lượng cao, nén cao** từ nội dung web. JPEG2000 bảo tồn tính chân thực hình ảnh trong khi giảm kích thước file đáng kể, làm cho nó lý tưởng cho thư viện số, lưu trữ nghiên cứu và bảo tồn nội dung web. Bằng cách chuyển đổi trang HTML thành hình ảnh JPEG2000, tổ chức có thể lưu trữ, chia sẻ và quản lý hiệu quả lượng lớn nội dung web hình ảnh mà không làm giảm chất lượng.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Thư viện số** – Lưu trữ và phân phối tài nguyên trên web dưới dạng hình ảnh chất lượng cao, gọn nhẹ.
- **Bản chụp web lưu trữ** – Bảo tồn các phiên bản lịch sử của trang web cho việc tuân thủ và lưu trữ hồ sơ.
- **Nền tảng học trực tuyến** – Chuyển đổi bài học web và nội dung tương tác thành tài liệu tham khảo hình ảnh chất lượng cao.
- **Công bố nghiên cứu** – Bao gồm hình ảnh trên web chính xác vào bài báo và báo cáo học thuật.
- **Bảo tồn nội dung web** – Bảo dưỡng khả năng truy cập dài hạn của các trang web giàu hình ảnh.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kịch Bản Tự Động Hóa" %}}

- **Các luồng công việc HTML-to-JPEG2000** – Tự động hóa việc chuyển đổi trang web thành hình ảnh nén cao.
- **Tạo bản chụp chất lượng cao tự động** – Tạo ra hình ảnh nhất quán, chính xác về mặt hình ảnh cho nhiều trang.
- **Luồng công việc lưu trữ lưu trữ hàng loạt** – Xử lý hiệu quả lượng lớn nội dung web cho việc lưu trữ hoặc phân tích.
- **Bảo tồn số hóa doanh nghiệp cấp độ** – Tích hợp chuyển đổi JPEG2000 vào các hệ thống lưu trữ và xuất bản quy mô lớn.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}