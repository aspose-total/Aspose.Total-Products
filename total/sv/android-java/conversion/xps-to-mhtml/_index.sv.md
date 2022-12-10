---
title: Android API för att rendera XPS till MHTML
description: Förvandla XPS till MHTML via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MHTML
otherformats: DOTX DOT OTT DOTM MARKDOWN PS DOCM PCL XAMLFLOW ODT RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XPS till MHTML på Android via Java" h2="Konvertera XPS till MHTML i mobilappar utan att installera någon programvara" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera konverteringsfunktionen XPS till MHTML i dina mobilappar genom att använda två API:er av paketet [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Först måste du konvertera XPS-filen till DOC med [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). För det andra, genom att använda Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), kan du rendera DOC till MHTML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera XPS till MHTML på Android via Java" %}}
1. Öppna XPS-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XPS till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i MHTML-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in MHTML som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Få XPS-filinformation på Android via Java" %}}
Innan du konverterar XPS till MHTML kan du behöva information om dokumentet, inklusive författare, skapelsedatum, nyckelord, ändringsdatum, ämne och titel. Denna information är användbar för beslutsfattande för konverteringsprocessen. Genom att använda det kraftfulla [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kan du få allt. För att få filspecifik information om en XPS-fil, skaffa först objektet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) med [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metod. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna.
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

{{% blocks/products/pf/feature-page-section  h2="Infoga slutanteckningar i MHTML-dokument i Android via Java" %}}
Förutom dokumentkonvertering kan du också lägga till en massa andra funktioner i dina Android-applikationer med [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. En av dessa funktioner är att infoga slutanteckningar och numrering i MHTML-dokument. Om du vill infoga en fotnot eller en slutnot i ett MHTML-dokument, använd metoden DocumentBuilder.InsertFootnote. Denna metod infogar en fotnot eller slutnot i dokumentet. Klasserna EndnoteOptions och FootnoteOptions representerar numreringsalternativ för fotnot och slutnot.
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
doc.save("output.mhtml", SaveFormat.MHTML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-dotx/" name="XPS Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-dot/" name="XPS Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-ott/" name="XPS Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-dotm/" name="XPS Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-markdown/" name="XPS Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-ps/" name="XPS Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-mhtml/" name="XPS Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-pcl/" name="XPS Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-xamlflow/" name="XPS Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-odt/" name="XPS Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-rtf/" name="XPS Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xps-to-flatopc/" name="XPS Till FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}