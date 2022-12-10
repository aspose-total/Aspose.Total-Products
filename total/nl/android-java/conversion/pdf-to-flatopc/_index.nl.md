---
title: Android API om PDF naar FLATOPC te renderen
description: Transformeer PDF naar FLATOPC via Android via Java API

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: FLAT_OPC
otherformats: MHTML DOTM PCL WORDML RTF OTT XAMLFLOW DOTX DOT ODT PS MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF naar FLATOPC op Android via Java" h2="Converteer PDF naar FLATOPC in mobiele apps zonder software te installeren" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt de conversiefunctie van PDF naar FLATOPC in uw mobiele apps integreren door twee API's van het pakket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) te gebruiken. Eerst moet u het PDF-bestand naar DOC converteren met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Ten tweede kunt u met behulp van de API voor tekstverwerking [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) DOC naar FLATOPC weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer PDF naar FLATOPC op Android via Java" %}}
1. Open het PDF-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer PDF naar DOC met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in FLATOPC-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) en stel FLATOPC in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://releases.aspose.com/total/java/) en installeer [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) en [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ontvang PDF-bestandsinformatie op Android via Java" %}}
Voordat u PDF naar FLATOPC converteert, heeft u mogelijk informatie nodig over het document, inclusief auteur, aanmaakdatum, trefwoorden, wijzigingsdatum, onderwerp en titel. Deze informatie is nuttig voor de besluitvorming over het conversieproces. Met behulp van de krachtige [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API kunt u het allemaal krijgen. Om bestandsspecifieke informatie over een PDF-bestand te krijgen, haalt u eerst het object [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) op met behulp van [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) methode. Zodra het DocumentInfo-object is opgehaald, kunt u de waarden van de afzonderlijke eigenschappen ophalen.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF document
Document doc = new Document("template.pdf");
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

{{% blocks/products/pf/feature-page-section  h2="Eindnoten invoegen in FLATOPC-document in Android via Java" %}}
Afgezien van documentconversie, kunt u ook een aantal andere functies toevoegen aan uw Android-applicaties met behulp van [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Een van die functies is het invoegen van eindnoten en nummering in het FLATOPC-document. Als u een voetnoot of een eindnoot in een FLATOPC-document wilt invoegen, gebruik dan de DocumentBuilder.InsertFootnote-methode. Deze methode voegt een voetnoot of eindnoot in het document in. De klassen EndnoteOptions en FootnoteOptions vertegenwoordigen nummeringsopties voor voetnoot en eindnoot.
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
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-mhtml/" name="PDF Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-dotm/" name="PDF Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-pcl/" name="PDF Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-wordml/" name="PDF Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-rtf/" name="PDF Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-ott/" name="PDF Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-xamlflow/" name="PDF Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-dotx/" name="PDF Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-dot/" name="PDF Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-odt/" name="PDF Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-ps/" name="PDF Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pdf-to-markdown/" name="PDF Tot MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}