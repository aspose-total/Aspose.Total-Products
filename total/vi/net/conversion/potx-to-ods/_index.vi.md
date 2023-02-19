---
title: Chuyển đổi POTX sang ODS qua C#
description: Chuyển đổi POTX sang ODS trong C# mà không cần sử dụng Microsoft Excel hoặc Powerpoint
url_ignore: /vi/net/conversion/potx-to-ods/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: ODS
otherformats: XLTM TSV XLAM MARKDOWN XLTX FODS XLS XLT ODS MHTML SXC DIF XLSX EXCEL XLSB XLSM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi POTX sang ODS qua C#" h2=".NET API để chuyển đổi POTX sang ODS mà không cần sử dụng Microsoft<sup>&reg;</sup> Excel hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể chuyển đổi tệp POTX thành ODS trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai ứng dụng các bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể xuất POTX sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi POTX sang ODS qua C#" %}}
1. Mở tệp POTX bằng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Xuất POTX dưới dạng HTML bằng cách sử dụng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu vào ODS bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho POTX sang ODS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ods&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POTX được bảo vệ sang ODS qua C#" %}}
Trong khi chuyển đổi tệp POTX sang ODS, nếu tài liệu POTX đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành ODS mà không giải mã tài liệu. Khi tài liệu của bạn được bảo vệ bằng mật khẩu, điều đó có nghĩa là nó thực thi các hạn chế nhất định đối với bản trình bày. Để loại bỏ các hạn chế, mật khẩu phải được nhập. Bản trình bày được bảo vệ bằng mật khẩu được coi là bản trình bày bị khóa. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POTX sang ODS với Watermark qua C#" %}}
Trong khi chuyển đổi tệp POTX sang ODS, bạn cũng có thể thêm hình mờ vào định dạng tệp ODS đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Sổ làm việc mới và mở tài liệu HTML đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu HTML của mình dưới dạng ODS với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-fods/" name="POTX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xltm/" name="POTX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xlt/" name="POTX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xlam/" name="POTX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-markdown/" name="POTX Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-excel/" name="POTX Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-mhtml/" name="POTX Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xlsb/" name="POTX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-ods/" name="POTX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-sxc/" name="POTX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xls/" name="POTX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xltx/" name="POTX Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xlsx/" name="POTX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-tsv/" name="POTX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dif/" name="POTX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-xlsm/" name="POTX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-doc/" name="POTX Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docx/" name="POTX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docm/" name="POTX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dot/" name="POTX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotm/" name="POTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotx/" name="POTX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-odt/" name="POTX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-ott/" name="POTX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-rtf/" name="POTX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-word/" name="POTX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-wordml/" name="POTX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-text/" name="POTX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-flatopx/" name="POTX Đến FLAĐếnPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}