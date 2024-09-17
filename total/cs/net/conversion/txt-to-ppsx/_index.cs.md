---
title: Převést TXT na PPSX přes C# .NET nebo pomocí bezplatného online převodníku
description: Převeďte dokumenty Word txt na soubory PowerPoint ppsx pomocí C#. Převeďte více souborů v rámci ASP.NET nebo jiných aplikací .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést TXT na PPSX pomocí C# nebo online" h2="Vytvářejte aplikace pro převod PPSX z Microsoft Word TXT na PowerPoint na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Jak převést TXT na PPSX pomocí C#" %}}

Abychom zautomatizovali proces pro jakékoli soubory dokumentů Word na dávkovou konverzi prezentací ppsx v PowerPointu, použijeme [Aspose.Words for .NET](https://products.aspose.com/words/net) a [Aspose.Slides pro .NET](https://products.aspose.com/slides/net) API. První z nich je rozhraní API pro zpracování textu pro zpracování nebo manipulaci s dokumenty Microsoft Word. Zatímco druhý je rozhraní API pro manipulaci s prezentacemi, které umožňuje vytvářet nebo upravovat snímky aplikace Microsoft PowerPoint. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net). Můžete přímo [stáhnout](https://releases.aspose.com/) z Nuget nebo můžete použít následující příkazy z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu TXT na PPSX přes C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Přidejte odkaz na Aspose.Total pro .NET
1. Načtěte soubor TXT pomocí třídy [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Uložte dokument TXT do HTML
1. Vytvořte objekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importujte obsah HTML v textovém rámečku libovolného tvaru snímku uvnitř prezentace
1. Uložte dokument pomocí [Aspose.Slides.Presentation.Save("output.ppsx", SaveFormat.Ppsx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Words pro .NET &amp; Aspose.Slides pro .NET DLL nebo Aspose.Total pro .NET DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tato ukázka kódu ukazuje, jak převést TXT na PPSX pomocí C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSX.

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

<h3>Online převodník TXT na PPSX</h3>

<iframe title="Online nástroj ppsx až txt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod TXT na PPSX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSX file." >}}

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
              <h2>Často kladené otázky</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak mohu převést TXT na PPSX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikace pro převod TXT je integrována výše. Chcete-li použít tuto aplikaci, můžete přidat svůj soubor TXT přetažením do určené bílé oblasti nebo kliknutím do oblasti importovat dokument. Poté stisknutím tlačítka Převést spusťte proces převodu. Po dokončení převodu TXT na PPSX si můžete stáhnout nově převedený soubor jediným kliknutím a bude vám k dispozici ve formě souboru PPSX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tento online převodník funguje rychle, ale primárně závisí na velikosti převáděného souboru TXT. U malých souborů TXT lze převod na PPSX dokončit během několika sekund. Pokud jste však převodní kód integrovali do aplikace .NET, bude rychlost převodu záviset na tom, jak dobře byla vaše aplikace optimalizována pro proces převodu.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět TXT na PPSX pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Po dokončení převodu TXT na PPSX bude okamžitě k dispozici odkaz ke stažení nově převedeného souboru PPSX. Zajišťuje také bezpečnost procesu převodu, protože všechny nahrané soubory, včetně souborů TXT, jsou zcela zabezpečené a po 24 hodinách budou ze systému odstraněny. Kromě toho odkazy ke stažení po uplynutí této doby přestanou fungovat, což zajistí soukromí a ochranu vašich souborů. Integrovaná aplikace je zdarma k použití a je navržena pro testovací účely, takže uživatelé mohou vyhodnotit výsledky před integrací kódu do svých projektů.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online převod TXT na PPSX můžete použít jakýkoli moderní webový prohlížeč, jako je Google Chrome, Firefox, Opera nebo Safari. Pokud však vyvíjíte desktopovou aplikaci, doporučuje se Aspose.Total TXT Conversion API pro hladké a efektivní zpracování.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}