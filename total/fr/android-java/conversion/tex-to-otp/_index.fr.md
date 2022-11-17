---
title: Exporter TEX vers OTP dans Android
description: API Android pour convertir TEX en OTP sans utiliser Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: OTP
otherformats: ODP PPS PPT XAML POTM PPSX POT POWERPOINT SWF PPSM POTX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir TEX en OTP sur Android via Java" h2="Transformez TEX en OTP dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez intégrer la fonctionnalité de conversion TEX en OTP dans vos applications Android en suivant deux étapes simples. Dans la première étape, vous pouvez exporter TEX vers PPTX en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Après cela, en utilisant [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez convertir PPTX en OTP. Les deux API relèvent du package [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter TEX vers OTP" %}}
1. Ouvrez le fichier TEX à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez TEX en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format OTP à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Otp` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) et [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier TEX protégé par mot de passe dans Android via Java" %}}
Lors du chargement du format de fichier TEX, votre document peut être protégé par un mot de passe. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.
{{% blocks/products/pf/feature-page-code %}}

```java
// open TEX document
Document doc = new Document("input.tex", "Your@Password");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Créer une image miniature du fichier OTP dans les applications Android" %}}
Après avoir converti TEX en OTP, vous pouvez également créer des images miniatures de votre document de sortie. En utilisant la riche fonctionnalité [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez générer des images miniatures des diapositives en créant une instance de la [Présentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Après cela, vous pouvez obtenir la référence de n'importe quelle diapositive souhaitée en utilisant son ID ou son index et obtenir l'image miniature de la diapositive référencée à une échelle spécifiée.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-otp/" name="TEX À OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-pps/" name="TEX À PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-ppt/" name="TEX À PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-xaml/" name="TEX À XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-potm/" name="TEX À POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-ppsx/" name="TEX À PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-pot/" name="TEX À POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-powerpoint/" name="TEX À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-swf/" name="TEX À SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-ppsm/" name="TEX À PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-potx/" name="TEX À POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/tex-to-pptm/" name="TEX À PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}