---
title: Konwertuj EPUB na POTX za pomocą Java API
description: Java API do konwersji EPUB na POTX bez użycia Microsoft Word
url_ignore: /pl/java/conversion/epub-to-potx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTX
otherformats: PPS POTX PPTM OTP POT PPSX XAML PPT POWERPOINT PPSM POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu EPUB do POTX" h2="Eksportuj EPUB do POTX za pośrednictwem lokalnego interfejsu API Java bez użycia programu Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz łatwo przekonwertować EPUB na POTX w dowolnej aplikacji Java J2SE, J2EE, J2ME. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować EPUB do PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, możesz przekonwertować PPTX na POTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji EPUB na POTX" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj EPUB na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie POTX za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Potx` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas ładowania pliku w formacie EPUB dokument może być chroniony hasłem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umożliwia również otwieranie zaszyfrowanych dokumentów. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz zaszyfrowany plik EPUB przez Java" %}}
Po przekonwertowaniu EPUB na POTX możesz również dodać do prezentacji predefiniowany typ widoku. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) zapewnia możliwość ustawienia typu widoku generowanej prezentacji, gdy jest ona otwierana w programie PowerPoint za pomocą [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Właściwość [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) służy do ustawiania typu widoku przy użyciu [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}  
Konwertowanie **EPUB na POTX (PowerPoint Open XML Template)** jest niezbędne do generowania **standaryzowanych nowoczesnych szablonów prezentacji** z publikacji cyfrowych. Pliki POTX zapewniają otwarty format oparty na XML do ponownego użytku, edytowalnych slajdów, umożliwiając spójny design i efektywne ponowne wykorzystanie treści. Poprzez przekształcenie EPUB w POTX, edukatorzy, wydawcy i przedsiębiorstwa mogą usprawnić tworzenie prezentacji, zachować spójność wizualną i wspierać skalowalne, profesjonalne przepływy pracy ze slajdami.  

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}  
- **Slajdy edukacyjne** – Tworzenie wielokrotnie używanych szablonów prezentacji wykładów i kursów.  
- **Ramy prezentacji biznesowych** – Standaryzacja slajdów korporacyjnych w zespołach i projektach.  
- **Szablony publikacji** – Opracowywanie spójnych układów slajdów promocyjnych i redakcyjnych.  
- **Prezentacje badawcze** – Przekształcanie treści akademickich w ustrukturyzowane, wizualnie atrakcyjne slajdy.  
- **Standaryzacja materiałów szkoleniowych** – Tworzenie jednolitych szablonów dla programów szkoleniowych korporacyjnych i edukacyjnych.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}  
- **Potoki EPUB do POTX** – Automatyzacja konwersji e-booków na standaryzowane szablony prezentacji.  
- **Automatyczne rozpowszechnianie szablonów** – Skuteczne wdrażanie slajdów POTX w zespołach lub organizacjach.  
- **Generowanie slajdów na podstawie metadanych** – Wypełnianie treści slajdów za pomocą strukturalnych danych e-booków.  
- **Przepływy pracy publikacji na poziomie przedsiębiorstwa** – Skalowanie tworzenia i dystrybucji szablonów slajdów w instytucjach edukacyjnych lub korporacyjnych.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}