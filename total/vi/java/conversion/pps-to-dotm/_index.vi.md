---
title: Chuyển đổi PPS sang DOTM qua Java
description: Java API để xuất PPS sang DOTM mà không cần sử dụng Microsoft Word hoặc PowerPoint
url_ignore: /vi/java/conversion/pps-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: DOTM
otherformats: DOTM RTF ODT FLATOPC DOTMX WORDML TEXT DOTMM DOTX WORD DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi PPS sang DOTM qua Java" h2="Trên Premise Java API cho PowerPoint chuyển đổi PPS sang DOTM trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Thư viện tự động hóa định dạng tệp cho phép các nhà phát triển Java tự động hóa quá trình chuyển đổi hàng loạt PowerPoint PPS sang Word DOTM. Chuyển đổi tài liệu là một quá trình gồm hai bước và liên quan đến việc sử dụng hai API. Chúng tôi sẽ sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/) là một API PowerPoint cho thao tác và quản lý bản trình bày để chuyển đổi PPS sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), chúng tôi sẽ chuyển đổi HTML thành DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển PPS sang DOTM qua Java" %}}
1. Mở tệp PPS bằng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPS sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Phương thức ISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng lớp [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
4. Lưu tài liệu sang định dạng DOTM bằng phương thức [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp PPS sang DOTM, bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể thực hiện chuyển đổi tệp PPS sang DOTM với hình mờ. Để thêm hình mờ vào tài liệu DOTM, trước tiên bạn có thể chuyển đổi tệp PPS sang HTML và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp HTML mới được tạo bằng cách sử dụng lớp [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument), tạo một bản sao của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-word/" name="PPS Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-dotx/" name="PPS Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-odt/" name="PPS Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-ott/" name="PPS Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-rtf/" name="PPS Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-flatopc/" name="PPS Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-wordml/" name="PPS Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-dotmm/" name="PPS Đến DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-text/" name="PPS Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-dotmx/" name="PPS Đến DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-dotm/" name="PPS Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pps-to-dot/" name="PPS Đến DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}