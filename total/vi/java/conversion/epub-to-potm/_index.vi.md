---
title: Chuyển đổi EPUB sang POTM thông qua Java API
description: Java API để chuyển đổi EPUB sang POTM mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/epub-to-potm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTM
otherformats: PPTM OTP PPT PPSM SWF XAML POTM POWERPOINT POT POTX PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất EPUB sang POTM" h2="Xuất EPUB sang POTM thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi EPUB sang POTM trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất EPUB sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành POTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi EPUB sang POTM" %}}
1. Mở tệp EPUB bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi EPUB sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng POTM bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Potm` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi tải định dạng tệp EPUB, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tệp EPUB được mã hóa qua Java" %}}
Sau khi chuyển đổi EPUB sang POTM, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Chuyển đổi **EPUB thành POTM (Mẫu PowerPoint có Macro)** là điều cần thiết để tạo ra **mẫu tương tác với tự động hóa** từ sách điện tử. Các tệp POTM cho phép tạo các slide có thể tái sử dụng với macro nhúng, cho phép quy trình làm việc tự động, cập nhật nội dung động và tính năng tương tác. Bằng cách chuyển đổi EPUB thành POTM, giáo viên, nhà xuất bản và doanh nghiệp có thể tạo ra các bài thuyết trình thông minh giúp tăng năng suất, chuẩn hóa thiết kế slide và tối ưu hóa quy trình đào tạo và báo cáo.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}
- **Thuyết trình học thuật tự động** – Tạo slide bài giảng với các yếu tố tương tác được cấu hình trước.
- **Tự động hóa slide doanh nghiệp** – Chuẩn hóa và tự động hóa quy trình thuyết trình nội bộ.
- **Quy trình xuất bản với macro** – Nhúng macro để tối ưu hóa cập nhật nội dung trong các mẫu thuyết trình.
- **Khung công việc nghiên cứu** – Chuyển nội dung học thuật thành các slide tương tác có macro.
- **Mẫu đào tạo cấp doanh nghiệp** – Cung cấp các bài thuyết trình đào tạo có thể tái sử dụng, tự động hóa trên toàn bộ nhóm.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}
- **Các luồng công việc EPUB thành POTM** – Tự động hóa quá trình chuyển đổi sách điện tử thành các mẫu thuyết trình có macro.
- **Tự động hóa thuyết trình có macro** – Kết hợp nội dung động và tương tác vào các slide.
- **Mẫu slide dựa trên siêu dữ liệu** – Sử dụng dữ liệu cấu trúc từ sách điện tử để tự động điền nội dung thuyết trình.
- **Tạo mẫu slide tập trung vào xuất bản hàng loạt** – Tạo ra các mẫu slide tương tác quy mô lớn cho doanh nghiệp hoặc các cơ sở giáo dục.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}