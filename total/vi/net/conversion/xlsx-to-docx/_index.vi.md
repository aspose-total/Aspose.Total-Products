---
title: Chuyển đổi XLSX sang DOCX với .NET 
description: Chuyển đổi XLSX sang DOCX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin

family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi XLSX sang DOCX qua C#" h2="Xuất Excel & reg; XLSX sang DOCX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLSX sang DOCX trên .NET" %}}
1. Mở tệp XLSX bằng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Chuyển đổi XLSX sang PDF và đặt SaveFormat thành Tự động
3. Tải tệp PDF đã chuyển đổi bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Lưu tài liệu sang định dạng DOCX bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) và đặt Docx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code cho chuyển đổi XLSX sang DOCX" gistPath="" %}}
```cs
// load the XLSX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsx");
// save XLSX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
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