---
title: Chuyển đổi XLS sang PPTX bằng C++
description: Chuyển đổi XLS sang PPTX trong các ứng dụng C++

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: DOCX DOC POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLS sang PPTX qua C++" h2="Xuất Excel <sup>&reg;</sup>; XLS sang PPTX trong các ứng dụng C++ đầy đủ chức năng" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLS sang PPTX trên C++" %}}
1. Mở tệp XLS bằng chức năng thành viên [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) của [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) tham chiếu lớp
2. Chuyển đổi XLS sang PDF và đặt SaveFormat thành Pdf
3. Tải tệp PDF đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Lưu tài liệu sang định dạng PPTX bằng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) và đặt Pptx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");
// save XLS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xls-to-pptxx/" name="XLS Đến PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xls-to-pptx/" name="XLS Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xls-to-powerpoint/" name="XLS Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xls-to-word/" name="XLS Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}