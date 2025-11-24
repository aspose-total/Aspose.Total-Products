---
title: API Java per esportare MD in DOCM
description: Converti MD in DOCM utilizzando l'API Java locale
url_ignore: /it/java/conversion/md-to-docm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOCM
otherformats: DOTM PS XAMLFLOW RTF MARKDOWN FLATOPC OTT PCL DOT WORDML ODT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Trasforma MD in DOCM tramite Java" h2="API Java On Premise per il rendering da MD a DOCM senza l'utilizzo di applicazioni di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire MD in DOCM utilizzando due semplici passaggi. Per prima cosa devi eseguire il rendering del file MD in DOC utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for Java](https://products.aspose.com/words/java/), puoi convertire DOC in DOCM. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire MD in DOCM" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MD in DOC utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato DOCM utilizzando il metodo [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare DOCM come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includono [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante la conversione da MD a DOCM, anche se il documento è protetto da password, è comunque possibile aprirlo utilizzando l'API di manipolazione PDF [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/). Per aprire il file crittografato, è necessario creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il MD utilizzando la password del proprietario.  
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
Durante il salvataggio del documento di input in formato file DOCM, puoi anche salvare il documento in un database anziché in un file system. Potrebbe essere necessario implementare l'archiviazione e il recupero di oggetti Document da e verso un database. Ciò sarebbe necessario se stessi implementando qualsiasi tipo di sistema di gestione dei contenuti. Per salvare il DOCM nel database è spesso necessario serializzare il documento per ottenere un array di byte. Questo può essere fatto utilizzando l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Dopo aver ottenuto il tuo array di byte, puoi memorizzarlo nel database usando l'istruzione SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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



La trasformazione dei file MD (Markdown) in file DOCM (Documenti abilitati ai macro di Word) consente ai team di arricchire i file di testo leggero con funzionalità di automazione interattive. I file DOCM supportano i macro incorporati, rendendoli ideali per la documentazione basata su flussi di lavoro, i modelli aziendali e i report generati automaticamente che richiedono azioni dinamiche all'interno di Word.



{{% blocks/products/pf/agp/feature-section-col title="Principali casi d'uso" %}}



* Conversione delle note Markdown dei programmatori in SOP potenziate da macro.

* Documenti di politica abilitati all'auto-azione per i flussi di lavoro aziendali.

* Modelli di proposte interattivi creati da file MD archiviati su Git.

* Registri di audit basati su macro generati da changelog basati su Markdown.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}



* Conversione pianificata da MD a DOCM per i team di conformità.

* Pipeline ETL che producono report di Word abilitati ai macro da Markdown.

* Flussi di lavoro CI/CD che rigenerano documenti DOCM dal contenuto del repository.

* Documentazione automatizzata attivata da macro per i dipartimenti di ingegneria.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}