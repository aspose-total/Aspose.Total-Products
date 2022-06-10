---
title: API Java pour exporter CGM vers DOTX
description: Convertir CGM en DOTX à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/cgm-to-dotx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTX
otherformats: WORDML XAMLFLOW DOT OTT ODT RTF DOTM MHTML PCL PS FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez CGM en DOTX via Java" h2="API Java sur site pour rendre CGM en DOTX sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir CGM en DOTX en utilisant deux étapes simples. Vous devez d'abord rendre le fichier CGM au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en DOTX. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir CGM en DOTX" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format DOTX à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez DOTX en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de CGM en DOTX, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le CGM à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document CGM protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier DOTX, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre DOTX dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTX);
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
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-rtf/" name="CGM Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-wordml/" name="CGM Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-odt/" name="CGM Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-flatopc/" name="CGM Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-ps/" name="CGM Pour PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-pcl/" name="CGM Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-mhtml/" name="CGM Pour MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-dotm/" name="CGM Pour DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-ott/" name="CGM Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-dotx/" name="CGM Pour DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-xamlflow/" name="CGM Pour XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/cgm-to-markdown/" name="CGM Pour MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}