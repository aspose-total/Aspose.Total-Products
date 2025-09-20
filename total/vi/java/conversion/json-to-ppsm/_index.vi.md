---
title: Chuyển đổi định dạng JSON sang PPSM qua Java
description: Phân tích cú pháp JSON thành PPSM trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: PPS POT POWERPOINT PPSM PPTM POTM PPSX OTP POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang PPSM qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành PPSM mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành PPSM trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PPTX. Sau đó, bằng cách sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX sang PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang PPSM qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng PPTX bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng PPSM bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành PPSM với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành PPSM qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành PPSM với hình mờ. Để thêm hình mờ vào tài liệu PPSM của bạn, trước tiên bạn có thể phân tích cú pháp JSON thành PPTX và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PPTX mới được tạo bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), lặp qua tất cả các trang chiếu, thêm văn bản sử dụng addTextFrame, đặt tất cả các tùy chọn liên quan như màu sắc, fillType, v.v. và có thể lưu tài liệu vào PPSM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành PPSM** là điều cần thiết để tạo ra **các tệp trình chiếu PowerPoint có khả năng kích hoạt macro từ dữ liệu cấu trúc**. Các tệp PPSM hỗ trợ macro nhúng, cho phép tương tác tự động, nội dung động và chức năng trình bày tiên tiến. Bằng cách chuyển đổi JSON thành PPSM, các tổ chức có thể tạo ra các bản trình diễn tương tác chuẩn hóa, tăng cường bài thuyết trình doanh nghiệp, phiên đào tạo và báo cáo dựa trên dữ liệu.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Bài thuyết trình doanh nghiệp tương tác** – Xây dựng bài trình diễn hấp dẫn với tự động hóa nhúng cho bài thuyết trình cho khách hàng hoặc nội bộ.
- **Quy trình đào tạo với tự động hóa** – Chuẩn hóa quy trình tiếp nhận và phiên học với tương tác do macro điều khiển.
- **Bài thuyết trình doanh nghiệp dựa trên dữ liệu** – Tạo ra báo cáo động và bảng điều khiển từ các bộ dữ liệu cấu trúc.
- **Chuyện kể về tiếp thị** – Tạo ra các bản trình diễn có khả năng kích hoạt macro cho các chiến dịch quảng cáo và ra mắt sản phẩm.
- **Báo cáo động cấp doanh nghiệp** – Tự động hóa bài trình diễn định kỳ cho báo cáo của ban lãnh đạo và các bộ phận.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON-to-PPSM** – Tự động hóa quá trình chuyển đổi dữ liệu cấu trúc thành các tệp trình chiếu có khả năng kích hoạt macro.
- **Tạo bài trình diễn có khả năng kích hoạt macro tự động** – Loại bỏ việc sản xuất bài trình diễn thủ công lặp đi lặp lại.
- **Bộ bài trình tương tác do JSON điều khiển** – Điền dữ liệu cấu trúc và macro động vào bài trình diễn.
- **Tự động hóa bài trình diễn động trên phạm vi doanh nghiệp** – Mở rộng bài trình diễn tương tác trên các nhóm và bộ phận.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}