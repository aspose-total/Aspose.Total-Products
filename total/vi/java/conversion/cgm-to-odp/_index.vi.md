---
title: Chuyển đổi CGM sang ODP thông qua Java API
description: Java API để chuyển đổi CGM sang ODP mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: PPS SWF POTX PPSX POTM PPT PPSM XAML OTP PPTM POT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất CGM sang ODP" h2="Xuất CGM sang ODP thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi CGM sang ODP trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất CGM sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành ODP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang ODP" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng ODP bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Odp` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-odp.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi tải định dạng tệp CGM, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tệp CGM được mã hóa qua Java" %}}
Sau khi chuyển đổi CGM sang ODP, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp CGM (Computer Graphics Metafile) sang ODP (OpenDocument Presentation) cho phép tích hợp mạch đồ họa vector chất lượng cao vào định dạng trình bày mã nguồn mở một cách mượt mà. Quá trình chuyển đổi này lý tưởng để đảm bảo tính tương thích đa nền tảng, cho phép việc kể chuyện trực quan chuyên nghiệp trong các bài thuyết trình giáo dục, doanh nghiệp và kỹ thuật mà không cần hy sinh chất lượng hình ảnh.

## ✅ Các Trường Hợp Sử Dụng Chính
- Nhúng sơ đồ vector vào bài thuyết trình LibreOffice Impress.
- Tạo ra báo cáo kỹ thuật và doanh nghiệp đa nền tảng.
- Tạo nội dung học thuật trực quan với hình minh họa có thể co giãn.
- Kết hợp sơ đồ kỹ thuật vào các slide trình bày.
- Tăng cường tài liệu hội nghị khoa học với đồ họa chính xác.

## ⚙️ Kịch Bản Tự Động Hóa
- Tích hợp đường ống tài liệu dựa trên Java để tạo ra slide tự động.
- Hệ thống sản xuất bài thuyết trình tương thích với LibreOffice.
- Công cụ tạo nội dung doanh nghiệp cho các bộ phận kỹ thuật.
- Luồng làm việc từ biểu đồ sang bài thuyết trình dựa trên API.
- Xử lý hàng loạt các sơ đồ CGM cho các bài thuyết trình quy mô lớn.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}