---
title: Converteer SXC naar WORD met C++
description: Converteer SXC naar WORD binnen C++-toepassingen
url: /nl/cpp/conversion/sxc-to-word/
family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: DOC
otherformats: DOC POWERPOINT PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer SXC naar WORD via C++" h2="Excel exporteren&reg; SXC naar WORD binnen volledig functionele C++-toepassingen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SXC naar WORD-conversie op C++" %}}
1. Open SXC-bestand met behulp van [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) lidfunctie van [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassereferentie
2. Converteer SXC naar PDF en stel SaveFormat in op Pdf
3. Laad het geconverteerde PDF-bestand met de klasseverwijzing [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Sla het wordument op in WORD-formaat met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) lidfunctie en stel Word in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/sxc-to-word/" name="SXC Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/sxc-to-powerpoint/" name="SXC Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/sxc-to-pptx/" name="SXC Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/sxc-to-wordx/" name="SXC Tot WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}