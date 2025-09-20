---
title: Chuyển đổi định dạng JSON sang WORDML thông qua Java
description: Phân tích cú pháp JSON thành WORDML trong Java mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: FLATOPC PS RTF DOC MOBI WORDML DOCM DOT PCL DOTX EPUB OTT WORD ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang WORDML thông qua Java" h2="API Java tại chỗ để phân tích cú pháp JSON thành WORDML mà không cần sử dụng Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi JSON thành WORDML trong các ứng dụng Java của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang WORDML bằng cách sử dụng API xử lý văn bản [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang WORDML qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook # save (java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng WORDML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
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
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho JSON của mình trong khi phân tích cú pháp JSON thành WORDML bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành WORDML qua Java" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành WORDML với hình mờ. Để thêm hình mờ vào tài liệu WORDML của bạn, trước tiên bạn có thể chuyển đổi tệp JSON sang PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào WORDML. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON sang WORDML** là điều cần thiết để tạo ra **WordprocessingML (tài liệu Word dựa trên XML) từ dữ liệu có cấu trúc**. WORDML cho phép trao đổi dữ liệu một cách liền mạch, tạo tài liệu theo mẫu và tương thích với quy trình làm việc dựa trên XML. Bằng cách chuyển đổi JSON thành WORDML, các tổ chức có thể tự động hóa việc tạo tài liệu, duy trì tính toàn vẹn của nội dung có cấu trúc và hỗ trợ việc xuất bản trong doanh nghiệp, chính phủ và giáo dục một cách hiệu quả.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Trao đổi dữ liệu giữa các hệ thống** – Hỗ trợ định dạng tài liệu tương thích cho ứng dụng doanh nghiệp.
- **Lưu trữ tài liệu doanh nghiệp** – Duy trì các tệp Word có cấu trúc, dựa trên XML để lưu trữ dài hạn.
- **Tạo tài liệu dựa trên mẫu** – Tự động hóa việc tạo tài liệu chuẩn từ các mẫu.
- **Lưu trữ kỷ lục số của chính phủ** – Tạo tài liệu Word sẵn sàng XML cho các hồ sơ chính thức.
- **Xuất bản học thuật có cấu trúc** – Tạo ra các bài báo nghiên cứu và nội dung giáo dục theo định dạng có cấu trúc.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON-sang-WordML** – Tự động hóa việc chuyển đổi dữ liệu có cấu trúc thành tài liệu Word dựa trên XML.
- **Tạo tài liệu XML tự động** – Tối ưu hóa việc tạo tài liệu hàng loạt trong khi duy trì cấu trúc.
- **Quy trình làm việc tài liệu dựa trên JSON** – Điền dữ liệu vào các tệp WordML trực tiếp từ các bộ dữ liệu có cấu trúc.
- **Báo cáo có cấu trúc cấp doanh nghiệp** – Mở rộng việc tạo tài liệu có cấu trúc tự động trên các bộ phận một cách hiệu quả.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}