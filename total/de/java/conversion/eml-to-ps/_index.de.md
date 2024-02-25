---
title: Exportieren Sie E-MAIL über Java nach PS
description: Java-API zum Konvertieren von E-MAIL in PS, ohne Microsoft Word oder Outlook zu verwenden
url_ignore: /de/java/conversion/eml-to-ps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PS
otherformats: EMF SVG RTF PCL DOTM XPS TIFF DOTX PS JPEG PNG DOCM PDF EPUB DOC GIF MD ODT WORDML OTT DOCX FLATOPC DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Rendern von E-MAIL in PS" h2="Exportieren Sie E-MAIL nach PS, indem Sie die lokale Java-API verwenden, ohne Abhängigkeiten von Drittanbietern zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Die E-Mail-Konvertierung ist eine leistungsstarke Funktion, die Java-Entwickler über [Aspose.Total for Java](https://products.aspose.com/total/java/) in alle Java J2SE-, J2EE-, J2ME-Anwendungen integrieren können. Durch die Verwendung von zwei APIs innerhalb des Pakets können Sie E-Mail-E-MAIL ohne Abhängigkeiten von Drittanbietern in PS konvertieren. Erstens können Sie die E-Mail-Manipulations-API [Aspose.Email for Java](https://products.aspose.com/email/java/) verwenden, um das EML-Dateiformat in HTML zu konvertieren. Zweitens können Sie HTML in PS rendern, indem Sie die Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie E-MAIL in PS" %}}
1. Öffnen Sie die EML-Datei mit der Klasse [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im PS-Format mit [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie PS als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie müssen Aspose.Total für Java direkt aus einem [Maven](https://releases.aspose.com/total/java/)-basierten Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
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

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}