---
title: Konvertera JSON-format till RTF via .NET
description: Analysera JSON till RTF i C# utan att använda Microsoft Word
url_ignore: /sv/net/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: DOCM ODT DOTX DOC EPUB WORD DOT OTT FLATOPC PCL MOBI PS RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera JSON-format till RTF via C#" h2="C# API för att tolka JSON till RTF utan att använda Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total för .NET](https://products.aspose.com/total/net/) kan du tolka JSON till RTF i alla .NET-, C#-, ASP.NET- och VB.NET-applikationer i två enkla steg. För det första, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), kan du exportera JSON till PDF. Efter det, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du konvertera PDF till RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till RTF via C#" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt och läs giltig JSON-data från filen
2. Importera JSON-fil till kalkylblad med klassen [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) och [Spara](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) den som PDF
3. Ladda PDF-dokument genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Spara dokumentet i RTF-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till RTF via C#" %}}
När du analyserar JSON till RTF kan du också ställa in layoutalternativ för din JSON med [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Det låter dig bearbeta Array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analysera JSON-format till RTF med vattenstämpel" %}}
Med hjälp av API:t kan du också konvertera JSON till RTF med vattenstämpel. För att lägga till en vattenstämpel till ditt RTF-dokument kan du först analysera JSON-filen till PDF och lägga till en vattenstämpel till den. För att lägga till en vattenstämpel, ladda den nyskapade PDF-filen med klassen [Document](https://reference.aspose.com/words/net/aspose.words/document), skapa en instans av TextWatermarkOptions och ställ in dess egenskaper, Ring Watermark.SetText-metoden och skicka vattenstämpeltext och objekt av TextWatermarkOptions. Efter att ha lagt till vattenstämpeln kan du spara dokumentet i RTF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}