---
title: Java API để kết xuất CGM sang SXC
description: Xuất CGM sang SXC qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-sxc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SXC
otherformats: FODS DIF MD XLSB EXCEL XLTX XLAM TSV XLTM ODS TXT XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang SXC qua Java" h2="Chuyển đổi tệp CGM sang SXC bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang SXC trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang SXC bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang SXC qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng SXC bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành SXC mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang SXC qua Java" %}}
Trong khi chuyển đổi tệp CGM sang SXC, bạn cũng có thể thêm hình mờ vào định dạng tệp SXC đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng SXC với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM sang SXC (định dạng OpenOffice Calc) chuyển đổi cho phép tích hợp đồ họa kỹ thuật hoặc dữ liệu bảng vào hệ thống bảng tính mã nguồn mở. Nó hỗ trợ khả năng tương thích với LibreOffice và các nền tảng tài liệu mã nguồn mở khác.

## ✅ Các Trường Hợp Sử Dụng Chính
- **Tích Hợp Bảng Kỹ Thuật** – Kết hợp biểu đồ với bảng dữ liệu cho báo cáo kỹ thuật.
- **Lưu Trữ Bảng Tính Dựa Trên Mã Nguồn Mở** – Lưu trữ hình minh họa kỹ thuật dựa trên vector cùng với dữ liệu.
- **Tương Thích Với Công Cụ Dựa Trên LibreOffice** – Đảm bảo việc sử dụng tệp mượt mà trong môi trường đa nền tảng.

## ⚙️ Kịch Bản Tự Động Hóa
- **Luồng Công Việc Chuyển Đổi Dữ Liệu Được Điều Khiển Bằng Java** – Chuyển đổi CGM sang các định dạng sẵn sàng cho bảng tính.
- **Quy Trình ETL Tài Liệu Mở** – Tự động hóa việc nhập các biểu đồ vector vào bảng tính.
- **Hệ Thống Báo Cáo Đa Nền Tảng** – Nhúng hình ảnh vào quá trình tạo báo cáo tự động.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}