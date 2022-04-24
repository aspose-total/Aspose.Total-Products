---
title: Chuyển đổi định dạng DOC sang JSON qua .NET
description: Chuyển đổi DOC sang JSON trong C# mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/net/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: CSV XLAM SXC TSV XLT EXCEL DIF XLSM XLTM XLSX XLSB FODS ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng DOC sang JSON qua C#" h2="Phân tích cú pháp DOC thành JSON qua C# mà không sử dụng Microsoft <sup> & reg; </sup> Word hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể chuyển đổi định dạng DOC sang JSON trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. các bước đơn giản. Thứ nhất, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể xuất DOC sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng DOC sang JSON qua C#" %}}
1. Mở tệp DOC bằng lớp [Document](https://apireference.aspose.com/words/net/aspose.words/document)
2. Chuyển đổi DOC sang HTML bằng phương pháp [Lưu](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng JSON bằng phương pháp [Lưu](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOC được bảo vệ sang định dạng JSON qua C#" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu DOC đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions. Ví dụ mã sau đây cho thấy cách thử mở tài liệu được mã hóa bằng mật khẩu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOC sang JSON trong Range thông qua C#" %}}
Trong khi chuyển đổi DOC sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để thiết lập phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, lấy CellsCollection của Worksheet chứa dữ liệu, tạo một phạm vi từ CellsCollection bằng cách chỉ định các chỉ số hàng & cột và gọi phương thức ExportRangeToJson với các tham chiếu đến các đối tượng Range & ExportRangeToJsonOptions. Cuối cùng, bạn có thể lưu dữ liệu JSON vào tệp thông qua phương thức File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-csv/" name="DOC Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlam/" name="DOC Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-sxc/" name="DOC Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-tsv/" name="DOC Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlt/" name="DOC Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-excel/" name="DOC Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-dif/" name="DOC Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsm/" name="DOC Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltm/" name="DOC Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsx/" name="DOC Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsb/" name="DOC Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-fods/" name="DOC Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ods/" name="DOC Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltx/" name="DOC Đến XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}