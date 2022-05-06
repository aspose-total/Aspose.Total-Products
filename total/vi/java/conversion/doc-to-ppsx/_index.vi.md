---
title: Chuyển đổi DOC sang PPSX qua Java
description: Java API để xuất DOC sang PPSX mà không cần sử dụng Microsoft Word hoặc PowerPoint
url_ignore: /vi/java/conversion/doc-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: PPSX
otherformats: POWERPOINT PPS PPTM PPT PPSM POTM PPTX POT POTX PPSX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi DOC sang PPSX qua Java" h2="Chuyển đổi DOC sang PPSX bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Thông thường, các nhà phát triển phải chuyển đổi tệp DOC sang PPSX theo chương trình. Bằng cách sử dụng các thư viện Java Tự động hóa Tệp [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tự động hóa quá trình kết xuất trong một vài bước đơn giản. Bạn có thể tải tệp DOC của mình bằng cách sử dụng [Aspose.Words for Java](https://products.aspose.com/words/java/) và chuyển đổi nó sang HTML. Sau đó, bằng cách sử dụng Java API thao tác mạnh mẽ trên PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể tạo một Bản trình bày mới, viết nội dung HTML trong đó và lưu dưới dạng PPSX .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển DOC sang PPSX qua Java" %}}
1. Mở tệp DOC bằng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Chuyển đổi tệp DOC sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
3. Khởi tạo đối tượng [Bản trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) mới
5. Trích xuất nội dung từ tệp HTML bằng BufferedReader và ghi nội dung vào tệp bản trình bày của bạn
6. Lưu tài liệu vào PPSX bằng phương thức [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp DOC sang PPSX, bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
API cũng cho phép bạn chuyển đổi các tài liệu DOC được bảo vệ bằng mật khẩu sang PPSX. Nếu tài liệu DOC đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng PPSX mà không sử dụng mật khẩu. Để mở một tài liệu được mã hóa, bạn có thể đặt mật khẩu chính xác trong đối tượng LoadOptions và chuyển nó đến phương thức khởi tạo Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ppsm/" name="DOC Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-pot/" name="DOC Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-powerpoint/" name="DOC Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-pptx/" name="DOC Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-potx/" name="DOC Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-pptm/" name="DOC Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-potm/" name="DOC Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-pps/" name="DOC Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ppsx/" name="DOC Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ppt/" name="DOC Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-csv/" name="DOC Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-dif/" name="DOC Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-fods/" name="DOC Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ods/" name="DOC Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-sxc/" name="DOC Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-tsv/" name="DOC Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlam/" name="DOC Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltm/" name="DOC Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-excel/" name="DOC Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xls/" name="DOC Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsb/" name="DOC Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsm/" name="DOC Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsx/" name="DOC Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlt/" name="DOC Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltm/" name="DOC Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltx/" name="DOC Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}