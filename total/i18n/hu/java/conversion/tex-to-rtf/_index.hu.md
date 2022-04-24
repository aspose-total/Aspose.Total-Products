---
title: Java API a TEX exportálásához RTF-be
description: Konvertálja a TEX-et RTF-re a helyszíni Java API használatával
url: /hu/java/conversion/tex-to-rtf/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: RTF
otherformats: DOTM DOT ODT RTF WORDML MARKDOWN PCL MHTML PS FLATOPC XAMLFLOW DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A TEX átalakítása RTF-re Java segítségével" h2="On Premise Java API a TEX megjelenítéséhez RTF-ben harmadik féltől származó alkalmazások használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépéssel a TEX-et RTF-má konvertálhatja. Először is le kell renderelnie a TEX-fájlt DOC-ban az [Aspose.PDF for Java] használatával (https://products.aspose.com/pdf/java/). Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for Java] (https://products.aspose.com/words/java/) használatával a DOC-t RTF-má konvertálhatja. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomagban található.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a TEX RTF-má konvertálásához" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével konvertálja a TEX-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot RTF formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a RTF-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Words for Java](https://docs.aspose.com/words/java/) install/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.RTF
outputDocument.save("output.rtf", SaveFormat.RTF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A TEX RTF-re konvertálása közben még akkor is megnyithatja a PDF Manipulation API [Aspose.PDF for Java] (https://docs.aspose.com/pdf/java/installation/) segítségével, ha dokumentuma jelszóval védett. A titkosított fájl megnyitásához létre kell hoznia egy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, és meg kell nyitnia a TEX-et a tulajdonos jelszavával.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a jelszóval védett TEX-dokumentumot Java-n keresztül" %}}
Miközben a bemeneti dokumentumot RTF fájlformátumba menti, fájlrendszer helyett adatbázisba is mentheti. Előfordulhat, hogy meg kell valósítania a dokumentumobjektumok tárolását és lekérését egy adatbázisba, illetve adatbázisból. Erre akkor lenne szükség, ha bármilyen típusú tartalomkezelő rendszert implementálna. A RTF adatbázisba mentéséhez gyakran szükség van a dokumentum szerializálására egy bájttömb beszerzéséhez. Ezt az [Aspose.Words for Java](https://products.aspose.com/words/Java/) API használatával teheti meg. A bájttömb beszerzése után SQL utasítás segítségével tárolhatja az adatbázisban. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-rtf/" name="TEX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-wordml/" name="TEX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-odt/" name="TEX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-flatopc/" name="TEX Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-ps/" name="TEX Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-pcl/" name="TEX Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-mhtml/" name="TEX Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-dotm/" name="TEX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-ott/" name="TEX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-dotx/" name="TEX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xamlflow/" name="TEX Nak nek XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-markdown/" name="TEX Nak nek MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}