---
title: Xuất MHTML sang PPSX trong Android
description: API Android để chuyển đổi MHTML sang PPSX mà không cần sử dụng Microsoft Word
url: /vi/android-java/conversion/mhtml-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: PPSX
otherformats: POTM POT PPSM OTP POWERPOINT SWF PPTM POTX XAML PPS ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi MHTML sang PPSX trên Android qua Java" h2="Chuyển đổi MHTML sang PPSX trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> PowerPoint hoặc Adobe <sup> <sup>&reg;</sup>; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi MHTML sang PPSX bên trong các ứng dụng Android của mình bằng hai bước đơn giản. Trong bước đầu tiên, bạn có thể xuất MHTML sang PPTX bằng cách sử dụng [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/). Sau đó, bằng cách sử dụng [Aspose.Slides dành cho Android qua Java](https://products.aspose.com/slides/android-java/), bạn có thể chuyển đổi PPTX sang PPSX. Cả hai API đều nằm trong gói [Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất MHTML sang PPSX" %}}
1. Mở tệp MHTML bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MHTML sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng PPSX bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Ppsx` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF cho Android qua Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Slides cho Android qua Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Mở tệp MHTML được bảo vệ bằng mật khẩu trong Android qua Java" %}}
Trong khi tải định dạng tệp MHTML, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo hình ảnh thu nhỏ của tệp PPSX trong ứng dụng Android" %}}
Sau khi chuyển đổi MHTML sang PPSX, bạn cũng có thể tạo hình ảnh thu nhỏ của tài liệu đầu ra của mình. Bằng cách sử dụng tính năng phong phú [Aspose.Slides dành cho Android qua Java](https://products.aspose.com/slides/android-java/), bạn có thể tạo hình ảnh thu nhỏ của các trang trình bày bằng cách tạo và phiên bản của [Bản trình bày]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) lớp. Sau đó, bạn có thể lấy tham chiếu của bất kỳ trang trình bày mong muốn nào bằng cách sử dụng ID hoặc chỉ mục của nó và lấy hình ảnh thu nhỏ của trang trình bày được tham chiếu trên một tỷ lệ cụ thể.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-potm/" name="MHTML Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-pot/" name="MHTML Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-ppsm/" name="MHTML Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-otp/" name="MHTML Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-powerpoint/" name="MHTML Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-swf/" name="MHTML Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-pptm/" name="MHTML Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-potx/" name="MHTML Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-xaml/" name="MHTML Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-pps/" name="MHTML Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-ppsx/" name="MHTML Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-ppt/" name="MHTML Đến PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}