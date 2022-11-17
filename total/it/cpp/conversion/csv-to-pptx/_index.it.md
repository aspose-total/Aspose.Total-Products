---
title: Converti CSV in PPTX con C++
description: Converti CSV in PPTX all'interno di applicazioni C++

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: PPTX
otherformats: WORD DOCX DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti CSV in PPTX tramite C++" h2="Esporta Excel<sup>&reg;</sup> CSV a PPTX all'interno di applicazioni C++ completamente funzionali" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da CSV a PPTX su C++" %}}
1. Aprire il file CSV utilizzando la funzione membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) di [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) riferimento alla classe
2. Converti CSV in PDF e imposta SaveFormat su Pdf
3. Caricare il file PDF convertito utilizzando il riferimento alla classe [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Salvare il pptxumento in formato PPTX utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) e impostare Pptx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the CSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");
// save CSV as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/csv-to-word/" name="CSV Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/csv-to-pptxx/" name="CSV Per PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/csv-to-pptx/" name="CSV Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/csv-to-powerpoint/" name="CSV Per POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}