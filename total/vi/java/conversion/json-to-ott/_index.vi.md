---
title: Chuyển đổi định dạng JSON sang OTT thông qua Java
description: Phân tích cú pháp JSON thành OTT trong Java mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC WORD MOBI RTF DOCM EPUB ODT OTT PS WORDML DOT PCL FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang OTT thông qua Java" h2="API Java tại chỗ để phân tích cú pháp JSON thành OTT mà không cần sử dụng Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể chuyển đổi JSON thành OTT trong các ứng dụng Java của mình theo quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể phân tích cú pháp JSON thành PDF. Trong bước thứ hai, bạn có thể chuyển đổi PDF sang OTT bằng cách sử dụng API xử lý văn bản [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang OTT qua Java" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) đối tượng và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) và [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook # save (java.lang.String,%20com.aspose.cells.SaveOptions)) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng OTT bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
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
Hơn nữa, API cho phép bạn đặt các tùy chọn bố cục cho JSON của mình trong khi phân tích cú pháp JSON thành OTT bằng [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành OTT qua Java" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành OTT với hình mờ. Để thêm hình mờ vào tài liệu OTT của bạn, trước tiên bạn có thể chuyển đổi tệp JSON sang PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), tạo một phiên bản của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào OTT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **JSON sang OTT** là điều cần thiết để tạo ra **mẫu tài liệu văn bản** từ các bộ dữ liệu có cấu trúc. OTT, định dạng Mẫu Văn bản OpenDocument, cung cấp một cách chuẩn để tạo ra các mẫu có thể tái sử dụng, có thể chỉnh sửa trong các bộ ứng dụng văn phòng mã nguồn mở như LibreOffice và OpenOffice. Bằng cách chuyển đổi JSON thành OTT, các tổ chức đảm bảo tính nhất quán, tuân thủ và tự động hóa trong việc tạo ra tài liệu qua nhiều luồng công việc.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

- **Khung tài liệu chính phủ** – Tạo các biểu mẫu và báo cáo chuẩn cho việc sử dụng chính thức.
- **Mẫu pháp lý** – Tự động hóa hợp đồng, thỏa thuận và các định dạng sẵn sàng tuân thủ.
- **Thư kinh doanh** – Duy trì tính nhất quán trong việc trao đổi doanh nghiệp.
- **Báo cáo giáo dục** – Tạo ra các mẫu tài liệu sẵn sàng cho mục đích nghiên cứu và bài tập.
- **Tích hợp văn phòng mã nguồn mở** – Sử dụng mẫu được điều khiển bởi JSON một cách liền mạch trong môi trường mã nguồn mở.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

- **Các đường ống JSON-OTT** – Tự động hóa việc tạo mẫu từ các bộ dữ liệu JSON có cấu trúc.
- **Quy trình làm việc mẫu tự động** – Giảm công sức định dạng thủ công qua các bộ phận.
- **Tạo tài liệu dựa trên JSON** – Bắt buộc tính nhất quán trong báo cáo doanh nghiệp và tuân thủ.
- **Phân phối mẫu doanh nghiệp** – Chuẩn hóa các mẫu tài liệu trên toàn bộ đội ngũ toàn cầu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}