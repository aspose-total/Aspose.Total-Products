---
title: Java API för att exportera XPS till FLATOPC
description: Konvertera XPS till FLATOPC med hjälp av det lokala Java API
url: /sv/java/conversion/xps-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: FLAT_OPC
otherformats: MARKDOWN OTT DOTX PS DOT PCL WORDML MHTML FLATOPC DOTM RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Förvandla XPS till FLATOPC via Java" h2="On Premise Java API för att rendera XPS till FLATOPC utan att använda någon tredjepartsapplikation" >}}
{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera XPS till FLATOPC genom att använda två enkla steg. Först måste du rendera XPS-filen till DOC med [Aspose.PDF för Java](https://products.aspose.com/pdf/java/). Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du konvertera DOC till FLATOPC. Båda API:erna kommer under paketet [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera XPS till FLATOPC" %}}
1. Öppna XPS-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XPS till DOC genom att använda [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i FLATOPC-format med metoden [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in FLATOPC som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Words för Java](https://docs.aspose.com/words/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du konverterar XPS till FLATOPC, även om ditt dokument är lösenordsskyddat, kan du fortfarande öppna det med PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). För att öppna den krypterade filen måste du skapa ett [Dokument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) objekt och öppna XPS med ägarens lösenord.  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna lösenordsskyddat XPS-dokument via Java" %}}
Samtidigt som du sparar ditt inmatade dokument i FLATOPC-filformat kan du också spara ditt dokument i databasen istället för ett filsystem. Du kan behöva implementera att lagra och hämta dokumentobjekt till och från en databas. Detta skulle vara nödvändigt om du skulle implementera någon typ av innehållshanteringssystem. För att spara din FLATOPC i databasen är det ofta nödvändigt att serialisera dokumentet för att få en byte-array. Detta kan göras med [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Efter att ha fått din byte-array kan du lagra den i databasen med hjälp av SQL-satsen. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.FLAT_OPC);
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
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-rtf/" name="XPS Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-wordml/" name="XPS Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-odt/" name="XPS Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-flatopc/" name="XPS Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-ps/" name="XPS Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-pcl/" name="XPS Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-mhtml/" name="XPS Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-dotm/" name="XPS Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-ott/" name="XPS Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-dotx/" name="XPS Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-xamlflow/" name="XPS Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-markdown/" name="XPS Till MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}