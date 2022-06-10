---
title: Chuyển đổi XLSB sang PPTX với .NET 
description: Chuyển đổi XLSB sang PPTX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin
url: /vi/net/conversion/xlsb-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: POWERPOINT WORD DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi XLSB sang PPTX qua C#" h2="Xuất Excel & reg; XLSB sang PPTX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLSB sang PPTX trên .NET" %}}
1. Mở tệp XLSB bằng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Chuyển đổi XLSB sang PDF và đặt SaveFormat thành Tự động
3. Tải tệp PDF đã chuyển đổi bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Lưu tài liệu sang định dạng PPTX bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) và đặt Pptx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code cho chuyển đổi XLSB sang PPTX" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-word/" name="CSV Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-powerpoint/" name="CSV Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-pptx/" name="CSV Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-docx/" name="CSV Đến DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}