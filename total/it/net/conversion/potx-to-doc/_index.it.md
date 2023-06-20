---
title: Converti POTX in DOC tramite C# .NET o con il convertitore online gratuito
description: Converti documenti PowerPoint in file doc di Word con C#. Converti più file all'interno di ASP.NET o altre applicazioni .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti POTX in DOC usando C# o in linea" h2="Crea app di conversione di documenti Microsoft PowerPoint POTX Presentation in Word DOC su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Come convertire POTX in DOC usando C#" %}}

Per automatizzare il processo di conversione batch di qualsiasi presentazione PowerPoint potx in file doc di Word, utilizzeremo [Aspose.Slides for .NET](https://products.aspose.com/slides/net) e [Aspose.Words per .NET](https://products.aspose.com/words/net) API. Il primo è un'API di manipolazione della presentazione di PowerPoint che consente di creare o modificare diapositive di Microsoft PowerPoint. Considerando che quest'ultima è un'API di elaborazione testi per l'elaborazione o la manipolazione di documenti Microsoft Word. Entrambe le API fanno parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net). Puoi [scaricare](https://releases.aspose.com/) direttamente da Nuget o utilizzare i seguenti comandi dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire POTX in DOC tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aggiungi riferimento ad Aspose.Slides per .NET e Aspose.Words per .NET
1. Caricare la presentazione PowerPoint POTX utilizzando la classe [Aspose.Slides.Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
1. Salva il documento in [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Oggetto
1. Crea [Aspose.Words.Document](https://apiference.aspose.com/words/net/aspose.words/document) e inizializzalo con l'oggetto MemoryStream
1. Salvare il documento utilizzando [Aspose.Words.Document.Save("output.doc", SaveFormat.Doc)](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Slides per .NET e Aspose.Words per .NET DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo esempio di codice mostra come convertire un POTX in DOC usando C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTX file
Aspose.Slides.Presentation potx = new Aspose.Slides.Presentation("source.potx");

var stream = new MemoryStream();

potx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var doc = new Aspose.Words.Document(stream);
      
// Save the Word DOC document
doc.Save("output.doc", Aspose.Words.SaveFormat.Doc);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertitore online da POTX a DOC</h3>

<iframe title="Strumento di conversione gratuito da potx a doc" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire POTX in DOC" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Domande frequenti</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Come posso convertire POTX in DOC online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'app online per la conversione POTX è integrata sopra. Per utilizzare l'app, puoi aggiungere il tuo file POTX trascinandolo nell'area designata o facendo clic all'interno dell'area per importare il file. Una volta aggiunto il file, fai clic sul pulsante Converti per avviare il processo di conversione. Al termine della conversione da POTX a DOC, puoi scaricare il file appena convertito con un solo clic e sarà disponibile in formato DOC.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo ci vuole per convertire POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">questo convertitore online è veloce, ma la velocità della conversione da POTX a DOC dipende principalmente dalla dimensione del file POTX da convertire. I file POTX più piccoli possono essere trasformati in formato DOC in pochi secondi. Inoltre, se hai integrato il codice di conversione da POTX a DOC all'interno di un'applicazione .NET, la velocità di conversione dipenderà da quanto bene hai ottimizzato la tua applicazione per il processo di conversione.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro convertire POTX in DOC utilizzando il convertitore Aspose.Total gratuito?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! Una volta completato il processo di conversione da POTX a DOC, il collegamento per il download del file DOC convertito sarà immediatamente disponibile. Tutti i file caricati, inclusi i file POTX, vengono eliminati dal sistema dopo 24 ore e i collegamenti per il download cessano di funzionare dopo questo periodo di tempo. Il convertitore online garantisce la sicurezza e la privacy dei tuoi file e l'app integrata è disponibile gratuitamente a scopo di test. Ciò consente agli utenti di verificare il risultato prima di integrare il codice nei loro progetti.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser devo usare per convertire POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web contemporaneo come Google Chrome, Firefox, Opera o Safari per convertire i file POTX in DOC online. Tuttavia, se stai creando un'applicazione desktop, l'API di conversione Aspose.Total POTX è consigliata per un processo di conversione fluido e senza interruzioni.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}