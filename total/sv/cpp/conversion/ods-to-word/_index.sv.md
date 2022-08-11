---
title: Konvertera ODS till WORD med C++
description: Konvertera ODS till WORD inom C++-applikationer
url: /sv/cpp/conversion/ods-to-word/
family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: DOC
otherformats: PPTX DOC DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera ODS till WORD via C++" h2="Exportera Excel&reg; ODS till WORD inom fullfunktionella C++-applikationer" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODS till WORD-konvertering på C++" %}}
1. Öppna ODS-filen med [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) medlemsfunktionen i [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassreferens
2. Konvertera ODS till PDF och ställ in SaveFormat till Pdf
3. Ladda den konverterade PDF-filen med klassreferens [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Spara dokumentet i WORD-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) och ställ in Word som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ods-to-pptx/" name="ODS Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ods-to-word/" name="ODS Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ods-to-wordx/" name="ODS Till WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ods-to-powerpoint/" name="ODS Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}