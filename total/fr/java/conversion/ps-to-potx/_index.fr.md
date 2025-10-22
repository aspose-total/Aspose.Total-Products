---
title: Convertir PS en POTX via l'API Java
description: API Java pour convertir PS en POTX sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPTM POWERPOINT POT PPSM POTX PPSX PPS PPT POTM OTP XAML SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter PS vers POTX" h2="Exportez PS vers POTX via l'API Java sur site sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez facilement convertir PS en POTX dans n'importe quelle application Java J2SE, J2EE, J2ME. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter PS vers PPTX. Après cela, en utilisant l'API de traitement PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), vous pouvez convertir PPTX en POTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir PS en POTX" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez PS en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format POTX à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Potx` comme format de sauvegarde
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
Après avoir converti PS en POTX, vous pouvez également ajouter un type de vue prédéfini pour votre présentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fournit une fonction permettant de définir le type d'affichage de la présentation générée lorsqu'elle est ouverte dans PowerPoint via [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La propriété [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) est utilisée pour définir le type de vue à l'aide de [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) énumérateur. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

La conversion de fichiers PS (PostScript) en POTX (modèle PowerPoint sans macros) permet aux équipes de créer des modèles de présentation propres et réutilisables tout en évitant les risques de sécurité liés aux macros. POTX préserve la conception et la mise en page PS dans un format de modèle sécurisé.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

* Transformation des diapositives PS en modèles réutilisables sans macro.
* Normalisation des présentations de formation ou éducatives.
* Migration des visuels marketing PS dans PowerPoint pour une image de marque cohérente.
* Préparation de modèles de diapositives professionnels sans soucis d'automatisation.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

* Conversion automatisée par lot de PS en POTX pour les bibliothèques de modèles.
* Intégration dans les systèmes de gestion de présentations d'entreprise.
* Mises à jour planifiées des modèles de présentation à partir de fichiers PS.
* Optimisation de la mise en page assistée par IA et extraction de diapositives à partir du contenu PS.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}