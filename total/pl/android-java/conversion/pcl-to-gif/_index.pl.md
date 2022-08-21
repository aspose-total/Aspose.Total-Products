---
title: Android API do renderowania PCL do GIF
description: Przekształć PCL w GIF przez Androida za pomocą Java API
url: /pl/android-java/conversion/pcl-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: GIF
otherformats: OTT DOTM XAMLFLOW DOCM MARKDOWN DOTX DOT WORDML MHTML PS FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj PCL do GIF na Androidzie przez Javę" h2="Konwertuj PCL na GIF w aplikacjach mobilnych bez instalowania żadnego oprogramowania" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji PCL na GIF w swoich aplikacjach mobilnych, korzystając z dwóch interfejsów API pakietu [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Najpierw musisz przekonwertować plik PCL na DOC za pomocą [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Po drugie, używając interfejsu API przetwarzania tekstu [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), możesz renderować DOC do GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj PCL na GIF na Androidzie przez Javę" %}}
1. Otwórz plik PCL za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj PCL na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie GIF za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw GIF jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Words na Androida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj informacje o plikach PCL na Androida za pośrednictwem Javy" %}}
Przed przekonwertowaniem PCL na GIF mogą być potrzebne informacje o dokumencie, takie jak autor, data utworzenia, słowa kluczowe, data modyfikacji, temat i tytuł. Informacje te są pomocne przy podejmowaniu decyzji dotyczących procesu konwersji. Korzystając z potężnego interfejsu API [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/), możesz to wszystko uzyskać. Aby uzyskać informacje specyficzne dla pliku o pliku PCL, najpierw pobierz obiekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) za pomocą [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Po pobraniu obiektu DocumentInfo można uzyskać wartości poszczególnych właściwości.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL document
Document doc = new Document("template.pcl");
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

{{% blocks/products/pf/feature-page-section  h2="Wstaw przypisy końcowe w dokumencie GIF w Androidzie za pośrednictwem Javy" %}}
Oprócz konwersji dokumentów możesz także dodać kilka innych funkcji do aplikacji na Androida, korzystając z interfejsu API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Jedną z tych funkcji jest wstawianie przypisów końcowych i numeracji w dokumencie GIF. Jeśli chcesz wstawić przypis dolny lub przypis końcowy w dokumencie GIF, użyj metody DocumentBuilder.InsertFootnote. Ta metoda wstawia przypis dolny lub przypis końcowy do dokumentu. Klasy EndnoteOptions i FootnoteOptions reprezentują opcje numerowania przypisów dolnych i końcowych.
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
doc.save("output.gif", SaveFormat.GIF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-ott/" name="PCL Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-dotm/" name="PCL Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-xamlflow/" name="PCL Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-gif/" name="PCL Do GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-markdown/" name="PCL Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-dotx/" name="PCL Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-dot/" name="PCL Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-wordml/" name="PCL Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-mhtml/" name="PCL Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-ps/" name="PCL Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-flatopc/" name="PCL Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pcl-to-rtf/" name="PCL Do RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}