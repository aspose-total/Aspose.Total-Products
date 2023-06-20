---
title: Konvertera WORDML till PPTX via C# .NET eller med gratis Online Converter
description: Konvertera Word wordml-dokument till PowerPoint pptx-filer med C#. Konvertera flera filer inom ASP.NET eller andra .NET-program.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera WORDML till PPTX med C# eller online" h2="Bygg Microsoft Word WORDML till PowerPoint PPTX-konverteringsappar på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Hur man konverterar WORDML till PPTX med C#" %}}

För att automatisera processen för alla Word-dokumentfiler till PowerPoint pptx-presentation batchkonvertering kommer vi att använda [Aspose.Words for .NET](https://products.aspose.com/words/net) och [Aspose.Slides för .NET](https://products.aspose.com/slides/net) API:er. Det förra är ett ordbehandlings-API för bearbetning eller manipulering av Microsoft Word-dokument. Medan det senare är ett presentationsmanipulerings-API som låter dig skapa eller ändra Microsoft PowerPoint-bilder. Båda API:erna är en del av paketet [Aspose.Total for .NET](https://products.aspose.com/total/net). Du kan [ladda ner](https://releases.aspose.com) direkt från Nuget eller kan använda följande kommandon från pakethanterarens konsol.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera WORDML till PPTX via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Lägg till referens för Aspose.Total för .NET
1. Ladda WORDML-fil med klassen [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Spara WORDML-dokumentet i HTML
1. Skapa [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) objekt
1. Importera HTML-innehåll i textramen i valfri bildform i presentationen
1. Spara dokumentet med [Aspose.Slides.Presentation.Save("output.pptx", SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
- Utvecklingsmiljö som Microsoft Visual Studio.
- Aspose.Words för .NET &amp; Aspose.Slides för .NET DLL eller Aspose.Total för .NET DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Detta kodexempel visar hur man konverterar en WORDML till PPTX med C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word WORDML file
Aspose.Words.Document wordml = new Aspose.Words.Document("sourceWordFile.wordml");

// Save WORDML file to HTML 
wordml.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages WORDML documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

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

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Online-omvandlare för WORDML till PPTX</h3>

<iframe title="wordml till pptx Conversion Online Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=wordml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera WORDML till PPTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Vanliga frågor</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur kan jag konvertera WORDML till PPTX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online-app för WORDML-konvertering är integrerad ovan. För att använda den här appen kan du lägga till din WORDML-fil genom att dra och släppa den i det angivna vita området eller genom att klicka inuti området för att importera dokumentet. Tryck sedan på knappen Konvertera för att starta konverteringsprocessen. När WORDML till PPTX-konverteringen är klar kan du ladda ner din nyligen konverterade fil med bara ett klick, och den kommer att vara tillgänglig för dig i form av en PPTX-fil.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur lång tid tar det att konvertera WORDML?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Denna onlinekonverterare fungerar snabbt men är främst beroende av storleken på WORDML-filen som konverteras. För små WORDML-filer kan konverteringen till PPTX slutföras på några sekunder. Men om du har integrerat konverteringskoden i en .NET-applikation kommer konverteringshastigheten att bero på hur väl din applikation har optimerats för konverteringsprocessen.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Är det säkert att konvertera WORDML till PPTX med gratis Aspose.Total-omvandlare?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Självklart! När WORDML till PPTX-konverteringen är klar kommer nedladdningslänken för den nyligen konverterade PPTX-filen att vara tillgänglig omedelbart. Det garanterar också säkerheten för konverteringsprocessen, eftersom alla uppladdade filer, inklusive WORDML-filer, är helt säkra och kommer att raderas från systemet efter 24 timmar. Dessutom kommer nedladdningslänkarna att sluta fungera efter denna period, vilket säkerställer integriteten och skyddet för dina filer. Den integrerade appen är gratis att använda och designad för testsyften så att användare kan utvärdera resultaten innan de integrerar koden i sina projekt.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Vilken webbläsare ska jag använda för att konvertera WORDML?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Du kan använda vilken modern webbläsare som helst, som Google Chrome, Firefox, Opera eller Safari, för WORDML till PPTX-konvertering online. Men om du utvecklar ett skrivbordsprogram rekommenderas Aspose.Total WORDML Conversion API för smidig och effektiv bearbetning.</span>
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