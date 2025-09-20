---
title: Chuyển đổi định dạng JSON sang PSD qua Java
description: Phân tích cú pháp JSON thành PSD trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: SVGZ WMF DICOM DXF IMAGE TGA EMZ PSD WMZ JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang PSD qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành PSD trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành PSD trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành JPEG. Sau đó, bằng cách sử dụng [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể chuyển đổi JPEG thành PSD.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang PSD qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng JPEG bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng PSD bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành PSD với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành PSD qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành PSD với hình mờ trong tài liệu PSD của mình. Để thêm hình mờ vào, trước tiên bạn có thể chuyển đổi JSON thành JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging/Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng PSD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành PSD** là điều cần thiết để tạo ra **tệp thiết kế Photoshop từ dữ liệu có cấu trúc**. Tệp PSD bảo tồn các lớp, văn bản và hiệu ứng, cho phép các nhà thiết kế làm việc với đồ họa có thể chỉnh sửa hoàn toàn được tạo ra từ các bộ dữ liệu động. Bằng cách chuyển đổi JSON thành PSD, các tổ chức có thể tối ưu hóa quy trình làm việc sáng tạo, tự động hóa hình ảnh tiếp thị và sản xuất tài sản thiết kế cá nhân hóa, sẵn sàng in ấn hoặc kỹ thuật số một cách hiệu quả.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Thiết kế đồ họa động** – Tạo ra các tệp thiết kế có lớp có thể thích nghi với các bộ dữ liệu thay đổi.
- **Tạo ra tác phẩm tiếp thị tự động** – Sản xuất biểu ngữ, hình ảnh truyền thông xã hội và đồ họa chiến dịch tự động.
- **Mẫu hình ảnh cá nhân hóa** – Tạo ra các mẫu cá nhân hóa cho nội dung cụ thể của khách hàng.
- **Mô phỏng web và ứng dụng** – Xây dựng mô phỏng tương tác cho trang web và ứng dụng di động.
- **Tác phẩm sẵn sàng in ấn** – Chuẩn bị các tệp PSD chất lượng cao để in ấn chuyên nghiệp.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON thành PSD** – Tự động hóa việc chuyển đổi dữ liệu có cấu trúc thành các tệp Photoshop có lớp.
- **Tạo lớp Photoshop tự động** – Tạo ra các lớp có thể chỉnh sửa theo chương trình để tăng hiệu quả.
- **Quy trình làm việc thiết kế dựa trên dữ liệu** – Tích hợp bộ dữ liệu trực tiếp vào quy trình sáng tạo.
- **Tự động hóa sáng tạo dựa trên JSON** – Mở rộng sản xuất thiết kế trên các dự án tiếp thị, web và in ấn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}