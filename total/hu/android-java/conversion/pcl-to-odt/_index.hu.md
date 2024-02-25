---
title: Android API a PCL megjelenítéséhez ODT-be
description: A PCL átalakítása ODT-re Androidon keresztül Java API-n keresztül

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: ODT
otherformats: MARKDOWN DOT PS RTF OTT DOTM DOCM XAMLFLOW WORDML MHTML FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a PCL-et ODT-be Androidon Java segítségével" h2="Konvertálja a PCL-et ODT-re a mobilalkalmazásokban szoftver telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A PCL–ODT konverziós funkciót integrálhatja mobilalkalmazásaiba az [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) csomag két API-jával. Először a PCL fájlt DOC formátumba kell konvertálnia az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával. Másodszor, a Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) használatával a DOC-t ODT-re renderelheti. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a PCL-et ODT-re Androidon Java segítségével" %}}
1. Nyissa meg a PCL-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. A [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével alakítsa át a PCL-et DOC-vé ) módszerrel
3. Töltse be a DOC-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words osztály használatával
4. Mentse a dokumentumot ODT formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel, és állítsa be a ODT-et mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Words for Android via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Szerezzen be PCL-fájladatokat Androidon a Java segítségével" %}}
A PCL ODT-re konvertálása előtt szükség lehet a dokumentumra vonatkozó információkra, beleértve a szerzőt, a létrehozás dátumát, a kulcsszavakat, a módosítás dátumát, tárgyát és címét. Ez az információ hasznos az átalakítási folyamattal kapcsolatos döntéshozatalban. A hatékony [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API használatával mindezt megszerezheti. Ha fájlspecifikus információkat szeretne kapni egy PCL-fájlról, először szerezze be a [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) objektumot a [getInfo](https://) használatával reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) módszerrel. A DocumentInfo objektum lekérése után megkaphatja az egyes tulajdonságok értékeit.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL document
Document doc = new Document("template.pcl");
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

{{% blocks/products/pf/feature-page-section  h2="Végjegyzetek beszúrása a ODT-dokumentumba Androidon Java segítségével" %}}
A dokumentumok konvertálásán kívül számos egyéb funkciót is hozzáadhat Android-alkalmazásaihoz az [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API használatával. Az egyik ilyen funkció a végjegyzetek beszúrása és a számozás a ODT-dokumentumban. Ha lábjegyzetet vagy végjegyzetet szeretne beszúrni egy ODT-dokumentumba, használja a DocumentBuilder.InsertFootnote metódust. Ez a módszer lábjegyzetet vagy végjegyzetet szúr be a dokumentumba. Az EndnoteOptions és FootnoteOptions osztályok a lábjegyzet és a végjegyzet számozási beállításait jelentik.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}