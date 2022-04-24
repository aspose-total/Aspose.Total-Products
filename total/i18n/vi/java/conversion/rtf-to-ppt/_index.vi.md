---
title: Chuyển đổi RTF sang PPT qua Java
description: Java API để xuất RTF sang PPT mà không cần sử dụng Microsoft Word hoặc PowerPoint
url: /vi/java/conversion/rtf-to-ppt/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: PPT
otherformats: POT PPT POWERPOINT PPTX PPS POTM POTX PPTM PPSX PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi RTF sang PPT qua Java" h2="Chuyển đổi RTF sang PPT bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Microsoft <sup> & reg; </sup> PowerPoint hoặc Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Thông thường, các nhà phát triển phải chuyển đổi tệp RTF sang PPT theo chương trình. Bằng cách sử dụng các thư viện Java Tự động hóa Tệp [Aspose.Total cho Java](https://products.aspose.com/total/java/), bạn có thể tự động hóa quá trình kết xuất trong một vài bước đơn giản. Bạn có thể tải tệp RTF của mình bằng cách sử dụng [Aspose.Words dành cho Java](https://products.aspose.com/words/java/) và chuyển đổi nó sang HTML. Sau đó, bằng cách sử dụng Java API thao tác mạnh mẽ trên PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể tạo một Bản trình bày mới, viết nội dung HTML trong đó và lưu dưới dạng PPT .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển RTF sang PPT qua Java" %}}
1. Mở tệp RTF bằng lớp [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Chuyển đổi tệp RTF sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save (java.lang.String, com.aspose.words.SaveOptions )) phương pháp
3. Khởi tạo đối tượng [Bản trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) mới
5. Trích xuất nội dung từ tệp HTML bằng BufferedReader và ghi nội dung vào tệp bản trình bày của bạn
6. Lưu tài liệu vào PPT bằng phương thức [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp RTF sang PPT, bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose / aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
API cũng cho phép bạn chuyển đổi các tài liệu RTF được bảo vệ bằng mật khẩu sang PPT. Nếu tài liệu RTF đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng PPT mà không sử dụng mật khẩu. Để mở một tài liệu được mã hóa, bạn có thể đặt mật khẩu chính xác trong đối tượng LoadOptions và chuyển nó đến phương thức khởi tạo Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-ppsm/" name="RTF Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-pot/" name="RTF Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-powerpoint/" name="RTF Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-pptx/" name="RTF Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-potx/" name="RTF Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-pptm/" name="RTF Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-potm/" name="RTF Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-pps/" name="RTF Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-ppsx/" name="RTF Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-ppt/" name="RTF Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-csv/" name="RTF Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-dif/" name="RTF Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-fods/" name="RTF Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-ods/" name="RTF Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-sxc/" name="RTF Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-tsv/" name="RTF Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xlam/" name="RTF Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xltm/" name="RTF Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-excel/" name="RTF Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xls/" name="RTF Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xlsb/" name="RTF Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xlsm/" name="RTF Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xlsx/" name="RTF Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xlt/" name="RTF Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xltm/" name="RTF Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/rtf-to-xltx/" name="RTF Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}