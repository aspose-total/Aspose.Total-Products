---
title: Java API a PDF exportálásához XAMLFLOW-be
description: Konvertálja a PDF-et XAMLFLOW-re a helyszíni Java API használatával
url_ignore: /hu/java/conversion/pdf-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XAML_FLOW
otherformats: WORDML XAMLFLOW OTT ODT RTF FLATOPC DOTX PS DOTM MARKDOWN PCL DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A PDF átalakítása XAMLFLOW-re Java segítségével" h2="On Premise Java API a PDF megjelenítéséhez XAMLFLOW-ben harmadik féltől származó alkalmazások használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépéssel a PDF-et XAMLFLOW-má konvertálhatja. Először is le kell renderelnie a PDF-fájlt DOC-ban az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a DOC-t XAMLFLOW-má konvertálhatja. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomagban található.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a PDF XAMLFLOW-má konvertálásához" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével konvertálja a PDF-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot XAMLFLOW formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a XAMLFLOW-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A PDF XAMLFLOW-re konvertálása közben még akkor is megnyithatja a PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) segítségével, ha dokumentuma jelszóval védett. A titkosított fájl megnyitásához létre kell hoznia egy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, és meg kell nyitnia a PDF-et a tulajdonos jelszavával.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a jelszóval védett PDF-dokumentumot Java-n keresztül" %}}
Miközben a bemeneti dokumentumot XAMLFLOW fájlformátumba menti, fájlrendszer helyett adatbázisba is mentheti. Előfordulhat, hogy meg kell valósítania a dokumentumobjektumok tárolását és lekérését egy adatbázisba, illetve adatbázisból. Erre akkor lenne szükség, ha bármilyen típusú tartalomkezelő rendszert implementálna. A XAMLFLOW adatbázisba mentéséhez gyakran szükség van a dokumentum szerializálására egy bájttömb beszerzéséhez. Ezt az [Aspose.Words for Java](https://products.aspose.com/words/Java/) API használatával teheti meg. A bájttömb beszerzése után SQL utasítás segítségével tárolhatja az adatbázisban. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-rtf/" name="PDF Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-wordml/" name="PDF Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-odt/" name="PDF Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-flatopc/" name="PDF Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ps/" name="PDF Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-pcl/" name="PDF Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-mhtml/" name="PDF Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dotm/" name="PDF Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ott/" name="PDF Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dotx/" name="PDF Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-xamlflow/" name="PDF Nak nek XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-markdown/" name="PDF Nak nek MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}