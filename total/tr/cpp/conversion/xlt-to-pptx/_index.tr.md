---
title: C++ ile XLT'yi PPTX'ye dönüştürün
description: C++ uygulamaları içinde XLT'yi PPTX'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: PPTX
otherformats: DOCX WORD POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLT'yi C++ ile PPTX'ye dönüştürün" h2="Excel'i Dışa Aktar&reg; Tam işlevli C++ uygulamalarında XLT'den PPTX'ye" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da XLT'den PPTX'ye Dönüştürme" %}}
1. [Fabrika](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) üye işlevini kullanarak XLT dosyasını açın /cpp/class/aspose.cells.factory) sınıf referansı
2. XLT'yi PDF'ye dönüştürün ve SaveFormat'ı Pdf'ye ayarlayın
3. Dönüştürülen PDF dosyasını [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) üye işlevini kullanarak belgeyi PPTX biçiminde kaydedin ve Belgeyi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlt-to-pptxx/" name="XLT İle PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlt-to-word/" name="XLT İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlt-to-powerpoint/" name="XLT İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xlt-to-pptx/" name="XLT İle PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}