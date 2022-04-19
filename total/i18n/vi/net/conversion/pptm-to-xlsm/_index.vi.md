---
title: Chuyển đổi PPTM sang XLSM qua C #
description: Chuyển đổi PPTM sang XLSM trong C # mà không cần sử dụng Microsoft Excel hoặc Powerpoint
url: /vi/net/conversion/pptm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: XLSM
otherformats: EXCEL DIF XLTM MHTML XLSM XLSX XLS FODS XLTX TSV XLAM ODS SXC XLT XLSB MARKDOWN DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi PPTM sang XLSM qua C #" h2=".NET API để chuyển đổi PPTM sang XLSM mà không cần sử dụng Microsoft <sup> & reg; </sup> Excel hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total cho .NET] (https://products.aspose.com/total/net/), bạn có thể chuyển đổi tệp PPTM thành XLSM trong bất kỳ ứng dụng .NET, C #, ASP.NET và VB.NET nào trong hai ứng dụng các bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Slides cho .NET] (https://products.aspose.com/slides/net/), bạn có thể xuất PPTM sang HTML. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET] (https://products.aspose.com/cells/net/), bạn có thể chuyển đổi HTML sang XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi PPTM sang XLSM qua C #" %}}
1. Mở tệp PPTM bằng lớp [Trình bày] (https://apireference.aspose.com/slides/net/aspose.slides/presentation)
2. Xuất PPTM dưới dạng HTML bằng cách sử dụng phương pháp [Lưu] (https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook] (https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu vào XLSM bằng phương pháp [Lưu] (https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPTM được bảo vệ sang XLSM qua C #" %}}
Trong khi chuyển đổi tệp PPTM sang XLSM, nếu tài liệu PPTM đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành XLSM mà không giải mã tài liệu. Khi tài liệu của bạn được bảo vệ bằng mật khẩu, điều đó có nghĩa là nó thực thi các hạn chế nhất định đối với bản trình bày. Để loại bỏ các hạn chế, mật khẩu phải được nhập. Bản trình bày được bảo vệ bằng mật khẩu được coi là bản trình bày bị khóa. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPTM sang XLSM với Watermark qua C #" %}}
Trong khi chuyển đổi tệp PPTM sang XLSM, bạn cũng có thể thêm hình mờ vào định dạng tệp XLSM đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Sổ làm việc mới và mở tài liệu HTML đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu HTML của mình dưới dạng XLSM với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-fods/" name="PPTM Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xltm/" name="PPTM Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xlt/" name="PPTM Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xlam/" name="PPTM Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-markdown/" name="PPTM Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-excel/" name="PPTM Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-mhtml/" name="PPTM Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xlsb/" name="PPTM Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-ods/" name="PPTM Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-sxc/" name="PPTM Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xls/" name="PPTM Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xltx/" name="PPTM Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xlsx/" name="PPTM Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-tsv/" name="PPTM Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-dif/" name="PPTM Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-xlsm/" name="PPTM Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-doc/" name="PPTM Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-docx/" name="PPTM Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-docm/" name="PPTM Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-dot/" name="PPTM Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-dotm/" name="PPTM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-dotx/" name="PPTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-odt/" name="PPTM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-ott/" name="PPTM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-rtf/" name="PPTM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-word/" name="PPTM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-wordml/" name="PPTM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-text/" name="PPTM Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pptm-to-flatopx/" name="PPTM Đến FLAĐếnPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}