---
title: Android API a XPS megjelenítéséhez MHTML-be
description: A XPS átalakítása MHTML-re Androidon keresztül Java API-n keresztül

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MHTML
otherformats: DOTX DOT OTT DOTM MARKDOWN PS DOCM PCL XAMLFLOW ODT RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a XPS-et MHTML-be Androidon Java segítségével" h2="Konvertálja a XPS-et MHTML-re a mobilalkalmazásokban szoftver telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A XPS–MHTML konverziós funkciót integrálhatja mobilalkalmazásaiba az [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) csomag két API-jával. Először a XPS fájlt DOC formátumba kell konvertálnia az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával. Másodszor, a Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) használatával a DOC-t MHTML-re renderelheti. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a XPS-et MHTML-re Androidon Java segítségével" %}}
1. Nyissa meg a XPS-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével alakítsa át a XPS-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot MHTML formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a MHTML-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Words for Android via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
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

{{% blocks/products/pf/feature-page-section  h2="Szerezzen be XPS-fájladatokat Androidon a Java segítségével" %}}
A XPS MHTML-re konvertálása előtt szükség lehet a dokumentumra vonatkozó információkra, beleértve a szerzőt, a létrehozás dátumát, a kulcsszavakat, a módosítás dátumát, tárgyát és címét. Ez az információ hasznos az átalakítási folyamattal kapcsolatos döntéshozatalban. A hatékony [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API használatával mindezt megszerezheti. Ha fájlspecifikus információkat szeretne kapni egy XPS-fájlról, először szerezze be a [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) objektumot a [getInfo](https://) használatával reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) módszerrel. A DocumentInfo objektum lekérése után megkaphatja az egyes tulajdonságok értékeit.
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

{{% blocks/products/pf/feature-page-section  h2="Végjegyzetek beszúrása a MHTML-dokumentumba Androidon Java segítségével" %}}
A dokumentumok konvertálásán kívül számos egyéb funkciót is hozzáadhat Android-alkalmazásaihoz az [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API használatával. Az egyik ilyen funkció a végjegyzetek beszúrása és a számozás a MHTML-dokumentumban. Ha lábjegyzetet vagy végjegyzetet szeretne beszúrni egy MHTML-dokumentumba, használja a DocumentBuilder.InsertFootnote metódust. Ez a módszer lábjegyzetet vagy végjegyzetet szúr be a dokumentumba. Az EndnoteOptions és FootnoteOptions osztályok a lábjegyzet és a végjegyzet számozási beállításait jelentik.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}