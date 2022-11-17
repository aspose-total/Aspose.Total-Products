---
title: C++ ile FODS'yi POWERPOINT'ye dönüştürün
description: C++ uygulamaları içinde FODS'yi POWERPOINT'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOCX PPTX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="FODS'yi C++ ile POWERPOINT'ye dönüştürün" h2="Excel'i Dışa Aktar&reg; Tam işlevli C++ uygulamalarında FODS'den POWERPOINT'ye" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da FODS'den POWERPOINT'ye Dönüştürme" %}}
1. [Fabrika](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) üye işlevini kullanarak FODS dosyasını açın /cpp/class/aspose.cells.factory) sınıf referansı
2. FODS'yi PDF'ye dönüştürün ve SaveFormat'ı Pdf'ye ayarlayın
3. Dönüştürülen PDF dosyasını [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) üye işlevini kullanarak belgeyi POWERPOINT biçiminde kaydedin ve Belgeyi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/fods-to-powerpointx/" name="FODS İle POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/fods-to-pptx/" name="FODS İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/fods-to-word/" name="FODS İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/fods-to-powerpoint/" name="FODS İle POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}