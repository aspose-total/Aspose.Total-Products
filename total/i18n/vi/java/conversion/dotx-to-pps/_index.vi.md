---
title: Chuyển đổi DOTX sang PPS qua Java
description: Java API để xuất DOTX sang PPS mà không cần sử dụng Microsoft Word hoặc PowerPoint
url: /vi/java/conversion/dotx-to-pps/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: PPS
otherformats: PPTM PPSM PPSX POT POTM PPTX POWERPOINT POTX PPT PPS CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi DOTX sang PPS qua Java" h2="Chuyển đổi DOTX sang PPS bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Microsoft <sup> & reg; </sup> PowerPoint hoặc Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Thông thường, các nhà phát triển phải chuyển đổi tệp DOTX sang PPS theo chương trình. Bằng cách sử dụng các thư viện Java Tự động hóa Tệp [Aspose.Total cho Java] (https://products.aspose.com/total/java/), bạn có thể tự động hóa quá trình kết xuất trong một vài bước đơn giản. Bạn có thể tải tệp DOTX của mình bằng cách sử dụng [Aspose.Words dành cho Java] (https://products.aspose.com/words/java/) và chuyển đổi nó sang HTML. Sau đó, bằng cách sử dụng Java API thao tác mạnh mẽ trên PowerPoint [Aspose.Slides for Java] (https://products.aspose.com/slides/java/), bạn có thể tạo một Bản trình bày mới, viết nội dung HTML trong đó và lưu dưới dạng PPS .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển DOTX sang PPS qua Java" %}}
1. Mở tệp DOTX bằng lớp [Dotxument] (https://apireference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Chuyển đổi tệp DOTX sang HTML bằng cách sử dụng [save] (https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#save (java.lang.String, com.aspose.words.SaveOptions )) phương pháp
3. Khởi tạo đối tượng [Bản trình bày] (https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) mới
5. Trích xuất nội dung từ tệp HTML bằng BufferedReader và ghi nội dung vào tệp bản trình bày của bạn
6. Lưu tài liệu vào PPS bằng phương thức [save] (https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp DOTX sang PPS, bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose / aspose-total) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dotx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
API cũng cho phép bạn chuyển đổi các tài liệu DOTX được bảo vệ bằng mật khẩu sang PPS. Nếu tài liệu DOTX đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng PPS mà không sử dụng mật khẩu. Để mở một tài liệu được mã hóa, bạn có thể đặt mật khẩu chính xác trong đối tượng LoadOptions và chuyển nó đến phương thức khởi tạo Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dotx-to-pptx.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-ppsm/" name="DOTX Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-pot/" name="DOTX Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-powerpoint/" name="DOTX Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-pptx/" name="DOTX Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-potx/" name="DOTX Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-pptm/" name="DOTX Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-potm/" name="DOTX Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-pps/" name="DOTX Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-ppsx/" name="DOTX Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-ppt/" name="DOTX Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-csv/" name="DOTX Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-dif/" name="DOTX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-fods/" name="DOTX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-ods/" name="DOTX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-sxc/" name="DOTX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-tsv/" name="DOTX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlam/" name="DOTX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xltm/" name="DOTX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-excel/" name="DOTX Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xls/" name="DOTX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsb/" name="DOTX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsm/" name="DOTX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsx/" name="DOTX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlt/" name="DOTX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xltm/" name="DOTX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xltx/" name="DOTX Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}