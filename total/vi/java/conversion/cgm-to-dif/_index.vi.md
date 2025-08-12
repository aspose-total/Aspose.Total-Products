---
title: Java API để kết xuất CGM sang DIF
description: Xuất CGM sang DIF qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: XLT XLSB XLAM DIF XLTX XLTM SXC TXT EXCEL ODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang DIF qua Java" h2="Chuyển đổi tệp CGM sang DIF bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang DIF trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang DIF bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang DIF qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng DIF bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành DIF mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang DIF qua Java" %}}
Trong khi chuyển đổi tệp CGM sang DIF, bạn cũng có thể thêm hình mờ vào định dạng tệp DIF đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng DIF với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp **Computer Graphics Metafile (CGM)** sang **DIF (Data Interchange Format)** là có giá trị đối với các tổ chức cần tích hợp nội dung hình ảnh hoặc có cấu trúc vào các hệ thống bảng tính cũ hoặc luồng công việc tính toán khoa học. Trong **môi trường doanh nghiệp và nghiên cứu dựa trên Java**, việc chuyển đổi này cho phép di chuyển mượt từ các định dạng cũ hơn, hỗ trợ tương thích với các công cụ thống kê, và tạo điều kiện cho việc mô hình dữ liệu có cấu trúc cho các ứng dụng kỹ thuật. Bằng cách biến đổi các biểu đồ CGM thành bảng DIF, các nhóm có thể thống nhất dữ liệu hình ảnh với bộ dữ liệu số, cải thiện khả năng truy cập và phân tích trên nhiều nền tảng.


## ✅ Các Trường Hợp Sử Dụng Chính

- **Di Dời Hệ Thống Bảng Tính Cũ**  
  Chuyển đổi dữ liệu CGM thành DIF để nhập mượt vào các chương trình bảng tính cũ vẫn đang sử dụng trong môi trường doanh nghiệp.

- **Nền Tảng Tính Toán Khoa Học**  
  Biến đổi dữ liệu CGM đồ họa thành DIF để tương thích với các công cụ phân tích số liệu trong vật lý, hóa học và mô hình môi trường.

- **Mô Hình Dữ Liệu Có Cấu Trúc Trong Ứng Dụng Kỹ Thuật**  
  Sử dụng DIF để đại diện cho các sơ đồ dựa trên CGM dưới dạng bảng có cấu trúc cho mô phỏng kỹ thuật và tích hợp dữ liệu CAD.


## ⚙️ Kịch Bản Tự Động Hóa

- **Thư Viện Java cho Chuyển Đổi Bảng Tính**  
  Thực hiện việc chuyển đổi tự động từ CGM sang DIF bằng cách sử dụng API Java xử lý các định dạng tương thích với bảng tính.

- **Xử Lý Batch trong Các Công Cụ ETL**  
  Tích hợp các bước chuyển đổi vào các đường ống Extract-Transform-Load dựa trên Java để xử lý lượng lớn dữ liệu kỹ thuật hoặc nghiên cứu.

- **Tích Hợp với Các Đường Ống Tính Toán Thống Kê**  
  Tự động cung cấp các tệp DIF đã chuyển đổi vào các mô-đun phân tích thống kê R, MATLAB hoặc Python thông qua quy trình làm việc dựa trên Java.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}