---
title: Konvertera XSLFO till SXC via C# API
description: C# API för att konvertera XSLFO-fil till SXC utan att använda Microsoft Excel eller Adobe Reader
url_ignore: /sv/net/conversion/xslfo-to-sxc/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: SXC
otherformats: XLSM XLTX TXT FODS XLT TSV MD SXC ODS XLSB EXCEL XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API för att rendera XSLFO till SXC" h2="Exportera XSLFO-fil till SXC via C# utan att använda Microsoft<sup>&reg;</sup> Excel eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt konvertera XSLFO-filer till SXC inom alla .NET-, C#-, ASP.NET- och VB.NET-applikationer. För det första, genom att använda [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du exportera XSLFO till XLSX. Efter det, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, kan du konvertera XLSX till SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API för att konvertera XSLFO till SXC" %}}
1. Öppna XSLFO-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera XSLFO till XLSX genom att använda metoden [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda XLSX-dokument med hjälp av klassen [Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Spara dokumentet i SXC-format med metoden [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) och ställ in "Sxc" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad XSLFO till SXC via C#" %}}
Om ditt XSLFO-dokument är lösenordsskyddat kan du inte konvertera det till SXC utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) och skicka filnamnet och lösenordet som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera XSLFO-fil till SXC med vattenstämpel via C#" %}}
När du konverterar XSLFO-fil till SXC, kan du också lägga till vattenstämpel till ditt utdata SXC-filformat. För att lägga till en vattenstämpel kan du skapa ett nytt Workbook-objekt och öppna det konverterade XLSX-dokumentet, välja Worksheet via dess index, skapa en Shape och använda dess AddTextEffect-funktion. Efter det kan du spara ditt XLSX-dokument som SXC med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}