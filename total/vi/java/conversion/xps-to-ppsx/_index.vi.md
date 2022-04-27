---
title: Chuyển đổi XPS sang PPSX thông qua Java API
description: Java API để chuyển đổi XPS sang PPSX mà không cần sử dụng Microsoft Word
url: /vi/java/conversion/xps-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: PPSX
otherformats: PPSM PPTM OTP PPT SWF XAML POTX POT PPS PPSX POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất XPS sang PPSX" h2="Xuất XPS sang PPSX thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total cho Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi XPS sang PPSX trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF dành cho Java](https://products.aspose.com/pdf/java/), bạn có thể xuất XPS sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi XPS sang PPSX" %}}
1. Mở tệp XPS bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi XPS sang PPTX bằng phương pháp [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng PPSX bằng phương thức [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Ppsx` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm [Aspose.PDF dành cho Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Slides dành cho Java](https://docs.aspose.com/slides/java/ cài đặt /) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}](](
Trong khi tải định dạng tệp XPS, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF dành cho Java](https://products.aspose.com/pdf/java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Tài liệu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}](](](](
{{% blocks/products/pf/feature-page-section  h2="Mở tệp XPS được mã hóa qua Java" %}}
Sau khi chuyển đổi XPS sang PPSX, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides dành cho Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-pps/" name="XPS Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-swf/" name="XPS Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-potx/" name="XPS Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-ppsx/" name="XPS Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-potm/" name="XPS Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-ppt/" name="XPS Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-ppsm/" name="XPS Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-xaml/" name="XPS Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-otp/" name="XPS Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-pptm/" name="XPS Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-pot/" name="XPS Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xps-to-powerpoint/" name="XPS Đến POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}