---
title: API Java pour exporter PS vers DOTM
description: Convertir PS en DOTM à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/ps-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DOTM
otherformats: DOTM OTT MHTML WORDML RTF XAMLFLOW ODT DOTX FLATOPC MARKDOWN PCL DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez PS en DOTM via Java" h2="API Java sur site pour rendre PS en DOTM sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir PS en DOTM en utilisant deux étapes simples. Vous devez d'abord rendre le fichier PS au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en DOTM. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir PS en DOTM" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez PS en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format DOTM à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez DOTM en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de PS en DOTM, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le PS à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document PS protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier DOTM, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre DOTM dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
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
```
{{< blocks/products/pf/agp/feature-section >}}

La conversion de fichiers PS (PostScript) en DOTM (Modèle activé par macro Word) combine la normalisation des modèles avec l'automatisation. Les utilisateurs peuvent réutiliser des mises en page tout en exploitant des macros pour automatiser la population de documents, les calculs ou la mise en forme.

{{% blocks/products/pf/agp/feature-section-col title="Principaux cas d'utilisation" %}}

* Transformation de rapports PS en modèles Word réutilisables activés par macro.
* Automatisation de la création de contrats ou de factures avec des mises en page dérivées de PostScript.
* Intégration de tables et graphiques générés par PS dans des modèles DOTM.
* Création de formulaires interactifs pour les flux de travail RH, financiers ou opérationnels.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

* Conversion en masse de PS en DOTM dans l'automatisation des flux de travail d'entreprise.
* Intégration avec des systèmes de génération de documents pour des tâches pilotées par macro.
* Population assistée par l'IA de modèles avec du contenu extrait de PS.
* Génération planifiée de modèles activés par macro pour répondre aux besoins de reporting récurrents.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}