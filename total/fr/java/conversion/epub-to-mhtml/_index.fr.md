---
title: API Java pour exporter EPUB vers MHTML
description: Convertir EPUB en MHTML à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/epub-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MHTML
otherformats: PS WORDML MARKDOWN PCL ODT RTF FLATOPC OTT XAMLFLOW DOTX MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez EPUB en MHTML via Java" h2="API Java sur site pour rendre EPUB en MHTML sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir EPUB en MHTML en utilisant deux étapes simples. Vous devez d'abord rendre le fichier EPUB au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en MHTML. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir EPUB en MHTML" %}}
1. Ouvrez le fichier EPUB à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez EPUB en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format MHTML à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez MHTML en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de EPUB en MHTML, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le EPUB à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document EPUB protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier MHTML, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre MHTML dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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
Convertir **EPUB en MHTML (Web Archive)** est important pour générer des **documents web à fichier unique** à partir de publications numériques. Les fichiers MHTML regroupent toutes les ressources - HTML, images et styles - dans une archive, garantissant la portabilité, la lisibilité hors ligne et la compatibilité avec les navigateurs. En transformant l'EPUB en MHTML, les éditeurs, les éducateurs et les entreprises peuvent fournir des livres électroniques sous forme de documents web autonomes optimisés pour une utilisation en ligne et hors ligne.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}
- **Lecture hors ligne d'e-books** - Fournir des livres numériques complets accessibles sans connexion Internet.
- **Archivage web** - Préserver le contenu des livres électroniques sous forme d'archives compatibles avec les navigateurs en un seul fichier.
- **Publication numérique pour navigateurs** - Partager le contenu EPUB dans un format web prêt à être ouvert.
- **Emballage de contenu éducatif** - Distribuer des leçons, des matériels d'étude et des livres électroniques dans des fichiers portables.
- **Flux de travail de documentation d'entreprise** - Rationaliser la publication interne en documents prêts pour les navigateurs.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}
- **Pipelines EPUB vers MHTML** - Automatiser la conversion de publications numériques en archives web à fichier unique.
- **Flux de travail automatisé d'e-books vers le web** - Simplifier la publication d'EPUB directement dans des formats pris en charge par les navigateurs.
- **Publication en masse pour un accès hors ligne** - Convertir des bibliothèques entières d'e-books en MHTML pour la portabilité.
- **Publication compatible avec les navigateurs multiplateformes** - Garantir une lecture fluide sur tous les principaux navigateurs.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}