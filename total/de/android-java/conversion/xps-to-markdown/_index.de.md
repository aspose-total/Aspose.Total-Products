---
title: Android-API zum Rendern von XPS in MARKDOWN
description: Wandeln Sie XPS über Android über die Java-API in MARKDOWN um
url: /de/android-java/conversion/xps-to-markdown/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MARKDOWN
otherformats: MHTML XAMLFLOW DOCM PS ODT OTT DOTM FLATOPC DOTX DOT WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie XPS in MARKDOWN auf Android über Java" h2="Konvertieren Sie XPS in MARKDOWN in mobilen Apps, ohne Software zu installieren" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die XPS-zu-MARKDOWN-Konvertierungsfunktion in Ihre mobilen Apps integrieren, indem Sie zwei APIs des Pakets [Aspose.Total für Android Java](https://products.aspose.com/total/android-java/) verwenden. Zuerst müssen Sie die XPS-Datei mit [Aspose.PDF für Android über Java](https://products.aspose.com/pdf/android-java/) in DOC konvertieren. Zweitens können Sie mit der Textverarbeitungs-API [Aspose.Words für Android Java](https://products.aspose.com/words/android-java/) DOC in MARKDOWN rendern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie XPS in MARKDOWN auf Android über Java" %}}
1. Öffnen Sie die XPS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie XPS in DOC, indem Sie [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im MARKDOWN-Format und legen Sie MARKDOWN fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF für Android über Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Words für Android über Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Erhalten Sie XPS-Dateiinformationen auf Android über Java" %}}
Vor der Konvertierung von XPS in MARKDOWN benötigen Sie möglicherweise Informationen über das Dokument, einschließlich Autor, Erstellungsdatum, Schlüsselwörter, Änderungsdatum, Betreff und Titel. Diese Informationen sind hilfreich für die Entscheidungsfindung für den Konvertierungsprozess. Mit der leistungsstarken API [Aspose.PDF für Android über Java](https://docs.aspose.com/pdf/androidjava/) können Sie all das abrufen. Um dateispezifische Informationen zu einer XPS-Datei zu erhalten, rufen Sie zuerst das Objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) mit [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) Methode. Nachdem das DocumentInfo-Objekt abgerufen wurde, können Sie die Werte der einzelnen Eigenschaften abrufen.
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
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

{{% blocks/products/pf/feature-page-section  h2="Endnoten in MARKDOWN-Dokument in Android über Java einfügen" %}}
Abgesehen von der Dokumentenkonvertierung können Sie Ihren Android-Anwendungen auch eine Reihe weiterer Funktionen hinzufügen, indem Sie die [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API verwenden. Eine dieser Funktionen ist das Einfügen von Endnoten und die Nummerierung in das MARKDOWN-Dokument. Wenn Sie eine Fußnote oder Endnote in ein MARKDOWN-Dokument einfügen möchten, verwenden Sie bitte die Methode DocumentBuilder.InsertFootnote. Diese Methode fügt eine Fußnote oder Endnote in das Dokument ein. Die Klassen EndnoteOptions und FootnoteOptions repräsentieren Nummerierungsoptionen für Fußnote und Endnote.
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
doc.save("output.markdown", SaveFormat.MARKDOWN);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-mhtml/" name="XPS Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-xamlflow/" name="XPS Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-markdown/" name="XPS Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-ps/" name="XPS Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-odt/" name="XPS Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-ott/" name="XPS Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-dotm/" name="XPS Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-flatopc/" name="XPS Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-dotx/" name="XPS Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-dot/" name="XPS Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-wordml/" name="XPS Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xps-to-rtf/" name="XPS Zu RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}