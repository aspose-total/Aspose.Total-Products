---
title: Chuyển đổi XML sang SWF thông qua Java API
description: Java API để chuyển đổi XML sang SWF mà không cần sử dụng Microsoft Word
url: /vi/java/conversion/xml-to-swf/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: SWF
otherformats: POTX PPSM POWERPOINT SWF POTM OTP POT XAML PPSX PPT PPS PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API để xuất XML sang SWF" h2="Xuất XML sang SWF thông qua API Java tại chỗ mà không sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total cho Java](https://products.aspose.com/total/java/), bạn có thể dễ dàng chuyển đổi XML sang SWF trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF dành cho Java](https://products.aspose.com/pdf/java/), bạn có thể xuất XML sang PPTX. Sau đó, bằng cách sử dụng API xử lý PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể chuyển đổi PPTX thành SWF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi XML sang SWF" %}}
1. Mở tệp XML bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi XML sang PPTX bằng phương pháp [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Lưu tài liệu sang định dạng SWF bằng phương thức [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) và đặt ` Swf` dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm [Aspose.PDF dành cho Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Slides dành cho Java](https://docs.aspose.com/slides/java/ cài đặt /) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}](](
Trong khi tải định dạng tệp XML, tài liệu của bạn có thể được bảo vệ bằng mật khẩu. [Aspose.PDF dành cho Java](https://products.aspose.com/pdf/java/) cũng cho phép bạn mở các tài liệu được mã hóa. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của [Tài liệu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}](](](](
{{% blocks/products/pf/feature-page-section  h2="Mở tệp XML được mã hóa qua Java" %}}
Sau khi chuyển đổi XML sang SWF, bạn cũng có thể thêm kiểu xem được xác định trước cho bản trình bày của mình. [Aspose.Slides dành cho Java](https://products.aspose.com/slides/java/) cung cấp một phương tiện để đặt kiểu xem cho bản trình bày đã tạo khi nó được mở trong PowerPoint thông qua [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) lớp. Thuộc tính [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) được sử dụng để đặt loại chế độ xem bằng cách sử dụng [ViewType](https:/điều tra viên /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-pps/" name="XML Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-swf/" name="XML Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-potx/" name="XML Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-ppsx/" name="XML Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-potm/" name="XML Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-ppt/" name="XML Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-ppsm/" name="XML Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-xaml/" name="XML Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-otp/" name="XML Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-pptm/" name="XML Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-pot/" name="XML Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/xml-to-powerpoint/" name="XML Đến POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}