---
title: Eksportuj OFT do TIFF przez Java
description: Java API do konwersji OFT na TIFF bez użycia Microsoft Word lub Outlook
url_ignore: /pl/java/conversion/oft-to-tiff/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: TIFF
otherformats: DOCX ODT DOCM DOTM EMF PNG DOC DOT SVG FLATOPC EPUB TIFF GIF TEXT WORDML OTT PDF PS MD PCL XPS JPEG RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do renderowania e-maili do TIFF" h2="Eksportuj OFT do TIFF za pomocą lokalnego interfejsu API Java bez korzystania z zależności innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja wiadomości e-mail to potężna funkcja, którą programiści Java mogą zintegrować z dowolnymi aplikacjami Java J2SE, J2EE, J2ME za pośrednictwem [Aspose.Total for Java](https://products.aspose.com/total/java/). Korzystając z dwóch interfejsów API w pakiecie, możesz przekonwertować e-mail OFT na TIFF bez żadnych zależności od stron trzecich. Po pierwsze, możesz użyć interfejsu Oft Manipulation API [Aspose.Oft for Java](https://products.aspose.com/email/java/), aby przekonwertować format pliku OFT na HTML. Po drugie, możesz renderować HTML do TIFF za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować OFT na TIFF" %}}
1. Otwórz plik OFT za pomocą klasy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Przekonwertuj OFT na HTML, używając [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metoda
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie TIFF za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metodę i ustaw TIFF jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Musisz użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TIFF
document.save("output.tiff", SaveFormat.TIFF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}