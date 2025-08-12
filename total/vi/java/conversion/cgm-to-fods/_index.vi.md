---
title: Java API để kết xuất CGM sang FODS
description: Xuất CGM sang FODS qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-fods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FODS
otherformats: ODS TSV XLTX EXCEL XLSB TXT SXC XLSM XLTM MD XLT DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang FODS qua Java" h2="Chuyển đổi tệp CGM sang FODS bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang FODS trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang FODS bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang FODS qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
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
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành FODS mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang FODS qua Java" %}}
Trong khi chuyển đổi tệp CGM sang FODS, bạn cũng có thể thêm hình mờ vào định dạng tệp FODS đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng FODS với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp **Computer Graphics Metafile (CGM)** sang định dạng **FODS (Flat OpenDocument Spreadsheet)** là một cách hiệu quả để biến dữ liệu kỹ thuật đồ họa thành các bảng tính có cấu trúc, chuẩn mở. Trong **các ứng dụng mã nguồn mở dựa trên Java**, việc chuyển đổi này cho phép kỹ sư, nhà nghiên cứu và nhà phân tích dữ liệu trích xuất các giá trị đo lường, thông số và chi tiết dựa trên vector từ các biểu đồ CGM vào các bảng tính FODS có thể chỉnh sửa. Với định dạng XML tuân thủ ODF, FODS đảm bảo tính tương thích với các công cụ như OpenOffice, giúp dễ dàng chia sẻ và hợp tác mà không bị ràng buộc bởi các hạn chế độc quyền.


## ✅ Các Trường Hợp Sử Dụng Chính

- **Chuyển đổi Dữ Liệu Kỹ Thuật Đồ Họa thành Bảng Tính**  
  Trích xuất dữ liệu đồ họa vector từ tệp CGM thành các hàng và cột có cấu trúc để phân tích.

- **Ghi Lại Giá Trị Đo Lường**  
  Lưu trữ và quản lý các giá trị đo lường kỹ thuật hoặc kết quả thí nghiệm trong định dạng bảng tính có thể mang theo.

- **Chia Sẻ thông qua Công Cụ ODF**  
  Phân phối dữ liệu bảng tính tạo ra từ CGM thông qua các ứng dụng tuân thủ ODF.


## ⚙️ Kịch Bản Tự Động Hóa

- **Thư Viện Java như JOpenDocument**  
  Tự động hóa việc chuyển đổi CGM sang FODS trong các luồng làm việc Java bằng cách sử dụng các thư viện xử lý bảng tính mã nguồn mở.

- **Tích Hợp LibreOffice Ẩn Đầu**  
  Chạy LibreOffice ở chế độ ẩn đầu từ các ứng dụng Java để chuyển đổi hàng loạt đồ họa CGM thành các bảng tính FODS.

- **Tạo Ra FODS hàng loạt**  
  Kết hợp phân tích CGM và tạo FODS vào các đường ống ETL dựa trên Java để trích xuất dữ liệu quy mô lớn.

- **Hệ Thống Xử Lý Dữ Liệu Mã Nguồn Mở**  
  Sử dụng FODS như một phần của các nền tảng khoa học hoặc kỹ thuật dựa trên Java để quản lý dữ liệu theo chuẩn mở, minh bạch.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}