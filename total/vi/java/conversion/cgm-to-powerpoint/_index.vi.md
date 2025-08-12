---
title: Chuyển đổi CGM sang POWERPOINT thông qua Java API
description: Java API để chuyển đổi CGM sang POWERPOINT mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: PPS PPT XAML OTP POTM PPSX POT POTX POWERPOINT PPTM PPSM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất CGM sang POWERPOINT" h2="Xuất CGM sang POWERPOINT thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi CGM sang POWERPOINT trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất CGM sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang POWERPOINT" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng POWERPOINT bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt `Powerpoint` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
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
Sau khi chuyển đổi CGM sang POWERPOINT, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM to PowerPoint chuyển đổi cho phép nhúng trực tiếp các biểu đồ kỹ thuật dựa trên vector vào các bài thuyết trình hoạt động hoàn chỉnh. Điều này rất quan trọng cho cập nhật kinh doanh, báo cáo dự án và trình diễn kỹ thuật, đảm bảo sự rõ ràng và chính xác trong giao tiếp hình ảnh.

## ✅ Các Trường Hợp Sử Dụng Chính
- **Báo Cáo Trực Quan cho Các Bên Liên Quan** – Bao gồm hình ảnh kỹ thuật chính xác để đưa ra quyết định.
- **Bài Thuyết Trình với Biểu Đồ Kỹ Thuật** – Tích hợp mượt mà các tệp CGM vào các slide.
- **Nội Dung Tiếp Thị với Hình Ảnh Kỹ Thuật** – Kết hợp thương hiệu với đồ họa kỹ thuật.

## ⚙️ Kịch Bản Tự Động Hóa
- **API Java PowerPoint** – Tự động hóa việc tạo slide từ các biểu đồ CGM với Apache POI.
- **Tạo Slide Doanh Nghiệp** – Tạo bài thuyết trình hàng loạt cho các báo cáo định kỳ.
- **Luồng Chuyển Đổi Tự Động từ CGM sang Slide** – Tích hợp vào các hệ thống quản lý nội dung doanh nghiệp.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}