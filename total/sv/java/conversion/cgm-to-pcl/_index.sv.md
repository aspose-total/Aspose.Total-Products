---
title: Java API för att exportera CGM till PCL
description: Konvertera CGM till PCL med hjälp av det lokala Java API
url_ignore: /sv/java/conversion/cgm-to-pcl/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PCL
otherformats: DOTX RTF WORDML OTT MARKDOWN MHTML PS DOTM ODT XAMLFLOW PCL FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Förvandla CGM till PCL via Java" h2="On Premise Java API för att rendera CGM till PCL utan att använda någon tredjepartsapplikation" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera CGM till PCL genom att använda två enkla steg. Först måste du rendera CGM-filen till DOC med [Aspose.PDF för Java](https://products.aspose.com/pdf/java/). Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du konvertera DOC till PCL. Båda API:erna kommer under paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera CGM till PCL" %}}
1. Öppna CGM-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera CGM till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i PCL-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in PCL som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Words för Java](https://docs.aspose.com/words/java/installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du konverterar CGM till PCL, även om ditt dokument är lösenordsskyddat, kan du fortfarande öppna det med PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). För att öppna den krypterade filen måste du skapa ett [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objekt och öppna CGM med ägarens lösenord.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddat CGM-dokument via Java" %}}
Samtidigt som du sparar ditt inmatade dokument i PCL-filformat kan du också spara ditt dokument i databasen istället för ett filsystem. Du kan behöva implementera att lagra och hämta dokumentobjekt till och från en databas. Detta skulle vara nödvändigt om du skulle implementera någon typ av innehållshanteringssystem. För att spara din PCL i databasen är det ofta nödvändigt att serialisera dokumentet för att få en byte-array. Detta kan göras med [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Efter att ha fått din byte-array kan du lagra den i databasen med hjälp av SQL-satsen. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}