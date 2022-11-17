---
title: API Android per il rendering da PCL a PS
description: Trasforma PCL in PS tramite Android tramite API Java

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: PS
otherformats: MARKDOWN WORDML OTT FLATOPC XAMLFLOW MHTML ODT DOTX RTF DOT DOCM DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da PCL a PS su Android tramite Java" h2="Converti PCL in PS nelle app mobili senza installare alcun software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da PCL a PS nelle tue app mobili utilizzando due API del pacchetto [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Per prima cosa devi convertire il file PCL in DOC usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). In secondo luogo, utilizzando l'API di elaborazione testi [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puoi eseguire il rendering di DOC in PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti PCL in PS su Android tramite Java" %}}
1. Aprire il file PCL utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PCL in DOC utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato PS utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare PS come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni informazioni sui file PCL su Android tramite Java" %}}
Prima di convertire PCL in PS, potresti aver bisogno di informazioni sul documento tra cui autore, data di creazione, parole chiave, data di modifica, oggetto e titolo. Queste informazioni sono utili per il processo decisionale per il processo di conversione. Usando la potente API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), puoi ottenere tutto. Per ottenere informazioni specifiche su un file PCL, ottenere prima l'oggetto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) utilizzando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) metodo. Una volta recuperato l'oggetto DocumentInfo, è possibile ottenere i valori delle singole proprietà.
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

{{% blocks/products/pf/feature-page-section  h2="Inserisci le note di chiusura nel documento PS in Android tramite Java" %}}
Oltre alla conversione dei documenti, puoi anche aggiungere una serie di altre funzionalità all'interno delle tue applicazioni Android utilizzando l'API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Una di queste funzionalità è l'inserimento di note di chiusura e numerazione nel documento PS. Se si desidera inserire una nota a piè di pagina o una nota di chiusura in un documento PS, utilizzare il metodo DocumentBuilder.InsertFootnote. Questo metodo inserisce una nota a piè di pagina o una nota di chiusura nel documento. Le classi EndnoteOptions e FootnoteOptions rappresentano le opzioni di numerazione per la nota a piè di pagina e la nota di chiusura.
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
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-markdown/" name="PCL Per MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-wordml/" name="PCL Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-ott/" name="PCL Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-flatopc/" name="PCL Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-xamlflow/" name="PCL Per XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-mhtml/" name="PCL Per MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-odt/" name="PCL Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-dotx/" name="PCL Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-rtf/" name="PCL Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-dot/" name="PCL Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-ps/" name="PCL Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pcl-to-dotm/" name="PCL Per DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}