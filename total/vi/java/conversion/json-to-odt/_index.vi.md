---
title: Chuyển đổi định dạng JSON sang ODT thông qua Java
description: Phân tích cú pháp JSON thành ODT trong Java mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: WORDML EPUB WORD RTF DOT ODT PCL PS DOCM DOC OTT MOBI FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang ODT thông qua Java" h2="API Java tại chỗ để phân tích cú pháp JSON thành ODT mà không cần sử dụng Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi JSON thành ODT trong các ứng dụng Java của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang ODT bằng cách sử dụng API xử lý văn bản [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang ODT qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook # save (java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng ODT bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
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
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho JSON của mình trong khi phân tích cú pháp JSON thành ODT bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành ODT qua Java" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành ODT với hình mờ. Để thêm hình mờ vào tài liệu ODT của bạn, trước tiên bạn có thể chuyển đổi tệp JSON sang PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON sang ODT** là điều cần thiết để tạo ra **tệp văn bản OpenDocument** từ các bộ dữ liệu có cấu trúc. ODT, định dạng gốc cho LibreOffice và OpenOffice, đảm bảo khả năng truy cập dài hạn, tương thích mã nguồn mở và tương thích trên nhiều nền tảng. Bằng cách chuyển đổi JSON thành ODT, các tổ chức có thể tự động tạo ra các tài liệu văn bản chuyên nghiệp, dựa trên dữ liệu mà không cần chỉnh sửa thủ công.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Tài liệu chính phủ** – Tạo ra các tài liệu tuân thủ, chuẩn hóa cho quản lý công cộng.
- **Luồng làm việc văn phòng mã nguồn mở** – Tích hợp dữ liệu JSON với môi trường LibreOffice và Apache OpenOffice.
- **Bài báo học thuật** – Tạo ra báo cáo nghiên cứu và xuất bản từ các bộ dữ liệu có cấu trúc.
- **Hợp đồng kinh doanh** – Tự động hóa việc soạn thảo thỏa thuận và tạo hợp đồng từ các bản ghi JSON.
- **Thư dữ liệu** – Tạo ra thư cá nhân, có cấu trúc theo quy mô lớn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON-to-ODT** – Tự động hóa quá trình chuyển đổi dữ liệu có cấu trúc thành tài liệu ODT có thể chỉnh sửa.
- **Tạo ODT tự động** – Giảm công sức thủ công bằng cách tạo ra các tệp văn bản sẵn sàng sử dụng trực tiếp từ JSON.
- **Tiêu chuẩn hóa JSON-to-OpenDocument** – Đảm bảo tuân thủ với các tiêu chuẩn mở cho việc chia sẻ tài liệu.
- **Luồng làm việc tài liệu đa nền tảng** – Kích hoạt tính tương thích mượt mà trên các hệ thống doanh nghiệp và học thuật.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}