---
title: Konvertera WORD till JSON-format via .NET
description: Konvertera WORD till JSON i C# utan att använda Microsoft Excel eller Adobe Reader
url_ignore: /sv/net/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: XLSX XLSM XLS XLT CSV TSV EXCEL XLSB SXC FODS DIF ODS XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera WORD till JSON-format via C#" h2="Analysera WORD till JSON via C# utan att använda Microsoft<sup>&reg;</sup> Word eller Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total för .NET](https://products.aspose.com/total/net/) kan du konvertera WORD till JSON-format i valfri .NET, C#, ASP.NET och VB.NET applikation i två enkla steg. För det första, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du exportera WORD till HTML. Efter det, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, kan du konvertera HTML till JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera WORD till JSON-format via C#" %}}
1. Öppna WORD-filen med klassen [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Konvertera WORD till HTML med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Spara dokumentet i JSON-format med metoden [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad WORD till JSON-format via C#" %}}
Med hjälp av API:t kan du också öppna det lösenordsskyddade dokumentet. Om ditt inmatade WORD-dokument är lösenordsskyddat kan du inte konvertera det till JSON-format utan att använda lösenordet. API:et låter dig öppna det krypterade dokumentet genom att skicka in rätt lösenord i ett LoadOptions-objekt. Följande kodexempel visar hur du försöker öppna ett krypterat dokument med ett lösenord:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera WORD till JSON i Range via C#" %}}
Medan du konverterar WORD till JSON kan du också ställa in intervallet till ditt utdata-JSON-format. För att ställa in intervallet kan du öppna den konverterade HTML-koden med Workbook-klassen, hämta CellsCollection av arbetsbladet som innehåller data, skapa ett intervall från CellsCollection genom att ange rad- och kolumnindex och anropa ExportRangeToJson-metoden med referenser till Range & ExportRangeToJsonOptions-objekt. Slutligen kan du spara JSON-data till fil via metoden File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}