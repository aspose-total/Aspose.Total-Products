---
title: Konvertera JSON-format till IMAGE via .NET
description: Analysera JSON till IMAGE i C# utan att använda tredje parts beroenden
url_ignore: /sv/net/conversion/json-to-image/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: WMZ TGA PSD IMAGE DICOM SVGZ EMZ JPEG2000 WMF DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera JSON-format till IMAGE via C#" h2="C# API för att tolka JSON till IMAGE utan att använda beroenden från tredje part" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du tolka JSON till IMAGE i alla .NET-, C#-, ASP.NET- och VB.NET-applikationer i två enkla steg. För det första, genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), kan du exportera JSON till JPEG. Efter det, genom att använda [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), kan du konvertera JPEG till IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till IMAGE via C#" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt och läs JSON-data från filen
2. Konvertera JSON till JPEG med metoden [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Ladda JPEG-dokument genom att använda klassen [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Spara dokumentet i IMAGE-format med metoden [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till IMAGE via C#" %}}
Medan du analyserar JSON till IMAGE kan du också ställa in layoutalternativ för din JSON med [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Det låter dig bearbeta Array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analysera JSON-format till IMAGE med vattenstämpel" %}}
Med hjälp av API:t kan du också konvertera JSON till IMAGE med vattenstämpel i ditt IMAGE-dokument. För att lägga till en vattenstämpel kan du först rendera ditt JSON-dokument till JPEG och lägga till en vattenstämpel i den. För att demonstrera operationen kan du ladda din konverterade JPEG-bild, lägga till transformationer med hjälp av ett objekt av klassen Matrix och rita en sträng som vattenstämpel på bildytan med hjälp av [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) klassens [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) metod. När du har lagt till vattenstämpeln kan du spara JPEG som IMAGE-format. Nedan är ett kodexempel som visar hur man lägger till en diagonal vattenstämpel till ditt dokument. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}