---
title: Android API do renderowania MD do DOTX
description: Przekształć MD w DOTX przez Androida za pomocą Java API

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOTX
otherformats: OTT XAMLFLOW PCL DOCM MARKDOWN MHTML DOT FLATOPC DOTM ODT RTF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj MD do DOTX na Androidzie przez Javę" h2="Konwertuj MD na DOTX w aplikacjach mobilnych bez instalowania żadnego oprogramowania" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz zintegrować funkcję konwersji MD na DOTX w swoich aplikacjach mobilnych, korzystając z dwóch interfejsów API pakietu [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Najpierw musisz przekonwertować plik MD na DOC za pomocą [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Po drugie, używając interfejsu API przetwarzania tekstu [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), możesz renderować DOC do DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj MD na DOTX na Androidzie przez Javę" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj MD na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie DOTX za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw DOTX jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://releases.aspose.com/total/java/)docs.aspose.com/pdf/androidjava/installation/) i [Aspose.Words na Androida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj informacje o plikach MD na Androida za pośrednictwem Javy" %}}
Przed przekonwertowaniem MD na DOTX mogą być potrzebne informacje o dokumencie, takie jak autor, data utworzenia, słowa kluczowe, data modyfikacji, temat i tytuł. Informacje te są pomocne przy podejmowaniu decyzji dotyczących procesu konwersji. Korzystając z potężnego interfejsu API [Aspose.PDF na Androida przez Javę](https://docs.aspose.com/pdf/androidjava/), możesz to wszystko uzyskać. Aby uzyskać informacje specyficzne dla pliku o pliku MD, najpierw pobierz obiekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) za pomocą [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Po pobraniu obiektu DocumentInfo można uzyskać wartości poszczególnych właściwości.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD document
Document doc = new Document("template.md");
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

{{% blocks/products/pf/feature-page-section  h2="Wstaw przypisy końcowe w dokumencie DOTX w Androidzie za pośrednictwem Javy" %}}
Oprócz konwersji dokumentów możesz także dodać kilka innych funkcji do aplikacji na Androida, korzystając z interfejsu API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Jedną z tych funkcji jest wstawianie przypisów końcowych i numeracji w dokumencie DOTX. Jeśli chcesz wstawić przypis dolny lub przypis końcowy w dokumencie DOTX, użyj metody DocumentBuilder.InsertFootnote. Ta metoda wstawia przypis dolny lub przypis końcowy do dokumentu. Klasy EndnoteOptions i FootnoteOptions reprezentują opcje numerowania przypisów dolnych i końcowych.
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
doc.save("output.dotx", SaveFormat.DOTX);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-ott/" name="MD Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-xamlflow/" name="MD Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-pcl/" name="MD Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-dotx/" name="MD Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-markdown/" name="MD Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-mhtml/" name="MD Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-dot/" name="MD Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-flatopc/" name="MD Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-dotm/" name="MD Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-odt/" name="MD Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-rtf/" name="MD Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/md-to-ps/" name="MD Do PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}