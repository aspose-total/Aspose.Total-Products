---
title: Rimuovi l'annotazione DOC online o gestisci le annotazioni utilizzando le app mobili Android
description: elimina gratuitamente i commenti dal file DOC tramite l'app online.Codice API Android per gestire i commenti dei file DOC.

family: total
platformtag: Android
feature: Annotate
informat: DOC
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Cancella commenti dal documento DOC online o gestisci tramite app Android" h2="Sviluppa una potente applicazione di utilità per l'annotazione di documenti DOC basata su Android.Codice elencato per la gestione dei commenti del file DOC." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovi le annotazioni DOC online" %}}

1. Importa il file DOC per eliminare i commenti caricandolo
1. Fallo facendo clic all'interno dell'area di rilascio tramite trascinamento dell'app di annotazione
1. A seconda della dimensione del file DOC e della velocità di Internet, attendere alcuni secondi
1. Fare clic sul pulsante "Rimuovi" per cancellare i commenti
1. Scarica il file immediatamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rimuovi i commenti del documento DOC tramite l'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Carica il documento tramite l'oggetto classe Document
1. Ottieni tutti i commenti da tutti i nodi utilizzando [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) e NodeType.COMMENT
1. Richiamare il metodo [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) per eliminare tutti i commenti
1. Chiama il metodo di salvataggio per salvare il file.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: elimina commenti dal file DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovere e aggiungere la risposta al commento DOC" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Carica il documento tramite l'oggetto classe Document
1. Ottieni commenti utilizzando getChild
1. Utilizza [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) per rimuovere la risposta specificata a questo commento
1. Utilizza [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) per aggiungere qualsiasi risposta a questo commento
1. Chiama il metodo di salvataggio per salvare il file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aggiungi commenti tramite l'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Crea un oggetto di classe Documento
1. Utilizzare [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) per creare il commento
1. Utilizza getParagraphs().add e getFirstParagraph().getRuns().add
1. Chiama il metodo di salvataggio per salvare il file with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: rimuovi e aggiungi risposta al commento dal file DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Codice: aggiunta di commenti" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Sviluppa l'app Android per l'annotazione dei documenti DOC</h2>

Hai bisogno di sviluppare un'app o un'utilità mobile per annotazioni DOC per fornire feedback, dare suggerimenti o collaborare con altri sul documento?Con [Aspose.Words for Android via Java](https://products.aspose.com/words/it/android-java/), un'API figlia di [Aspose.Total for Android via Java](https://products.aspose.com/total/it/android-java/), qualsiasi sviluppatore Android può integrare il codice API di cui sopra all'interno della propria applicazione di annotazione dei documenti.La potente libreria Android consente di programmare qualsiasi soluzione di annotazione di documenti.Inoltre può supportare molti formati popolari incluso il formato DOC.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Libreria Android per annotare file DOC" %}}

- Ospitiamo i nostri pacchetti Java in [Repository Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java è un file JAR comune contenente codice byte.
- Segui [istruzioni passo passo](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) su come installare Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

- Sono supportati Java SE 7 e le versioni Java più recenti.
- Pacchetto separato per Java SE 6 nel caso in cui si sia obbligati a utilizzare JRE obsoleto.
- Il pacchetto Java è multipiattaforma e funziona su tutti i sistemi operativi con implementazione JVM.
- I sistemi operativi includono Microsoft Windows, Linux, macOS, Android e iOS.

<br />
Per maggiori dettagli sulle dipendenze dei pacchetti opzionali, come JogAmp JOGL, motore dei caratteri Harfbuzz, Java Advanced Imaging JAI, fare riferimento a [Documentazione del prodotto](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}