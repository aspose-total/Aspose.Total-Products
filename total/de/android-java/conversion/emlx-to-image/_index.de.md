---
title: Rendern Sie E-MAIL zu IMAGE in der Andorid App
description: Exportieren Sie E-MAIL nach IMAGE, ohne Microsoft Word oder Outlook in Ihren Android-Anwendungen zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PNG
otherformats: PS DOTX RTF GIF JPEG OTT DOCM TIFF WORDML PNG EPUB FLATOPC DOCX XPS PCL EMF DOT TEXT DOTM ODT DOC MD PDF SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Wandeln Sie E-MAIL in IMAGE in Andorid-Apps um" h2="Entwerfen von Andorid-Anwendungen zum Exportieren von E-MAIL nach IMAGE mithilfe von Andorid über die Java-API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid-Apps sind für Endbenutzer täglich einfach zu verwenden. Tag für Tag steigt die Zahl der Benutzer von Android-Telefonen. Mit den leistungsstarken [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dateiformatautomatisierungsbibliotheken können Sie E-Mail-Manipulations- und Konvertierungsanwendungen entwickeln. Sie können EMLX in IMAGE konvertieren, indem Sie [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Mit der ersten API können Sie das EMLX-Dateiformat in HTML konvertieren und mit der zweiten API können Sie HTML als IMAGE rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie E-MAIL in IMAGE in Andorid" %}}
1. Öffnen Sie die EMLX-Datei mit der Klasse [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage).
2. Konvertieren Sie E-MAIL in HTML, indem Sie [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) Methode
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im IMAGE-Format mit [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode und legen Sie IMAGE als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://releases.aspose.com/total/java/) und verwenden Installieren Sie [Aspose.Emlx für Android über Java](https://docs.aspose.com/emlx/androidjava/installation/) und [Aspose.Words für Andorid über Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}