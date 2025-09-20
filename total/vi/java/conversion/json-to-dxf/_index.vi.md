---
title: Chuyển đổi định dạng JSON sang DXF qua Java
description: Phân tích cú pháp JSON thành DXF trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: DXF WMF WMZ SVGZ TGA JPEG2000 PSD EMZ DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang DXF qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành DXF trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành DXF trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành JPEG. Sau đó, bằng cách sử dụng [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), bạn có thể chuyển đổi JPEG thành DXF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang DXF qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng JPEG bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Lưu tài liệu sang định dạng DXF bằng cách sử dụng [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) phương pháp
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
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành DXF với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành DXF qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành DXF với hình mờ trong tài liệu DXF của mình. Để thêm hình mờ vào, trước tiên bạn có thể chuyển đổi JSON thành JPEG và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp hình ảnh bằng lớp [Hình ảnh](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), tạo một đối tượng của lớp [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) lớp và khởi tạo nó bằng đối tượng Image, tạo một [Matrix](https://reference.aspose.com/imaging/java/ đối tượng com.aspose.imaging/Matrix) và đặt bản dịch và chuyển đổi thành góc mong muốn và thêm hình mờ bằng cách sử dụng [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# phương thức drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Sau khi thêm hình mờ vào hình ảnh của mình, bạn có thể lưu JPEG dưới định dạng DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON sang DXF (Drawing Exchange Format)** là điều cần thiết để tạo ra **bản vẽ CAD** từ các bộ dữ liệu có cấu trúc. DXF là định dạng được sử dụng rộng rãi trong kiến trúc, kỹ thuật, thiết kế công nghiệp và ứng dụng GIS, làm cho nó lý tưởng để chuyển đổi dữ liệu dựa trên JSON thành các bản vẽ kỹ thuật chính xác, có thể chỉnh sửa. Quá trình chuyển đổi này cho phép quy trình làm việc từ dữ liệu đến thiết kế mượt mà hơn, cải thiện tính tương thích giữa các hệ thống CAD và hỗ trợ tự động hóa trong quy trình thiết kế hiện đại.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Bố cục kiến trúc** – Chuyển đổi dữ liệu xây dựng thành các kế hoạch tầng CAD có thể chỉnh sửa.
- **Mô hình kỹ thuật** – Tạo ra các thiết kế cấu trúc và cơ khí từ đầu vào JSON.
- **Tự động hóa CAD dựa trên JSON** – Tối ưu hóa quy trình làm việc CAD bằng cách chuyển đổi các bộ dữ liệu có cấu trúc.
- **Quy trình thiết kế công nghiệp** – Tạo ra các bản vẽ sản phẩm và thành phần chính xác từ dữ liệu JSON.
- **Thiết kế bản đồ GIS** – Chuyển đổi dữ liệu địa lý thành DXF cho các dự án quy hoạch đô thị và hạ tầng.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Luồng dữ liệu JSON sang DXF** – Tự động hóa quá trình chuyển đổi dữ liệu có cấu trúc thành các bản vẽ sẵn sàng cho CAD.
- **Tạo ra các biểu đồ kỹ thuật tự động** – Tạo ra các biểu đồ kỹ thuật trực tiếp từ các bộ dữ liệu JSON.
- **Quy trình làm việc từ dữ liệu đến thiết kế** – Cho phép tích hợp mượt mà của dữ liệu có cấu trúc vào các ứng dụng CAD.
- **Mô hình hạ tầng thông minh** – Nâng cao hệ thống hạ tầng và bản đồ hiện đại với đầu ra DXF dựa trên JSON.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}