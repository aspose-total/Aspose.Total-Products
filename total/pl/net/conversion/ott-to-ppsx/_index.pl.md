---
title: Konwertuj OTT na PPSX przez C# .NET lub za pomocą bezpłatnego konwertera online
description: Konwertuj dokumenty Word ott na pliki ppsx programu PowerPoint za pomocą C#. Konwertuj wiele plików w ASP.NET lub innych aplikacjach .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj OTT na PPSX za pomocą C# lub online" h2="Twórz aplikacje do konwersji Microsoft Word OTT na PowerPoint PPSX na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Jak przekonwertować OTT na PPSX za pomocą C#" %}}

Aby zautomatyzować proces konwersji dowolnych plików dokumentów programu Word do wsadowej konwersji prezentacji PowerPoint ppsx, użyjemy [Aspose.Words for .NET](https://products.aspose.com/words/net) i [Aspose.Slides dla .NET](https://products.aspose.com/slides/net) API. Ten pierwszy to interfejs API do przetwarzania tekstu do przetwarzania lub manipulowania dokumentami Microsoft Word. Natomiast ten ostatni to interfejs API do manipulacji prezentacją, który pozwala tworzyć lub modyfikować slajdy programu Microsoft PowerPoint. Oba interfejsy API są częścią pakietu [Aspose.Total for .NET](https://products.aspose.com/total/net). Możesz bezpośrednio [pobrać](https://releases.aspose.com) z Nuget lub użyć następujących poleceń z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować OTT na PPSX za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Dodaj odwołanie do Aspose.Total dla .NET
1. Załaduj plik OTT za pomocą klasy [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Zapisz dokument OTT w HTML
1. Utwórz obiekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importuj zawartość HTML do ramki tekstowej dowolnego kształtu slajdu w prezentacji
1. Zapisz dokument za pomocą [Aspose.Slides.Presentation.Save("output.ppsx", SaveFormat.Ppsx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z platformami .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
- Środowisko programistyczne, takie jak Microsoft Visual Studio.
- Aspose.Words dla .NET &amp; Aspose.Slides dla bibliotek DLL platformy .NET lub Aspose.Total dla bibliotek DLL platformy .NET, do których odwołuje się projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje, jak przekonwertować OTT na PPSX przy użyciu C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word OTT file
Aspose.Words.Document ott = new Aspose.Words.Document("sourceWordFile.ott");

// Save OTT file to HTML 
ott.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages OTT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSX.

using (Presentation ppsx = new Presentation()){

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

	// Save the PPSX Presentation
	ppsx.Save("filepath\\pres.ppsx", Aspose.Slides.Export.SaveFormat.Ppsx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Konwerter online dla OTT na PPSX</h3>

<iframe title="Narzędzie online do konwersji ppsx na ott" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsx&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do konwersji OTT na PPSX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSX file." >}}

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
              <h2>Często Zadawane Pytania</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak mogę przekonwertować OTT na PPSX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Aplikacja online do konwersji OTT jest zintegrowana powyżej. Aby korzystać z tej aplikacji, możesz dodać plik OTT, przeciągając go i upuszczając w wyznaczonym białym obszarze lub klikając wewnątrz obszaru, aby zaimportować dokument. Następnie naciśnij przycisk Konwertuj, aby rozpocząć proces konwersji. Po zakończeniu konwersji OTT do PPSX możesz jednym kliknięciem pobrać nowo przekonwertowany plik, który będzie dostępny w postaci pliku PPSX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak długo trwa konwersja OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ten konwerter online działa szybko, ale przede wszystkim zależy od rozmiaru konwertowanego pliku OTT. W przypadku małych plików OTT konwersję do formatu PPSX można przeprowadzić w ciągu kilku sekund. Jeśli jednak kod konwersji został zintegrowany z aplikacją .NET, szybkość konwersji będzie zależeć od tego, jak dobrze aplikacja została zoptymalizowana pod kątem procesu konwersji.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Czy konwersja OTT na PPSX za pomocą darmowego konwertera Aspose.Total jest bezpieczna?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Oczywiście! Po zakończeniu konwersji OTT na PPSX link do pobrania nowo przekonwertowanego pliku PPSX będzie natychmiast dostępny. Zapewnia również bezpieczeństwo procesu konwersji, ponieważ wszystkie przesyłane pliki, w tym pliki OTT, są całkowicie bezpieczne i zostaną usunięte z systemu po 24 godzinach. Ponadto łącza do pobierania przestaną działać po tym okresie, zapewniając prywatność i ochronę Twoich plików. Zintegrowana aplikacja jest bezpłatna i zaprojektowana do celów testowych, aby użytkownicy mogli ocenić wyniki przed zintegrowaniem kodu ze swoimi projektami.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jakiej przeglądarki powinienem użyć do konwersji OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Możesz użyć dowolnej nowoczesnej przeglądarki internetowej, takiej jak Google Chrome, Firefox, Opera lub Safari, do konwersji online OTT na PPSX. Jeśli jednak tworzysz aplikację komputerową, zalecany jest Aspose.Total OTT Conversion API do płynnego i wydajnego przetwarzania.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}