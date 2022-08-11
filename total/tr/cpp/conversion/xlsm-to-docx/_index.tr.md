---
title: C++ ile XLSM'yi DOCX'ye dönüştürün
description: C++ uygulamaları içinde XLSM'yi DOCX'ye dönüştürün
url: /tr/cpp/conversion/xlsm-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOCX
otherformats: PPTX POWERPOINT DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLSM'yi C++ ile DOCX'ye dönüştürün" h2="Excel'i Dışa Aktar&reg; Tam işlevli C++ uygulamalarında XLSM'den DOCX'ye" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da XLSM'den DOCX'ye Dönüştürme" %}}
1. [Fabrika](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) üye işlevini kullanarak XLSM dosyasını açın /cpp/class/aspose.cells.factory) sınıf referansı
2. XLSM'yi PDF'ye dönüştürün ve SaveFormat'ı Pdf'ye ayarlayın
3. Dönüştürülen PDF dosyasını [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) üye işlevini kullanarak belgeyi DOCX biçiminde kaydedin ve Belgeyi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlsm-to-pptx/" name="XLSM İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlsm-to-powerpoint/" name="XLSM İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlsm-to-docx/" name="XLSM İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlsm-to-word/" name="XLSM İle WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}