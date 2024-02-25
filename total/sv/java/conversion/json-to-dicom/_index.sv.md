---
title: Konvertera JSON-format till DICOM via Java
description: Analysera JSON till DICOM i Java utan att använda Microsoft PowerPoint
url_ignore: /sv/java/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM DXF WMF TGA SVGZ EMZ IMAGE JPEG2000 PSD WMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera JSON-format till DICOM via Java" h2="Java API för att analysera JSON-format till DICOM i alla Java J2SE, J2EE, J2ME-applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
Med hjälp av [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du konvertera JSON-format till DICOM i valfri Java-applikation i två enkla steg. För det första, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du tolka JSON till JPEG. Efter det, genom att använda [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), kan du konvertera JPEG till DICOM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till DICOM via Java" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt och öppna JSON-filen
2. Spara JSON som JPEG med [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metod
3. Ladda JPEG-dokument genom att använda klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Spara dokumentet i DICOM-format med [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Dessutom låter API:et dig tolka JSON till DICOM med specificerade layoutalternativ. För att specificera layoutalternativen kan du använda klassen [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Det låter dig bearbeta en array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till DICOM via Java" %}}
Med hjälp av API:t kan du också konvertera JSON till DICOM med vattenstämpel i ditt DICOM-dokument. För att lägga till en vattenstämpel kan du först konvertera JSON till JPEG och lägga till en vattenstämpel i den. För att lägga till vattenstämpel, ladda en bildfil med klassen [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), skapa ett objekt av [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) klass och initiera den med bildobjekt, skapa en ny [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) och ställ in översättning och transformation till önskad vinkel och lägg till vattenstämpel med [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) metod. När du har lagt till vattenstämpeln i din bild kan du spara JPEG som DICOM-format. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}