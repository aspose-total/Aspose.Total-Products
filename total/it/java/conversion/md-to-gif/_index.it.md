---
title: API Java per esportare MD in GIF
description: Converti MD in GIF utilizzando l'API Java locale
url_ignore: /it/java/conversion/md-to-gif/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: GIF
otherformats: FLATOPC OTT MHTML DOTX WORDML GIF DOT DOTM PCL ODT RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Trasforma MD in GIF tramite Java" h2="API Java On Premise per il rendering da MD a GIF senza l'utilizzo di applicazioni di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire MD in GIF utilizzando due semplici passaggi. Per prima cosa devi eseguire il rendering del file MD in DOC utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for Java](https://products.aspose.com/words/java/), puoi convertire DOC in GIF. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire MD in GIF" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MD in DOC utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato GIF utilizzando il metodo [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare GIF come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includono [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante la conversione da MD a GIF, anche se il documento è protetto da password, è comunque possibile aprirlo utilizzando l'API di manipolazione PDF [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/). Per aprire il file crittografato, è necessario creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il MD utilizzando la password del proprietario.  
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
Durante il salvataggio del documento di input in formato file GIF, puoi anche salvare il documento in un database anziché in un file system. Potrebbe essere necessario implementare l'archiviazione e il recupero di oggetti Document da e verso un database. Ciò sarebbe necessario se stessi implementando qualsiasi tipo di sistema di gestione dei contenuti. Per salvare il GIF nel database è spesso necessario serializzare il documento per ottenere un array di byte. Questo può essere fatto utilizzando l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Dopo aver ottenuto il tuo array di byte, puoi memorizzarlo nel database usando l'istruzione SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
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
"""
{{< blocks/products/pf/agp/feature-section >}}



La conversione di Markdown (MD) in GIF consente di trasformare contenuti di testo, diagrammi o organigrammi in animazioni in loop. I GIF sono ampiamente supportati, rendendoli adatti per tutorial, contenuti sui social media e visualizzazioni interattive leggere.



{{% blocks/products/pf/agp/feature-section-col title="Principali casi d'uso" %}}



* Conversione di organigrammi Markdown in GIF didattici.

* Schede di riferimento animate per codifica o flussi di lavoro documentali.

* Visualizzazioni adatte ai social media derivate da appunti Markdown.

* Illustrazioni in loop per guide tecniche o demo software.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}



* Generazione automatica di GIF dagli aggiornamenti della documentazione Markdown.

* Elaborazione batch di più diagrammi Markdown in GIF.

* Integrazione con i flussi di contenuti per produrre GIF per portali online.

* Conversione programmata da Markdown a GIF per piattaforme di marketing o didattiche.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
"""
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}