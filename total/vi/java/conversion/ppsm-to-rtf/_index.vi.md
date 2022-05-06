---
title: Chuyển đổi PPSM sang RTF qua Java
description: Java API để xuất PPSM sang RTF mà không cần sử dụng Microsoft Word hoặc PowerPoint
url_ignore: /vi/java/conversion/ppsm-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: RTF
otherformats: RTFX RTFM TEXT OTT WORDML DOTX WORD RTF ODT FLATOPC DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi PPSM sang RTF qua Java" h2="Trên Premise Java API cho PowerPoint chuyển đổi PPSM sang RTF trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Thư viện tự động hóa định dạng tệp cho phép các nhà phát triển Java tự động hóa quá trình chuyển đổi hàng loạt PowerPoint PPSM sang Word RTF. Chuyển đổi tài liệu là một quá trình gồm hai bước và liên quan đến việc sử dụng hai API. Chúng tôi sẽ sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/) là một API PowerPoint cho thao tác và quản lý bản trình bày để chuyển đổi PPSM sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), chúng tôi sẽ chuyển đổi HTML thành RTF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển PPSM sang RTF qua Java" %}}
1. Mở tệp PPSM bằng lớp [Trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPSM sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Phương thức ISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng RTF bằng phương thức [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp PPSM sang RTF, bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể thực hiện chuyển đổi tệp PPSM sang RTF với hình mờ. Để thêm hình mờ vào tài liệu RTF, trước tiên bạn có thể chuyển đổi tệp PPSM sang HTML và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp HTML mới được tạo bằng cách sử dụng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), tạo một bản sao của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-word/" name="PPSM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-dotx/" name="PPSM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-odt/" name="PPSM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-ott/" name="PPSM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-rtf/" name="PPSM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-flatopc/" name="PPSM Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-wordml/" name="PPSM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-rtfm/" name="PPSM Đến RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-text/" name="PPSM Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-rtfx/" name="PPSM Đến RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-dotm/" name="PPSM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsm-to-dot/" name="PPSM Đến DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}