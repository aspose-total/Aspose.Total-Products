---
title: Converti OTT in ODP tramite C# .NET o con il convertitore online gratuito
description: Converti documenti Word in file odp PowerPoint con C#. Converti più file all'interno di ASP.NET o altre applicazioni .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti OTT in ODP usando C# o in linea" h2="Crea app di conversione da Microsoft Word OTT a PowerPoint ODP su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Come convertire OTT in ODP usando C#" %}}

Al fine di automatizzare il processo per qualsiasi file di Word ott nella conversione batch di presentazioni PowerPoint odp, utilizzeremo [Aspose.Words for .NET](https://products.aspose.com/words/net) e [Aspose.Slides per .NET](https://products.aspose.com/slides/net) API. La prima è un'API di elaborazione testi per l'elaborazione o la manipolazione di documenti Microsoft Word. Considerando che quest'ultima è un'API di manipolazione della presentazione che ti consente di creare o modificare diapositive di Microsoft PowerPoint. Entrambe le API fanno parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net). Puoi [scaricare](https://releases.aspose.com/) direttamente da Nuget o utilizzare i seguenti comandi dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire OTT in ODP tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aggiungere il riferimento di Aspose.Total per .NET
1. Caricare il file OTT utilizzando la classe [Aspose.Words.Document](https://apiference.aspose.com/words/net/aspose.words/document)
1. Salva il documento OTT in HTML
1. Crea un oggetto [Aspose.Slides.Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
1. Importa contenuto HTML nella cornice di testo di qualsiasi forma di diapositiva all'interno della presentazione
1. Salvare il documento utilizzando [Aspose.Slides.Presentation.Save("output.odp", SaveFormat.Odp)](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Words per .NET &amp; Aspose.Slides per DLL .NET o Aspose.Total per DLL .NET a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo esempio di codice mostra come convertire un OTT in ODP usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word OTT file
Aspose.Words.Document ott = new Aspose.Words.Document("sourceWordFile.ott");

// Save OTT file to HTML 
ott.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages OTT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to ODP.

using (Presentation odp = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the ODP Presentation
	odp.Save("filepath\\pres.odp", Aspose.Slides.Export.SaveFormat.Odp);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertitore online da OTT a ODP</h3>

<iframe title="Strumento di conversione gratuito da ott a odp" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=odp&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire OTT in ODP" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant ODP file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos OTT a ODP mediante programación: casos de uso" %}}
I'll translate the given text into Italian using Google's language code it.

OTF (Font di tipo aperto) sono utilizzati per archiviare informazioni grafiche vettoriali, rendendoli ideali per creare tipografia di alta qualità e loghi. Tuttavia, quando si lavora con immagini rasterizzate, formati come ODP diventano essenziali per la pubblicazione e la presentazione.

La conversione degli OTF in formati ODP è necessaria per sbloccare il pieno potenziale delle tue capacità di pubblicazione e presentazione. Questa conversione consente a te:

**Casi d'uso:**

*   **Presentazioni aziendali**: Converti i font OTF per creare presentazioni affascinanti, incorpora loghi aziendali e migliora l'apparenza visiva complessiva.
*   **Pubblicazione di documenti**: Usa ODP per pubblicare documenti di alta qualità, come rapporti, articoli e libri elettronici, con tipografia professionale e ben progettata.
*   **Branding e identità**: Converti gli OTF per creare un branding coerente su diverse piattaforme, comprese siti web, social media e materiali di marketing.
*   **Disegno grafico**: Usa ODP per disegnare grafici visivamente attiranti, come infografiche, diagrammi e illustrazioni, con controllo preciso delle fonte.
*   **Display digitali e schermi pubblici**: Converti i font OTF per creare segnalazione digitale impattante, display pubblici e kioschi interattivi con una tipografia chiara e leggibile.
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>Come posso convertire OTT in ODP online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'app online per la conversione OTT è integrata sopra. Per utilizzare questa app, puoi aggiungere il tuo file OTT trascinandolo nell'area bianca designata o facendo clic all'interno dell'area per importare il documento. Successivamente, premi il pulsante Converti per avviare il processo di conversione. Al termine della conversione da OTT a ODP, puoi scaricare il file appena convertito con un solo clic e sarà disponibile sotto forma di file ODP.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo ci vuole per convertire OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Questo convertitore online funziona rapidamente ma dipende principalmente dalle dimensioni del file OTT convertito. Per i piccoli file OTT, la conversione in ODP può essere completata in pochi secondi. Tuttavia, se hai integrato il codice di conversione all'interno di un'applicazione .NET, la velocità di conversione dipenderà dall'ottimizzazione dell'applicazione per il processo di conversione.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro convertire OTT in ODP utilizzando il convertitore Aspose.Total gratuito?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! Una volta completata la conversione da OTT a ODP, il collegamento per il download del file ODP appena convertito sarà immediatamente disponibile. Garantisce inoltre la sicurezza del processo di conversione, poiché tutti i file caricati, inclusi i file OTT, sono completamente sicuri e verranno eliminati dal sistema dopo 24 ore. Inoltre, i link per il download smetteranno di funzionare dopo questo periodo, garantendo la privacy e la protezione dei tuoi file. L'app integrata è gratuita e progettata per scopi di test in modo che gli utenti possano valutare i risultati prima di integrare il codice nei loro progetti.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser devo usare per convertire OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web moderno, come Google Chrome, Firefox, Opera o Safari, per la conversione online da OTT a ODP. Tuttavia, se stai sviluppando un'applicazione desktop, l'API Aspose.Total OTT Conversion è consigliata per un'elaborazione fluida ed efficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}