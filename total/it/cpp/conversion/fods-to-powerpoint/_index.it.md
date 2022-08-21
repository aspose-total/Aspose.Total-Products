---
title: Converti FODS in POWERPOINT con C++
description: Converti FODS in POWERPOINT all'interno di applicazioni C++
url: /it/cpp/conversion/fods-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOCX PPTX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti FODS in POWERPOINT tramite C++" h2="Esporta Excel<sup>&reg;</sup> FODS a POWERPOINT all'interno di applicazioni C++ completamente funzionali" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS a POWERPOINT su C++" %}}
1. Aprire il file FODS utilizzando la funzione membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) di [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) riferimento alla classe
2. Converti FODS in PDF e imposta SaveFormat su Pdf
3. Caricare il file PDF convertito utilizzando il riferimento alla classe [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Salvare il powerpointumento in formato POWERPOINT utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) e impostare Powerpoint come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
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
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-powerpointx/" name="FODS Per POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-pptx/" name="FODS Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-word/" name="FODS Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-powerpoint/" name="FODS Per POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}