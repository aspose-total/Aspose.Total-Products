---
title: EPUB exporteren naar PPT in Android
description: Android API om EPUB naar PPT te converteren zonder Microsoft Word te gebruiken
url: /nl/android-java/conversion/epub-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPT
otherformats: PPS POT OTP XAML PPTM PPSM PPSX POTX SWF ODP POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer EPUB naar PPT op Android via Java" h2="Transformeer EPUB naar PPT binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> PowerPoint of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van EPUB naar PPT in uw Android-applicaties integreren met behulp van twee eenvoudige stappen. In de eerste stap kunt u EPUB naar PPTX exporteren met [Aspose.PDF voor Android via Java](https://products.aspose.com/pdf/android-java/). Daarna kunt u met [Aspose.Slides voor Android via Java](https://products.aspose.com/slides/android-java/) PPTX naar PPT converteren. Beide API's vallen onder het pakket [Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om EPUB naar PPT te exporteren" %}}
1. Open het EPUB-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer EPUB naar PPTX met behulp van de [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) methode
3. Laad het PPTX-document met behulp van de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Sla het document op in PPT-formaat met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) methode en stel ` Ppt` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF voor Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Slides voor Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd EPUB-bestand in Android via Java" %}}
Tijdens het laden van de EPUB-bestandsindeling is uw document mogelijk beveiligd met een wachtwoord. Met [Aspose.PDF voor Android via Java](https://products.aspose.com/pdf/android-java/) kunt u ook versleutelde documenten openen. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) initialiseren .lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een miniatuurafbeelding van het PPT-bestand in Android-applicaties" %}}
Na het converteren van EPUB naar PPT, kunt u ook miniatuurafbeeldingen van uw uitvoerdocument maken. Door de uitgebreide functie [Aspose.Slides voor Android via Java](https://products.aspose.com/slides/android-java/) te gebruiken, kunt u miniatuurafbeeldingen van de dia's genereren door de [Presentatie]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) klasse. Daarna kunt u de referentie van elke gewenste dia verkrijgen door de ID of index te gebruiken en de miniatuurafbeelding van de dia waarnaar wordt verwezen op een gespecificeerde schaal krijgen.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("output.ppt");
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-pps/" name="EPUB Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-pot/" name="EPUB Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-otp/" name="EPUB Tot OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-xaml/" name="EPUB Tot XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-pptm/" name="EPUB Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-ppsm/" name="EPUB Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-ppsx/" name="EPUB Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-potx/" name="EPUB Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-swf/" name="EPUB Tot SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-ppt/" name="EPUB Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-potm/" name="EPUB Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-powerpoint/" name="EPUB Tot POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}