---
title: Konvertera MHTML till FODS via C# API
description: C# API för att konvertera MHTML-fil till FODS utan att använda Microsoft Excel eller Adobe Reader
url_ignore: /sv/net/conversion/mhtml-to-fods/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: FODS
otherformats: XLSB XLSM FODS TSV EXCEL XLT TXT XLTM MD ODS XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API för att rendera MHTML till FODS" h2="Exportera MHTML-fil till FODS via C# utan att använda Microsoft<sup>&reg;</sup> Excel eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt konvertera MHTML-filer till FODS inom alla .NET-, C#-, ASP.NET- och VB.NET-applikationer. För det första, genom att använda [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du exportera MHTML till XLSX. Efter det, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, kan du konvertera XLSX till FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API för att konvertera MHTML till FODS" %}}
1. Öppna MHTML-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera MHTML till XLSX genom att använda metoden [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda XLSX-dokument med hjälp av klassen [Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Spara dokumentet i FODS-format med metoden [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) och ställ in "Fods" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad MHTML till FODS via C#" %}}
Om ditt MHTML-dokument är lösenordsskyddat kan du inte konvertera det till FODS utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) och skicka filnamnet och lösenordet som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera MHTML-fil till FODS med vattenstämpel via C#" %}}
När du konverterar MHTML-fil till FODS, kan du också lägga till vattenstämpel till ditt utdata FODS-filformat. För att lägga till en vattenstämpel kan du skapa ett nytt Workbook-objekt och öppna det konverterade XLSX-dokumentet, välja Worksheet via dess index, skapa en Shape och använda dess AddTextEffect-funktion. Efter det kan du spara ditt XLSX-dokument som FODS med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}