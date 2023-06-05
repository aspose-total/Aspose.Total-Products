---
title: Eksportuj MD do PPT w systemie Android
description: Android API do konwersji MD na PPT bez użycia Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPT
otherformats: XAML POWERPOINT OTP PPSM POTM PPTM POT PPSX ODP SWF PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj MD na PPT na Androidzie przez Javę" h2="Przekształć MD w PPT w swoich aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji MD na PPT w swoich aplikacjach na Androida, wykonując dwa proste kroki. W pierwszym kroku możesz wyeksportować MD do PPTX, używając [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/). Następnie, używając [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), możesz przekonwertować PPTX na PPT. Oba interfejsy API są objęte pakietem [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do eksportu MD do PPT" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj MD na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie PPT za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Ppt` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://releases.aspose.com/total/java/)docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Slides na Androida przez Javę](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
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
{{% blocks/products/pf/feature-page-section  h2="Utwórz obraz miniatury pliku PPT w aplikacjach na Androida" %}}
Po przekonwertowaniu MD na PPT możesz również tworzyć miniatury dokumentu wyjściowego. Korzystając z bogatej funkcji [Aspose.Slides na Androida przez Javę](https://products.aspose.com/slides/android-java/) możesz generować miniatury slajdów, tworząc i instancję [Prezentacjareference.aspose.com/slides/java/com.aspose.slides/Presentation). Następnie możesz uzyskać odwołanie do dowolnego slajdu, używając jego identyfikatora lub indeksu, i uzyskać miniaturę tego slajdu w określonej skali.
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}