---
title: Renderuj EMAIL do PS w aplikacji Andorid
description: Eksportuj EMAIL do PS bez używania Microsoft Word lub Outlook w swoich aplikacjach Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PS
otherformats: OTT EPUB DOT DOCM EMF PNG WORDML XPS PCL GIF ODT RTF JPEG DOTX DOCX MD SVG DOTM FLATOPC BMP PDF TEXT DOC TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Przekształć EMAIL w PS w aplikacjach na Androida" h2="Projektowanie aplikacji Andorid do eksportu EMAIL do PS za pomocą Andorid za pośrednictwem Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikacje Andorid są łatwe w użyciu dla użytkowników końcowych na co dzień. Z dnia na dzień rośnie liczba użytkowników telefonów z systemem Android. Korzystając z potężnych bibliotek [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation, możesz tworzyć aplikacje do manipulacji i konwersji poczty e-mail. Możesz przekonwertować EMAIL na PS, łącząc [Aspose.Email dla Androida Java](https://products.aspose.com/email/android-java/) i [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Używając pierwszego API, możesz przekonwertować format pliku EMAIL na HTML, a używając drugiego API, możesz renderować HTML jako PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj EMAIL na PS w Andorid" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Przekonwertuj EMAIL na HTML, używając [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) )) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie PS za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) i ustaw PS jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://releases.aspose.com/total/java/)//docs.aspose.com/email/androidjava/installation/) i [Aspose.Words dla Andorida przez Javę](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PS
document.save("output.ps", SaveFormat.PS); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}