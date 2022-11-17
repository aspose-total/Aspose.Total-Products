---
title: Konversi FODS ke DOC dengan C++
description: Konversi FODS ke DOC dalam aplikasi C++

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOC
otherformats: DOCX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi FODS ke DOC melalui C++" h2="Ekspor Excel<sup>&reg;</sup> FODS ke DOC dalam aplikasi C++ yang berfungsi penuh" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi FODS ke DOC di C++" %}}
1. Buka file FODS menggunakan [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) fungsi anggota [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referensi kelas
2. Konversi FODS ke PDF dan atur SaveFormat ke Pdf
3. Muat file PDF yang dikonversi menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Simpan dokumen ke format DOC menggunakan fungsi anggota [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) dan setel Doc sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/fods-to-docx/" name="FODS Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/fods-to-powerpoint/" name="FODS Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/fods-to-word/" name="FODS Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/fods-to-pptx/" name="FODS Ke PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}