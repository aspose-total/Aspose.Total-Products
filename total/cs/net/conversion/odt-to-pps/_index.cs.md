---
title: Převést ODT na PPS přes C# .NET nebo pomocí bezplatného online převodníku
description: Převeďte dokumenty Word odt na soubory PowerPoint pps pomocí C#. Převeďte více souborů v rámci ASP.NET nebo jiných aplikací .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést ODT na PPS pomocí C# nebo online" h2="Vytvářejte aplikace pro převod PPS z Microsoft Word ODT na PowerPoint na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Jak převést ODT na PPS pomocí C#" %}}

Abychom zautomatizovali proces pro jakékoli soubory dokumentů Word na dávkovou konverzi prezentací pps v PowerPointu, použijeme [Aspose.Words for .NET](https://products.aspose.com/words/net) a [Aspose.Slides pro .NET](https://products.aspose.com/slides/net) API. První z nich je rozhraní API pro zpracování textu pro zpracování nebo manipulaci s dokumenty Microsoft Word. Zatímco druhý je rozhraní API pro manipulaci s prezentacemi, které umožňuje vytvářet nebo upravovat snímky aplikace Microsoft PowerPoint. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net). Můžete přímo [stáhnout](https://releases.aspose.com/) z Nuget nebo můžete použít následující příkazy z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu ODT na PPS přes C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Přidejte odkaz na Aspose.Total pro .NET
1. Načtěte soubor ODT pomocí třídy [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Uložte dokument ODT do HTML
1. Vytvořte objekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importujte obsah HTML v textovém rámečku libovolného tvaru snímku uvnitř prezentace
1. Uložte dokument pomocí [Aspose.Slides.Presentation.Save("output.pps", SaveFormat.Pps)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Words pro .NET &amp; Aspose.Slides pro .NET DLL nebo Aspose.Total pro .NET DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tato ukázka kódu ukazuje, jak převést ODT na PPS pomocí C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPS.

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

<h3>Online převodník ODT na PPS</h3>

<iframe title="Online nástroj pps až odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod ODT na PPS" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPS file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru ODT do PPS: Případy použití" %}}
Soubory ODT jsou využívány pro ukládání prostého textu, což je ideální pro tvorbu dokumentů s matematickými rovnáním a formulami. Nicméně, když pracujeme s prezentacemi jako PPS (PowerPoint Slides), stávají se nezbytnými pro tvorbu angažujících a dynamických vizuálních obsahů.

Konverze souborů ODT na formáty PPS je nezbytná, aby jste mohli využít plnou kapacitu svých schopností při tvorbě prezentací. Tato konverze vám umožňuje:

**Užití:**

*   **Prezentace matematických rovnání**: Konvertujte soubory ODT na formáty PPS pro prezentaci komplexních matematických rovnání, formul a tabuloků v jednoduchém a stručném způsobu.  
*   **Výpočty z formulí**: Používáte PPS k vizualizaci výpočtů, derivace výsledků a zobrazení řešení matematických problémů.  
*   **Generace obrázků z textu**: Konvertujte soubory ODT na tvorbu obrazců z textového obsahu, vytvářející jedinečné vizuální znacení komplexní informace.  
*   **Animované prezentace rovnání**: Používáte PPS k vytvoření animovaných prezentací, které ilustrují matematické pojmy, rovnání nebo formuly v zábavném způsobu.  
*   **Interaktivní diagramy a ilustrace**: Konvertujte soubory ODT na tvorbu interaktivních diagramů, ilustrací a infografik, které pomáhají vizualizovat komplexní údaje nebo ideje.
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
              <h2>Často kladené otázky</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak mohu převést ODT na PPS Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikace pro převod ODT je integrována výše. Chcete-li použít tuto aplikaci, můžete přidat svůj soubor ODT přetažením do určené bílé oblasti nebo kliknutím do oblasti importovat dokument. Poté stisknutím tlačítka Převést spusťte proces převodu. Po dokončení převodu ODT na PPS si můžete stáhnout nově převedený soubor jediným kliknutím a bude vám k dispozici ve formě souboru PPS.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tento online převodník funguje rychle, ale primárně závisí na velikosti převáděného souboru ODT. U malých souborů ODT lze převod na PPS dokončit během několika sekund. Pokud jste však převodní kód integrovali do aplikace .NET, bude rychlost převodu záviset na tom, jak dobře byla vaše aplikace optimalizována pro proces převodu.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět ODT na PPS pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Po dokončení převodu ODT na PPS bude okamžitě k dispozici odkaz ke stažení nově převedeného souboru PPS. Zajišťuje také bezpečnost procesu převodu, protože všechny nahrané soubory, včetně souborů ODT, jsou zcela zabezpečené a po 24 hodinách budou ze systému odstraněny. Kromě toho odkazy ke stažení po uplynutí této doby přestanou fungovat, což zajistí soukromí a ochranu vašich souborů. Integrovaná aplikace je zdarma k použití a je navržena pro testovací účely, takže uživatelé mohou vyhodnotit výsledky před integrací kódu do svých projektů.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online převod ODT na PPS můžete použít jakýkoli moderní webový prohlížeč, jako je Google Chrome, Firefox, Opera nebo Safari. Pokud však vyvíjíte desktopovou aplikaci, doporučuje se Aspose.Total ODT Conversion API pro hladké a efektivní zpracování.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}