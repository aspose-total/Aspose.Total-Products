---
title: Konvertera JSON-format till PPSX via .NET
description: Analysera JSON till PPSX i C# utan att använda Microsoft PowerPoint
url_ignore: /sv/net/conversion/json-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSX
otherformats: PPTM PPSM POWERPOINT PPS POTM PPT POTX PPSX POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera JSON-format till PPSX via C#" h2="C# API för att tolka JSON till PPSX utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera JSON till PPSX i alla .NET-, C#-, ASP.NET- och VB.NET-applikationer i två enkla steg. För det första, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), kan du analysera JSON till PPTX. Efter det, genom att använda [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), kan du konvertera PPTX till PPSX. Båda API:erna ingår i paketet [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till PPSX via C#" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt och läs giltig JSON-data från filen
2. Importera JSON-fil till kalkylblad med klassen [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) och [Spara](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) det som PPTX
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Spara dokumentet i PPSX-format med metoden [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till PPSX via C#" %}}
Medan du analyserar JSON till PPSX kan du också ställa in layoutalternativ för ditt JSON-format med [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Det låter dig bearbeta array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JSON-format till PPSX med vattenstämpel" %}}
Med hjälp av API:t kan du också konvertera JSON till PPSX med vattenstämpel. För att lägga till ett vattenmärke till ditt PPSX-dokument kan du först analysera JSON till PPTX och lägga till ett vattenmärke till det. För att lägga till en vattenstämpel, ladda den nyskapade PPTX-filen med klassen [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), välj huvudpresentationen, lägg till formtyp med hjälp av Lägg till AutoShape och lägg till vattenstämpeltext med AddTextFrame. När du har lagt till vattenstämpeln kan du spara dokumentet i PPSX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}