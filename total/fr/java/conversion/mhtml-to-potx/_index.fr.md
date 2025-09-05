---
title: Conversion en ligne de MHTML en POTX ou développement d'une application basée sur Java pour convertir des fichiers MHTML
description: Application en ligne gratuite pour convertir des fichiers MHTML en POTX. Code de bibliothèque de conversion Java pour les documents MHTML. 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: POTX
otherformats: POTX POTM PPS SWF PPT PPSM PPSX POT XAML PPTM POWERPOINT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Application de conversion en ligne MHTML en POTX et code Java pour convertir les fichiers MHTML" h2="Développer une puissante application de conversion et d'exportation MHTML basée sur Java. Convertissez un ou plusieurs fichiers MHTML en POTX et d'autres formats via l'API d'automatisation Java. Convertissez librement les fichiers MHTML en ligne via l'application avec téléchargement instantané." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Application de conversion en ligne gratuite MHTML vers POTX" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=potx&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertissez des fichiers MHTML en POTX en ligne à l'aide de l'application" %}}

1. Téléchargez les fichiers MHTML à convertir
1. Attendez quelques secondes ou plus selon la taille de MHTML
1. Gardez un œil sur la barre d'état de téléchargement
1. Cliquez sur le bouton « Convertir »
1. MHTML sera converti en document POTX
1. Téléchargez le fichier POTX converti

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir MHTML en POTX via l'API d'automatisation Java" %}}


1. Ouvrez le fichier MHTML à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez MHTML en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format POTX à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Potx` comme format de sauvegarde



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Quelques cas supplémentaires pour enregistrer MHTML dans POTX avec d'autres fonctionnalités comme Exigences de conversion, Ouvrir le fichier MHTML crypté via Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Développer une application de conversion de fichiers MHTML à l'aide de Java</h2>

Besoin de développer une application logicielle basée sur Java pour enregistrer et exporter facilement des fichiers MHTML vers un document POTX ? Avec [Aspose.Total for Java](https://products.aspose.com/total/fr/java/), tout développeur Java peut intégrer le code API ci-dessus pour programmer l'application de conversion dans divers formats, notamment Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, fichiers de courrier électronique, images (JPG, PNG, BMP, GIF) et d'autres formats. Bibliothèque Java puissante pour la conversion de documents, prend en charge de nombreux formats populaires, y compris le format MHTML. Pour exporter et restituer des documents vers d'autres formats, les programmeurs peuvent utiliser les API enfants Aspose.Total for Java, notamment [Aspose.Words for Java](https://products.aspose.com/words/fr/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/fr/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/fr/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/fr/java/) et plus.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque de conversion MHTML pour Java" %}}

Il existe des options alternatives pour intégrer Aspose.Total for Java sur votre système. Veuillez choisir celui qui correspond à vos besoins et suivez les instructions étape par étape :<br /><br />

- Utilisez Aspose.Total for Java directement à partir d'un projet basé sur Maven et incluez l'API enfant pertinente dans pom.xml.
- Alternativement, on peut obtenir un fichier ZIP à partir de [Téléchargements](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Enregistrement de MHTML dans les exigences de l'application POTX" %}}

Tout système d’exploitation capable d’exécuter Java Runtime Environment (JRE) peut exécuter Aspose.Total for Java. La liste suivante répertorie principalement, mais pas tous, les systèmes d'exploitation pris en charge. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS et autres
- macOS : 10.9 (Mavericks) et versions ultérieures
- Mobile : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}