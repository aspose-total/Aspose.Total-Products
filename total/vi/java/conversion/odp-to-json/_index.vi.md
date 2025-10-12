---
title: Chuyển đổi định dạng ODP sang JSON qua Java
description: Chuyển đổi định dạng ODP sang JSON qua Java mà không cần sử dụng Microsoft Excel hoặc PowerPoint
url_ignore: /vi/java/conversion/odp-to-json/
family: total
platformtag: net
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng ODP sang JSON qua Java" h2="Trên API Premise Java để xuất ODP sang JSON mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi ODP sang định dạng JSON qua [Aspose.Total for Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Trong bước đầu tiên, bạn có thể xuất ODP sang HTML bằng cách sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Thứ hai, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng ODP sang JSON qua Java" %}}
1. Mở tệp ODP bằng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi ODP sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Phương thức ISaveOptions-)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng JSON bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu ODP đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi ODP được bảo vệ sang định dạng JSON qua Java" %}}
Trong khi chuyển đổi ODP sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để đặt phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, tạo Phạm vi dữ liệu được xuất bằng phương thức Cells.createRange, gọi phương thức JsonUtility.exportRangeToJson với các tham chiếu của Range & ExportRangeToJsonOptions và ghi dữ liệu chuỗi JSON vào tệp qua Phương thức BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **ODP thành JSON** cho phép trích xuất cấu trúc nội dung trình bày vào định dạng **đọc được bởi máy**, cho phép trao đổi dữ liệu mượt mà, phân tích và tích hợp với các hệ thống web hiện đại hoặc tự động hóa.
{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

* Chuyển đổi dữ liệu trình bày thành các định dạng cấu trúc cho APIs
* Trích xuất slide, văn bản và siêu dữ liệu cho phân tích hoặc lập chỉ mục
* Di dời nội dung trình bày sang các ứng dụng dựa trên web
* Lưu trữ dữ liệu trình bày trong cơ sở dữ liệu để tìm kiếm và truy xuất
* Hỗ trợ việc hiểu và phân loại nội dung dựa trên trí tuệ nhân tạo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}
* Chuyển đổi ODP thành JSON tự động cho các hệ thống quản lý nội dung
* Tích hợp vào các đường ống ETL (Extract, Transform, Load)
* Hiển thị động dữ liệu trình bày trong ứng dụng web hoặc di động
* Chuyển đổi theo lô cho kho lưu trữ tài sản số hoặc APIs
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}