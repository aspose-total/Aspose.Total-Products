---
title: API Java per esportare MD in XAMLFLOW
description: Converti MD in XAMLFLOW utilizzando l'API Java locale
url_ignore: /it/java/conversion/md-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: XAML_FLOW
otherformats: PS ODT PCL DOTM DOT RTF MARKDOWN FLATOPC WORDML XAMLFLOW DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Trasforma MD in XAMLFLOW tramite Java" h2="API Java On Premise per il rendering da MD a XAMLFLOW senza l'utilizzo di applicazioni di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire MD in XAMLFLOW utilizzando due semplici passaggi. Per prima cosa devi eseguire il rendering del file MD in DOC utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for Java](https://products.aspose.com/words/java/), puoi convertire DOC in XAMLFLOW. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire MD in XAMLFLOW" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MD in DOC utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato XAMLFLOW utilizzando il metodo [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare XAMLFLOW come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includono [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-xaml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante la conversione da MD a XAMLFLOW, anche se il documento è protetto da password, è comunque possibile aprirlo utilizzando l'API di manipolazione PDF [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/). Per aprire il file crittografato, è necessario creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il MD utilizzando la password del proprietario.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Aprire il documento MD protetto da password tramite Java" %}}
Durante il salvataggio del documento di input in formato file XAMLFLOW, puoi anche salvare il documento in un database anziché in un file system. Potrebbe essere necessario implementare l'archiviazione e il recupero di oggetti Document da e verso un database. Ciò sarebbe necessario se stessi implementando qualsiasi tipo di sistema di gestione dei contenuti. Per salvare il XAMLFLOW nel database è spesso necessario serializzare il documento per ottenere un array di byte. Questo può essere fatto utilizzando l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Dopo aver ottenuto il tuo array di byte, puoi memorizzarlo nel database usando l'istruzione SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversione di Markdown (MD) in XAMLFLOW consente la creazione di diagrammi interattivi basati su flussi e layout dell'applicazione utilizzando il markup XAML. Ideale per la visualizzazione del software, la prototipazione dell'interfaccia utente e la documentazione dei flussi di lavoro.



{{% blocks/products/pf/agp/feature-section-col title="Casi d'Uso Principali" %}}



* Costruzione di diagrammi di flusso interattivi dalla documentazione Markdown.

* Prototipazione dei flussi di lavoro dell'applicazione WPF utilizzando il contenuto Markdown.

* Traduzione delle note sui processi tecnici in visualizzazioni XAMLFlow.

* Incorporazione dei flussi generati da Markdown nelle anteprime dell'applicazione interattive.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scenari di Automazione" %}}



* Pipeline automatizzate da MD a XAMLFLOW per i team di sviluppo.

* Generazione batch di flussi interattivi dalle note Markdown.

* Aggiornamenti programmati dei diagrammi dei flussi nella documentazione del software.

* Integrazione con CI/CD per convertire gli schemi di processo Markdown in componenti XAMLFLOW.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}