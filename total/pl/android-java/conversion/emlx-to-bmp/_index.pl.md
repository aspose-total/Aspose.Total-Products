---
title: Renderuj EMLX do BMP w aplikacji Andorid
description: Eksportuj EMLX do BMP bez używania Microsoft Word lub Outlook w swoich aplikacjach Andorid

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: BMP
otherformats: JPEG DOC EPUB GIF PS TIFF RTF PCL XPS MD DOT OTT DOCM DOTX SVG ODT PNG DOCX DOTM WORDML FLATOPC PDF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Przekształć EMLX w BMP w aplikacjach na Androida" h2="Projektowanie aplikacji Andorid do eksportu EMLX do BMP za pomocą Andorid za pośrednictwem Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikacje Andorid są łatwe w użyciu dla użytkowników końcowych na co dzień. Z dnia na dzień rośnie liczba użytkowników telefonów z systemem Android. Korzystając z potężnych bibliotek [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, możesz tworzyć aplikacje do manipulacji i konwersji poczty e-mail. Możesz przekonwertować EMLX na BMP, łącząc [Aspose.Emlx dla Androida Java](https://products.aspose.com/emlx/android-java/) i [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Używając pierwszego API, możesz przekonwertować format pliku EMLX na HTML, a używając drugiego API, możesz renderować HTML jako BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj EMLX na BMP w Andorid" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Przekonwertuj EMLX na HTML, używając [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) )) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie BMP za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) i ustaw BMP jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Emlx na Androida przez Javę](https://docs.aspose.com/emlx/androidjava/installation/) i [Aspose.Words dla Andorida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-jpeg/" name="EMLX Do JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-doc/" name="EMLX Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-epub/" name="EMLX Do EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-gif/" name="EMLX Do GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-ps/" name="EMLX Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-tiff/" name="EMLX Do TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-rtf/" name="EMLX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-pcl/" name="EMLX Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-xps/" name="EMLX Do XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-md/" name="EMLX Do MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-dot/" name="EMLX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-ott/" name="EMLX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-docm/" name="EMLX Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-dotx/" name="EMLX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-svg/" name="EMLX Do SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-odt/" name="EMLX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-png/" name="EMLX Do PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-docx/" name="EMLX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-dotm/" name="EMLX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-wordml/" name="EMLX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-flatopc/" name="EMLX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-pdf/" name="EMLX Do PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-text/" name="EMLX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/emlx-to-emf/" name="EMLX Do EMF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}