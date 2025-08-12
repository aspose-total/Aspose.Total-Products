---
title: Java API để kết xuất CGM sang TSV
description: Xuất CGM sang TSV qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: XLT ODS XLSB XLTM XLAM TXT SXC MD DIF FODS XLSM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang TSV qua Java" h2="Chuyển đổi tệp CGM sang TSV bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang TSV trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang TSV bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang TSV qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng TSV bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành TSV mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang TSV qua Java" %}}
Trong khi chuyển đổi tệp CGM sang TSV, bạn cũng có thể thêm hình mờ vào định dạng tệp TSV đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng TSV với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp CGM (Computer Graphics Metafile) thành định dạng TSV (Tab-Separated Values) bằng cách sử dụng tiện ích Java đảm bảo sự căn chỉnh cột chính xác và xử lý dữ liệu thân thiện với Unix. Điều này đặc biệt quan trọng trong quy trình làm việc kỹ thuật nơi đầu ra mô phỏng và tập dữ liệu đo cần được xử lý trong môi trường đa nền tảng. Các API Java I/O và thư viện TSV cho phép xây dựng các đường ống chuyển đổi CGM-to-TSV mạnh mẽ và có khả năng mở rộng phù hợp với quy trình ETL.

## ✅ Các Trường Hợp Sử Dụng Chính
- Tạo bảng căn chỉnh cột từ dữ liệu đo dựa trên CGM.
- Xuất kết quả mô phỏng thành TSV để nghiên cứu và phân tích.
- Đảm bảo tương thích với các công cụ xử lý dòng lệnh Unix/Linux.
- Hỗ trợ trao đổi dữ liệu trong các ứng dụng kỹ thuật mã nguồn mở.

## ⚙️ Kịch Bản Tự Động Hóa
- Java I/O và thư viện TSV cho các biến đổi CGM-to-TSV tự động.
- Chuyển đổi lô không giao diện của các tệp CGM kỹ thuật cho quy trình làm việc báo cáo.
- Đường ống ETL đa nền tảng sử dụng các bộ xử lý dữ liệu dựa trên Java.
- Tích hợp với môi trường tính toán khoa học và cụm HPC.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}