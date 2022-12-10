---
title: Android API om EPUB naar MARKDOWN te renderen
description: Transformeer EPUB naar MARKDOWN via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: MARKDOWN
otherformats: WORDML ODT RTF XAMLFLOW FLATOPC PCL DOCM DOTM DOTX MHTML OTT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EPUB naar MARKDOWN op Android via Java" h2="Converteer EPUB naar MARKDOWN in mobiele apps zonder software te installeren" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van EPUB naar MARKDOWN in uw mobiele apps integreren door twee API's van het pakket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) te gebruiken. Eerst moet u het EPUB-bestand naar DOC converteren met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Ten tweede kunt u met behulp van de API voor tekstverwerking [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) DOC naar MARKDOWN weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer EPUB naar MARKDOWN op Android via Java" %}}
1. Open het EPUB-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer EPUB naar DOC met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in MARKDOWN-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) en stel MARKDOWN in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://releases.aspose.com/total/java/) en installeer [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ontvang EPUB-bestandsinformatie op Android via Java" %}}
Voordat u EPUB naar MARKDOWN converteert, heeft u mogelijk informatie nodig over het document, inclusief auteur, aanmaakdatum, trefwoorden, wijzigingsdatum, onderwerp en titel. Deze informatie is nuttig voor de besluitvorming over het conversieproces. Met behulp van de krachtige [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kunt u het allemaal krijgen. Om bestandsspecifieke informatie over een EPUB-bestand te krijgen, haalt u eerst het object [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) op met behulp van [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) methode. Zodra het DocumentInfo-object is opgehaald, kunt u de waarden van de afzonderlijke eigenschappen ophalen.
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

{{% blocks/products/pf/feature-page-section  h2="Eindnoten invoegen in MARKDOWN-document in Android via Java" %}}
Afgezien van documentconversie, kunt u ook een aantal andere functies toevoegen aan uw Android-applicaties met behulp van [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Een van die functies is het invoegen van eindnoten en nummering in het MARKDOWN-document. Als u een voetnoot of een eindnoot in een MARKDOWN-document wilt invoegen, gebruik dan de DocumentBuilder.InsertFootnote-methode. Deze methode voegt een voetnoot of eindnoot in het document in. De klassen EndnoteOptions en FootnoteOptions vertegenwoordigen nummeringsopties voor voetnoot en eindnoot.
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-wordml/" name="EPUB Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-odt/" name="EPUB Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-rtf/" name="EPUB Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-xamlflow/" name="EPUB Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-flatopc/" name="EPUB Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-pcl/" name="EPUB Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-markdown/" name="EPUB Tot MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-dotm/" name="EPUB Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-dotx/" name="EPUB Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-mhtml/" name="EPUB Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-ott/" name="EPUB Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/epub-to-dot/" name="EPUB Tot DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}