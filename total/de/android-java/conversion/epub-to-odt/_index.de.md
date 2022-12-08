---
title: Android-API zum Rendern von EPUB in ODT
description: Wandeln Sie EPUB über Android über die Java-API in ODT um

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: ODT
otherformats: PS XAMLFLOW MARKDOWN DOTX FLATOPC RTF DOCM DOTM OTT MHTML PCL WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie EPUB in ODT auf Android über Java" h2="Konvertieren Sie EPUB in ODT in mobilen Apps, ohne Software zu installieren" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die EPUB-zu-ODT-Konvertierungsfunktion in Ihre mobilen Apps integrieren, indem Sie zwei APIs des Pakets [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) verwenden. Zuerst müssen Sie die EPUB-Datei mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) in DOC konvertieren. Zweitens können Sie mit der Textverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) DOC in ODT rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie EPUB in ODT auf Android über Java" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie EPUB in DOC, indem Sie [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im ODT-Format und legen Sie ODT fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Erhalten Sie EPUB-Dateiinformationen auf Android über Java" %}}
Vor der Konvertierung von EPUB in ODT benötigen Sie möglicherweise Informationen über das Dokument, einschließlich Autor, Erstellungsdatum, Schlüsselwörter, Änderungsdatum, Betreff und Titel. Diese Informationen sind hilfreich für die Entscheidungsfindung für den Konvertierungsprozess. Mit der leistungsstarken API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) können Sie all das abrufen. Um dateispezifische Informationen zu einer EPUB-Datei zu erhalten, rufen Sie zuerst das Objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) mit [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) Methode. Nachdem das DocumentInfo-Objekt abgerufen wurde, können Sie die Werte der einzelnen Eigenschaften abrufen.
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB document
Document doc = new Document("template.epub");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Endnoten in ODT-Dokument in Android über Java einfügen" %}}
Abgesehen von der Dokumentenkonvertierung können Sie Ihren Android-Anwendungen auch eine Reihe weiterer Funktionen hinzufügen, indem Sie die [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API verwenden. Eine dieser Funktionen ist das Einfügen von Endnoten und die Nummerierung in das ODT-Dokument. Wenn Sie eine Fußnote oder Endnote in ein ODT-Dokument einfügen möchten, verwenden Sie bitte die Methode DocumentBuilder.InsertFootnote. Diese Methode fügt eine Fußnote oder Endnote in das Dokument ein. Die Klassen EndnoteOptions und FootnoteOptions repräsentieren Nummerierungsoptionen für Fußnote und Endnote.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.odt", SaveFormat.ODT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-ps/" name="EPUB Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-xamlflow/" name="EPUB Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-markdown/" name="EPUB Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-dotx/" name="EPUB Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-flatopc/" name="EPUB Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-rtf/" name="EPUB Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-odt/" name="EPUB Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-dotm/" name="EPUB Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-ott/" name="EPUB Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-mhtml/" name="EPUB Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-pcl/" name="EPUB Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/epub-to-wordml/" name="EPUB Zu WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}