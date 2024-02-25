---
title: Konwertuj PDF na OTP za pomocą Java API
description: Java API do konwersji PDF na OTP bez użycia Microsoft Word
url_ignore: /pl/java/conversion/pdf-to-otp/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: OTP
otherformats: POWERPOINT PPSM OTP POTM SWF POTX XAML PPT PPSX PPTM PPS POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu PDF do OTP" h2="Eksportuj PDF do OTP za pośrednictwem lokalnego interfejsu API Java bez użycia programu Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz łatwo przekonwertować PDF na OTP w dowolnej aplikacji Java J2SE, J2EE, J2ME. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować PDF do PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, możesz przekonwertować PPTX na OTP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji PDF na OTP" %}}
1. Otwórz plik PDF za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj PDF na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie OTP za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw `OTP` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas ładowania pliku w formacie PDF dokument może być chroniony hasłem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umożliwia również otwieranie zaszyfrowanych dokumentów. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz zaszyfrowany plik PDF przez Java" %}}
Po przekonwertowaniu PDF na OTP możesz również dodać do prezentacji predefiniowany typ widoku. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) zapewnia możliwość ustawienia typu widoku generowanej prezentacji, gdy jest ona otwierana w programie PowerPoint za pomocą [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Właściwość [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) służy do ustawiania typu widoku przy użyciu [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}