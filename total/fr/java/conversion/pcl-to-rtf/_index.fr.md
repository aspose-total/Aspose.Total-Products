---
title: Conversion en ligne de PCL en RTF ou développement d'une application basée sur Java pour convertir des fichiers PCL
description: Application en ligne gratuite pour convertir des fichiers PCL en RTF. Code de bibliothèque de conversion Java pour les documents PCL. 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: RTF
otherformats: ODT WORDML DOTM FLATOPC DOTX MARKDOWN MHTML OTT XAMLFLOW PS RTF DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Application de conversion en ligne PCL en RTF et code Java pour convertir les fichiers PCL" h2="Développer une puissante application de conversion et d'exportation PCL basée sur Java. Convertissez un ou plusieurs fichiers PCL en RTF et d'autres formats via l'API d'automatisation Java. Convertissez librement les fichiers PCL en ligne via l'application avec téléchargement instantané." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Application de conversion en ligne gratuite PCL vers RTF" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=rtf&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertissez des fichiers PCL en RTF en ligne à l'aide de l'application" %}}

1. Téléchargez les fichiers PCL à convertir
1. Attendez quelques secondes ou plus selon la taille de PCL
1. Gardez un œil sur la barre d'état de téléchargement
1. Cliquez sur le bouton « Convertir »
1. PCL sera converti en document RTF
1. Téléchargez le fichier RTF converti

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir PCL en RTF via l'API d'automatisation Java" %}}


1. Ouvrez le fichier PCL à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez PCL en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format RTF à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez RTF en tant que format de sauvegarde



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bfec283bb7a30344c355fa8754a3e3a7" "convert-pcl-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Quelques cas supplémentaires pour enregistrer PCL dans RTF avec d'autres fonctionnalités comme Exigences de conversion, Ouvrir un document PCL protégé par mot de passe via Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.pcl", "password");
// save PCL as a DOC 
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

<h2>Développer une application de conversion de fichiers PCL à l'aide de Java</h2>

Besoin de développer une application logicielle basée sur Java pour enregistrer et exporter facilement des fichiers PCL vers un document RTF ? Avec [Aspose.Total for Java](https://products.aspose.com/total/fr/java/), tout développeur Java peut intégrer le code API ci-dessus pour programmer l'application de conversion dans divers formats, notamment Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, fichiers de courrier électronique, images (JPG, PNG, BMP, GIF) et d'autres formats. Bibliothèque Java puissante pour la conversion de documents, prend en charge de nombreux formats populaires, y compris le format PCL. Pour exporter et restituer des documents vers d'autres formats, les programmeurs peuvent utiliser les API enfants Aspose.Total for Java, notamment [Aspose.Words for Java](https://products.aspose.com/words/fr/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/fr/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/fr/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/fr/java/) et plus.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque de conversion PCL pour Java" %}}

Il existe des options alternatives pour intégrer Aspose.Total for Java sur votre système. Veuillez choisir celui qui correspond à vos besoins et suivez les instructions étape par étape :<br /><br />

- Utilisez Aspose.Total for Java directement à partir d'un projet basé sur Maven et incluez l'API enfant pertinente dans pom.xml.
- Alternativement, on peut obtenir un fichier ZIP à partir de [Téléchargements](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Enregistrement de PCL dans les exigences de l'application RTF" %}}

Tout système d’exploitation capable d’exécuter Java Runtime Environment (JRE) peut exécuter Aspose.Total for Java. La liste suivante répertorie principalement, mais pas tous, les systèmes d'exploitation pris en charge. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS et autres
- macOS : 10.9 (Mavericks) et versions ultérieures
- Mobile : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}

**Conversion de PCL en RTF** permet de transformer les sorties du **Langage de Commande d'Imprimante** en documents au format **Rich Text Format (RTF)** pour une compatibilité étendue, une édition facile et une utilisation multiplateforme.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

* Conversion de documents imprimés en fichiers texte enrichi modifiables
* Préservation de la mise en forme de base tout en assurant la portabilité
* Partage de rapports générés par impression sur plusieurs traitements de texte
* Préparation de versions de documents légères pour une utilisation archivistique

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

* Conversion par lot de fichiers d'impression PCL en RTF pour distribution
* Intégration de pipelines PCL-en-RTF dans les systèmes d'entreprise
* Génération automatisée de rapports textuels formatés à partir de données d'impression

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}