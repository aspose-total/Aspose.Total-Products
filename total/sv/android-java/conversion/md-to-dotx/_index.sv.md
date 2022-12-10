---
title: Android API för att rendera MD till DOTX
description: Förvandla MD till DOTX via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOTX
otherformats: OTT XAMLFLOW PCL DOCM MARKDOWN MHTML DOT FLATOPC DOTM ODT RTF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera MD till DOTX på Android via Java" h2="Konvertera MD till DOTX i mobilappar utan att installera någon programvara" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan integrera konverteringsfunktionen MD till DOTX i dina mobilappar genom att använda två API:er av paketet [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Först måste du konvertera MD-filen till DOC med [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). För det andra, genom att använda Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), kan du rendera DOC till DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MD till DOTX på Android via Java" %}}
1. Öppna MD-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera MD till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i DOTX-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in DOTX som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Få MD-filinformation på Android via Java" %}}
Innan du konverterar MD till DOTX kan du behöva information om dokumentet, inklusive författare, skapelsedatum, nyckelord, ändringsdatum, ämne och titel. Denna information är användbar för beslutsfattande för konverteringsprocessen. Genom att använda det kraftfulla [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kan du få allt. För att få filspecifik information om en MD-fil, skaffa först objektet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) med [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metod. När DocumentInfo-objektet är hämtat kan du få värdena för de enskilda egenskaperna.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD document
Document doc = new Document("template.md");
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

{{% blocks/products/pf/feature-page-section  h2="Infoga slutanteckningar i DOTX-dokument i Android via Java" %}}
Förutom dokumentkonvertering kan du också lägga till en massa andra funktioner i dina Android-applikationer med [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. En av dessa funktioner är att infoga slutanteckningar och numrering i DOTX-dokument. Om du vill infoga en fotnot eller en slutnot i ett DOTX-dokument, använd metoden DocumentBuilder.InsertFootnote. Denna metod infogar en fotnot eller slutnot i dokumentet. Klasserna EndnoteOptions och FootnoteOptions representerar numreringsalternativ för fotnot och slutnot.
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
doc.save("output.dotx", SaveFormat.DOTX);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-ott/" name="MD Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-xamlflow/" name="MD Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-pcl/" name="MD Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-dotx/" name="MD Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-markdown/" name="MD Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-mhtml/" name="MD Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-dot/" name="MD Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-flatopc/" name="MD Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-dotm/" name="MD Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-odt/" name="MD Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-rtf/" name="MD Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/md-to-ps/" name="MD Till PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}