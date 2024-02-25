---
title: Rimuovi l'annotazione ODT online o gestisci le annotazioni tramite Java
description: elimina gratuitamente i commenti dal file ODT tramite l'app online. Codice API Java per gestire i commenti dei file ODT.

family: total
platformtag: Java
feature: Annotate
informat: ODT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Cancella commenti dal documento ODT online o gestisci tramite Java" h2="Sviluppa una potente applicazione di utilità per l'annotazione di documenti ODT basata su Java.Codice elencato per la gestione dei commenti del file ODT tramite Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovi le annotazioni ODT online" %}}

1. Importa il file ODT per eliminare i commenti caricandolo
1. Fallo facendo clic all'interno dell'area di rilascio tramite trascinamento dell'app di annotazione
1. A seconda della dimensione del file ODT e della velocità di Internet, attendere alcuni secondi
1. Fare clic sul pulsante "Rimuovi" per cancellare i commenti
1. Scarica il file immediatamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rimuovi i commenti del documento ODT tramite Java" %}}

1. Aggiungi riferimento alla libreria al progetto Java
1. Carica il documento tramite l'oggetto classe Document
1. Ottieni tutti i commenti da tutti i nodi utilizzando [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) e NodeType.COMMENT
1. Richiama il metodo [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) per eliminare tutti i commenti
1. Chiama il metodo di salvataggio per salvare il file.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Esempio di codice in Java per eliminare i commenti dal file ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovere e aggiungere la risposta al commento ODT" %}}

1. Aggiungi riferimento alla libreria al progetto Java
1. Carica il documento tramite l'oggetto classe Document
1. Ottieni commenti utilizzando getChild
1. Utilizza [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) per rimuovere la risposta specificata a questo commento
1. Utilizza [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) per aggiungere qualsiasi risposta a questo commento
1. Chiama il metodo di salvataggio per salvare il file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aggiungi commenti tramite Java" %}}

1. Aggiungi riferimento alla libreria al progetto Java
1. Crea un oggetto di classe Documento
1. Usa [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) per creare il commento
1. Utilizza getParagraphs().add e getFirstParagraph().getRuns().add
1. Chiama il metodo di salvataggio per salvare il file with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice Java per rimuovere e aggiungere la risposta al commento dal file ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Codice Java: aggiunta di commenti" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Sviluppare l'applicazione di annotazione dei documenti ODT tramite Java</h2>

Hai bisogno di sviluppare un'app o un'utilità di annotazione ODT per fornire feedback, dare suggerimenti o collaborare con altri sul documento?Con [Aspose.Words for Java](https://products.aspose.com/words/java/), un'API figlia di [Aspose.Total for Java](https://products.aspose.com/total/java/), qualsiasi sviluppatore Java può integrare il codice API di cui sopra all'interno della propria applicazione di annotazione dei documenti.La potente libreria Java consente di programmare qualsiasi soluzione di annotazione di documenti. Inoltre può supportare molti formati popolari incluso il formato ODT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Libreria Java per annotare file ODT" %}}
Esistono opzioni alternative per installare "[Aspose.Words for Java](https://products.aspose.com/words/java/)" o "[Aspose.Total for Java](https://products.aspose.com/total/java/)" sul tuo sistema.Il nostro pacchetto Java è progettato per essere multipiattaforma, compatibile con le implementazioni JVM su vari sistemi operativi come Microsoft Windows, Linux, macOS, Android e iOS. Scegline uno che soddisfi le tue esigenze e segui le istruzioni passo passo:<br />

- Installa [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)
- O da [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)
- Passo dopo passo [Istruzioni](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

- Java SE 7 o versioni Java recenti
- Pacchetto separato per Java SE 6 nel caso in cui tu abbia questo JRE obsoleto.

<br />
Per i dettagli su JogAmp JOGL, motore di carattere Harfbuzz e Java Advanced Imaging JAI, fare riferimento a [Documentazione del prodotto](https://docs.aspose.com/words/java/system-requirements/#optional-dependencies).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Domande frequenti" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Domande frequenti</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Posso utilizzare il codice Java sopra nella mia applicazione?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sì, puoi scaricare questo codice e utilizzarlo allo scopo di sviluppare un'applicazione di annotazione di documenti basata su Java.Questo codice può rappresentare una risorsa preziosa per migliorare la funzionalità e le capacità dei tuoi progetti nel campo dell'elaborazione e della manipolazione dei documenti backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Questa app per l'annotazione di documenti online funziona solo su Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Hai la flessibilità di avviare l'annotazione del documento per la rimozione dei commenti su qualsiasi dispositivo, indipendentemente dal sistema operativo su cui viene eseguito, sia esso Windows, Linux, Mac OS o Android.Tutto ciò che serve è un browser web moderno e una connessione Internet attiva.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro utilizzare l'app online per annotare il documento ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! I file di output generati tramite il nostro servizio verranno rimossi in modo sicuro e automatico dai nostri server entro un periodo di 24 ore.Di conseguenza, i collegamenti di visualizzazione associati a questi file cesseranno di essere funzionali dopo tale periodo.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser dovrebbe utilizzare l'app?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web moderno come Google Chrome, Firefox, Opera o Safari per l'annotazione di documenti ODT online.Tuttavia, se stai sviluppando un'applicazione desktop, ti consigliamo di utilizzare l'API di elaborazione dei documenti Aspose.Total per una gestione efficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}