---
title: Konvertera webbsidor HTML till bilder med C#
description: Skrapa webbsidor och exportera HTML till bilder. Utveckla .NET-applikationer för att skrapa webbplatsdata till JPEG, PNG, GIF, BMP etc. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera webbsidor till bilder via C#" h2="Extrahera webbplatsdata från HTML-webbsidor. Konvertera HTML till JPG, GIF, PNG, BMP-bilder i .NET-applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Varför konvertera webbsidor till bilder?</h2>
<p>Att konvertera webbsidor till bilder kan vara användbart i en mängd olika situationer. Det är ett vanligt krav för många applikationer. I vissa scenarier är det nödvändigt att fånga hela webbsidan som en bild, inklusive de delar som inte är synliga på skärmen. Detta kan vara användbart för att skapa förhandsvisningar av webbplatser, fånga kvitton och fakturor eller arkivera webbsidor för juridiska ändamål. Den kan användas för att skapa skärmdumpar av webbsidor för dokumentations- eller teständamål. Den kan också användas för att skapa miniatyrer eller förhandsvisningar av webbsidor för användning i sökresultat eller bildgallerier. Oavsett om du bygger en skrivbordsapplikation eller en webbapplikation, finns det många alternativ tillgängliga för att konvertera webbsidor till bilder med C#.</p><br />

<p>Att konvertera webbsidor till bilder med C# kan ge flera fördelar, inklusive:</p><br />
<ul>
<li>Förbättrad tillgänglighet: Bilder kan vara lättare att läsa och förstå för personer med synnedsättning eller andra funktionsnedsättningar.</li>
<li>Ökad portabilitet: Bilder kan enkelt delas eller bäddas in i andra dokument eller applikationer.</li>
</ul>
<p>Att konvertera webbsidor till bilder med C# kan också innebära vissa utmaningar, inklusive:</p><br />
<ul>
<li>Begränsat formatstöd: Vissa API:er eller verktyg kanske inte stöder alla bildformat eller kan ha begränsningar för storleken eller upplösningen på utdatabilderna.</li>
<li>Kompatibilitetsproblem: Vissa webbsidor kanske inte renderas korrekt i alla webbläsare eller kan kräva specifika inställningar eller plugins för att visas korrekt.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur konverterar man webbsidor till bilder med C#?" %}}
För att konvertera webbsidor till bilder med C# kan du använda ett Aspose.HTML för .NET API som tillhandahåller denna funktion för att konvertera HTML-sidor till bildformat, inklusive JPEG, PNG och TIFF.</p>

1. Ladda ett HTML-dokument med en av konstruktörerna som finns tillgängliga i [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Du kan ladda HTML från en fil, HTML-kod, en stream eller en URL.
2. Skapa en ny instans av [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) och ställ in egenskapen ImageFormat till JPEG. Som standard är egenskapen Format inställd på PNG.
3. Använd [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metod från Converter-klassen för att spara HTML-dokumentet som en JPEG-fil. Du måste tillhandahålla HTMLDocument, ImageSaveOptions och utdatafilens sökväg som parametrar till ConvertHTML()-metoden.
4. Den resulterande JPEG-filen kommer att sparas till den angivna sökvägen.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Krav för webbskrotning och bildkonvertering" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller installera direkt från Package Manager Console i Visual Studio.

Två [Aspose.Total for .NET](https://products.aspose.com/total/net/) barn-API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) kommer att integreras.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}