---
title: Eksportuj EMAIL do OTT przez Java
description: Java API do konwersji EMAIL na OTT bez użycia Microsoft Word lub Outlook
url_ignore: /pl/java/conversion/email-to-ott/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: OTT
otherformats: WORDML RTF ODT JPEG PNG SVG DOTX GIF DOCM EMF DOT MD TEXT DOC DOTM XPS TIFF PS PCL OTT EPUB DOCX PDF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do renderowania e-maili do OTT" h2="Eksportuj EMAIL do OTT za pomocą lokalnego interfejsu API Java bez korzystania z zależności innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja wiadomości e-mail to potężna funkcja, którą programiści Java mogą zintegrować z dowolnymi aplikacjami Java J2SE, J2EE, J2ME za pośrednictwem [Aspose.Total for Java](https://products.aspose.com/total/java/). Korzystając z dwóch interfejsów API w pakiecie, możesz przekonwertować e-mail EMAIL na OTT bez żadnych zależności od stron trzecich. Po pierwsze, możesz użyć interfejsu Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/), aby przekonwertować format pliku EMAIL na HTML. Po drugie, możesz renderować HTML do OTT za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować EMAIL na OTT" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Przekonwertuj EMAIL na HTML, używając [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie OTT za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metodę i ustaw OTT jako SaveFormat
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