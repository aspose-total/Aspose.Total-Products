---
title: Convertir PS en PPS via l'API Java
description: API Java pour convertir PS en PPS sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/ps-to-pps/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPS
otherformats: PPSM PPS POTM XAML POT PPT OTP POWERPOINT POTX SWF PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter PS vers PPS" h2="Exportez PS vers PPS via l'API Java sur site sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez facilement convertir PS en PPS dans n'importe quelle application Java J2SE, J2EE, J2ME. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter PS vers PPTX. Après cela, en utilisant l'API de traitement PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), vous pouvez convertir PPTX en PPS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir PS en PPS" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez PS en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format PPS à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Pps` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors du chargement du format de fichier PS, votre document peut être protégé par un mot de passe. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier PS crypté via Java" %}}
Après avoir converti PS en PPS, vous pouvez également ajouter un type de vue prédéfini pour votre présentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fournit une fonction permettant de définir le type d'affichage de la présentation générée lorsqu'elle est ouverte dans PowerPoint via [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La propriété [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) est utilisée pour définir le type de vue à l'aide de [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) énumérateur. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}

La conversion de fichiers PS (PostScript) en PPS (PowerPoint Show) permet de présenter directement des diapositives PostScript statiques en mode diaporama. Le format PPS est idéal pour les présentations client, les démonstrations ou les environnements d'affichage automatisé.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

* Transformation des ensembles de diapositives PS en présentations prêtes à être lues.
* Préparation de visuels marketing basés sur PS pour des démonstrations en direct.
* Création de contenu éducatif interactif à partir de diapositives PostScript.
* Livraison de diapositives techniques ou d'entreprise dans un format prêt pour la présentation.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

* Conversion en lot de PS en PPS pour des présentations de formation ou de vente.
* Génération planifiée de fichiers PPS à partir de rapports PS archivés.
* Intégration avec des systèmes de gestion de présentation pour une livraison automatisée.
* Conversion de mise en page assistée par IA pour garantir la fidélité en mode diaporama.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}