---
title: Exportieren Sie E-MAIL über Java nach ODT
description: Java-API zum Konvertieren von E-MAIL in ODT, ohne Microsoft Word oder Outlook zu verwenden
url: /de/java/conversion/email-to-odt/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: ODT
otherformats: DOT JPEG PCL DOTM DOTX EPUB MD DOC TIFF PNG OTT XPS ODT RTF DOCM WORDML GIF PDF TEXT DOCX EMF FLATOPC SVG PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Rendern von E-MAIL in ODT" h2="Exportieren Sie E-MAIL nach ODT, indem Sie die lokale Java-API verwenden, ohne Abhängigkeiten von Drittanbietern zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Die E-Mail-Konvertierung ist eine leistungsstarke Funktion, die Java-Entwickler über [Aspose.Total for Java](https://products.aspose.com/total/java/) in alle Java J2SE-, J2EE-, J2ME-Anwendungen integrieren können. Durch die Verwendung von zwei APIs innerhalb des Pakets können Sie E-Mail-E-MAIL ohne Abhängigkeiten von Drittanbietern in ODT konvertieren. Erstens können Sie die E-Mail-Manipulations-API [Aspose.Email for Java](https://products.aspose.com/email/java/) verwenden, um das EMAIL-Dateiformat in HTML zu konvertieren. Zweitens können Sie HTML in ODT rendern, indem Sie die Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie E-MAIL in ODT" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://apireference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://apireference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im ODT-Format mit [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie ODT als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie müssen Aspose.Total für Java direkt aus einem [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)-basierten Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-png/" name="MSG Zu PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-doc/" name="MSG Zu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-ott/" name="MSG Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-odt/" name="MSG Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-wordml/" name="MSG Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-dotx/" name="MSG Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-svg/" name="MSG Zu SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-docx/" name="MSG Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-epub/" name="MSG Zu EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-text/" name="MSG Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-xps/" name="MSG Zu XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-ps/" name="MSG Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-flatopc/" name="MSG Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-docm/" name="MSG Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-jpeg/" name="MSG Zu JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-tiff/" name="MSG Zu TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-dot/" name="MSG Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-emf/" name="MSG Zu EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-rtf/" name="MSG Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-gif/" name="MSG Zu GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-pcl/" name="MSG Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-dotm/" name="MSG Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-md/" name="MSG Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/msg-to-pdf/" name="MSG Zu PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}