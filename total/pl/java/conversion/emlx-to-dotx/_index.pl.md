---
title: Eksportuj EMLX do DOTX przez Java
description: Java API do konwersji EMLX na DOTX bez użycia Microsoft Word lub Outlook
url_ignore: /pl/java/conversion/emlx-to-dotx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOTX
otherformats: GIF EPUB DOTM OTT ODT DOCM PDF DOT RTF DOTX DOC PS PCL TIFF XPS FLATOPC SVG JPEG WORDML DOCX MD TEXT PNG EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do renderowania e-maili do DOTX" h2="Eksportuj EMLX do DOTX za pomocą lokalnego interfejsu API Java bez korzystania z zależności innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja wiadomości e-mail to potężna funkcja, którą programiści Java mogą zintegrować z dowolnymi aplikacjami Java J2SE, J2EE, J2ME za pośrednictwem [Aspose.Total for Java](https://products.aspose.com/total/java/). Korzystając z dwóch interfejsów API w pakiecie, możesz przekonwertować e-mail EMLX na DOTX bez żadnych zależności od stron trzecich. Po pierwsze, możesz użyć interfejsu Emlx Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/), aby przekonwertować format pliku EMLX na HTML. Po drugie, możesz renderować HTML do DOTX za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować EMLX na DOTX" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Przekonwertuj EMLX na HTML, używając [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie DOTX za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metodę i ustaw DOTX jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Musisz użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}