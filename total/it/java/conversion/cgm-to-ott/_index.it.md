---
title: API Java per esportare CGM in OTT
description: Converti CGM in OTT utilizzando l'API Java locale
url_ignore: /it/java/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: WORDML RTF ODT DOT DOTM XAMLFLOW PCL MHTML DOTX OTT MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Trasforma CGM in OTT tramite Java" h2="API Java On Premise per il rendering da CGM a OTT senza l'utilizzo di applicazioni di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire CGM in OTT utilizzando due semplici passaggi. Per prima cosa devi eseguire il rendering del file CGM in DOC utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for Java](https://products.aspose.com/words/java/), puoi convertire DOC in OTT. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire CGM in OTT" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti CGM in DOC utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il file DOC utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) di Aspose.Words
4. Salvare il documento in formato OTT utilizzando il metodo [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e impostare OTT come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includono [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante la conversione da CGM a OTT, anche se il documento è protetto da password, è comunque possibile aprirlo utilizzando l'API di manipolazione PDF [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/). Per aprire il file crittografato, è necessario creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il CGM utilizzando la password del proprietario.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Aprire il documento CGM protetto da password tramite Java" %}}
Durante il salvataggio del documento di input in formato file OTT, puoi anche salvare il documento in un database anziché in un file system. Potrebbe essere necessario implementare l'archiviazione e il recupero di oggetti Document da e verso un database. Ciò sarebbe necessario se stessi implementando qualsiasi tipo di sistema di gestione dei contenuti. Per salvare il OTT nel database è spesso necessario serializzare il documento per ottenere un array di byte. Questo può essere fatto utilizzando l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Dopo aver ottenuto il tuo array di byte, puoi memorizzarlo nel database usando l'istruzione SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Converting i file **Computer Graphics Metafile (CGM)** nel formato **OTT (OpenDocument Text Template)** è vitale per le organizzazioni che utilizzano ambienti open-source e conformi a ODF. Sulle piattaforme basate su **Java**, questa conversione consente di incorporare diagrammi CGM e visualizzazioni tecniche in modelli riutilizzabili compatibili con LibreOffice e altri editor OpenDocument. I modelli OTT garantiscono coerenza nel design, agevolano la modifica collaborativa e semplificano la generazione di report standardizzati tra team distribuiti, mantenendo standard aperti per l'interoperabilità.


## ✅ Principali casi d'uso

- **Generazione di report conforme a ODF**  
  Creare report basati su standard in cui le visualizzazioni CGM si integrano perfettamente con il contenuto strutturato di OpenDocument.

- **Modifica collaborativa dei documenti**  
  Archiviare modelli OTT arricchiti da CGM in repository condivisi per la modifica multiutente in tempo reale su piattaforme open-source.


## ⚙️ Scenari di automazione

- **Automazione Java tramite convertitore**  
  Utilizzare le API di Aspose nei flussi di lavoro Java per convertire i file CGM in modelli OTT per distribuzioni automatizzate.

- **Integrazioni SDK di LibreOffice**  
  Sfruttare lo SDK di LibreOffice nelle applicazioni Java per popolare e personalizzare modelli OTT basati su CGM.

- **Sistemi ETL per la creazione di documenti su larga scala**  
  Integrare la conversione da CGM a OTT nei pipeline ETL basati su Java per la generazione di documenti su larga scala basati su modelli.

- **Piattaforme enterprise open-source**  
  Distribuire modelli OTT con diagrammi CGM incorporati nei sistemi di gestione dei contenuti e automazione dei documenti basati su Java.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}