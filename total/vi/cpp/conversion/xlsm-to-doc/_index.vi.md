---
title: Chuyển đổi XLSM sang DOC bằng C++
description: Chuyển đổi XLSM sang DOC trong các ứng dụng C++

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLSM sang DOC qua C++" h2="Xuất Excel <sup>&reg;</sup>; XLSM sang DOC trong các ứng dụng C++ đầy đủ chức năng" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLSM sang DOC trên C++" %}}
1. Mở tệp XLSM bằng chức năng thành viên [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) của [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) tham chiếu lớp
2. Chuyển đổi XLSM sang PDF và đặt SaveFormat thành Pdf
3. Tải tệp PDF đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Lưu tài liệu sang định dạng DOC bằng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) và đặt Doc là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xlsm-to-powerpoint/" name="XLSM Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xlsm-to-word/" name="XLSM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xlsm-to-pptx/" name="XLSM Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/xlsm-to-docx/" name="XLSM Đến DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}