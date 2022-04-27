---
title: Chuyển đổi POTX sang DOCM qua Java
description: Java API để xuất POTX sang DOCM mà không cần sử dụng Microsoft Word hoặc PowerPoint
url: /vi/java/conversion/potx-to-docm/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: DOCMM
otherformats: TEXT ODT DOCM WORD RTF FLATOPC DOTM DOCMX WORDML DOTX DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi POTX sang DOCM qua Java" h2="Trên Premise Java API cho PowerPoint chuyển đổi POTX sang DOCM trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total cho Java](https://products.aspose.com/total/java/) Thư viện tự động hóa định dạng tệp cho phép các nhà phát triển Java tự động hóa quá trình chuyển đổi hàng loạt PowerPoint POTX sang Word DOCM. Chuyển đổi tài liệu là một quá trình gồm hai bước và liên quan đến việc sử dụng hai API. Chúng tôi sẽ sử dụng [Aspose.Slides dành cho Java](https://products.aspose.com/slides/java/) là một API PowerPoint cho thao tác và quản lý bản trình bày để chuyển đổi POTX sang HTML. Sau đó, bằng cách sử dụng API xử lý văn bản giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), chúng tôi sẽ chuyển đổi HTML thành DOCM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển POTX sang DOCM qua Java" %}}
1. Mở tệp POTX bằng lớp [Trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi POTX sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Phương thức ISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng DOCM bằng phương thức [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp POTX sang DOCM, bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}](
Sử dụng API, bạn cũng có thể thực hiện chuyển đổi tệp POTX sang DOCM với hình mờ. Để thêm hình mờ vào tài liệu DOCM, trước tiên bạn có thể chuyển đổi tệp POTX sang HTML và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp HTML mới được tạo bằng cách sử dụng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), tạo một bản sao của TextWatermarkOptions và đặt thuộc tính của nó, Gọi phương thức Watermark.setText và chuyển văn bản & đối tượng hình mờ của TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-word/" name="POTX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotx/" name="POTX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-odt/" name="POTX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-ott/" name="POTX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-rtf/" name="POTX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-flatopc/" name="POTX Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-wordml/" name="POTX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docmm/" name="POTX Đến DOCMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-text/" name="POTX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docmx/" name="POTX Đến DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotm/" name="POTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dot/" name="POTX Đến DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}