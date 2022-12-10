---
title: Chuyển đổi PPSX sang XLSM qua C#
description: Chuyển đổi PPSX sang XLSM trong C# mà không cần sử dụng Microsoft Excel hoặc Powerpoint
url_ignore: /vi/net/conversion/ppsx-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: XLSM
otherformats: DIF TSV XLS ODS EXCEL XLT MHTML XLSX XLTX MARKDOWN XLTM XLAM XLSB FODS SXC XLSM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi PPSX sang XLSM qua C#" h2=".NET API để chuyển đổi PPSX sang XLSM mà không cần sử dụng Microsoft<sup>&reg;</sup> Excel hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể chuyển đổi tệp PPSX thành XLSM trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai ứng dụng các bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể xuất PPSX sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi PPSX sang XLSM qua C#" %}}
1. Mở tệp PPSX bằng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Xuất PPSX dưới dạng HTML bằng cách sử dụng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu vào XLSM bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPSX được bảo vệ sang XLSM qua C#" %}}
Trong khi chuyển đổi tệp PPSX sang XLSM, nếu tài liệu PPSX đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành XLSM mà không giải mã tài liệu. Khi tài liệu của bạn được bảo vệ bằng mật khẩu, điều đó có nghĩa là nó thực thi các hạn chế nhất định đối với bản trình bày. Để loại bỏ các hạn chế, mật khẩu phải được nhập. Bản trình bày được bảo vệ bằng mật khẩu được coi là bản trình bày bị khóa. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPSX sang XLSM với Watermark qua C#" %}}
Trong khi chuyển đổi tệp PPSX sang XLSM, bạn cũng có thể thêm hình mờ vào định dạng tệp XLSM đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Sổ làm việc mới và mở tài liệu HTML đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu HTML của mình dưới dạng XLSM với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-fods/" name="PPSX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xltm/" name="PPSX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xlt/" name="PPSX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xlam/" name="PPSX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-markdown/" name="PPSX Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-excel/" name="PPSX Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-mhtml/" name="PPSX Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xlsb/" name="PPSX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-ods/" name="PPSX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-sxc/" name="PPSX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xls/" name="PPSX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xltx/" name="PPSX Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xlsx/" name="PPSX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-tsv/" name="PPSX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dif/" name="PPSX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-xlsm/" name="PPSX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-doc/" name="PPSX Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-docx/" name="PPSX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-docm/" name="PPSX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dot/" name="PPSX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dotm/" name="PPSX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dotx/" name="PPSX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-odt/" name="PPSX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-ott/" name="PPSX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-rtf/" name="PPSX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-word/" name="PPSX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-wordml/" name="PPSX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-text/" name="PPSX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-flatopx/" name="PPSX Đến FLAĐếnPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}