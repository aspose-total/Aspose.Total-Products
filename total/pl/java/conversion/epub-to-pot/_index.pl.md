---
title: Konwertuj EPUB na POT za pomocą Java API
description: Java API do konwersji EPUB na POT bez użycia Microsoft Word
url_ignore: /pl/java/conversion/epub-to-pot/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POT
otherformats: POTX POTM POWERPOINT XAML PPS POT OTP PPSX PPSM PPTM SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu EPUB do POT" h2="Eksportuj EPUB do POT za pośrednictwem lokalnego interfejsu API Java bez użycia programu Microsoft<sup>&reg;</sup> PowerPoint lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz łatwo przekonwertować EPUB na POT w dowolnej aplikacji Java J2SE, J2EE, J2ME. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować EPUB do PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, możesz przekonwertować PPTX na POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji EPUB na POT" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj EPUB na PPTX za pomocą metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie POT za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) i ustaw ` Pot` jako SaveFormat
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
Po przekonwertowaniu EPUB na POT możesz również dodać do prezentacji predefiniowany typ widoku. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) zapewnia możliwość ustawienia typu widoku generowanej prezentacji, gdy jest ona otwierana w programie PowerPoint za pomocą [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Właściwość [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) służy do ustawiania typu widoku przy użyciu [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
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
```
{{< blocks/products/pf/agp/feature-section >}}  
Konwertowanie **EPUB na POT (szablon PowerPoint)** jest niezbędne do generowania **niestandardowych szablonów slajdów** z publikacji cyfrowych. Pliki POT umożliwiają ponowne wykorzystywanie, edytowalne ramy prezentacji, zapewniając spójny design i efektywne ponowne wykorzystanie treści. Poprzez przekształcenie EPUB w POT, edukatorzy, wydawcy i firmy mogą usprawnić tworzenie slajdów, zachować spójność marki i formatowania oraz wspierać skalowalne przepływy pracy związane z prezentacjami.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}  
- **Ramki wykładów akademickich** – Tworzenie wielokrotnie używanych szablonów slajdów do kursów i seminariów.  
- **Szablony wydawnictw** – Opracowywanie spójnych układów prezentacji marketingowych i promocyjnych.  
- **Szablony prezentacji korporacyjnych** – Standaryzacja slajdów w różnych działach i zespołach.  
- **Ramki prezentacji badawczych** – Przekształcanie treści naukowych w uporządkowane, wizualnie atrakcyjne slajdy.  
- **Ustawienia slajdów edukacyjnych** – Tworzenie szablonów planów lekcji, warsztatów i sesji szkoleniowych.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}  
- **Potoki EPUB do POT** – Automatyzacja konwersji publikacji cyfrowych na szablony PowerPoint.  
- **Automatyczne generowanie szablonów PowerPoint** – Szybkie tworzenie standaryzowanych projektów slajdów z treści e-booków.  
- **Konwersja metadanych na szablon** – Integracja strukturalnych danych e-booków w wielokrotnie używane układy slajdów.  
- **Automatyzacja szablonów na poziomie przedsiębiorstwa** – Skalowanie tworzenia i dystrybucji szablonów prezentacji w organizacjach.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}