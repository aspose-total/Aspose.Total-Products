---
title: Exporter PCL vers POTX dans Android
description: API Android pour convertir PCL en POTX sans utiliser Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: POTX
otherformats: OTP POTM PPSM ODP POWERPOINT PPTM POT XAML PPSX PPS PPT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir PCL en POTX sur Android via Java" h2="Transformez PCL en POTX dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez intégrer la fonctionnalité de conversion PCL en POTX dans vos applications Android en suivant deux étapes simples. Dans la première étape, vous pouvez exporter PCL vers PPTX en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Après cela, en utilisant [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez convertir PPTX en POTX. Les deux API relèvent du package [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter PCL vers POTX" %}}
1. Ouvrez le fichier PCL à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez PCL en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format POTX à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Potx` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://releases.aspose.com/total/java/)cs.aspose.com/pdf/androidjava/installation/) et [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier PCL protégé par mot de passe dans Android via Java" %}}
Lors du chargement du format de fichier PCL, votre document peut être protégé par un mot de passe. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Créer une image miniature du fichier POTX dans les applications Android" %}}
Après avoir converti PCL en POTX, vous pouvez également créer des images miniatures de votre document de sortie. En utilisant la riche fonctionnalité [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez générer des images miniatures des diapositives en créant une instance de la [Présentationreference.aspose.com/slides/java/com.aspose.slides/Presentation). Après cela, vous pouvez obtenir la référence de n'importe quelle diapositive souhaitée en utilisant son ID ou son index et obtenir l'image miniature de la diapositive référencée à une échelle spécifiée.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}