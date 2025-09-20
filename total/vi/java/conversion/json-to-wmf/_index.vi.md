---
title: Chuyển đổi định dạng JSON sang WMF qua Java
description: Phân tích cú pháp JSON thành WMF trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: TGA DICOM JPEG2000 WMZ EMZ PSD WMF DXF SVGZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang WMF qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành WMF trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành WMF trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành JPEG. Sau đó, bằng cách sử dụng [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể chuyển đổi JPEG thành WMF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang WMF qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng JPEG bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng WMF bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
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
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành WMF với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành WMF qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành WMF với hình mờ trong tài liệu WMF của mình. Để thêm hình mờ vào, trước tiên bạn có thể chuyển đổi JSON thành JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging/Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành WMF** là điều cần thiết để tạo ra **đồ họa Windows Metafile từ dữ liệu có cấu trúc**. Các tệp WMF cung cấp đồ họa vector có khả năng mở rộng tương thích với các ứng dụng Windows cũ và tài liệu Office. Bằng cách chuyển đổi JSON thành WMF, các tổ chức có thể tự động hóa việc tạo ra sơ đồ, biểu đồ và minh họa kỹ thuật trong khi đảm bảo tính nhất quán và khả năng tương thích trên các luồng công việc doanh nghiệp.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Ứng dụng Windows cũ** – Duy trì tính tương thích với phần mềm cũ yêu cầu đồ họa WMF.
- **Sơ đồ có khả năng mở rộng** – Tạo ra sơ đồ dựa trên vector có khả năng mở rộng mà không mất chất lượng.
- **Tích hợp với tài liệu Office** – Nhúng đồ họa WMF trực tiếp vào tệp Word, PowerPoint và Excel.
- **Biểu đồ doanh nghiệp** – Tự động hóa việc tạo ra biểu đồ từ các bộ dữ liệu có cấu trúc cho báo cáo doanh nghiệp.
- **Minh họa kỹ thuật** – Tạo ra minh họa chính xác, dựa trên dữ liệu cho sách hướng dẫn và tài liệu kỹ thuật.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON thành WMF** – Tự động hóa việc chuyển đổi dữ liệu có cấu trúc thành đồ họa vector WMF.
- **Tạo đồ họa vector tự động** – Giảm thiểu việc tạo ra sơ đồ và minh họa thủ công.
- **Vẽ biểu đồ dựa trên JSON** – Điền biểu đồ và hình ảnh trực tiếp từ các bộ dữ liệu.
- **Luồng công việc minh họa cấp doanh nghiệp** – Tích hợp việc tạo ra WMF vào các luồng công việc tài liệu doanh nghiệp.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}