---
title: Chuyển đổi PDF sang MD thông qua API C#
description: C# API để chuyển đổi tệp PDF sang MD mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/net/conversion/pdf-to-md/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MD
otherformats: XLSB TXT TSV XLAM SXC MD XLT DIF FODS EXCEL XLSM XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị PDF sang MD" h2="Xuất tệp PDF sang MD qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp PDF sang MD trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất PDF sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi PDF sang MD" %}}
1. Mở tệp PDF bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi PDF sang XLSX bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng MD bằng phương pháp [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Md` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF được bảo vệ sang MD qua C#" %}}
Nếu tài liệu PDF của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành MD mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PDF sang MD với Watermark qua C#" %}}
Trong khi chuyển đổi tệp PDF sang MD, bạn cũng có thể thêm hình mờ vào định dạng tệp MD đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng MD với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-sxc/" name="PDF Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xltx/" name="PDF Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-md/" name="PDF Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-tsv/" name="PDF Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-txt/" name="PDF Đến TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-ods/" name="PDF Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xlt/" name="PDF Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xlsm/" name="PDF Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xlam/" name="PDF Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xltm/" name="PDF Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-dif/" name="PDF Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/pdf-to-xlsb/" name="PDF Đến XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}