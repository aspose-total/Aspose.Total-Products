---
title: Konvertera XLTX till DOC med C++
description: Konvertera XLTX till DOC inom C++-applikationer
url: /sv/cpp/conversion/xltx-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX DOCX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera XLTX till DOC via C++" h2="Exportera Excel<sup>&reg;</sup> XLTX till DOC inom fullfunktionella C++-applikationer" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTX till DOC-konvertering på C++" %}}
1. Öppna XLTX-filen med [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) medlemsfunktionen i [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) klassreferens
2. Konvertera XLTX till PDF och ställ in SaveFormat till Pdf
3. Ladda den konverterade PDF-filen med klassreferens [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Spara dokumentet i DOC-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) och ställ in Doc som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xltx-to-pptx/" name="XLTX Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xltx-to-docx/" name="XLTX Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xltx-to-word/" name="XLTX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xltx-to-powerpoint/" name="XLTX Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}