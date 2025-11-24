---
title: Java API để kết xuất MD sang FODS
description: Xuất MD sang FODS qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/md-to-fods/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: FODS
otherformats: XLAM TSV SXC XLTX ODS FODS DIF XLSM XLTM XLSB TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất MD sang FODS qua Java" h2="Chuyển đổi tệp MD sang FODS bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi MD sang FODS trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất MD thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang FODS bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp MD sang FODS qua Java" %}}
1. Mở tệp MD bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MD sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng FODS bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu MD của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành FODS mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi MD được bảo vệ sang FODS qua Java" %}}
Trong khi chuyển đổi tệp MD sang FODS, bạn cũng có thể thêm hình mờ vào định dạng tệp FODS đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng FODS với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Chuyển đổi MD (Markdown) sang FODS (Flat OpenDocument Spreadsheet) tạo ra các tệp bảng tính dựa trên XML có thể chỉnh sửa lý tưởng cho các bộ ứng dụng văn phòng mã nguồn mở. FODS giữ nguyên cấu trúc ô, công thức và định dạng trong một bố cục dựa trên văn bản, thân thiện với phiên bản.



{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}



* Xuất các bộ dữ liệu Markdown sang các định dạng bảng tính mã nguồn mở.

* Tạo các tệp FODS có cấu trúc cho người dùng LibreOffice.

* Nhập các bảng MD vào các bảng tính XML phẳng cho các nhóm phát triển.

* Duy trì các bản lưu trữ bảng tính dưới dạng có thể đọc được bằng văn bản.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}



* Chuyển đổi hàng loạt sang FODS để minh bạch kiểm soát phiên bản.

* Tích hợp MD-to-FODS trong các đường ống ETL mã nguồn mở.

* Tạo bảng tính tự động cho tài liệu chính phủ hoặc tổ chức phi chính phủ.

* Tạo ra FODS dựa trên cơ sở kích hoạt trong các luồng công việc tài liệu liên tục.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}