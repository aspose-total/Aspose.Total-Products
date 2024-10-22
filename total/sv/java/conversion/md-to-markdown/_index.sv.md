---
title: Java API för att exportera MD till MARKDOWN
description: Konvertera MD till MARKDOWN med hjälp av det lokala Java API
url_ignore: /sv/java/conversion/md-to-markdown/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: MARKDOWN
otherformats: DOTX PS DOT RTF XAMLFLOW MHTML WORDML FLATOPC PCL MARKDOWN DOTM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Förvandla MD till MARKDOWN via Java" h2="On Premise Java API för att rendera MD till MARKDOWN utan att använda någon tredjepartsapplikation" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera MD till MARKDOWN genom att använda två enkla steg. Först måste du rendera MD-filen till DOC med [Aspose.PDF för Java](https://products.aspose.com/pdf/java/). Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du konvertera DOC till MARKDOWN. Båda API:erna kommer under paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera MD till MARKDOWN" %}}
1. Öppna MD-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera MD till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i MARKDOWN-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in MARKDOWN som SaveFormat
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
När du konverterar MD till MARKDOWN, även om ditt dokument är lösenordsskyddat, kan du fortfarande öppna det med PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). För att öppna den krypterade filen måste du skapa ett [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objekt och öppna MD med ägarens lösenord.  
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
Samtidigt som du sparar ditt inmatade dokument i MARKDOWN-filformat kan du också spara ditt dokument i databasen istället för ett filsystem. Du kan behöva implementera att lagra och hämta dokumentobjekt till och från en databas. Detta skulle vara nödvändigt om du skulle implementera någon typ av innehållshanteringssystem. För att spara din MARKDOWN i databasen är det ofta nödvändigt att serialisera dokumentet för att få en byte-array. Detta kan göras med [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Efter att ha fått din byte-array kan du lagra den i databasen med hjälp av SQL-satsen. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}