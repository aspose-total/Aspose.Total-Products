---
title: Rimuovi l'annotazione POTM online o gestisci le annotazioni utilizzando le app mobili Android
description: elimina gratuitamente i commenti dal file POTM tramite l'app online.Codice API Android per gestire i commenti dei file POTM.

family: total
platformtag: Android
feature: Annotate
informat: POTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Cancella commenti dalla presentazione POTM online o gestisci tramite app Android" h2="Sviluppa una potente applicazione di utilità per l'annotazione delle presentazioni POTM basata su Android.Codice elencato per la gestione dei commenti del file POTM." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovi le annotazioni POTM online" %}}

1. Importa il file POTM per eliminare i commenti caricandolo
1. Fallo facendo clic all'interno dell'area di rilascio tramite trascinamento dell'app di annotazione
1. A seconda della dimensione del file POTM e della velocità di Internet, attendere alcuni secondi
1. Fare clic sul pulsante "Rimuovi" per cancellare i commenti
1. Scarica il file immediatamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rimuovi i commenti di presentazione POTM tramite l'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Carica POTM tramite l'oggetto classe Presentazione
1. Scorri ogni autore tramite la raccolta Presentation.getCommentAuthors()
1. Richiamare il metodo clear() per eliminare il relativo commento
1. Infine chiama getCommentAuthors().clear() per rimuovere tutti gli autori
1. Chiama il metodo di salvataggio per salvare il file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: elimina commenti e autori dalla presentazione POTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Aggiungi commenti alla presentazione POTM tramite l'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Carica POTM tramite l'oggetto classe Presentazione
1. Richiama Presentation.getCommentAuthors().addAuthor(String, String) per aggiungere gli autori
1. Utilizzare ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) per l'aggiunta di commenti
1. Chiama il metodo di salvataggio per salvare il file with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: aggiunta di commenti" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Sviluppa l'app Android per l'annotazione dei documenti POTM</h2>

Hai bisogno di sviluppare un'app o un'utilità mobile per annotazioni POTM per fornire feedback, dare suggerimenti o collaborare con altri sul documento?Con [Aspose.Slides for Android via Java](https://products.aspose.com/slides/it/android-java/), un'API figlia di [Aspose.Total for Android via Java](https://products.aspose.com/total/it/android-java/), qualsiasi sviluppatore Android può integrare il codice API di cui sopra all'interno della propria applicazione di annotazione dei documenti.La potente libreria Android consente di programmare qualsiasi soluzione di annotazione di documenti.Inoltre può supportare molti formati popolari incluso il formato POTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Libreria Android per annotare file POTM" %}}

- Ospitiamo i nostri pacchetti Java in [Repository Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java è un file JAR comune contenente codice byte.
- Segui [istruzioni passo passo](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) su come installare Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

- J2SE 6.0 (Java 1.6) e versioni successive
- Il pacchetto Java è multipiattaforma e funziona su tutti i sistemi operativi con implementazione JVM.

<br />
Per maggiori dettagli fare riferimento a [Documentazione del prodotto](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}