---
title: Converteer XLS naar POWERPOINT met C++
description: Converteer XLS naar POWERPOINT binnen C++-toepassingen

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: DOC WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer XLS naar POWERPOINT via C++" h2="Excel exporteren&reg; XLS naar POWERPOINT binnen volledig functionele C++-toepassingen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS naar POWERPOINT-conversie op C++" %}}
1. Open XLS-bestand met behulp van [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) lidfunctie van [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassereferentie
2. Converteer XLS naar PDF en stel SaveFormat in op Pdf
3. Laad het geconverteerde PDF-bestand met de klasseverwijzing [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Sla het powerpointument op in POWERPOINT-formaat met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) lidfunctie en stel Powerpoint in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");
// save XLS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-powerpoint/" name="XLS Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-word/" name="XLS Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-powerpointx/" name="XLS Tot POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-pptx/" name="XLS Tot PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}