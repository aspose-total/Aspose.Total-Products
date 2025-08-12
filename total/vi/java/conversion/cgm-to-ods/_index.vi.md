---
title: Java API để kết xuất CGM sang ODS
description: Xuất CGM sang ODS qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-ods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODS
otherformats: XLTM XLSB XLSM XLT SXC MD DIF EXCEL ODS XLAM TXT FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang ODS qua Java" h2="Chuyển đổi tệp CGM sang ODS bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang ODS trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang ODS bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang ODS qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng ODS bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành ODS mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang ODS qua Java" %}}
Trong khi chuyển đổi tệp CGM sang ODS, bạn cũng có thể thêm hình mờ vào định dạng tệp ODS đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng ODS với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
"""
Chuyển đổi tệp CGM (Computer Graphics Metafile) sang ODS (OpenDocument Spreadsheet) cho phép kết hợp sơ đồ dựa trên vector với dữ liệu có cấu trúc trong các định dạng bảng tính mã nguồn mở. Việc chuyển đổi này là cần thiết cho báo cáo kỹ thuật, tài liệu kỹ thuật và các nhiệm vụ phân tích yêu cầu cả dữ liệu bảng và hình ảnh chất lượng cao.

## ✅ Các Trường Hợp Sử Dụng Chính
- Tạo báo cáo kỹ thuật bảng tính với sơ đồ nhúng.
- Tài liệu dự án mã nguồn mở với tham chiếu hình ảnh.
- Phân tích dữ liệu khoa học cùng với biểu đồ dựa trên vector.
- Theo dõi quy trình sản xuất với sơ đồ tích hợp.
- Báo cáo môi trường và khảo sát chứa dữ liệu biểu đồ.

## ⚙️ Kịch Bản Tự Động Hóa
- Hệ thống ETL dựa trên Java xuất dữ liệu kết hợp và sơ đồ.
- Công cụ xuất dữ liệu khoa học cho nội dung có cấu trúc và hình ảnh.
- API tương thích văn phòng cho tài liệu kỹ thuật đa định dạng.
- Đường ống hình ảnh dữ liệu tự động.
- Tích hợp với LibreOffice Calc để truy cập đa nền tảng.
"""
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}