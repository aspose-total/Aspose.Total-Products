---
title: C++ API för att konvertera CGM till XLSB
description: Konvertera CGM till XLSB via C++ API utan att använda Microsoft Excel eller Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLTX EXCEL SXC TXT XLSM XLT XLAM TSV MD FODS CSV XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera CGM till XLSB i C++-applikationer" h2="Konvertera CGM till XLSB i inbyggda C++-program utan att kräva Microsoft<sup>&reg;</sup> Excel eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Att konvertera CGM till XLSB i C++ via [Aspose.Total for C++](https://products.aspose.com/total/cpp/) filformatsautomatiseringsbibliotek är en enkel process i två steg. I det första steget kan du exportera CGM till XLSX genom att använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), därefter genom att använda [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) Spreadsheet Programming API, du kan konvertera XLSX till XLSB. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera CGM till XLSB" %}}
1. Öppna CGM-filen med [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klassreferens
2. Konvertera CGM till XLSX genom att använda medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Ladda XLSX-dokument med hjälp av klassreferens [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Spara dokumentet i XLSB-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hämta eller ställ in CGM-filinformation via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) låter dig också få information om ditt CGM-dokument och låter dig fatta välgrundade beslut innan din konverteringsprocess. För att få filspecifik information om en CGM-fil måste du först anropa metoden [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) för [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klass. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna. Dessutom kan du också ställa in egenskaperna genom att använda respektive metoder i klassen DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Spara XLSB-filformat för att streama via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) gör det möjligt att spara XLSB-filformat för att streama. För att spara filer till en ström, skapa ett MemoryStream- eller FileStream-objekt och spara filen till det strömobjektet genom att anropa [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektets [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metod. Ange önskat filformat med uppräkningen [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) när du anropar Spara-metoden.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsb-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}