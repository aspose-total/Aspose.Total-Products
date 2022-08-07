---
title: Rendern Sie E-MAIL zu WORD in der Andorid App
description: Exportieren Sie E-MAIL nach WORD, ohne Microsoft Word oder Outlook in Ihren Android-Anwendungen zu verwenden
url: /de/android-java/conversion/email-to-word/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOCX
otherformats: XPS FLATOPC PNG PDF WORDML PCL JPEG DOCX DOCM DOT BMP TEXT TIFF DOTX OTT SVG DOC EMF DOTM EPUB ODT GIF PS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Wandeln Sie E-MAIL in WORD in Andorid-Apps um" h2="Entwerfen von Andorid-Anwendungen zum Exportieren von E-MAIL nach WORD mithilfe von Andorid über die Java-API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid-Apps sind für Endbenutzer täglich einfach zu verwenden. Tag für Tag steigt die Zahl der Benutzer von Android-Telefonen. Mit den leistungsstarken [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dateiformatautomatisierungsbibliotheken können Sie E-Mail-Manipulations- und Konvertierungsanwendungen entwickeln. Sie können EMAIL in WORD konvertieren, indem Sie [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Mit der ersten API können Sie das EMAIL-Dateiformat in HTML konvertieren und mit der zweiten API können Sie HTML als WORD rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie E-MAIL in WORD in Andorid" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im WORD-Format mit [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie WORD als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.Email für Android über Java](https://docs.aspose.com/email/androidjava/installation/) und [Aspose.Words für Andorid über Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCX
document.save("output.docx", SaveFormat.DOCX); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-xps/" name="MSG Zu XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-flatopc/" name="MSG Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-png/" name="MSG Zu PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-pdf/" name="MSG Zu PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-wordml/" name="MSG Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-pcl/" name="MSG Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-jpeg/" name="MSG Zu JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-docx/" name="MSG Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-docm/" name="MSG Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-dot/" name="MSG Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-word/" name="MSG Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-text/" name="MSG Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-tiff/" name="MSG Zu TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-dotx/" name="MSG Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-ott/" name="MSG Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-svg/" name="MSG Zu SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-doc/" name="MSG Zu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-emf/" name="MSG Zu EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-dotm/" name="MSG Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-epub/" name="MSG Zu EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-odt/" name="MSG Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-gif/" name="MSG Zu GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-ps/" name="MSG Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/msg-to-rtf/" name="MSG Zu RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}