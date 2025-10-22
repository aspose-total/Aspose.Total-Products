---
title: Conversion en ligne de SVG en RTF ou développement d'une application basée sur Java pour convertir des fichiers SVG
description: Application en ligne gratuite pour convertir des fichiers SVG en RTF. Code de bibliothèque de conversion Java pour les documents SVG. 

family: total
platformtag: Java
feature: conversion
informat: SVG
outformat: RTF
otherformats: PCL PS OTT WORDML XAMLFLOW ODT MARKDOWN MHTML RTF DOTX FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Application de conversion en ligne SVG en RTF et code Java pour convertir les fichiers SVG" h2="Développer une puissante application de conversion et d'exportation SVG basée sur Java. Convertissez un ou plusieurs fichiers SVG en RTF et d'autres formats via l'API d'automatisation Java. Convertissez librement les fichiers SVG en ligne via l'application avec téléchargement instantané." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Application de conversion en ligne gratuite SVG vers RTF" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=rtf&from=svg" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertissez des fichiers SVG en RTF en ligne à l'aide de l'application" %}}

1. Téléchargez les fichiers SVG à convertir
1. Attendez quelques secondes ou plus selon la taille de SVG
1. Gardez un œil sur la barre d'état de téléchargement
1. Cliquez sur le bouton « Convertir »
1. SVG sera converti en document RTF
1. Téléchargez le fichier RTF converti

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir SVG en RTF via l'API d'automatisation Java" %}}


1. Ouvrez le fichier SVG à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez SVG en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format RTF à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez RTF en tant que format de sauvegarde



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "9d35e538d5c86861600eb8a36ddf2ef2" "convert-svg-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Quelques cas supplémentaires pour enregistrer SVG dans RTF avec d'autres fonctionnalités comme Exigences de conversion, Ouvrir un document SVG protégé par mot de passe via Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.svg", "password");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Développer une application de conversion de fichiers SVG à l'aide de Java</h2>

Besoin de développer une application logicielle basée sur Java pour enregistrer et exporter facilement des fichiers SVG vers un document RTF ? Avec [Aspose.Total for Java](https://products.aspose.com/total/fr/java/), tout développeur Java peut intégrer le code API ci-dessus pour programmer l'application de conversion dans divers formats, notamment Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, fichiers de courrier électronique, images (JPG, PNG, BMP, GIF) et d'autres formats. Bibliothèque Java puissante pour la conversion de documents, prend en charge de nombreux formats populaires, y compris le format SVG. Pour exporter et restituer des documents vers d'autres formats, les programmeurs peuvent utiliser les API enfants Aspose.Total for Java, notamment [Aspose.Words for Java](https://products.aspose.com/words/fr/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/fr/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/fr/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/fr/java/) et plus.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque de conversion SVG pour Java" %}}

Il existe des options alternatives pour intégrer Aspose.Total for Java sur votre système. Veuillez choisir celui qui correspond à vos besoins et suivez les instructions étape par étape :<br /><br />

- Utilisez Aspose.Total for Java directement à partir d'un projet basé sur Maven et incluez l'API enfant pertinente dans pom.xml.
- Alternativement, on peut obtenir un fichier ZIP à partir de [Téléchargements](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Enregistrement de SVG dans les exigences de l'application RTF" %}}

Tout système d’exploitation capable d’exécuter Java Runtime Environment (JRE) peut exécuter Aspose.Total for Java. La liste suivante répertorie principalement, mais pas tous, les systèmes d'exploitation pris en charge. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS et autres
- macOS : 10.9 (Mavericks) et versions ultérieures
- Mobile : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}

Convertir un SVG en RTF (Rich Text Format) permet d'intégrer des diagrammes vectoriels dans des documents texte universellement pris en charge. RTF conserve la mise en forme sur différents processeurs de texte et systèmes d'exploitation.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

* Intégration de visuels SVG dans des rapports ou manuels multiplateformes.
* Documents techniques ou éducatifs normalisés avec des graphiques vectoriels.
* Modèles de projet portables incorporant des diagrammes SVG.
* Articles académiques ou présentations nécessitant des formats texte compatibles.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

* Conversion automatisée par lots de SVG en RTF pour la distribution de documents.
* Mises à jour planifiées pour les manuels techniques avec de nouveaux visuels SVG.
* Intégration avec des systèmes de gestion de contenu pour un accès multiplateforme.
* Génération déclenchée de documents RTF pour des flux de travail hors ligne ou portables.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}