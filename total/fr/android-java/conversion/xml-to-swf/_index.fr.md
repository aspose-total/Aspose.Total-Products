---
title: Exporter XML vers SWF dans Android
description: API Android pour convertir XML en SWF sans utiliser Microsoft Word
url: /fr/android-java/conversion/xml-to-swf/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: SWF
otherformats: POTM PPSX ODP XAML PPSM POWERPOINT OTP PPS PPT POT PPTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir XML en SWF sur Android via Java" h2="Transformez XML en SWF dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez intégrer la fonctionnalité de conversion XML en SWF dans vos applications Android en suivant deux étapes simples. Dans la première étape, vous pouvez exporter XML vers PPTX en utilisant [Aspose.PDF pour Android via Java](https://products.aspose.com/pdf/android-java/). Après cela, en utilisant [Aspose.Slides pour Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez convertir PPTX en SWF. Les deux API relèvent du package [Aspose.Total pour Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter XML vers SWF" %}}
1. Ouvrez le fichier XML à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XML en PPTX en utilisant la méthode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format SWF à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Swf` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF pour Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) et [Aspose.Slides pour Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier XML protégé par mot de passe dans Android via Java" %}}
Lors du chargement du format de fichier XML, votre document peut être protégé par un mot de passe. [Aspose.PDF pour Android via Java](https://products.aspose.com/pdf/android-java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer une image miniature du fichier SWF dans les applications Android" %}}
Après avoir converti XML en SWF, vous pouvez également créer des images miniatures de votre document de sortie. En utilisant la riche fonctionnalité [Aspose.Slides pour Android via Java](https://products.aspose.com/slides/android-java/), vous pouvez générer des images miniatures des diapositives en créant une instance de la [Présentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Après cela, vous pouvez obtenir la référence de n'importe quelle diapositive souhaitée en utilisant son ID ou son index et obtenir l'image miniature de la diapositive référencée à une échelle spécifiée.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a SWF file
Presentation presentation = new Presentation("output.swf");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-potm/" name="XML À POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-ppsx/" name="XML À PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-swf/" name="XML À SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-xaml/" name="XML À XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-ppsm/" name="XML À PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-powerpoint/" name="XML À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-otp/" name="XML À OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-pps/" name="XML À PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-ppt/" name="XML À PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-pot/" name="XML À POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-pptm/" name="XML À PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xml-to-potx/" name="XML À POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}