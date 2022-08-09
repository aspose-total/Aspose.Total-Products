---
title: API Android per il rendering da PDF a DOCM
description: Trasforma PDF in DOCM tramite Android tramite API Java
url: /it/android-java/conversion/pdf-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: DOCM
otherformats: ODT OTT FLATOPC MARKDOWN DOTX RTF PS DOT XAMLFLOW MHTML PCL DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da PDF a DOCM su Android tramite Java" h2="Converti PDF in DOCM nelle app mobili senza installare alcun software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da PDF a DOCM nelle tue app mobili utilizzando due API del pacchetto [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Per prima cosa devi convertire il file PDF in DOC usando [Aspose.PDF per Android via Java](https://products.aspose.com/pdf/android-java/). In secondo luogo, utilizzando l'API di elaborazione testi [Aspose.Words per Android Java](https://products.aspose.com/words/android-java/), puoi eseguire il rendering di DOC in DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti PDF in DOCM su Android tramite Java" %}}
1. Aprire il file PDF utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PDF in DOC utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato DOCM utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare DOCM come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF per Android tramite Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Words per Android tramite Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni informazioni sui file PDF su Android tramite Java" %}}
Prima di convertire PDF in DOCM, potresti aver bisogno di informazioni sul documento tra cui autore, data di creazione, parole chiave, data di modifica, oggetto e titolo. Queste informazioni sono utili per il processo decisionale per il processo di conversione. Usando la potente API [Aspose.PDF per Android via Java](https://docs.aspose.com/pdf/androidjava/), puoi ottenere tutto. Per ottenere informazioni specifiche su un file PDF, ottenere prima l'oggetto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) utilizzando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metodo. Una volta recuperato l'oggetto DocumentInfo, è possibile ottenere i valori delle singole proprietà.
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

{{% blocks/products/pf/feature-page-section  h2="Inserisci le note di chiusura nel documento DOCM in Android tramite Java" %}}
Oltre alla conversione dei documenti, puoi anche aggiungere una serie di altre funzionalità all'interno delle tue applicazioni Android utilizzando l'API [Aspose.Words per Android tramite Java](https://products.aspose.com/words/androidjava/). Una di queste funzionalità è l'inserimento di note di chiusura e numerazione nel documento DOCM. Se si desidera inserire una nota a piè di pagina o una nota di chiusura in un documento DOCM, utilizzare il metodo DocumentBuilder.InsertFootnote. Questo metodo inserisce una nota a piè di pagina o una nota di chiusura nel documento. Le classi EndnoteOptions e FootnoteOptions rappresentano le opzioni di numerazione per la nota a piè di pagina e la nota di chiusura.
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
doc.save("output.docm", SaveFormat.DOCM);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-odt/" name="PDF Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-ott/" name="PDF Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-flatopc/" name="PDF Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-markdown/" name="PDF Per MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-dotx/" name="PDF Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-rtf/" name="PDF Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-ps/" name="PDF Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-dot/" name="PDF Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-xamlflow/" name="PDF Per XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-mhtml/" name="PDF Per MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-pcl/" name="PDF Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-dotm/" name="PDF Per DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}