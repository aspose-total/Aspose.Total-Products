---
title: Eksportuj XPS do ODP w systemie Android
description: Android API do konwersji XPS na ODP bez użycia Microsoft Word
url: /pl/android-java/conversion/xps-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: ODP
otherformats: PPSM PPSX PPTM POTM POT XAML SWF PPT OTP POTX POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj XPS na ODP na Androidzie przez Javę" h2="Przekształć XPS w ODP w swoich aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji XPS na ODP w swoich aplikacjach na Androida, wykonując dwa proste kroki. W pierwszym kroku możesz wyeksportować XPS do PPTX, używając [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/). Następnie, używając [Aspose.Slides dla Androida przez Javę](https://products.aspose.com/slides/android-java/), możesz przekonwertować PPTX na ODP. Oba interfejsy API są objęte pakietem [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do eksportu XPS do ODP" %}}
1. Otwórz plik XPS za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj XPS na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie ODP za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Odp` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Slides na Androida przez Javę](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Otwórz plik XPS chroniony hasłem w Androidzie przez Java" %}}
Podczas ładowania pliku w formacie XPS dokument może być chroniony hasłem. [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/) umożliwia również otwieranie zaszyfrowanych dokumentów. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz obraz miniatury pliku ODP w aplikacjach na Androida" %}}
Po przekonwertowaniu XPS na ODP możesz również tworzyć miniatury dokumentu wyjściowego. Korzystając z bogatej funkcji [Aspose.Slides na Androida przez Javę](https://products.aspose.com/slides/android-java/) możesz generować miniatury slajdów, tworząc i instancję [Prezentacja]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Następnie możesz uzyskać odwołanie do dowolnego slajdu, używając jego identyfikatora lub indeksu, i uzyskać miniaturę tego slajdu w określonej skali.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
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
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-ppsm/" name="XPS Do PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-ppsx/" name="XPS Do PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-pptm/" name="XPS Do PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-potm/" name="XPS Do POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-pot/" name="XPS Do POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-xaml/" name="XPS Do XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-swf/" name="XPS Do SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-ppt/" name="XPS Do PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-otp/" name="XPS Do OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-potx/" name="XPS Do POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-powerpoint/" name="XPS Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xps-to-pps/" name="XPS Do PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}