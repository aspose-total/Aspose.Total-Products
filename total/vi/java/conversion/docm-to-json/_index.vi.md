---
title: Chuyển đổi định dạng DOCM sang JSON qua Java
description: Chuyển đổi định dạng DOCM sang JSON qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url_ignore: /vi/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng DOCM sang JSON qua Java" h2="Trên API Premise Java để chuyển đổi DOCM sang JSON mà không cần sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi định dạng DOCM sang JSON thông qua [Aspose.Total for Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể xuất DOCM sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng DOCM sang JSON qua Java" %}}
1. Mở tệp DOCM bằng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Chuyển đổi DOCM sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng JSON bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu DOCM đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions. Ví dụ mã sau đây cho thấy cách thử mở tài liệu được mã hóa bằng mật khẩu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOCM được bảo vệ sang định dạng JSON qua Java" %}}
Trong khi chuyển đổi DOCM sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để đặt phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, tạo Phạm vi dữ liệu được xuất bằng phương thức Cells.createRange, gọi phương thức JsonUtility.exportRangeToJson với các tham chiếu của Range & ExportRangeToJsonOptions và ghi dữ liệu chuỗi JSON vào tệp qua Phương thức BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi **DOCM (Tài liệu có Macro cho Word)** sang **JSON (JavaScript Object Notation)** là rất quan trọng để biến nội dung tài liệu tĩnh, bảng và các trường biểu mẫu thành **dữ liệu có cấu trúc, có thể đọc bằng máy**. JSON nhẹ, dễ đọc và được sử dụng rộng rãi trong **API, phân tích, ứng dụng web và quy trình tự động hóa**. Bằng cách trích xuất dữ liệu từ DOCM sang JSON, tổ chức có thể mở khóa tính tương tác trên các nền tảng hiện đại, cho phép tích hợp nhanh hơn và đảm bảo dữ liệu sẵn sàng cho **xử lý, xác thực và phân phối theo thời gian thực**.

## ✅ Các Trường Hợp Sử Dụng Chính

- **Xuất Dữ Liệu Tài Liệu đến REST/GraphQL APIs**
  Cung cấp nội dung DOCM trích xuất dưới dạng JSON để tiêu thụ trực tiếp trong ứng dụng web và di động thông qua API.

- **Cung Cấp Dữ Liệu vào Cơ Sở Dữ Liệu NoSQL và Hồ Sơ Dữ Liệu**
  Tải dữ liệu có cấu trúc tạo ra từ DOCM vào MongoDB, Elasticsearch hoặc hồ sơ dữ liệu dựa trên đám mây.

- **Cung Cấp Dữ Liệu JSON Thời Gian Thực cho Bảng Điều Khiển**
  Truyền các chỉ số và số liệu dựa trên tài liệu vào bảng điều khiển BI và các công cụ giám sát.

- **Xác Thực Đầu Vào Trong JSON Schema**
  Đảm bảo tính nhất quán và tính toàn vẹn bằng việc điều chỉnh dữ liệu trường DOCM với các quy tắc JSON Schema.

- **Kích Hoạt Hệ Thống CMS không đầu hoặc Kiến Trúc Microservice**
  Tích hợp nội dung DOCM vào các hệ thống phân tán, ưu tiên API nơi mà JSON là ngôn ngữ chung.

## ⚙️ Kịch Bản Tự Động Hóa

- **Trích Xuất DOCM sang JSON với Bản Đồ Trường**
  Xác định các bản đồ để biến đổi bảng, tiêu đề và trường thành các đối tượng JSON có cấu trúc.

- **Chức Năng Không Máy chuyển đổi và Phát Sự Kiện JSON**
  Kích hoạt chuyển đổi khi tải lên tệp, phát sự kiện JSON tới các hệ thống dựa trên sự kiện.

- **Công Việc ETL chuẩn hóa Loại và Khóa**
  Chuẩn hóa xuất DOCM thành cấu trúc JSON nhất quán cho phân tích hậu cần.

- **Webhooks đẩy JSON tới Hệ Thống Hậu Cần**
  Tự động hóa việc xuất DOCM sang JSON cung cấp cho CRM, công cụ ERP hoặc ứng dụng bên thứ ba.

- **Quy Tắc Quản Trị loại bỏ Macro và PII trước Khi Xuất JSON**
  Áp dụng kiểm tra tuân thủ để đảm bảo đầu ra JSON an toàn, được làm sạch từ các tệp có Macro.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}