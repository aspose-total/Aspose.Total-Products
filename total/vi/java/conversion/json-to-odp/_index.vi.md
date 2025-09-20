---
title: Chuyển đổi định dạng JSON sang ODP qua Java
description: Phân tích cú pháp JSON thành ODP trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-odp/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPS PPT PPTM PPSM POWERPOINT POT POTM OTP PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang ODP qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành ODP mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành ODP trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PPTX. Sau đó, bằng cách sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX sang ODP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang ODP qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng PPTX bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng ODP bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
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
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành ODP với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành ODP qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành ODP với hình mờ. Để thêm hình mờ vào tài liệu ODP của bạn, trước tiên bạn có thể phân tích cú pháp JSON thành PPTX và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PPTX mới được tạo bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), lặp qua tất cả các trang chiếu, thêm văn bản sử dụng addTextFrame, đặt tất cả các tùy chọn liên quan như màu sắc, fillType, v.v. và có thể lưu tài liệu vào ODP. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành ODP** là rất quan trọng để tạo ra **bài thuyết trình OpenDocument** trực tiếp từ các bộ dữ liệu có cấu trúc. ODP, định dạng tiêu chuẩn được sử dụng bởi LibreOffice và OpenOffice, đảm bảo sự tương thích hoàn toàn với các bộ ứng dụng văn phòng mã nguồn mở và quy trình làm việc đa nền tảng. Bằng cách biến đổi JSON thành ODP, các tổ chức có thể tạo ra các bài thuyết trình linh hoạt, có thể tái sử dụng và chuẩn hóa mà không cần nỗ lực thủ công.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Bài thuyết trình doanh nghiệp** – Xây dựng bài thuyết trình doanh nghiệp dựa trên dữ liệu trực tiếp từ các nguồn có cấu trúc.
- **Slide giáo dục** – Tạo tài liệu giảng dạy và bộ slide bài giảng từ các bộ dữ liệu học thuật.
- **Slide trình bày dữ liệu** – Tự động hóa bài thuyết trình cho nhà đầu tư hoặc bán hàng bằng cách sử dụng dữ liệu thời gian thực.
- **Quy trình làm việc của chính phủ** – Hỗ trợ tính minh bạch và tuân thủ với các slide ODP tiêu chuẩn mở.
- **Tích hợp với văn phòng mã nguồn mở** – Đảm bảo tính tương thích liền mạch với LibreOffice, Apache OpenOffice và các công cụ tuân thủ ODF khác.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON thành ODP** – Tự động hóa chuyển đổi dữ liệu có cấu trúc thành các bài thuyết trình tiêu chuẩn mở.
- **Tạo slide tự động** – Tiết kiệm thời gian bằng cách tạo ra các slide sẵn sàng trình bày trực tiếp từ các bộ dữ liệu.
- **Quy trình làm việc từ dữ liệu đến bài thuyết trình** – Tích hợp hệ thống dữ liệu doanh nghiệp với việc tạo ODP cho báo cáo.
- **Chuẩn hóa bài thuyết trình doanh nghiệp** – Đảm bảo tính đồng nhất trong thiết kế, cấu trúc và tuân thủ trên toàn bộ tổ chức quy mô lớn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}