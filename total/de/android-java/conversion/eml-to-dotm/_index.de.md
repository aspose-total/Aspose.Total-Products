---
title: Rendern Sie E-MAIL zu DOTM in der Andorid App
description: Exportieren Sie E-MAIL nach DOTM, ohne Microsoft Word oder Outlook in Ihren Android-Anwendungen zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOTM
otherformats: PNG TEXT JPEG DOCM EMF GIF OTT PCL PDF WORDML DOCX DOT ODT DOC PS EPUB FLATOPC DOTX RTF MD XPS SVG TIFF BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Wandeln Sie E-MAIL in DOTM in Andorid-Apps um" h2="Entwerfen von Andorid-Anwendungen zum Exportieren von E-MAIL nach DOTM mithilfe von Andorid über die Java-API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid-Apps sind für Endbenutzer täglich einfach zu verwenden. Tag für Tag steigt die Zahl der Benutzer von Android-Telefonen. Mit den leistungsstarken [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dateiformatautomatisierungsbibliotheken können Sie E-Mail-Manipulations- und Konvertierungsanwendungen entwickeln. Sie können EML in DOTM konvertieren, indem Sie [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Mit der ersten API können Sie das EML-Dateiformat in HTML konvertieren und mit der zweiten API können Sie HTML als DOTM rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie E-MAIL in DOTM in Andorid" %}}
1. Öffnen Sie die EML-Datei mit der Klasse [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im DOTM-Format mit [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie DOTM als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://releases.aspose.com/total/java/) und verwenden Installieren Sie [Aspose.Eml für Android über Java](https://docs.aspose.com/eml/androidjava/installation/) und [Aspose.Words für Andorid über Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOTM
document.save("output.dotm", SaveFormat.DOTM); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}