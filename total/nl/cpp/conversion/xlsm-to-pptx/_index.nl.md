---
title: Converteer XLSM naar PPTX met C++
description: Converteer XLSM naar PPTX binnen C++-toepassingen

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: DOCX DOC POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer XLSM naar PPTX via C++" h2="Excel exporteren&reg; XLSM naar PPTX binnen volledig functionele C++-toepassingen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSM naar PPTX-conversie op C++" %}}
1. Open XLSM-bestand met behulp van [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) lidfunctie van [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassereferentie
2. Converteer XLSM naar PDF en stel SaveFormat in op Pdf
3. Laad het geconverteerde PDF-bestand met de klasseverwijzing [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Sla het pptxument op in PPTX-formaat met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) lidfunctie en stel Pptx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xlsm-to-pptxx/" name="XLSM Tot PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xlsm-to-pptx/" name="XLSM Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xlsm-to-powerpoint/" name="XLSM Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xlsm-to-word/" name="XLSM Tot WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}