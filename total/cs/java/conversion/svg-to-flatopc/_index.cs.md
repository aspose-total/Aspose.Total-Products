---
title: Java API pro export SVG do FLATOPC
description: Převeďte SVG na FLATOPC pomocí on premise Java API
url: /cs/java/conversion/svg-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: FLAT_OPC
otherformats: PCL ODT DOTM WORDML FLATOPC MARKDOWN XAMLFLOW RTF DOTX MHTML OTT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformujte SVG na FLATOPC přes Java" h2="On Premise Java API pro vykreslení SVG do FLATOPC bez použití jakékoli aplikace třetí strany" >}}
{{% blocks/products/pf/feature-page-summary %}}
SVG můžete převést na FLATOPC pomocí dvou jednoduchých kroků. Nejprve musíte vykreslit soubor SVG do DOC pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for Java](https://products.aspose.com/words/java/) převést DOC na FLATOPC. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod SVG na FLATOPC" %}}
1. Otevřete soubor SVG pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte SVG na DOC pomocí [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu FLATOPC pomocí metody [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte FLATOPC jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}](
Při převodu SVG na FLATOPC, i když je váš dokument chráněn heslem, jej stále můžete otevřít pomocí rozhraní API pro manipulaci s PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Chcete-li otevřít zašifrovaný soubor, musíte vytvořit objekt [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) a otevřít SVG pomocí hesla vlastníka.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.svg", "password");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete dokument SVG chráněný heslem přes Java" %}}
Při ukládání vstupního dokumentu do formátu souboru FLATOPC můžete také dokument uložit do databáze namísto systému souborů. Možná budete muset implementovat ukládání a načítání objektů Document do az databáze. To by bylo nutné, pokud byste implementovali jakýkoli typ systému pro správu obsahu. Aby bylo možné uložit váš FLATOPC do databáze, je často nutné dokument serializovat a získat tak bajtové pole. To lze provést pomocí rozhraní API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po získání bajtového pole jej můžete uložit do databáze pomocí příkazu SQL. 
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
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-rtf/" name="SVG Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-wordml/" name="SVG Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-odt/" name="SVG Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-flatopc/" name="SVG Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-ps/" name="SVG Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-pcl/" name="SVG Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-mhtml/" name="SVG Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-dotm/" name="SVG Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-ott/" name="SVG Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-dotx/" name="SVG Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xamlflow/" name="SVG Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-markdown/" name="SVG Na MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}