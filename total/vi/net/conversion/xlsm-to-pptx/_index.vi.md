---
title: Chuyển đổi XLSM sang PPTX với .NET hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Chuyển đổi XLSM sang PPTX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã.

family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: DOC POWERPOINT DOCX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Chuyển đổi XLSM sang PPTX qua C# hoặc Ứng dụng trực tuyến" h2="Xuất Excel & reg; XLSM sang PPTX trên Nền tảng .NET Framework, .NET Core, Mono hoặc Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLSM sang PPTX trên .NET" %}}
1. Mở tệp XLSM bằng lớp [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Chuyển đổi XLSM sang PDF và đặt SaveFormat thành Tự động
3. Tải tệp PDF đã chuyển đổi bằng lớp [Tài liệu](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Lưu tài liệu sang định dạng PPTX bằng phương pháp [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) và đặt Pptx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code cho chuyển đổi XLSM sang PPTX" gistPath="" %}}
```cs
// load the XLSM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsm");
// save XLSM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho XLSM sang PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}