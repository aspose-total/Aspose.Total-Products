---
title: Filformatskonvertering via Java 
url: /sv/java/conversion/
description: Konvertera Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-bilder, diagram, videoformat och olika andra format med bara några rader Java-kod.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Filformatskonvertering via Java" h2="Konvertera Microsoft<sup>&reg;</sup> Office-dokument, PDF, bilder, HTML och flera andra filer utan att använda någon annan programvara." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) påskyndar utvecklingen av dokumenthanteringslösningar från grunden eller förbättrar befintliga applikationer för att hantera dokumenthantering med lätthet. API skapar, redigerar och konverterar inte bara Microsoft Office-dokument utan hanterar även PDF, HTML, bilder TIFF, JPG, PNG, BMP och SVG, e-postfiler, videoformat, 3D, CAD och mycket mer. Det är en samling av API:er för dokumenthantering och manipulation av lösningar utan några mjukvaruberoenden inom några Java J2SE, J2EE, J2ME-applikationer. Programmerare kan enkelt skapa, uppdatera, rendera, skriva ut och konvertera mellan de mest populära formaten inom alla Java-baserade applikationer.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertering från Word till Excel" %}}
Total API stöder inte bara interkonvertering av Microsoft Word-format utan även konvertering av Word till Excel, PDF, HTML, Bilder, EPUB, Markdown och XPS. Konverteringsprocessen är enkel. Låt oss överväga fallet med **Word till Excel**-konvertering. Ladda Microsoft Word-fil med klassen [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) och konvertera **WORD till HTML** med hjälp av [Spara-metoden](https: //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Öppna sedan det konverterade HTML-dokumentet genom att använda klassen [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) och spara dokumentet i XLSX-format med [Spara](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod.
 Utvecklare kan också konvertera [Word till PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Konvertering från Word till Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till bilder" %}}
API stöder konvertering av PDF till bilder som JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel och andra format. För konvertering av PDF till bild, låt oss betrakta JPG-bilden som målfil. Processen är att ladda en PDF-fil med hjälp av Document class och initiera [JpegDevice class](https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) objekt och rendera PDF till JPEG via [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) metod
Ladda JPEG-fil genom att använda klassen [Image](https://apireference.aspose.com/imaging/java/aspose.imaging/image) och anropa till sist metoden Spara.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint till Excel-filer" %}}

För att konvertera Microsoft PowerPoint-filer till olika filer inklusive Excel Word, MHTML, Relevanta under-API:er som ingår i huvud Aspose.Total för Java API. Processen att konvertera PowerPoint-filer till Excel-dokument, ladda PowerPoint-filen med klassen [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) och konvertera **PowerPoint till HTML** med med metoden [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Ladda sedan det konverterade HTML-dokumentet genom att använda klassen [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) och spara dokumentet i EXCEL-format med [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod. Koden för **PowerPoint till Word**-konvertering anges också.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint till Excel-konvertering" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint till Word-konvertering" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}