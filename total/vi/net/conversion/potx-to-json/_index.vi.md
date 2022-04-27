---
title: Chuyển đổi định dạng POTX sang JSON qua .NET
description: Chuyển đổi POTX sang JSON trong C# mà không cần sử dụng Microsoft Excel hoặc Powerpoint
url: /vi/net/conversion/potx-to-json/
family: total
platformtag: net
feature: conversion
informat: POTX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng POTX sang JSON qua C#" h2="Xuất POTX sang JSON qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể chuyển đổi định dạng POTX sang JSON trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. các bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể xuất POTX sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng POTX sang JSON qua C#" %}}
1. Mở tệp POTX bằng lớp [Trình bày](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
2. Chuyển đổi POTX sang HTML bằng phương pháp [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng JSON bằng phương pháp [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POTX được bảo vệ sang định dạng JSON qua C#" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu POTX đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions. Ví dụ mã sau đây cho thấy cách mở một tài liệu được mã hóa bằng mật khẩu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POTX sang JSON trong Phạm vi thông qua C#" %}}
Trong khi chuyển đổi POTX sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để thiết lập phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, lấy CellsCollection của Worksheet chứa dữ liệu, tạo một phạm vi từ CellsCollection bằng cách chỉ định các chỉ số hàng & cột và gọi phương thức ExportRangeToJson với các tham chiếu đến các đối tượng Range & ExportRangeToJsonOptions. Cuối cùng, bạn có thể lưu dữ liệu JSON vào tệp thông qua phương thức File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-doc/" name="POTX Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docm/" name="POTX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-docx/" name="POTX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dot/" name="POTX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotm/" name="POTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-dotx/" name="POTX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-odt/" name="POTX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-ott/" name="POTX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-rtf/" name="POTX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-text/" name="POTX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-word/" name="POTX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/potx-to-wordml/" name="POTX Đến WORDML" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}