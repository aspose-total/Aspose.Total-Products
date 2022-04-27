---
title: Konwertuj MHTML na POT za pomocą Java API
description: Java API do konwersji MHTML na POT bez użycia Microsoft Word
url: /pl/java/conversion/mhtml-to-pot/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: POT
otherformats: PPTM POT PPSX PPSM POTX POWERPOINT XAML SWF OTP PPS PPT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu MHTML do POT" h2="Eksportuj MHTML do POT za pośrednictwem lokalnego interfejsu API Java bez użycia programu Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz łatwo przekonwertować MHTML na POT w dowolnej aplikacji Java J2SE, J2EE, J2ME. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować MHTML do PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, możesz przekonwertować PPTX na POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji MHTML na POT" %}}
1. Otwórz plik MHTML za pomocą klasy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj MHTML na PPTX za pomocą metody [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie POT za pomocą metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Pot` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Slides for Java](https://docs.aspose.com/slides/java/ instalacja/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas ładowania pliku w formacie MHTML dokument może być chroniony hasłem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umożliwia również otwieranie zaszyfrowanych dokumentów. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz zaszyfrowany plik MHTML przez Java" %}}
Po przekonwertowaniu MHTML na POT możesz również dodać do prezentacji predefiniowany typ widoku. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) zapewnia możliwość ustawienia typu widoku generowanej prezentacji, gdy jest ona otwierana w programie PowerPoint za pomocą [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Właściwość [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) służy do ustawiania typu widoku przy użyciu [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-pps/" name="MHTML W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-swf/" name="MHTML W celu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-potx/" name="MHTML W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-ppsx/" name="MHTML W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-potm/" name="MHTML W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-ppt/" name="MHTML W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-ppsm/" name="MHTML W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-xaml/" name="MHTML W celu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-otp/" name="MHTML W celu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-pptm/" name="MHTML W celu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-pot/" name="MHTML W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-powerpoint/" name="MHTML W celu POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}