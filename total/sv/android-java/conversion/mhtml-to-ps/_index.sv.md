---
title: Android API för att rendera MHTML till PS
description: Förvandla MHTML till PS via Android via Java API
url: /sv/android-java/conversion/mhtml-to-ps/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: PS
otherformats: FLATOPC DOTX PCL RTF ODT XAMLFLOW OTT MARKDOWN DOCM WORDML DOT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera MHTML till PS på Android via Java" h2="Konvertera MHTML till PS i mobilappar utan att installera någon programvara" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera konverteringsfunktionen MHTML till PS i dina mobilappar genom att använda två API:er av paketet [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Först måste du konvertera MHTML-filen till DOC med [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). För det andra, genom att använda Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), kan du rendera DOC till PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MHTML till PS på Android via Java" %}}
1. Öppna MHTML-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera MHTML till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i PS-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in PS som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Få MHTML-filinformation på Android via Java" %}}
Innan du konverterar MHTML till PS kan du behöva information om dokumentet, inklusive författare, skapelsedatum, nyckelord, ändringsdatum, ämne och titel. Denna information är användbar för beslutsfattande för konverteringsprocessen. Genom att använda det kraftfulla [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kan du få allt. För att få filspecifik information om en MHTML-fil, skaffa först objektet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) med [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metod. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
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

{{% blocks/products/pf/feature-page-section  h2="Infoga slutanteckningar i PS-dokument i Android via Java" %}}
Förutom dokumentkonvertering kan du också lägga till en massa andra funktioner i dina Android-applikationer med [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. En av dessa funktioner är att infoga slutanteckningar och numrering i PS-dokument. Om du vill infoga en fotnot eller en slutnot i ett PS-dokument, använd metoden DocumentBuilder.InsertFootnote. Denna metod infogar en fotnot eller slutnot i dokumentet. Klasserna EndnoteOptions och FootnoteOptions representerar numreringsalternativ för fotnot och slutnot.
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
doc.save("output.ps", SaveFormat.PS);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-flatopc/" name="MHTML Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-dotx/" name="MHTML Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-pcl/" name="MHTML Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-rtf/" name="MHTML Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-odt/" name="MHTML Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-xamlflow/" name="MHTML Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-ott/" name="MHTML Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-markdown/" name="MHTML Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-ps/" name="MHTML Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-wordml/" name="MHTML Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-dot/" name="MHTML Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/mhtml-to-dotm/" name="MHTML Till DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}