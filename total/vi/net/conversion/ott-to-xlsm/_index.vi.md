---
title: .NET API để chuyển đổi OTT sang XLSM
description: C# API để chuyển đổi OTT sang XLSM mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/ott-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSM
otherformats: XLT XLSX XLSB DIF XLS ODS TSV FODS XLSM XLTM EXCEL XLTX XLAM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API để chuyển đổi OTT sang XLSM" h2="Xuất OTT sang XLSM qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể bao gồm tính năng chuyển đổi OTT sang XLSM trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất OTT sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi OTT sang XLSM" %}}
1. Mở tệp OTT bằng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Chuyển đổi OTT sang HTML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng XLSM bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `XLSM` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Tải tài liệu OTT từ Luồng qua C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) cũng cho phép bạn tải tài liệu OTT qua luồng. Để mở tài liệu từ luồng, chỉ cần chuyển đối tượng luồng có chứa tài liệu vào phương thức khởi tạo [Document](https://reference.aspose.com/words/net/aspose.words/document). Ví dụ mã sau đây cho thấy cách mở một tài liệu từ một luồng:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm thuộc tính tùy chỉnh trong tệp XLSM qua C#" %}}
Trong khi chuyển đổi OTT sang XLSM, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) cho phép bạn thêm các thuộc tính tùy chỉnh trong tài liệu XLSM của mình. Để thêm thuộc tính tùy chỉnh, bạn có thể sử dụng phương thức [Thêm](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) cho phương thức [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) lớp. Phương thức Thêm sẽ thêm thuộc tính vào tệp Excel và trả về một tham chiếu cho thuộc tính tài liệu mới dưới dạng [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) đối tượng. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-dif/" name="OTT Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xlsb/" name="OTT Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-tsv/" name="OTT Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-fods/" name="OTT Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xlt/" name="OTT Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-excel/" name="OTT Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xlsx/" name="OTT Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-ods/" name="OTT Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-sxc/" name="OTT Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xlam/" name="OTT Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xltm/" name="OTT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xlsm/" name="OTT Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xls/" name="OTT Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ott-to-xltx/" name="OTT Đến XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}