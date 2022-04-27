---
title: .NET API để chuyển đổi WORD sang TSV
description: C# API để chuyển đổi WORD sang TSV mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/net/conversion/word-to-tsv/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: TSV
otherformats: XLSX XLT SXC XLTM XLTX DIF FODS TSV XLS XLSM ODS XLSB XLAM EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API để chuyển đổi WORD sang TSV" h2="Xuất WORD sang TSV qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể bao gồm tính năng chuyển đổi WORD sang TSV trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất WORD sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang TSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi WORD sang TSV" %}}
1. Mở tệp WORD bằng lớp [Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument)
2. Chuyển đổi WORD sang HTML bằng phương pháp [Save](https://apireference.aspose.com/words/net/aspose.words.wordument/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng TSV bằng phương pháp [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `TSV` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu WORD từ Luồng qua C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) cũng cho phép bạn tải tài liệu WORD qua luồng. Để mở tài liệu từ luồng, chỉ cần chuyển đối tượng luồng có chứa tài liệu vào phương thức khởi tạo [Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument). Ví dụ mã sau đây cho thấy cách mở một tài liệu từ một luồng:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm thuộc tính tùy chỉnh trong tệp TSV qua C#" %}}
Trong khi chuyển đổi WORD sang TSV, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) cho phép bạn thêm các thuộc tính tùy chỉnh trong tài liệu TSV của mình. Để thêm thuộc tính tùy chỉnh, bạn có thể sử dụng phương thức [Thêm](https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordumentpropertycollection/methods/add/index) cho phương thức [CustomWordumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordumentpropertycollection) lớp. Phương thức Thêm sẽ thêm thuộc tính vào tệp Excel và trả về một tham chiếu cho thuộc tính tài liệu mới dưới dạng [Aspose.Cells.Properties.WordumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/wordumentproperty) đối tượng. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-dif/" name="WORD Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xlsb/" name="WORD Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-tsv/" name="WORD Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-fods/" name="WORD Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xlt/" name="WORD Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-excel/" name="WORD Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xlsx/" name="WORD Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-ods/" name="WORD Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-sxc/" name="WORD Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xlam/" name="WORD Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xltm/" name="WORD Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xlsm/" name="WORD Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xls/" name="WORD Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/word-to-xltx/" name="WORD Đến XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}