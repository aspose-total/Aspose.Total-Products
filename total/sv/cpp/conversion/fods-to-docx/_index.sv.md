---
title: Konvertera FODS till DOCX med C++
description: Konvertera FODS till DOCX inom C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOCX
otherformats: DOC WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera FODS till DOCX via C++" h2="Exportera Excel<sup>&reg;</sup> FODS till DOCX inom fullfunktionella C++-applikationer" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="FODS till DOCX-konvertering på C++" %}}
1. Öppna FODS-filen med [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) medlemsfunktionen i [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassreferens
2. Konvertera FODS till PDF och ställ in SaveFormat till Pdf
3. Ladda den konverterade PDF-filen med klassreferens [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Spara dokumentet i DOCX-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) och ställ in Docx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/fods-to-docx/" name="FODS Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/fods-to-word/" name="FODS Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/fods-to-pptx/" name="FODS Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/fods-to-powerpoint/" name="FODS Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}