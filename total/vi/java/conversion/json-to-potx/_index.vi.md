---
title: Chuyển đổi định dạng JSON sang POTX qua Java
description: Phân tích cú pháp JSON thành POTX trong Java mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/java/conversion/json-to-potx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPT PPSM POWERPOINT POTM POTX OTP POT PPS PPSX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang POTX qua Java" h2="API Java để phân tích cú pháp định dạng JSON thành POTX mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi định dạng JSON thành POTX trong bất kỳ ứng dụng Java nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PPTX. Sau đó, bằng cách sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX sang POTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang POTX qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mới và mở tệp JSON
2. Lưu JSON dưới dạng PPTX bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) phương pháp
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng POTX bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
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
Hơn nữa, API cho phép bạn phân tích cú pháp JSON thành POTX với các tùy chọn bố cục được chỉ định. Để chỉ định các tùy chọn bố cục, bạn có thể sử dụng lớp [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý một mảng dưới dạng bảng, bỏ qua giá trị rỗng, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày tháng, đặt định dạng ngày và số và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành POTX qua Java" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành POTX với hình mờ. Để thêm hình mờ vào tài liệu POTX của bạn, trước tiên bạn có thể phân tích cú pháp JSON thành PPTX và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PPTX mới được tạo bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), lặp qua tất cả các trang chiếu, thêm văn bản sử dụng addTextFrame, đặt tất cả các tùy chọn liên quan như màu sắc, fillType, v.v. và có thể lưu tài liệu vào POTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành POTX** là điều cần thiết để tạo ra **các tệp mẫu PowerPoint chuẩn từ dữ liệu có cấu trúc**. Các mẫu POTX đảm bảo tính nhất quán của thương hiệu, bố cục có thể tái sử dụng và khung cảnh trình bày có thể mở rộng mà không cần macro. Bằng cách chuyển đổi JSON thành POTX, các tổ chức có thể tự động hóa quy trình làm việc trình bày theo thương hiệu, điều chỉnh giao tiếp trên toàn bộ nhóm và tăng tốc quá trình tạo slide cho nhu cầu doanh nghiệp.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Mẫu thương hiệu doanh nghiệp** – Tạo các mẫu PowerPoint có thể tái sử dụng và mang thương hiệu trực tiếp từ các bộ dữ liệu có cấu trúc.
- **Bộ slide tích hợp dữ liệu** – Xây dựng khung cảnh mẫu tích hợp nội dung được cung cấp bởi JSON.
- **Các buổi đào tạo** – Chuẩn hóa các slide giáo dục và giới thiệu cho việc trình bày nhất quán.
- **Các chiến dịch tiếp thị** – Tạo các mẫu trình bày được tùy chỉnh cho các chiến dịch và sự kiện.
- **Báo cáo doanh nghiệp nhất quán** – Đảm bảo các slide báo cáo đồng nhất trên các bộ phận.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON thành POTX** – Tự động hóa quá trình chuyển đổi dữ liệu có cấu trúc thành các mẫu chuẩn.
- **Tạo mẫu thương hiệu tự động** – Loại bỏ các công việc thiết kế thủ công lặp đi lặp lại cho các bộ slide PowerPoint.
- **Phân phối PowerPoint chuẩn hóa** – Cung cấp các tệp mẫu nhất quán trên các hệ thống doanh nghiệp.
- **Quy trình làm việc trình bày dựa trên JSON** – Điền vào các khung cảnh mẫu có thể tái sử dụng với dữ liệu động.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}