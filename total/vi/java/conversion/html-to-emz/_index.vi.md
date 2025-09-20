---
title: Chuyển đổi HTML sang EMZ qua Java
description: Xuất tệp HTML sang EMZ trong các ứng dụng Java của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/java/conversion/html-to-emz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: EMZ
otherformats: PSD DXF TGA  SVGZ IMAGE WMZ JPEG2000 EMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi HTML sang EMZ qua Java" h2="Xuất tệp HTML sang EMZ trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi tệp html sang hình ảnh EMZ trong Java bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất HTML sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể kết xuất JPEG thành EMZ. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xuất HTML sang EMZ qua Java" %}}
1. Mở tệp HTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Khởi tạo đối tượng lớp và kết xuất HTML thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. phương thức aspose.pdf.Page-java.io.OutputStream-)
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng EMZ bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang EMZ trong một tệp duy nhất qua Java" %}}
API cũng cho phép bạn xuất tệp HTML sang EMZ thành một tệp duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu HTML của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang EMZ. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể nhận một hình ảnh TIFF duy nhất bằng cách sử dụng [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- phương thức java.io.OutputStream-) của lớp [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và lưu nó thành định dạng EMZ bằng cách sử dụng [save](https:// phương thức apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang EMZ với Watermark qua Java" %}}
Sử dụng API, bạn cũng có thể xuất tệp HTML sang EMZ với hình mờ trong tài liệu EMZ của mình. Để thêm hình mờ, trước tiên bạn có thể chuyển đổi HTML sang JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging / Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay HTML sang tệp EMZ qua Java" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh EMZ đầu ra theo nhu cầu của mình. Phương thức Image.rotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Thư viện cung cấp các phương thức đơn giản để thực hiện các hoạt động phức tạp trong khi gói gọn tất cả các chi tiết xấu xí. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và gọi Hình ảnh. phương thức xoay trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **HTML sang EMZ (Compressed Enhanced Metafile)** là quan trọng để tạo ra **đồ họa Windows nhẹ** từ trang web. Các tệp EMZ cung cấp đồ họa vector nén tích hợp hoàn hảo với Microsoft Office, các ứng dụng doanh nghiệp và hệ thống lưu trữ. Bằng cách chuyển đổi HTML thành EMZ, tổ chức có thể giảm kích thước tệp, duy trì khả năng mở rộng và đảm bảo tính tương thích mượt mà trên các quy trình làm việc doanh nghiệp và giáo dục.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Đồ họa văn phòng** – Nhúng biểu đồ và hình ảnh nén trực tiếp vào Word, Excel và PowerPoint.
- **Biểu đồ** – Chuyển đổi sơ đồ dựa trên web thành các tệp EMZ có thể mở rộng để tái sử dụng.
- **Đồ họa báo cáo doanh nghiệp** – Tạo ra đồ họa nhỏ gọn cho tài liệu và bài thuyết trình doanh nghiệp.
- **Tài liệu giáo dục** – Cung cấp hình minh họa nhẹ, chất lượng cao trong nội dung học thuật.
- **Quy trình lưu trữ** – Lưu trữ đồ họa vector nén, sẵn sàng cho Windows để truy cập lâu dài.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống HTML-to-EMZ** – Tự động hóa việc chuyển đổi trang web thành các tệp metafile nén.
- **Nén tệp metafile tự động** – Tối ưu hóa quy trình làm việc bằng cách giảm kích thước đồ họa mà không mất chất lượng.
- **Quy trình làm việc đồ họa tài liệu hàng loạt** – Chuyển đổi nhiều hình ảnh cho báo cáo và xuất bản quy mô doanh nghiệp.
- **Tự động hóa xuất bản cấp doanh nghiệp** – Chuẩn hóa đồ họa EMZ để tích hợp đồng nhất trên các bộ phận.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}