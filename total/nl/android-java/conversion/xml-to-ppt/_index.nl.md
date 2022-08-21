---
title: XML exporteren naar PPT in Android
description: Android API om XML naar PPT te converteren zonder Microsoft Word te gebruiken
url: /nl/android-java/conversion/xml-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: PPT
otherformats: ODP OTP POT POTM SWF PPSX POTX PPS XAML POWERPOINT PPTM PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer XML naar PPT op Android via Java" h2="Transformeer XML naar PPT binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> PowerPoint of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van XML naar PPT in uw Android-applicaties integreren met behulp van twee eenvoudige stappen. In de eerste stap kunt u XML naar PPTX exporteren met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Daarna kunt u met [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) PPTX naar PPT converteren. Beide API's vallen onder het pakket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om XML naar PPT te exporteren" %}}
1. Open het XML-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer XML naar PPTX met behulp van de [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) methode
3. Laad het PPTX-document met behulp van de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Sla het document op in PPT-formaat met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) methode en stel ` Ppt` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd XML-bestand in Android via Java" %}}
Tijdens het laden van de XML-bestandsindeling is uw document mogelijk beveiligd met een wachtwoord. Met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kunt u ook versleutelde documenten openen. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) initialiseren .lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een miniatuurafbeelding van het PPT-bestand in Android-applicaties" %}}
Na het converteren van XML naar PPT, kunt u ook miniatuurafbeeldingen van uw uitvoerdocument maken. Door de uitgebreide functie [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) te gebruiken, kunt u miniatuurafbeeldingen van de dia's genereren door de [Presentatie]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) klasse. Daarna kunt u de referentie van elke gewenste dia verkrijgen door de ID of index te gebruiken en de miniatuurafbeelding van de dia waarnaar wordt verwezen op een gespecificeerde schaal krijgen.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-ppt/" name="XML Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-otp/" name="XML Tot OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-pot/" name="XML Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-potm/" name="XML Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-swf/" name="XML Tot SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-ppsx/" name="XML Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-potx/" name="XML Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-pps/" name="XML Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-xaml/" name="XML Tot XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-powerpoint/" name="XML Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-pptm/" name="XML Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xml-to-ppsm/" name="XML Tot PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}