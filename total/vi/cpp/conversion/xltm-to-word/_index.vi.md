---
title: Chuyển đổi XLTM sang WORD bằng C++
description: Chuyển đổi XLTM sang WORD trong các ứng dụng C++

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOC
otherformats: PPTX POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLTM sang WORD qua C++" h2="Xuất Excel <sup>&reg;</sup>; XLTM sang WORD trong các ứng dụng C++ đầy đủ chức năng" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLTM sang WORD trên C++" %}}
1. Mở tệp XLTM bằng chức năng thành viên [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) của [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) tham chiếu lớp
2. Chuyển đổi XLTM sang PDF và đặt SaveFormat thành Pdf
3. Tải tệp PDF đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Lưu tài liệu sang định dạng WORD bằng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) và đặt Word là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xltm-to-pptx/" name="XLTM Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xltm-to-powerpoint/" name="XLTM Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xltm-to-wordx/" name="XLTM Đến WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xltm-to-word/" name="XLTM Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}