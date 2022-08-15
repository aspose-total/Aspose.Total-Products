---
title: C++ API för att konvertera PDF till EXCEL
description: Konvertera PDF till EXCEL via C++ API utan att använda Microsoft Excel eller Adobe Reader
url: /sv/cpp/conversion/pdf-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: CSV
otherformats: CSV MD XLSB XLTX SXC XLTM DIF XLT ODS XLAM TSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera PDF till EXCEL i C++-applikationer" h2="Konvertera PDF till EXCEL i inbyggda C++-program utan att kräva Microsoft<sup>&reg;</sup> Excel eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Att konvertera PDF till EXCEL i C++ via [Aspose.Total for C++](https://products.aspose.com/total/cpp/) filformatsautomatiseringsbibliotek är en enkel process i två steg. I det första steget kan du exportera PDF till XLSX genom att använda [Aspose.PDF för C++](https://products.aspose.com/pdf/cpp/), därefter genom att använda [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) Spreadsheet Programming API, du kan konvertera XLSX till EXCEL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera PDF till EXCEL" %}}
1. Öppna PDF-filen med [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klassreferens
2. Konvertera PDF till XLSX genom att använda medlemsfunktionen [Spara](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Ladda XLSX-dokument med hjälp av klassreferens [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Spara dokumentet i EXCEL-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hämta eller ställ in PDF-filinformation via C++" %}}
[Aspose.PDF för C++](https://products.aspose.com/pdf/cpp/) låter dig också få information om ditt PDF-dokument och låter dig fatta välgrundade beslut innan din konverteringsprocess. För att få filspecifik information om en PDF-fil måste du först anropa metoden [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) för [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klass. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna. Dessutom kan du också ställa in egenskaperna genom att använda respektive metoder i klassen DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Spara EXCEL-filformat för att streama via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) gör det möjligt att spara EXCEL-filformat för att streama. För att spara filer till en ström, skapa ett MemoryStream- eller FileStream-objekt och spara filen till det strömobjektet genom att anropa [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektets [Spara](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metod. Ange önskat filformat med uppräkningen [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) när du anropar Spara-metoden.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-excel/" name="PDF Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-md/" name="PDF Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-xlsb/" name="PDF Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-xltx/" name="PDF Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-sxc/" name="PDF Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-xltm/" name="PDF Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-dif/" name="PDF Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-xlt/" name="PDF Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-ods/" name="PDF Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-xlam/" name="PDF Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-tsv/" name="PDF Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pdf-to-fods/" name="PDF Till FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}