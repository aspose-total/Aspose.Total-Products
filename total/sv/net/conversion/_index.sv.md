---
title: Filformatskonvertering via C# 

description: Konvertera Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-bilder, diagram, videoformat och många andra populära filer med bara några rader C#-kod.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Filformatskonvertering via C# .NET" h2="Konvertera Microsoft<sup>&reg;</sup> Office-filer, PDF, bilder, HTML och olika andra format utan att använda någon annan programvara." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET Total Library](https://products.aspose.com/total/net/) påskyndar utvecklingen av dokumenthanteringslösningar från grunden eller förbättrar befintliga applikationer för att hantera dokumentmanipulation med lätthet. API hanterar inte bara Microsoft Office-dokument utan hanterar även PDF, HTML, bilder TIFF, JPG, PNG, BMP och SVG, e-postfiler, videoformat, GIS-dataformat och mycket mer. Det är en komplett uppsättning av API:er för dokumenthantering och manipulering av lösningar utan några mjukvaruberoenden. Programmerare kan enkelt skapa, uppdatera, rendera, skriva ut och konvertera mellan de mest populära formaten inom alla .NET-baserade applikationer.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera Word till PDF" %}}
Total API stöder inte bara interkonvertering av Microsoft Word-format utan även konvertering av Word till PDF, HTML, bilder, EPUB, Markdown och XPS. Konverteringsprocessen är enkel. Ladda klassen Document via Document och anropa bara metoden Spara med målformat. Det är så enkelt. Utvecklare kan kontrollera [konverteringsresultatet](https://products.aspose.com/words/net/conversion/word-to-pdf/) innan kodintegrering av **Word till PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Konvertering av Word till PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till bilder" %}}
API stöder konvertering av PDF till bilder, Powerpoint, Excel och andra format. För konvertering av PDF till bild, låt oss betrakta JPG-bilden som målfil. Processen är att ladda en PDF-fil med hjälp av Document class och initiera [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) objekt och rendera PDF till JPEG via [Process](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metod
Ladda JPEG-fil genom att använda klassen [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) och anropa till sist metoden Spara.

{{% blocks/products/pf/feature-page-code h3="C# - Konvertering av PDF till bild" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera Excel till Word och PowerPoint" %}}

För att konvertera Microsoft Excel-format till olika filer inklusive Word och PowerPoint, Relevanta under-API:er som ingår i huvud Aspose.Total för .NET API. Processen att konvertera Excel-filer till Word-dokument, ladda EXCEL-filen med klassen [Arbetsbok](https://reference.aspose.com/cells/net/aspose.cells/workbook) och konvertera EXCEL till PDF först och ställ in SaveFormat till Auto. Ladda sedan den konverterade PDF-filen med klassen Document och anropa metoden Spara och ställ in Doc, Docx som SaveFormat. Koden listad även för Microsoft **Excel till Powerpoint**-konvertering.

{{% blocks/products/pf/feature-page-code h3="C# - JSON till Excel-konvertering" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Konvertering av Excel till JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}