---
title: Chuyển đổi CGM sang POT thông qua Java API
description: Java API để chuyển đổi CGM sang POT mà không cần sử dụng Microsoft Word
url_ignore: /vi/java/conversion/cgm-to-pot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POT
otherformats: PPSM PPT PPTM PPS POTM OTP PPSX SWF POWERPOINT POTX XAML POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất CGM sang POT" h2="Xuất CGM sang POT thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi CGM sang POT trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), bạn có thể xuất CGM sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang POT" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng POT bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Pot` dưới dạng SaveFormat
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
Sau khi chuyển đổi CGM sang POT, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi tệp CGM (Computer Graphics Metafile) sang POT (PowerPoint Template) trong môi trường dựa trên Java cho phép các tổ chức tạo ra các mẫu trình bày có thể tái sử dụng, chuẩn hóa được làm phong phú bằng các biểu đồ kỹ thuật. Quy trình này có giá trị đối với các lĩnh vực kỹ thuật, kinh doanh và giáo dục cần các bố cục trang slide nhất quán, thương hiệu doanh nghiệp và biểu đồ hình ảnh chính xác.

## ✅ Các Trường Hợp Sử Dụng Chính
- **Trình Bày Kinh Doanh Chuẩn Hóa** – Duy trì tính nhất quán của thương hiệu trên tất cả các bài trình bày của công ty.
- **Bộ Slide Kỹ Thuật Có Thể Tái Sử Dụng** – Xây dựng trước các bố cục với các biểu đồ CGM nhúng để báo cáo dự án nhanh hơn.
- **Mẫu Báo Cáo Mang Thương Hiệu** – Tạo các mẫu PowerPoint sẵn sàng sử dụng cho các chu kỳ báo cáo định kỳ.

## ⚙️ Kịch Bản Tự Động Hóa
- **Công Cụ Trình Bày Dựa Trên Java** – Sử dụng Apache POI hoặc các API tương tự để tích hợp chuyển đổi CGM sang POT.
- **Công Cụ Tạo Tệp Văn Phòng** – Tự động hóa việc tạo tệp POT với các biểu đồ nhúng cho nhiều bộ phận.
- **Luồng Làm Việc Tự Động Hóa Nội Dung** – Triển khai các tập lệnh được lên lịch để tạo và cập nhật các mẫu PowerPoint theo lô.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}