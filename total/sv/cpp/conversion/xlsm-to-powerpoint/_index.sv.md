---
title: Konvertera XLSM till POWERPOINT med C++
description: Konvertera XLSM till POWERPOINT inom C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: DOC WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera XLSM till POWERPOINT via C++" h2="Exportera Excel<sup>&reg;</sup> XLSM till POWERPOINT inom fullfunktionella C++-applikationer" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSM till POWERPOINT-konvertering på C++" %}}
1. Öppna XLSM-filen med [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) medlemsfunktionen i [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassreferens
2. Konvertera XLSM till PDF och ställ in SaveFormat till Pdf
3. Ladda den konverterade PDF-filen med klassreferens [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Spara dokumentet i POWERPOINT-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) och ställ in Powerpoint som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xlsm-to-powerpoint/" name="XLSM Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xlsm-to-word/" name="XLSM Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xlsm-to-pptx/" name="XLSM Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xlsm-to-powerpointx/" name="XLSM Till POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}