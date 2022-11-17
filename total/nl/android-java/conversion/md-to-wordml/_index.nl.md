---
title: Android API om MD naar WORDML te renderen
description: Transformeer MD naar WORDML via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: WORD_ML
otherformats: MHTML ODT DOT MARKDOWN PCL FLATOPC RTF DOTM DOTX OTT PS DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MD naar WORDML op Android via Java" h2="Converteer MD naar WORDML in mobiele apps zonder software te installeren" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van MD naar WORDML in uw mobiele apps integreren door twee API's van het pakket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) te gebruiken. Eerst moet u het MD-bestand naar DOC converteren met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Ten tweede kunt u met behulp van de API voor tekstverwerking [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) DOC naar WORDML weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer MD naar WORDML op Android via Java" %}}
1. Open het MD-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer MD naar DOC met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in WORDML-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) en stel WORDML in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WORD_ML
outputDocument.save("output.word_ml", SaveFormat.WORD_ML);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ontvang MD-bestandsinformatie op Android via Java" %}}
Voordat u MD naar WORDML converteert, heeft u mogelijk informatie nodig over het document, inclusief auteur, aanmaakdatum, trefwoorden, wijzigingsdatum, onderwerp en titel. Deze informatie is nuttig voor de besluitvorming over het conversieproces. Met behulp van de krachtige [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kunt u het allemaal krijgen. Om bestandsspecifieke informatie over een MD-bestand te krijgen, haalt u eerst het object [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) op met behulp van [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) methode. Zodra het DocumentInfo-object is opgehaald, kunt u de waarden van de afzonderlijke eigenschappen ophalen.
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

{{% blocks/products/pf/feature-page-section  h2="Eindnoten invoegen in WORDML-document in Android via Java" %}}
Afgezien van documentconversie, kunt u ook een aantal andere functies toevoegen aan uw Android-applicaties met behulp van [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Een van die functies is het invoegen van eindnoten en nummering in het WORDML-document. Als u een voetnoot of een eindnoot in een WORDML-document wilt invoegen, gebruik dan de DocumentBuilder.InsertFootnote-methode. Deze methode voegt een voetnoot of eindnoot in het document in. De klassen EndnoteOptions en FootnoteOptions vertegenwoordigen nummeringsopties voor voetnoot en eindnoot.
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
doc.save("output.word_ml", SaveFormat.WORD_ML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-mhtml/" name="MD Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-odt/" name="MD Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-dot/" name="MD Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-markdown/" name="MD Tot MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-pcl/" name="MD Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-flatopc/" name="MD Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-rtf/" name="MD Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-dotm/" name="MD Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-dotx/" name="MD Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-ott/" name="MD Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-ps/" name="MD Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/md-to-wordml/" name="MD Tot WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}