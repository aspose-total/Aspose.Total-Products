---
title: Converti TXT in PPS tramite C# .NET o con il convertitore online gratuito
description: Converti documenti Word in file pps PowerPoint con C#. Converti più file all'interno di ASP.NET o altre applicazioni .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti TXT in PPS usando C# o in linea" h2="Crea app di conversione da Microsoft Word TXT a PowerPoint PPS su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Come convertire TXT in PPS usando C#" %}}

Al fine di automatizzare il processo per qualsiasi file di Word txt nella conversione batch di presentazioni PowerPoint pps, utilizzeremo [Aspose.Words for .NET](https://products.aspose.com/words/net) e [Aspose.Slides per .NET](https://products.aspose.com/slides/net) API. La prima è un'API di elaborazione testi per l'elaborazione o la manipolazione di documenti Microsoft Word. Considerando che quest'ultima è un'API di manipolazione della presentazione che ti consente di creare o modificare diapositive di Microsoft PowerPoint. Entrambe le API fanno parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net). Puoi [scaricare](https://releases.aspose.com/) direttamente da Nuget o utilizzare i seguenti comandi dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire TXT in PPS tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aggiungere il riferimento di Aspose.Total per .NET
1. Caricare il file TXT utilizzando la classe [Aspose.Words.Document](https://apiference.aspose.com/words/net/aspose.words/document)
1. Salva il documento TXT in HTML
1. Crea un oggetto [Aspose.Slides.Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
1. Importa contenuto HTML nella cornice di testo di qualsiasi forma di diapositiva all'interno della presentazione
1. Salvare il documento utilizzando [Aspose.Slides.Presentation.Save("output.pps", SaveFormat.Pps)](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Words per .NET &amp; Aspose.Slides per DLL .NET o Aspose.Total per DLL .NET a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo esempio di codice mostra come convertire un TXT in PPS usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPS.

using (Presentation pps = new Presentation()){

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

	// Save the PPS Presentation
	pps.Save("filepath\\pres.pps", Aspose.Slides.Export.SaveFormat.Pps);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertitore online da TXT a PPS</h3>

<iframe title="Strumento di conversione gratuito da txt a pps" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire TXT in PPS" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPS file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos TXT a PPS mediante programación: casos de uso" %}}
Converting file testo (.TXT) in presentazioni di PowerPoint (.PPS) è essenziale per rivelare appieno le capacità di progettazione della tua presentazione. Tuttavia, quando si lavora con dati testuali, i file di testo non strutturati diventano necessari per lo storage e l'analisi dei dati.

La conversione dei file .TXT in formati .PPS è necessaria per rivelare appieno le capacità di visualizzazione e analisi della presentazione. Questa conversione consente a te:

**Casi d'uso:**

*   **Gestione del contenuto delle presentazioni**: Convertire i file .TXT per creare presentazioni affascinanti, gestire il contenuto in modo efficace e semplificare il processo di progettazione.
*   **Rapporti dati e dashboard interattivi**: Usare i file .PPS per visualizzare gli insight dati-driven, creare dashboard interattivi e facilitare decisioni più informate presso i soggetti coinvolti.
*   **Collaborazione e condivisione di contenuti**: Convertire i file .TXT per collaborare con i membri del team, condividere il contenuto in modo efficiente e garantire una comunicazione senza ostacoli tra le squadre.
*   **Consistenza del marchio e guide dello stile**: Usare i file .PPS per mantenere la consistenza del marchio, stabilire guide dello stile e migliorare l'aspetto visivo complessivo delle presentazioni.
*   **Accessibilità e inclusione**: Convertire i file .TXT per creare presentazioni accessibili, dare priorità al design inclusivo e soddisfare le esigenze di un pubblico diversificato.
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
                          <span itemprop="name"><b>Come posso convertire TXT in PPS online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'app online per la conversione TXT è integrata sopra. Per utilizzare questa app, puoi aggiungere il tuo file TXT trascinandolo nell'area bianca designata o facendo clic all'interno dell'area per importare il documento. Successivamente, premi il pulsante Converti per avviare il processo di conversione. Al termine della conversione da TXT a PPS, puoi scaricare il file appena convertito con un solo clic e sarà disponibile sotto forma di file PPS.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo ci vuole per convertire TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Questo convertitore online funziona rapidamente ma dipende principalmente dalle dimensioni del file TXT convertito. Per i piccoli file TXT, la conversione in PPS può essere completata in pochi secondi. Tuttavia, se hai integrato il codice di conversione all'interno di un'applicazione .NET, la velocità di conversione dipenderà dall'ottimizzazione dell'applicazione per il processo di conversione.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro convertire TXT in PPS utilizzando il convertitore Aspose.Total gratuito?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! Una volta completata la conversione da TXT a PPS, il collegamento per il download del file PPS appena convertito sarà immediatamente disponibile. Garantisce inoltre la sicurezza del processo di conversione, poiché tutti i file caricati, inclusi i file TXT, sono completamente sicuri e verranno eliminati dal sistema dopo 24 ore. Inoltre, i link per il download smetteranno di funzionare dopo questo periodo, garantendo la privacy e la protezione dei tuoi file. L'app integrata è gratuita e progettata per scopi di test in modo che gli utenti possano valutare i risultati prima di integrare il codice nei loro progetti.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser devo usare per convertire TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web moderno, come Google Chrome, Firefox, Opera o Safari, per la conversione online da TXT a PPS. Tuttavia, se stai sviluppando un'applicazione desktop, l'API Aspose.Total TXT Conversion è consigliata per un'elaborazione fluida ed efficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}