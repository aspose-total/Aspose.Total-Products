---
title: API Java per esportare CGM in MHTML
description: Converti CGM in MHTML utilizzando l'API Java locale
url_ignore: /it/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Trasforma CGM in MHTML tramite Java" h2="API Java On Premise per il rendering da CGM a MHTML senza l'utilizzo di applicazioni di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire CGM in MHTML utilizzando due semplici passaggi. Per prima cosa devi eseguire il rendering del file CGM in DOC utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for Java](https://products.aspose.com/words/java/), puoi convertire DOC in MHTML. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire CGM in MHTML" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti CGM in DOC utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato MHTML utilizzando il metodo [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare MHTML come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includono [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante la conversione da CGM a MHTML, anche se il documento è protetto da password, è comunque possibile aprirlo utilizzando l'API di manipolazione PDF [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/). Per aprire il file crittografato, è necessario creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il CGM utilizzando la password del proprietario.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Aprire il documento CGM protetto da password tramite Java" %}}
Durante il salvataggio del documento di input in formato file MHTML, puoi anche salvare il documento in un database anziché in un file system. Potrebbe essere necessario implementare l'archiviazione e il recupero di oggetti Document da e verso un database. Ciò sarebbe necessario se stessi implementando qualsiasi tipo di sistema di gestione dei contenuti. Per salvare il MHTML nel database è spesso necessario serializzare il documento per ottenere un array di byte. Questo può essere fatto utilizzando l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Dopo aver ottenuto il tuo array di byte, puoi memorizzarlo nel database usando l'istruzione SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertire i file **Computer Graphics Metafile (CGM)** nel formato **MHTML (MIME HTML)** è essenziale per preservare documenti complessi di ingegneria e tecnici con grafica integrata in un unico file autocontenuto. Nei sistemi di archiviazione web basati su **Java**, questa conversione consente alle organizzazioni di memorizzare documenti completi, inclusi elementi visivi CGM, stili e risorse, all'interno di un archivio portatile adatto alla visualizzazione offline e alla distribuzione in intranet. MHTML garantisce che le specifiche di progettazione, i report e i disegni rimangano integri per un accesso e una distribuzione a lungo termine.

---

## ✅ Principali casi d'uso

- **Raggruppamento di Documenti di Ingegneria con Grafica Integrata**  
  Raggruppare diagrammi CGM e contenuti correlati in MHTML per registrazioni tecniche coerenti e autocontenute.

- **Visualizzazione Offline nei Portali Intranet**  
  Fornire documenti arricchiti da CGM in formato MHTML per un accesso offline senza interruzioni attraverso le reti aziendali.

- **Archiviazione delle Specifiche di Progettazione**  
  Memorizzare versioni MHTML delle specifiche basate su CGM per conformità, riferimento e documentazione di progetto.

---

## ⚙️ Scenari di Automazione

- **Librerie Java con Supporto MHTML**  
  Utilizzare API come **Aspose.Words for Java** o esportatori Java personalizzati per generare file MHTML da documenti basati su CGM.

- **Strumenti di Esportazione Basati sul Web**  
  Integrare la conversione da CGM a MHTML in applicazioni web basate su Java per un'immediata confezione dei file.

- **Flussi di Lavoro di Conversione basati su Servlet**  
  Distribuire servlet Java che elaborano input CGM e producono archivi MHTML per una distribuzione sicura.

- **Pipeline di Archiviazione Automatica**  
  Includere passaggi da CGM a MHTML in sistemi di gestione documentale o ETL basati su Java per l'archiviazione programmata.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}