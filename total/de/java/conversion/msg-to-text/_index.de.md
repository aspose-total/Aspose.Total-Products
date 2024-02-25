---
title: Exportieren Sie E-MAIL über Java nach TEXT
description: Java-API zum Konvertieren von E-MAIL in TEXT, ohne Microsoft Word oder Outlook zu verwenden
url_ignore: /de/java/conversion/msg-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: FLATOPC EMF WORDML TIFF PDF TEXT ODT PS SVG MD PNG DOTX GIF DOC RTF PCL DOTM DOCM OTT JPEG EPUB DOT XPS DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Rendern von E-MAIL in TEXT" h2="Exportieren Sie E-MAIL nach TEXT, indem Sie die lokale Java-API verwenden, ohne Abhängigkeiten von Drittanbietern zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Die E-Mail-Konvertierung ist eine leistungsstarke Funktion, die Java-Entwickler über [Aspose.Total for Java](https://products.aspose.com/total/java/) in alle Java J2SE-, J2EE-, J2ME-Anwendungen integrieren können. Durch die Verwendung von zwei APIs innerhalb des Pakets können Sie E-Mail-E-MAIL ohne Abhängigkeiten von Drittanbietern in TEXT konvertieren. Erstens können Sie die E-Mail-Manipulations-API [Aspose.Email for Java](https://products.aspose.com/email/java/) verwenden, um das MSG-Dateiformat in HTML zu konvertieren. Zweitens können Sie HTML in TEXT rendern, indem Sie die Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie E-MAIL in TEXT" %}}
1. Öffnen Sie die MSG-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im TEXT-Format mit [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie TEXT als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie müssen Aspose.Total für Java direkt aus einem [Maven](https://releases.aspose.com/total/java/)-basierten Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}