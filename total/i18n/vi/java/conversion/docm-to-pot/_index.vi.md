---
title: Chuyển đổi DOCM sang POT qua Java
description: Java API để xuất DOCM sang POT mà không cần sử dụng Microsoft Word hoặc PowerPoint
url: /vi/java/conversion/docm-to-pot/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: POT
otherformats: POTX PPTX PPS POT PPSX PPSM POTM POWERPOINT PPT PPTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi DOCM sang POT qua Java" h2="Chuyển đổi DOCM sang POT bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Microsoft <sup> & reg; </sup> PowerPoint hoặc Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Thông thường, các nhà phát triển phải chuyển đổi tệp DOCM sang POT theo chương trình. Bằng cách sử dụng các thư viện Java Tự động hóa Tệp [Aspose.Total cho Java](https://products.aspose.com/total/java/), bạn có thể tự động hóa quá trình kết xuất trong một vài bước đơn giản. Bạn có thể tải tệp DOCM của mình bằng cách sử dụng [Aspose.Words dành cho Java](https://products.aspose.com/words/java/) và chuyển đổi nó sang HTML. Sau đó, bằng cách sử dụng Java API thao tác mạnh mẽ trên PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể tạo một Bản trình bày mới, viết nội dung HTML trong đó và lưu dưới dạng POT .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển DOCM sang POT qua Java" %}}
1. Mở tệp DOCM bằng lớp [Docmument](https://apireference.aspose.com/words/java/com.aspose.words/Docmument)
2. Chuyển đổi tệp DOCM sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save (java.lang.String, com.aspose.words.SaveOptions )) phương pháp
3. Khởi tạo đối tượng [Bản trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) mới
5. Trích xuất nội dung từ tệp HTML bằng BufferedReader và ghi nội dung vào tệp bản trình bày của bạn
6. Lưu tài liệu vào POT bằng phương thức [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp DOCM sang POT, bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose / aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
API cũng cho phép bạn chuyển đổi các tài liệu DOCM được bảo vệ bằng mật khẩu sang POT. Nếu tài liệu DOCM đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng POT mà không sử dụng mật khẩu. Để mở một tài liệu được mã hóa, bạn có thể đặt mật khẩu chính xác trong đối tượng LoadOptions và chuyển nó đến phương thức khởi tạo Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-ppsm/" name="DOCM Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-pot/" name="DOCM Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-powerpoint/" name="DOCM Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-pptx/" name="DOCM Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-potx/" name="DOCM Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-pptm/" name="DOCM Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-potm/" name="DOCM Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-pps/" name="DOCM Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-ppsx/" name="DOCM Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-ppt/" name="DOCM Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-csv/" name="DOCM Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-dif/" name="DOCM Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-fods/" name="DOCM Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-ods/" name="DOCM Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-sxc/" name="DOCM Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-tsv/" name="DOCM Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xlam/" name="DOCM Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xltm/" name="DOCM Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-excel/" name="DOCM Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xls/" name="DOCM Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xlsb/" name="DOCM Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xlsm/" name="DOCM Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xlsx/" name="DOCM Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xlt/" name="DOCM Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xltm/" name="DOCM Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docm-to-xltx/" name="DOCM Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}