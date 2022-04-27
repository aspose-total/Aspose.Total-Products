---
title: Java API om XPS naar WORDML te exporteren
description: Converteer XPS naar WORDML met behulp van on-premise Java API
url: /nl/java/conversion/xps-to-wordml/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: WORD_ML
otherformats: MHTML PS DOTM PCL MARKDOWN FLATOPC XAMLFLOW WORDML DOTX RTF OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformeer XPS naar WORDML via Java" h2="On Premise Java API om XPS naar WORDML te renderen zonder een applicatie van derden te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
U kunt XPS naar WORDML converteren met behulp van twee eenvoudige stappen. Eerst moet u het XPS-bestand naar DOC renderen met [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC naar WORDML converteren. Beide API's vallen onder het pakket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API om XPS naar WORDML te converteren" %}}
1. Open het XPS-bestand met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer XPS naar DOC met behulp van [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in WORDML-formaat met behulp van [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) methode en stel WORDML in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Words voor Java](https://docs.aspose.com/words/java/ installatie/) in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WORD_ML
outputDocument.save("output.word_ml", SaveFormat.WORD_ML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Tijdens het converteren van XPS naar WORDML kunt u, zelfs als uw document met een wachtwoord is beveiligd, het nog steeds openen met de PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Om het versleutelde bestand te openen, moet u een [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)-object maken en de XPS openen met het wachtwoord van de eigenaar.  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd XPS-document via Java" %}}
Terwijl u uw invoerdocument opslaat in WORDML-bestandsindeling, kunt u uw document ook opslaan in een database in plaats van in een bestandssysteem. Mogelijk moet u het opslaan en ophalen van documentobjecten van en naar een database implementeren. Dit zou nodig zijn als u een inhoudsbeheersysteem zou implementeren. Om uw WORDML in de database op te slaan, is het vaak nodig om het document te serialiseren om een bytearray te verkrijgen. Dit kan worden gedaan met behulp van [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Nadat u uw byte-array hebt ontvangen, kunt u deze in de database opslaan met behulp van een SQL-instructie. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.WORD_ML);
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
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-rtf/" name="XPS Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-wordml/" name="XPS Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-odt/" name="XPS Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-flatopc/" name="XPS Tot FLATotPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-ps/" name="XPS Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-pcl/" name="XPS Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-mhtml/" name="XPS Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-dotm/" name="XPS Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-ott/" name="XPS Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-dotx/" name="XPS Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-xamlflow/" name="XPS Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xps-to-markdown/" name="XPS Tot MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}