---
title: Chuyển đổi HTML sang DICOM qua Java
description: Xuất tệp HTML sang DICOM trong các ứng dụng Java của bạn mà không cần sử dụng bất kỳ ứng dụng nào của bên thứ ba
url_ignore: /vi/java/conversion/html-to-dicom/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: DICOM
otherformats: WMZ TGA SVGZ DICOM WMF EMZ DXF PSD JPEG2000 IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi HTML sang DICOM qua Java" h2="Xuất tệp HTML sang DICOM trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi tệp html sang hình ảnh DICOM trong Java bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất HTML sang JPEG. Sau đó, bằng cách sử dụng API xử lý hình ảnh [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể kết xuất JPEG thành DICOM. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Xuất HTML sang DICOM qua Java" %}}
1. Mở tệp HTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Khởi tạo đối tượng lớp và kết xuất HTML thành JPEG bằng cách sử dụng [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. phương thức aspose.pdf.Page-java.io.OutputStream-)
3. Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng DICOM bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang DICOM trong một tệp duy nhất qua Java" %}}
API cũng cho phép bạn xuất tệp HTML sang DICOM thành một tệp duy nhất. Để chuyển đổi tất cả các trang, trước tiên bạn có thể kết xuất tài liệu HTML của mình thành một tệp TIFF và sau đó, bạn có thể xuất tệp TIFF sang DICOM. Bạn có thể mở tệp đầu vào bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và tạo các đối tượng thiết bị Resolution, TiffSettings và TIFF. Bạn có thể nhận một hình ảnh TIFF duy nhất bằng cách sử dụng [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- phương thức java.io.OutputStream-) của lớp [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Cuối cùng, bạn có thể tải tệp TIFF bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và lưu nó thành định dạng DICOM bằng cách sử dụng [save](https:// phương thức apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang DICOM với Watermark qua Java" %}}
Sử dụng API, bạn cũng có thể xuất tệp HTML sang DICOM với hình mờ trong tài liệu DICOM của mình. Để thêm hình mờ, trước tiên bạn có thể chuyển đổi HTML sang JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging / Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi & xoay HTML sang tệp DICOM qua Java" %}}
Sử dụng API, bạn cũng có thể xoay hình ảnh DICOM đầu ra theo nhu cầu của mình. Phương thức Image.rotateFlip có thể được sử dụng để xoay hình ảnh 90/180/170 độ và lật hình ảnh theo chiều ngang hoặc chiều dọc. Thư viện cung cấp các phương thức đơn giản để thực hiện các hoạt động phức tạp trong khi gói gọn tất cả các chi tiết xấu xí. Bạn có thể chỉ định kiểu xoay và lật để áp dụng cho hình ảnh. Để xoay và lật hình ảnh, bạn có thể tải hình ảnh JPEG đã chuyển đổi bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) và gọi Hình ảnh. phương thức xoay trong khi chỉ định [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **HTML sang DICOM** là điều cần thiết để tạo ra **đầu ra tương thích với hình ảnh y học** từ dữ liệu trên web. DICOM đảm bảo rằng hình ảnh lâm sàng và thông tin liên quan đến chăm sóc sức khỏe được chuẩn hóa để tương thích, lưu trữ và tích hợp trên các hệ thống y tế. Bằng cách chuyển nội dung HTML thành DICOM, các nhà cung cấp dịch vụ chăm sóc sức khỏe và nhà nghiên cứu có thể tối ưu hóa quy trình làm việc y tế trong khi duy trì tuân thủ các tiêu chuẩn ngành.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}
- **Các nền tảng y tế từ xa** – Tích hợp dữ liệu y tế trên web vào các hệ thống tương thích với DICOM.
- **Tích hợp báo cáo y tế** – Nhúng báo cáo văn bản và hình ảnh vào các định dạng chăm sóc sức khỏe tiêu chuẩn.
- **Quy trình làm việc y tế** – Cho phép trao đổi dữ liệu bệnh nhân một cách liền mạch qua các phòng ban.
- **Lưu trữ hình ảnh lâm sàng** – Lưu trữ hình ảnh và nội dung trên web liên quan trong các bộ lưu trữ DICOM.
- **Tương thích giữa các hệ thống** – Hỗ trợ chia sẻ dữ liệu chuẩn hóa giữa các ứng dụng chăm sóc sức khỏe.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}
- **Các đường ống HTML-to-DICOM** – Tự động hóa việc chuyển đổi nội dung y tế trên web sang DICOM.
- **Nhúng báo cáo y tế tự động** – Tích hợp dữ liệu HTML vào quy trình làm việc hình ảnh bệnh nhân.
- **Chuyển đổi dữ liệu y tế hàng loạt** – Xử lý nhiều báo cáo hoặc trang web một cách hiệu quả theo quy mô.
- **Quy trình làm việc lâm sàng cấp doanh nghiệp** – Chuẩn hóa việc chuyển đổi HTML sang DICOM trên các tổ chức chăm sóc sức khỏe.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}