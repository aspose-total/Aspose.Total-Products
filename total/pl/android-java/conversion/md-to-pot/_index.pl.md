---
title: Eksportuj MD do POT w systemie Android
description: Android API do konwersji MD na POT bez użycia Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: POT
otherformats: POTX POWERPOINT PPSM OTP PPT ODP PPSX POTM XAML SWF PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj MD na POT na Androidzie przez Javę" h2="Przekształć MD w POT w swoich aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji MD na POT w swoich aplikacjach na Androida, wykonując dwa proste kroki. W pierwszym kroku możesz wyeksportować MD do PPTX, używając [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/). Następnie, używając [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), możesz przekonwertować PPTX na POT. Oba interfejsy API są objęte pakietem [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do eksportu MD do POT" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj MD na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie POT za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Pot` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Slides na Androida przez Javę](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Otwórz plik MD chroniony hasłem w Androidzie przez Java" %}}
Podczas ładowania pliku w formacie MD dokument może być chroniony hasłem. [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/) umożliwia również otwieranie zaszyfrowanych dokumentów. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Utwórz obraz miniatury pliku POT w aplikacjach na Androida" %}}
Po przekonwertowaniu MD na POT możesz również tworzyć miniatury dokumentu wyjściowego. Korzystając z bogatej funkcji [Aspose.Slides na Androida przez Javę](https://products.aspose.com/slides/android-java/) możesz generować miniatury slajdów, tworząc i instancję [Prezentacja]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Następnie możesz uzyskać odwołanie do dowolnego slajdu, używając jego identyfikatora lub indeksu, i uzyskać miniaturę tego slajdu w określonej skali.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-potx/" name="MD Do POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-powerpoint/" name="MD Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-ppsm/" name="MD Do PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-otp/" name="MD Do OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-ppt/" name="MD Do PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-pot/" name="MD Do POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-ppsx/" name="MD Do PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-potm/" name="MD Do POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-xaml/" name="MD Do XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-swf/" name="MD Do SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-pptm/" name="MD Do PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-pps/" name="MD Do PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}