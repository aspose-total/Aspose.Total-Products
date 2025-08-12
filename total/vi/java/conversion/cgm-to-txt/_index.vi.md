---
title: Java API để kết xuất CGM sang TXT
description: Xuất CGM sang TXT qua Java API mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xuất CGM sang TXT qua Java" h2="Chuyển đổi tệp CGM sang TXT bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tích hợp tính năng chuyển đổi CGM sang TXT trong các ứng dụng Java của mình theo quy trình hai bước. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể kết xuất CGM thành XLSX. Trong bước thứ hai, bạn có thể chuyển đổi XLSX sang TXT bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp CGM sang TXT qua Java" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng TXT bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) trong pom.xml của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành TXT mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang TXT qua Java" %}}
Trong khi chuyển đổi tệp CGM sang TXT, bạn cũng có thể thêm hình mờ vào định dạng tệp TXT đầu ra của mình. Để thêm hình mờ, hãy tạo Sổ làm việc mới để mở tệp XLSX đã chuyển đổi. Chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng addTextEffect của nó, đặt màu sắc, độ trong suốt và hơn thế nữa. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng TXT với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp **Computer Graphics Metafile (CGM)** sang định dạng **TXT (Plain Text)** là quan trọng để trích xuất, tài liệu hóa và xử lý thông tin đồ họa vector dưới dạng nhẹ, dễ đọc cho con người. Trong **các đường ống xử lý dữ liệu được cung cấp bởi Java**, việc chuyển đổi này cho phép biến đổi các biểu đồ CGM thành các biểu diễn dựa trên văn bản để ghi nhật ký, lưu trữ siêu dữ liệu hoặc phân tích phía dưới. Bằng cách ghi lại các yếu tố mô tả của tệp CGM trong TXT, tổ chức có thể đơn giản hóa việc tích hợp với các hệ thống khác, cho phép tìm kiếm và lập chỉ mục nhanh chóng, và duy trì khả năng tương thích dài hạn.



## ✅ Các Trường Hợp Sử Dụng Chính

- **Ghi Nhật Ký Dựa Trên Văn Bản của Biểu Đồ**  
  Lưu trữ thông tin biểu đồ CGM dưới dạng văn bản thuần cho mục đích kiểm toán, gỡ lỗi hoặc lưu trữ dài hạn.

- **Trích Xuất Mô Tả Đồ Họa Vector**  
  Chuyển đổi cấu trúc CGM thành TXT để phân tích, lập chỉ mục tìm kiếm hoặc tích hợp với các công cụ phân tích.

- **Tài Liệu Siêu Dữ Liệu Kỹ Thuật**  
  Tài liệu hóa dữ liệu kỹ thuật liên quan đến CGM trong các tệp TXT để tham khảo nhanh và lưu trữ nhẹ.



## ⚙️ Kịch Bản Tự Động Hóa

- **Thư Viện Java I/O cho Chuyển Đổi**  
  Sử dụng các API xử lý tệp Java tiêu chuẩn cùng với các trình phân tích CGM để trích xuất và ghi nội dung vào các tệp TXT.

- **Dịch Vụ Theo Dõi Tệp**  
  Tự động hóa việc chuyển đổi CGM sang TXT bằng cách theo dõi thư mục với `WatchService` của Java để xử lý sự kiện tệp mới.

- **Công Việc Chuyển Đổi Đợt**  
  Xử lý lượng lớn tệp CGM trong các công việc định kỳ của Java, xuất các biểu diễn văn bản cho mục đích lưu trữ hoặc phân tích.

- **Công Cụ Xuất Văn Bản Thuần trong Các Đường Ống ETL**  
  Tích hợp phân tích CGM và xuất TXT vào các luồng làm việc Extract-Transform-Load dựa trên Java cho việc xử lý dữ liệu có cấu trúc.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}