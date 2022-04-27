---
title: .NET API để chuyển đổi DOTX sang XLAM
description: C# API để chuyển đổi DOTX sang XLAM mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/net/conversion/dotx-to-xlam/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLAM
otherformats: XLSB XLTM SXC TSV DIF XLTX XLAM EXCEL XLSM FODS XLSX XLT XLS ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API để chuyển đổi DOTX sang XLAM" h2="Xuất DOTX sang XLAM qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể bao gồm tính năng chuyển đổi DOTX sang XLAM trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất DOTX sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi DOTX sang XLAM" %}}
1. Mở tệp DOTX bằng lớp [Dotxument](https://apireference.aspose.com/words/net/aspose.words/dotxument)
2. Chuyển đổi DOTX sang HTML bằng phương pháp [Save](https://apireference.aspose.com/words/net/aspose.words.dotxument/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng XLAM bằng phương pháp [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `XLAM` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu DOTX từ Luồng qua C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) cũng cho phép bạn tải tài liệu DOTX qua luồng. Để mở tài liệu từ luồng, chỉ cần chuyển đối tượng luồng có chứa tài liệu vào phương thức khởi tạo [Dotxument](https://apireference.aspose.com/words/net/aspose.words/dotxument). Ví dụ mã sau đây cho thấy cách mở một tài liệu từ một luồng:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm thuộc tính tùy chỉnh trong tệp XLAM qua C#" %}}
Trong khi chuyển đổi DOTX sang XLAM, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) cho phép bạn thêm các thuộc tính tùy chỉnh trong tài liệu XLAM của mình. Để thêm thuộc tính tùy chỉnh, bạn có thể sử dụng phương thức [Thêm](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection/methods/add/index) cho phương thức [CustomDotxumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection) lớp. Phương thức Thêm sẽ thêm thuộc tính vào tệp Excel và trả về một tham chiếu cho thuộc tính tài liệu mới dưới dạng [Aspose.Cells.Properties.DotxumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/dotxumentproperty) đối tượng. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

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