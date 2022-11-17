---
title: Converti FODS in DOC con C++
description: Converti FODS in DOC all'interno di applicazioni C++

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOC
otherformats: DOCX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti FODS in DOC tramite C++" h2="Esporta Excel<sup>&reg;</sup> FODS a DOC all'interno di applicazioni C++ completamente funzionali" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS a DOC su C++" %}}
1. Aprire il file FODS utilizzando la funzione membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) di [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) riferimento alla classe
2. Converti FODS in PDF e imposta SaveFormat su Pdf
3. Caricare il file PDF convertito utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Salvare il documento in formato DOC utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) e impostare Doc come SaveFormat
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
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-docx/" name="FODS Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-powerpoint/" name="FODS Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-word/" name="FODS Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/fods-to-pptx/" name="FODS Per PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}