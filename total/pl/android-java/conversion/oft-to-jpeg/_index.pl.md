---
title: Renderuj OFT do JPEG w aplikacji Andorid
description: Eksportuj OFT do JPEG bez używania Microsoft Word lub Outlook w swoich aplikacjach Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: JPEG
otherformats: DOT EMF EPUB XPS DOTX WORDML ODT DOC TEXT BMP DOCM GIF MD DOTM PNG TIFF FLATOPC RTF OTT PDF PS SVG DOCX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Przekształć OFT w JPEG w aplikacjach na Androida" h2="Projektowanie aplikacji Andorid do eksportu OFT do JPEG za pomocą Andorid za pośrednictwem Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikacje Andorid są łatwe w użyciu dla użytkowników końcowych na co dzień. Z dnia na dzień rośnie liczba użytkowników telefonów z systemem Android. Korzystając z potężnych bibliotek [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, możesz tworzyć aplikacje do manipulacji i konwersji poczty e-mail. Możesz przekonwertować OFT na JPEG, łącząc [Aspose.Oft dla Androida Java](https://products.aspose.com/oft/android-java/) i [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Używając pierwszego API, możesz przekonwertować format pliku OFT na HTML, a używając drugiego API, możesz renderować HTML jako JPEG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj OFT na JPEG w Andorid" %}}
1. Otwórz plik OFT za pomocą klasy [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Przekonwertuj OFT na HTML, używając [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) )) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie JPEG za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) i ustaw JPEG jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://releases.aspose.com/total/java/)docs.aspose.com/oft/androidjava/installation/) i [Aspose.Words dla Andorida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.JPEG
document.save("output.jpeg", SaveFormat.JPEG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}