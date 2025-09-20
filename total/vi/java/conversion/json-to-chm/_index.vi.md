---
title: Chuyển đổi định dạng JSON sang CHM thông qua Java
description: Phân tích cú pháp JSON thành CHM trong Java mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang CHM thông qua Java" h2="API Java tại chỗ để phân tích cú pháp JSON thành CHM mà không cần sử dụng Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi JSON thành CHM trong các ứng dụng Java của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang CHM bằng cách sử dụng API xử lý văn bản [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang CHM qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook # save (java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng CHM bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho JSON của mình trong khi phân tích cú pháp JSON thành CHM bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành CHM qua Java" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành CHM với hình mờ. Để thêm hình mờ vào tài liệu CHM của bạn, trước tiên bạn có thể chuyển đổi tệp JSON sang PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành CHM (Compiled HTML Help)** là điều cần thiết để xây dựng **sổ tay trợ giúp biên soạn** trực tiếp từ tài liệu có cấu trúc. Tệp CHM kết hợp nhiều chủ đề trợ giúp thành một nguồn tài nguyên duyệt, tìm kiếm và truy cập ngoại tuyến duy nhất, làm cho chúng lý tưởng cho hỗ trợ phần mềm và quản lý kiến thức doanh nghiệp. Bằng cách biến đổi JSON thành CHM, tổ chức có thể tối ưu hóa việc giao tài liệu, cải thiện tính khả dụng và đảm bảo khả năng truy cập ngay cả khi không có kết nối internet.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Tài liệu phần mềm** – Đóng gói hướng dẫn kỹ thuật vào định dạng biên soạn, dễ sử dụng.
- **Hệ thống trợ giúp ngoại tuyến** – Cung cấp tài liệu mà không cần truy cập internet.
- **Cơ sở kiến thức doanh nghiệp** – Tập trung kiến thức tổ chức vào một tệp trợ giúp có cấu trúc.
- **Tài liệu đào tạo** – Phân phối tài nguyên học tập biên soạn cho nhân viên hoặc sinh viên.
- **Tài liệu tham chiếu API cho nhà phát triển** – Chuyển đổi định nghĩa JSON có cấu trúc thành tài liệu tham chiếu ngoại tuyến có thể tìm kiếm.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kịch Bản Tự Động Hóa" %}}

- **Các luồng dữ liệu JSON-CHM** – Tự động hóa quá trình chuyển đổi dữ liệu có cấu trúc thành sổ tay trợ giúp biên soạn.
- **Tạo tệp trợ giúp tự động** – Tạo tệp CHM trực tiếp từ nội dung dựa trên JSON đang phát triển.
- **Biên soạn dữ liệu thành tài liệu** – Chuyển đổi tài liệu JSON có cấu trúc thành hệ thống trợ giúp có thể truy cập.
- **Phân phối kiến thức ngoại tuyến** – Tiêu chuẩn hóa sổ tay CHM cho đào tạo và hỗ trợ trên toàn doanh nghiệp.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}