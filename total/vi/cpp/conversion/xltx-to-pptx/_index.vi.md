---
title: Chuyển đổi XLTX sang PPTX bằng C++ hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Chuyển đổi XLTX sang PPTX trong các ứng dụng C++ hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã.

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: POWERPOINT DOC DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLTX sang PPTX qua C++ hoặc trực tuyến" h2="Xuất Excel <sup>&reg;</sup>; XLTX sang PPTX trong các ứng dụng C++ đầy đủ chức năng" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi XLTX sang PPTX trên C++" %}}
1. Mở tệp XLTX bằng chức năng thành viên [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) của [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) tham chiếu lớp
2. Chuyển đổi XLTX sang PDF và đặt SaveFormat thành Pdf
3. Tải tệp PDF đã chuyển đổi bằng cách sử dụng tham chiếu lớp [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Lưu tài liệu sang định dạng PPTX bằng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) và đặt Pptx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến từ XLTX sang PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xltx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xltx-to-pptx/">Hãy dùng thử ứng dụng miễn phí của chúng tôi để chuyển đổi XLTX sang PPTX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}