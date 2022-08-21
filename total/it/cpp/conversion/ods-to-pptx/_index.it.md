---
title: Converti ODS in PPTX con C++
description: Converti ODS in PPTX all'interno di applicazioni C++
url: /it/cpp/conversion/ods-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: PPTX
otherformats: POWERPOINT DOCX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti ODS in PPTX tramite C++" h2="Esporta Excel<sup>&reg;</sup> ODS a PPTX all'interno di applicazioni C++ completamente funzionali" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da ODS a PPTX su C++" %}}
1. Aprire il file ODS utilizzando la funzione membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) di [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) riferimento alla classe
2. Converti ODS in PDF e imposta SaveFormat su Pdf
3. Caricare il file PDF convertito utilizzando il riferimento alla classe [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Salvare il pptxumento in formato PPTX utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) e impostare Pptx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ods-to-powerpoint/" name="ODS Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ods-to-pptxx/" name="ODS Per PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ods-to-word/" name="ODS Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ods-to-pptx/" name="ODS Per PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}