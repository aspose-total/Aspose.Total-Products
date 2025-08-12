---
title: API Java để xuất CGM sang MHTML
description: Chuyển đổi CGM sang MHTML bằng cách sử dụng API Java tiền đề
url_ignore: /vi/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi CGM sang MHTML qua Java" h2="Trên API Premise Java để kết xuất CGM thành MHTML mà không sử dụng bất kỳ ứng dụng bên thứ ba nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi CGM sang MHTML bằng hai bước đơn giản. Trước tiên, bạn cần kết xuất tệp CGM thành DOC bằng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể chuyển đổi DOC thành MHTML. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang MHTML" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng MHTML bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt MHTML dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi chuyển đổi CGM thành MHTML, ngay cả khi tài liệu của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở nó bằng API thao tác PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Để mở tệp được mã hóa, bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở CGM bằng mật khẩu của chủ sở hữu.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tài liệu CGM được bảo vệ bằng mật khẩu qua Java" %}}
Trong khi lưu tài liệu đầu vào của bạn ở định dạng tệp MHTML, bạn cũng có thể lưu tài liệu của mình vào cơ sở dữ liệu thay vì hệ thống tệp. Bạn có thể cần triển khai việc lưu trữ và truy xuất các đối tượng Tài liệu đến và từ cơ sở dữ liệu. Điều này sẽ cần thiết nếu bạn đang triển khai bất kỳ loại hệ thống quản lý nội dung nào. Để lưu MHTML của bạn vào cơ sở dữ liệu, thông thường cần phải tuần tự hóa tài liệu để có được một mảng byte. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Sau khi nhận được mảng byte của bạn, bạn có thể lưu trữ nó trong cơ sở dữ liệu bằng cách sử dụng câu lệnh SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp **Computer Graphics Metafile (CGM)** sang định dạng **MHTML (MIME HTML)** là điều cần thiết để bảo tồn tài liệu kỹ thuật và kỹ thuật phức tạp với đồ họa nhúng trong một tệp tự chứa duy nhất. Trong **hệ thống lưu trữ web dựa trên Java**, việc chuyển đổi này cho phép tổ chức lưu trữ tài liệu hoàn chỉnh—bao gồm hình ảnh CGM, kiểu dáng và tài nguyên—trong một bản lưu trữ di động phù hợp để xem ngoại tuyến và triển khai trên mạng nội bộ. MHTML đảm bảo rằng các thông số thiết kế, báo cáo và bản vẽ vẫn nguyên vẹn để truy cập và phân phối lâu dài.

---

## ✅ Các Trường Hợp Sử Dụng Chính

- **Đóng Gói Tài Liệu Kỹ Thuật với Đồ Họa Nhúng**  
  Đóng gói sơ đồ CGM và nội dung liên quan vào MHTML để tạo ra hồ sơ kỹ thuật nhất quán, tự chứa.

- **Xem Ngoại Tuyến trên Cổng Thông Tin Nội Bộ**  
  Cung cấp tài liệu được tăng cường bằng CGM dưới dạng MHTML để truy cập ngoại tuyến mượt mà trên mạng nội bộ doanh nghiệp.

- **Lưu Trữ Thông Số Thiết Kế**  
  Lưu trữ phiên bản MHTML của các thông số dựa trên CGM để tuân thủ, tham khảo và tài liệu dự án.

---

## ⚙️ Kịch Bản Tự Động Hóa

- **Thư Viện Java hỗ trợ MHTML**  
  Sử dụng API như **Aspose.Words cho Java** hoặc các công cụ xuất Java tùy chỉnh để tạo ra tệp MHTML từ tài liệu dựa trên CGM.

- **Công Cụ Xuất Dữ Liệu Dựa trên Web**  
  Tích hợp chuyển đổi CGM sang MHTML vào ứng dụng web dựa trên Java để đóng gói tệp ngay lập tức.

- **Luồng Công Việc Chuyển Đổi Dựa trên Servlet**  
  Triển khai servlet Java xử lý đầu vào CGM và tạo ra bản lưu trữ MHTML để phân phối an toàn.

- **Các Luồng Công Việc Lưu Trữ Tự Động**  
  Bao gồm các bước chuyển đổi CGM sang MHTML trong hệ thống quản lý tài liệu hoặc hệ thống ETL dựa trên Java để lưu trữ theo lịch trình.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}