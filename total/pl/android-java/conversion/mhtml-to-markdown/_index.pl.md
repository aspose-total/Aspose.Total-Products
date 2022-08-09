---
title: Android API do renderowania MHTML do MARKDOWN
description: Przekształć MHTML w MARKDOWN przez Androida za pomocą Java API
url: /pl/android-java/conversion/mhtml-to-markdown/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: MARKDOWN
otherformats: OTT ODT DOTM DOT FLATOPC RTF XAMLFLOW WORDML DOCM DOTX PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj MHTML do MARKDOWN na Androidzie przez Javę" h2="Konwertuj MHTML na MARKDOWN w aplikacjach mobilnych bez instalowania żadnego oprogramowania" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji MHTML na MARKDOWN w swoich aplikacjach mobilnych, korzystając z dwóch interfejsów API pakietu [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Najpierw musisz przekonwertować plik MHTML na DOC za pomocą [Aspose.PDF dla Androida przez Javę](https://products.aspose.com/pdf/android-java/). Po drugie, używając interfejsu API przetwarzania tekstu [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), możesz renderować DOC do MARKDOWN. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj MHTML na MARKDOWN na Androidzie przez Javę" %}}
1. Otwórz plik MHTML za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj MHTML na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie MARKDOWN za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw MARKDOWN jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Words na Androida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj informacje o plikach MHTML na Androida za pośrednictwem Javy" %}}
Przed przekonwertowaniem MHTML na MARKDOWN mogą być potrzebne informacje o dokumencie, takie jak autor, data utworzenia, słowa kluczowe, data modyfikacji, temat i tytuł. Informacje te są pomocne przy podejmowaniu decyzji dotyczących procesu konwersji. Korzystając z potężnego interfejsu API [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/), możesz to wszystko uzyskać. Aby uzyskać informacje specyficzne dla pliku o pliku MHTML, najpierw pobierz obiekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) za pomocą [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Po pobraniu obiektu DocumentInfo można uzyskać wartości poszczególnych właściwości.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Wstaw przypisy końcowe w dokumencie MARKDOWN w Androidzie za pośrednictwem Javy" %}}
Oprócz konwersji dokumentów możesz także dodać kilka innych funkcji do aplikacji na Androida, korzystając z interfejsu API [Aspose.Words dla Androida przez Javę](https://products.aspose.com/words/androidjava/). Jedną z tych funkcji jest wstawianie przypisów końcowych i numeracji w dokumencie MARKDOWN. Jeśli chcesz wstawić przypis dolny lub przypis końcowy w dokumencie MARKDOWN, użyj metody DocumentBuilder.InsertFootnote. Ta metoda wstawia przypis dolny lub przypis końcowy do dokumentu. Klasy EndnoteOptions i FootnoteOptions reprezentują opcje numerowania przypisów dolnych i końcowych.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.markdown", SaveFormat.MARKDOWN);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-ott/" name="MHTML Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-odt/" name="MHTML Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-dotm/" name="MHTML Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-dot/" name="MHTML Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-flatopc/" name="MHTML Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-rtf/" name="MHTML Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-xamlflow/" name="MHTML Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-wordml/" name="MHTML Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-markdown/" name="MHTML Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-dotx/" name="MHTML Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-ps/" name="MHTML Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/mhtml-to-pcl/" name="MHTML Do PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}