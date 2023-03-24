---
title: MHTML exporteren naar PPSX in Android
description: Android API om MHTML naar PPSX te converteren zonder Microsoft Word te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: PPSX
otherformats: POTM POT PPSM OTP POWERPOINT SWF PPTM POTX XAML PPS ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer MHTML naar PPSX op Android via Java" h2="Transformeer MHTML naar PPSX binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> PowerPoint of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van MHTML naar PPSX in uw Android-applicaties integreren met behulp van twee eenvoudige stappen. In de eerste stap kunt u MHTML naar PPTX exporteren met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Daarna kunt u met [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) PPTX naar PPSX converteren. Beide API's vallen onder het pakket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om MHTML naar PPSX te exporteren" %}}
1. Open het MHTML-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer MHTML naar PPTX met behulp van de [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) methode
3. Laad het PPTX-document met behulp van de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Sla het document op in PPSX-formaat met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) methode en stel ` Ppsx` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://releases.aspose.com/total/java/) en installeer [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd MHTML-bestand in Android via Java" %}}
Tijdens het laden van de MHTML-bestandsindeling is uw document mogelijk beveiligd met een wachtwoord. Met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kunt u ook versleutelde documenten openen. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) initialiseren .lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Maak een miniatuurafbeelding van het PPSX-bestand in Android-applicaties" %}}
Na het converteren van MHTML naar PPSX, kunt u ook miniatuurafbeeldingen van uw uitvoerdocument maken. Door de uitgebreide functie [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) te gebruiken, kunt u miniatuurafbeeldingen van de dia's genereren door de [Presentatie]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) klasse. Daarna kunt u de referentie van elke gewenste dia verkrijgen door de ID of index te gebruiken en de miniatuurafbeelding van de dia waarnaar wordt verwezen op een gespecificeerde schaal krijgen.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}