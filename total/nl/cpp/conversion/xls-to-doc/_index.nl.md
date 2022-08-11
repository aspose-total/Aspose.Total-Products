---
title: Converteer XLS naar DOC met C++
description: Converteer XLS naar DOC binnen C++-toepassingen
url: /nl/cpp/conversion/xls-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer XLS naar DOC via C++" h2="Excel exporteren&reg; XLS naar DOC binnen volledig functionele C++-toepassingen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS naar DOC-conversie op C++" %}}
1. Open XLS-bestand met behulp van [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) lidfunctie van [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassereferentie
2. Converteer XLS naar PDF en stel SaveFormat in op Pdf
3. Laad het geconverteerde PDF-bestand met de klasseverwijzing [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Sla het document op in DOC-formaat met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) lidfunctie en stel Doc in als SaveFormat
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
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-powerpoint/" name="XLS Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-word/" name="XLS Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-pptx/" name="XLS Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xls-to-docx/" name="XLS Tot DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}