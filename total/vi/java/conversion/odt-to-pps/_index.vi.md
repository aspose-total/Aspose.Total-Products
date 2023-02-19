---
title: Chuyển đổi ODT sang PPS qua Java
description: Java API để xuất ODT sang PPS mà không cần sử dụng Microsoft Word hoặc PowerPoint
url_ignore: /vi/java/conversion/odt-to-pps/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: PPS
otherformats: POTX POTM PPT POT PPTM PPTX PPSX PPS PPSM POWERPOINT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi ODT sang PPS qua Java" h2="Chuyển đổi ODT sang PPS bằng cách sử dụng API Java tiền đề trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint hoặc Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Thông thường, các nhà phát triển phải chuyển đổi tệp ODT sang PPS theo chương trình. Bằng cách sử dụng các thư viện Java Tự động hóa Tệp [Aspose.Total for Java](https://products.aspose.com/total/java/), bạn có thể tự động hóa quá trình kết xuất trong một vài bước đơn giản. Bạn có thể tải tệp ODT của mình bằng cách sử dụng [Aspose.Words for Java](https://products.aspose.com/words/java/) và chuyển đổi nó sang HTML. Sau đó, bằng cách sử dụng Java API thao tác mạnh mẽ trên PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), bạn có thể tạo một Bản trình bày mới, viết nội dung HTML trong đó và lưu dưới dạng PPS .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển ODT sang PPS qua Java" %}}
1. Mở tệp ODT bằng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Chuyển đổi tệp ODT sang HTML bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String, com.aspose.words.SaveOptions)) phương pháp
3. Khởi tạo đối tượng [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) mới
5. Trích xuất nội dung từ tệp HTML bằng BufferedReader và ghi nội dung vào tệp bản trình bày của bạn
6. Lưu tài liệu vào PPS bằng phương thức [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Để chuyển đổi tệp ODT sang PPS, bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) dựa trên dự án và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho ODT sang PPS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pps&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
API cũng cho phép bạn chuyển đổi các tài liệu ODT được bảo vệ bằng mật khẩu sang PPS. Nếu tài liệu ODT đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng PPS mà không sử dụng mật khẩu. Để mở một tài liệu được mã hóa, bạn có thể đặt mật khẩu chính xác trong đối tượng LoadOptions và chuyển nó đến phương thức khởi tạo Tài liệu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-ppsm/" name="ODT Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-pot/" name="ODT Đến POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-powerpoint/" name="ODT Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-pptx/" name="ODT Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-potx/" name="ODT Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-pptm/" name="ODT Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-potm/" name="ODT Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-pps/" name="ODT Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-ppsx/" name="ODT Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-ppt/" name="ODT Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-csv/" name="ODT Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-dif/" name="ODT Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-fods/" name="ODT Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-ods/" name="ODT Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-sxc/" name="ODT Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-tsv/" name="ODT Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xlam/" name="ODT Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xltm/" name="ODT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-excel/" name="ODT Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xls/" name="ODT Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xlsb/" name="ODT Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xlsm/" name="ODT Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xlsx/" name="ODT Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xlt/" name="ODT Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xltm/" name="ODT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/odt-to-xltx/" name="ODT Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}