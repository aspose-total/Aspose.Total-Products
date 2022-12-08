---
title: Android-API zum Rendern von SVG in DOCM
description: Wandeln Sie SVG über Android über die Java-API in DOCM um

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOCM
otherformats: FLATOPC DOTX PCL MARKDOWN ODT RTF PS MHTML XAMLFLOW DOT DOTM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie SVG in DOCM auf Android über Java" h2="Konvertieren Sie SVG in DOCM in mobilen Apps, ohne Software zu installieren" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die SVG-zu-DOCM-Konvertierungsfunktion in Ihre mobilen Apps integrieren, indem Sie zwei APIs des Pakets [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) verwenden. Zuerst müssen Sie die SVG-Datei mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) in DOC konvertieren. Zweitens können Sie mit der Textverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) DOC in DOCM rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie SVG in DOCM auf Android über Java" %}}
1. Öffnen Sie die SVG-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie SVG in DOC, indem Sie [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im DOCM-Format und legen Sie DOCM fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Erhalten Sie SVG-Dateiinformationen auf Android über Java" %}}
Vor der Konvertierung von SVG in DOCM benötigen Sie möglicherweise Informationen über das Dokument, einschließlich Autor, Erstellungsdatum, Schlüsselwörter, Änderungsdatum, Betreff und Titel. Diese Informationen sind hilfreich für die Entscheidungsfindung für den Konvertierungsprozess. Mit der leistungsstarken API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) können Sie all das abrufen. Um dateispezifische Informationen zu einer SVG-Datei zu erhalten, rufen Sie zuerst das Objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) mit [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) Methode. Nachdem das DocumentInfo-Objekt abgerufen wurde, können Sie die Werte der einzelnen Eigenschaften abrufen.
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG document
Document doc = new Document("template.svg");
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

{{% blocks/products/pf/feature-page-section  h2="Endnoten in DOCM-Dokument in Android über Java einfügen" %}}
Abgesehen von der Dokumentenkonvertierung können Sie Ihren Android-Anwendungen auch eine Reihe weiterer Funktionen hinzufügen, indem Sie die [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API verwenden. Eine dieser Funktionen ist das Einfügen von Endnoten und die Nummerierung in das DOCM-Dokument. Wenn Sie eine Fußnote oder Endnote in ein DOCM-Dokument einfügen möchten, verwenden Sie bitte die Methode DocumentBuilder.InsertFootnote. Diese Methode fügt eine Fußnote oder Endnote in das Dokument ein. Die Klassen EndnoteOptions und FootnoteOptions repräsentieren Nummerierungsoptionen für Fußnote und Endnote.
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
doc.save("output.docm", SaveFormat.DOCM);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-flatopc/" name="SVG Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-dotx/" name="SVG Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-pcl/" name="SVG Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-markdown/" name="SVG Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-odt/" name="SVG Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-rtf/" name="SVG Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-ps/" name="SVG Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-mhtml/" name="SVG Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-xamlflow/" name="SVG Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-dot/" name="SVG Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-dotm/" name="SVG Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/svg-to-wordml/" name="SVG Zu WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}