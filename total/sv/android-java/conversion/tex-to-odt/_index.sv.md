---
title: Android API för att rendera TEX till ODT
description: Förvandla TEX till ODT via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: ODT
otherformats: DOT MHTML RTF MARKDOWN PCL FLATOPC XAMLFLOW OTT PS DOTX WORDML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera TEX till ODT på Android via Java" h2="Konvertera TEX till ODT i mobilappar utan att installera någon programvara" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera konverteringsfunktionen TEX till ODT i dina mobilappar genom att använda två API:er av paketet [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Först måste du konvertera TEX-filen till DOC med [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). För det andra, genom att använda Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), kan du rendera DOC till ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera TEX till ODT på Android via Java" %}}
1. Öppna TEX-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera TEX till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i ODT-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in ODT som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Få TEX-filinformation på Android via Java" %}}
Innan du konverterar TEX till ODT kan du behöva information om dokumentet, inklusive författare, skapelsedatum, nyckelord, ändringsdatum, ämne och titel. Denna information är användbar för beslutsfattande för konverteringsprocessen. Genom att använda det kraftfulla [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kan du få allt. För att få filspecifik information om en TEX-fil, skaffa först objektet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) med [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metod. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX document
Document doc = new Document("template.tex");
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

{{% blocks/products/pf/feature-page-section  h2="Infoga slutanteckningar i ODT-dokument i Android via Java" %}}
Förutom dokumentkonvertering kan du också lägga till en massa andra funktioner i dina Android-applikationer med [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. En av dessa funktioner är att infoga slutanteckningar och numrering i ODT-dokument. Om du vill infoga en fotnot eller en slutnot i ett ODT-dokument, använd metoden DocumentBuilder.InsertFootnote. Denna metod infogar en fotnot eller slutnot i dokumentet. Klasserna EndnoteOptions och FootnoteOptions representerar numreringsalternativ för fotnot och slutnot.
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-dot/" name="TEX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-mhtml/" name="TEX Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-rtf/" name="TEX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-markdown/" name="TEX Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-pcl/" name="TEX Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-flatopc/" name="TEX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-xamlflow/" name="TEX Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-ott/" name="TEX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-ps/" name="TEX Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-dotx/" name="TEX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-wordml/" name="TEX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/tex-to-dotm/" name="TEX Till DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}