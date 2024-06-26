---
title: Xuất XSLFO sang ODP trong Android
description: API Android để chuyển đổi XSLFO sang ODP mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: ODP
otherformats: PPT PPSX PPS PPTM PPSM XAML POTM POTX OTP POWERPOINT SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XSLFO sang ODP trên Android qua Java" h2="Chuyển đổi XSLFO sang ODP trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> PowerPoint hoặc Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi XSLFO sang ODP bên trong các ứng dụng Android của mình bằng hai bước đơn giản. Trong bước đầu tiên, bạn có thể xuất XSLFO sang PPTX bằng cách sử dụng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Sau đó, bằng cách sử dụng [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), bạn có thể chuyển đổi PPTX sang ODP. Cả hai API đều nằm trong gói [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất XSLFO sang ODP" %}}
1. Mở tệp XSLFO bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi XSLFO sang PPTX bằng phương pháp [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng ODP bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Odp` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Slides cho Android qua Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Mở tệp XSLFO được bảo vệ bằng mật khẩu trong Android qua Java" %}}
Trong khi tải định dạng tệp XSLFO, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tạo hình ảnh thu nhỏ của tệp ODP trong ứng dụng Android" %}}
Sau khi chuyển đổi XSLFO sang ODP, bạn cũng có thể tạo hình ảnh thu nhỏ của tài liệu đầu ra của mình. Bằng cách sử dụng tính năng phong phú [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), bạn có thể tạo hình ảnh thu nhỏ của các trang trình bày bằng cách tạo và phiên bản của [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) lớp. Sau đó, bạn có thể lấy tham chiếu của bất kỳ trang trình bày mong muốn nào bằng cách sử dụng ID hoặc chỉ mục của nó và lấy hình ảnh thu nhỏ của trang trình bày được tham chiếu trên một tỷ lệ cụ thể.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}