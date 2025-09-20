---
title: Chuyển đổi định dạng JSON sang EPUB thông qua Java
description: Phân tích cú pháp JSON thành EPUB trong Java mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/json-to-epub/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EPUB
otherformats: DOTX EPUB PCL MOBI WORDML OTT FLATOPC PS DOT DOC WORD RTF ODT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang EPUB thông qua Java" h2="API Java tại chỗ để phân tích cú pháp JSON thành EPUB mà không cần sử dụng Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi JSON thành EPUB trong các ứng dụng Java của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang EPUB bằng cách sử dụng API xử lý văn bản [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang EPUB qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook # save (java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng EPUB bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
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
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho JSON của mình trong khi phân tích cú pháp JSON thành EPUB bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành EPUB qua Java" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành EPUB với hình mờ. Để thêm hình mờ vào tài liệu EPUB của bạn, trước tiên bạn có thể chuyển đổi tệp JSON sang PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào EPUB. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON thành EPUB** là điều cần thiết để tạo ra **sách điện tử** từ các bộ dữ liệu có cấu trúc. Tệp EPUB cung cấp một định dạng có thể thay đổi rộng rãi để cung cấp kiến thức qua các thiết bị đọc sách điện tử, thiết bị di động và nền tảng học tập. Bằng cách chuyển đổi JSON thành EPUB, các tổ chức có thể tự động hóa việc xuất bản nội dung, tạo tài liệu học tập tương tác và phân phối tài nguyên kiến thức chuẩn hóa dưới dạng số trong một định dạng số di động.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Xuất bản tự động** – Chuyển đổi bộ dữ liệu thành sách điện tử sẵn sàng đọc.
- **Tài liệu học tập** – Cung cấp tài liệu học tập có cấu trúc tương tác trong định dạng EPUB.
- **Sách điện tử dựa trên dữ liệu** – Tạo ra các xuất bản động trực tiếp từ đầu vào JSON.
- **Xuất bản nghiên cứu** – Xuất bản các kết quả nghiên cứu học thuật và đầu ra nghiên cứu có cấu trúc dưới dạng sách điện tử.
- **Phân phối kiến thức doanh nghiệp** – Chuẩn hóa chia sẻ kiến thức nội bộ thông qua thư viện số.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON thành EPUB** – Tự động hóa việc tạo sách điện tử từ các nguồn dữ liệu có cấu trúc.
- **Tạo sách điện tử theo thời gian thực** – Tạo ra các xuất bản cập nhật trực tiếp từ các nguồn cấp dữ liệu JSON trực tiếp.
- **Xuất bản tài liệu học tập tự động** – Tối ưu hóa quy trình sản xuất tài liệu học tập cho các cơ sở giáo dục.
- **Tích hợp thư viện số** – Kết hợp các EPUB được điều khiển bởi JSON vào các kho lưu trữ doanh nghiệp và học thuật.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}