---
title: Xuất MD sang POTM trong Android
description: API Android để chuyển đổi MD sang POTM mà không cần sử dụng Microsoft Word
url: /vi/android-java/conversion/md-to-potm/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: POTM
otherformats: PPTM PPSM PPSX PPT POTX SWF PPS ODP OTP POWERPOINT XAML POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi MD sang POTM trên Android qua Java" h2="Chuyển đổi MD sang POTM trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> PowerPoint hoặc Adobe <sup> <sup>&reg;</sup>; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi MD sang POTM bên trong các ứng dụng Android của mình bằng hai bước đơn giản. Trong bước đầu tiên, bạn có thể xuất MD sang PPTX bằng cách sử dụng [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/). Sau đó, bằng cách sử dụng [Aspose.Slides dành cho Android qua Java](https://products.aspose.com/slides/android-java/), bạn có thể chuyển đổi PPTX sang POTM. Cả hai API đều nằm trong gói [Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất MD sang POTM" %}}
1. Mở tệp MD bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MD sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng POTM bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Potm` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF cho Android qua Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Slides cho Android qua Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Mở tệp MD được bảo vệ bằng mật khẩu trong Android qua Java" %}}
Trong khi tải định dạng tệp MD, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo hình ảnh thu nhỏ của tệp POTM trong ứng dụng Android" %}}
Sau khi chuyển đổi MD sang POTM, bạn cũng có thể tạo hình ảnh thu nhỏ của tài liệu đầu ra của mình. Bằng cách sử dụng tính năng phong phú [Aspose.Slides dành cho Android qua Java](https://products.aspose.com/slides/android-java/), bạn có thể tạo hình ảnh thu nhỏ của các trang trình bày bằng cách tạo và phiên bản của [Bản trình bày]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) lớp. Sau đó, bạn có thể lấy tham chiếu của bất kỳ trang trình bày mong muốn nào bằng cách sử dụng ID hoặc chỉ mục của nó và lấy hình ảnh thu nhỏ của trang trình bày được tham chiếu trên một tỷ lệ cụ thể.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("output.potm");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-pptm/" name="MD Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-ppsm/" name="MD Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-ppsx/" name="MD Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-ppt/" name="MD Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-potx/" name="MD Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-swf/" name="MD Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-pps/" name="MD Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-potm/" name="MD Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-otp/" name="MD Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-powerpoint/" name="MD Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-xaml/" name="MD Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/md-to-pot/" name="MD Đến POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}