---
title: API Java pour exporter MD vers GIF
description: Convertir MD en GIF à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/md-to-gif/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: GIF
otherformats: FLATOPC OTT MHTML DOTX WORDML GIF DOT DOTM PCL ODT RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez MD en GIF via Java" h2="API Java sur site pour rendre MD en GIF sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir MD en GIF en utilisant deux étapes simples. Vous devez d'abord rendre le fichier MD au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en GIF. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir MD en GIF" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez MD en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format GIF à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez GIF en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de MD en GIF, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le MD à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document MD protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier GIF, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre GIF dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
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
{{< blocks/products/pf/agp/feature-section >}}



La conversion de Markdown (MD) en GIF permet de transformer le contenu textuel, les diagrammes ou les organigrammes en animations en boucle. Les GIF sont largement pris en charge, ce qui les rend adaptés aux tutoriels, au contenu des médias sociaux et aux visuels interactifs légers.



{{% blocks/products/pf/agp/feature-section-col title="Principaux cas d'utilisation" %}}



* Conversion des organigrammes Markdown en GIFs pédagogiques.

* Fiches de triche animées pour le codage ou les flux de documentation.

* Visualisations conviviales pour les médias sociaux issues de notes Markdown.

* Illustrations en boucle pour les guides techniques ou les démonstrations de logiciels.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Génération automatisée de GIF à partir des mises à jour de la documentation Markdown.

* Traitement par lots de plusieurs diagrammes Markdown en GIF.

* Intégration avec les pipelines de contenu pour produire des GIFs pour les portails en ligne.

* Conversion planifiée de Markdown en GIF pour les plateformes marketing ou éducatives.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}