---
title: Java API för att exportera MD till DOT
description: Konvertera MD till DOT med hjälp av det lokala Java API
url_ignore: /sv/java/conversion/md-to-dot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOT
otherformats: WORDML RTF OTT DOTM PS DOT FLATOPC XAMLFLOW MHTML MARKDOWN PCL ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Förvandla MD till DOT via Java" h2="On Premise Java API för att rendera MD till DOT utan att använda någon tredjepartsapplikation" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera MD till DOT genom att använda två enkla steg. Först måste du rendera MD-filen till DOC med [Aspose.PDF för Java](https://products.aspose.com/pdf/java/). Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du konvertera DOC till DOT. Båda API:erna kommer under paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera MD till DOT" %}}
1. Öppna MD-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera MD till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i DOT-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in DOT som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Words för Java](https://docs.aspose.com/words/java/installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du konverterar MD till DOT, även om ditt dokument är lösenordsskyddat, kan du fortfarande öppna det med PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). För att öppna den krypterade filen måste du skapa ett [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objekt och öppna MD med ägarens lösenord.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddat MD-dokument via Java" %}}
Samtidigt som du sparar ditt inmatade dokument i DOT-filformat kan du också spara ditt dokument i databasen istället för ett filsystem. Du kan behöva implementera att lagra och hämta dokumentobjekt till och från en databas. Detta skulle vara nödvändigt om du skulle implementera någon typ av innehållshanteringssystem. För att spara din DOT i databasen är det ofta nödvändigt att serialisera dokumentet för att få en byte-array. Detta kan göras med [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Efter att ha fått din byte-array kan du lagra den i databasen med hjälp av SQL-satsen. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOT);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Att konvertera MD (Markdown) till DOT (Word-mall) hjälper företag att standardisera varumärkesdokument samtidigt som de bibehåller versionskontrollerat innehåll i Markdown. DOT-mallar bevarar formateringskonsistens och säkerställer att teamen omedelbart kan generera nya Word-filer från en ren, återanvändbar struktur.



{{% blocks/products/pf/agp/feature-section-col title="Användningsområden" %}}



* Skapa konsekventa brevpapper från Markdown-baserade mallar.

* Publicera varumärkesgodkända marknadsföringsblad från MD-utkast.

* HR-team skapar mallar för introduktionsdokument från MD-guides.

* Juridiska avdelningar standardiserar kontraktsstrukturer hämtade från Markdown.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario" %}}



* Automatisk generering av DOT-mallar i CMS-publiceringsflöden.

* Centraliserad konvertering för distribuerade team som uppdaterar varumärkesresurser.

* Schemalagd återgenerering av huvudmallar lagrade i Git.

* Automatisk skapande av DOT för franchising eller dokumentationsbehov för flera filialer.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}