---
title: Java API om PDF naar DOTM te exporteren
description: Converteer PDF naar DOTM met behulp van on-premise Java API
url_ignore: /nl/java/conversion/pdf-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: DOTM
otherformats: MARKDOWN ODT PCL WORDML XAMLFLOW DOTM RTF DOTX MHTML FLATOPC OTT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformeer PDF naar DOTM via Java" h2="On Premise Java API om PDF naar DOTM te renderen zonder een applicatie van derden te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
U kunt PDF naar DOTM converteren met behulp van twee eenvoudige stappen. Eerst moet u het PDF-bestand naar DOC renderen met [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC naar DOTM converteren. Beide API's vallen onder het pakket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API om PDF naar DOTM te converteren" %}}
1. Open het PDF-bestand met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer PDF naar DOC met behulp van [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in DOTM-formaat met behulp van [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) methode en stel DOTM in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Words voor Java](https://docs.aspose.com/words/java/installation/) in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Tijdens het converteren van PDF naar DOTM kunt u, zelfs als uw document met een wachtwoord is beveiligd, het nog steeds openen met de PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Om het versleutelde bestand te openen, moet u een [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)-object maken en de PDF openen met het wachtwoord van de eigenaar.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd PDF-document via Java" %}}
Terwijl u uw invoerdocument opslaat in DOTM-bestandsindeling, kunt u uw document ook opslaan in een database in plaats van in een bestandssysteem. Mogelijk moet u het opslaan en ophalen van documentobjecten van en naar een database implementeren. Dit zou nodig zijn als u een inhoudsbeheersysteem zou implementeren. Om uw DOTM in de database op te slaan, is het vaak nodig om het document te serialiseren om een bytearray te verkrijgen. Dit kan worden gedaan met behulp van [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Nadat u uw byte-array hebt ontvangen, kunt u deze in de database opslaan met behulp van een SQL-instructie. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-rtf/" name="PDF Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-wordml/" name="PDF Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-odt/" name="PDF Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-flatopc/" name="PDF Tot FLATotPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-ps/" name="PDF Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-pcl/" name="PDF Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-mhtml/" name="PDF Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-dotm/" name="PDF Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-ott/" name="PDF Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-dotx/" name="PDF Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-xamlflow/" name="PDF Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pdf-to-markdown/" name="PDF Tot MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}