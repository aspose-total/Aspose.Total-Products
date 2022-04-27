---
title: Java API pro export TEX do OTT
description: Převeďte TEX na OTT pomocí on premise Java API
url: /cs/java/conversion/tex-to-ott/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: OTT
otherformats: MARKDOWN DOT OTT ODT PS DOTX PCL XAMLFLOW DOTM FLATOPC RTF MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformujte TEX na OTT přes Java" h2="On Premise Java API pro vykreslení TEX do OTT bez použití jakékoli aplikace třetí strany" >}}
{{% blocks/products/pf/feature-page-summary %}}
TEX můžete převést na OTT pomocí dvou jednoduchých kroků. Nejprve musíte vykreslit soubor TEX do DOC pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for Java](https://products.aspose.com/words/java/) převést DOC na OTT. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod TEX na OTT" %}}
1. Otevřete soubor TEX pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte TEX na DOC pomocí [uložit](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu OTT pomocí metody [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte OTT jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Words for Java](https://docs.aspose.com/words/java/ instalace/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.OTT
outputDocument.save("output.ott", SaveFormat.OTT);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}](
Při převodu TEX na OTT, i když je váš dokument chráněn heslem, jej stále můžete otevřít pomocí rozhraní API pro manipulaci s PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Chcete-li otevřít zašifrovaný soubor, musíte vytvořit objekt [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) a otevřít TEX pomocí hesla vlastníka.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete dokument TEX chráněný heslem přes Java" %}}
Při ukládání vstupního dokumentu do formátu souboru OTT můžete také dokument uložit do databáze namísto systému souborů. Možná budete muset implementovat ukládání a načítání objektů Document do az databáze. To by bylo nutné, pokud byste implementovali jakýkoli typ systému pro správu obsahu. Aby bylo možné uložit váš OTT do databáze, je často nutné dokument serializovat a získat tak bajtové pole. To lze provést pomocí rozhraní API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po získání bajtového pole jej můžete uložit do databáze pomocí příkazu SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-rtf/" name="TEX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-wordml/" name="TEX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-odt/" name="TEX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-flatopc/" name="TEX Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-ps/" name="TEX Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-pcl/" name="TEX Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-mhtml/" name="TEX Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-dotm/" name="TEX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-ott/" name="TEX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-dotx/" name="TEX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-xamlflow/" name="TEX Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-markdown/" name="TEX Na MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}