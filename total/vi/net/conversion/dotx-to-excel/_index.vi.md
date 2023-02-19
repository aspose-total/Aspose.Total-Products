---
title: .NET API để chuyển đổi DOTX sang EXCEL
description: C# API để chuyển đổi DOTX sang EXCEL mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/dotx-to-excel/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLSX
otherformats: XLAM ODS TSV XLT FODS EXCEL DIF XLTM XLS SXC XLSM XLSB EXCEL XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API để chuyển đổi DOTX sang EXCEL" h2="Xuất DOTX sang EXCEL qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể bao gồm tính năng chuyển đổi DOTX sang EXCEL trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất DOTX sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi DOTX sang EXCEL" %}}
1. Mở tệp DOTX bằng lớp [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. Chuyển đổi DOTX sang HTML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng EXCEL bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `EXCEL` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho DOTX sang EXCEL</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlsx&from=dotx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu DOTX từ Luồng qua C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) cũng cho phép bạn tải tài liệu DOTX qua luồng. Để mở tài liệu từ luồng, chỉ cần chuyển đối tượng luồng có chứa tài liệu vào phương thức khởi tạo [Document](https://reference.aspose.com/words/net/aspose.words/Document). Ví dụ mã sau đây cho thấy cách mở một tài liệu từ một luồng:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm thuộc tính tùy chỉnh trong tệp EXCEL qua C#" %}}
Trong khi chuyển đổi DOTX sang EXCEL, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) cho phép bạn thêm các thuộc tính tùy chỉnh trong tài liệu EXCEL của mình. Để thêm thuộc tính tùy chỉnh, bạn có thể sử dụng phương thức [Thêm](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) cho phương thức [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) lớp. Phương thức Thêm sẽ thêm thuộc tính vào tệp Excel và trả về một tham chiếu cho thuộc tính tài liệu mới dưới dạng [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/Documentproperty) đối tượng. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-dif/" name="DOTX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsb/" name="DOTX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-tsv/" name="DOTX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-fods/" name="DOTX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlt/" name="DOTX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-excel/" name="DOTX Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsx/" name="DOTX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-ods/" name="DOTX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-sxc/" name="DOTX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlam/" name="DOTX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xltm/" name="DOTX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xlsm/" name="DOTX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xls/" name="DOTX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotx-to-xltx/" name="DOTX Đến XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}