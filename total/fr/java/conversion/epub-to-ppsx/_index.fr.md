---
title: Convertir EPUB en PPSX via l'API Java
description: API Java pour convertir EPUB en PPSX sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: POWERPOINT XAML PPTM PPT PPSM OTP PPS POT POTM POTX SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter EPUB vers PPSX" h2="Exportez EPUB vers PPSX via l'API Java sur site sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez facilement convertir EPUB en PPSX dans n'importe quelle application Java J2SE, J2EE, J2ME. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter EPUB vers PPTX. Après cela, en utilisant l'API de traitement PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), vous pouvez convertir PPTX en PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir EPUB en PPSX" %}}
1. Ouvrez le fichier EPUB à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez EPUB en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format PPSX à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Ppsx` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors du chargement du format de fichier EPUB, votre document peut être protégé par un mot de passe. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier EPUB crypté via Java" %}}
Après avoir converti EPUB en PPSX, vous pouvez également ajouter un type de vue prédéfini pour votre présentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fournit une fonction permettant de définir le type d'affichage de la présentation générée lorsqu'elle est ouverte dans PowerPoint via [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La propriété [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) est utilisée pour définir le type de vue à l'aide de [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) énumérateur. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
La conversion **EPUB en PPSX (PowerPoint Open XML Show)** est essentielle pour générer des **fichiers de diaporama modernes** à partir d'eBooks. Les fichiers PPSX fournissent un format basé sur XML ouvert pour les diaporamas qui se lancent directement en mode présentation, garantissant ainsi une compatibilité et un affichage professionnel. En transformant l'EPUB en PPSX, les éducateurs, les éditeurs et les entreprises peuvent livrer efficacement des présentations soignées, rationaliser le partage de contenu et maintenir une cohérence sur les affichages numériques et en direct.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}
- **Présentations de prévisualisation** – Présentez le contenu de l'eBook sous forme de diapositives interactives pour les clients ou les lecteurs.
- **Cours académiques** – Convertissez le contenu des manuels scolaires en diapositives de cours prêtes à être diffusées.
- **Présentations de documents de recherche** – Livrez des diapositives structurées pour des conférences et des séminaires.
- **Présentations d'entreprise** – Présentez les documents d'entreprise dans un format de diaporama professionnel et moderne.
- **Sessions de formation** – Créez des diapositives pédagogiques pour des ateliers et des programmes d'apprentissage en ligne.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}
- **Pipelines EPUB vers PPSX** – Automatisez la conversion d'eBooks en fichiers de diaporama modernes.
- **Génération automatisée de diaporamas** – Produisez des diapositives prêtes à être diffusées directement à partir de publications numériques.
- **Conversion en masse d'eBooks en PowerPoint** – Convertissez efficacement plusieurs eBooks en présentations.
- **Flux de travail de publication au niveau de l'entreprise** – Intégrez la génération de PPSX dans des systèmes de distribution de présentations à grande échelle et de gestion de contenu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}