---
title: Převést PPS na TXT přes C# .NET nebo pomocí bezplatného online převodníku
description: Převádějte dokumenty pps aplikace PowerPoint na soubory dokumentů Word pomocí C#. Převeďte více souborů v rámci ASP.NET nebo jiných aplikací .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést PPS na TXT pomocí C# nebo online" h2="Vytvářejte aplikace Microsoft PowerPoint PPS Presentation do aplikací pro převod dokumentů Word TXT na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Jak převést PPS na TXT pomocí C#" %}}

Abychom zautomatizovali proces jakékoli prezentace pps v PowerPointu na dávkovou konverzi souborů dokumentů aplikace Word, použijeme [Aspose.Slides for .NET](https://products.aspose.com/slides/net) a [Aspose.Words pro .NET](https://products.aspose.com/words/net) API. První z nich je rozhraní API pro manipulaci s prezentacemi aplikace PowerPoint, které umožňuje vytvářet nebo upravovat snímky aplikace Microsoft PowerPoint. Zatímco druhý je rozhraním pro zpracování textu pro zpracování nebo manipulaci s dokumenty Microsoft Word. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net). Můžete přímo [stáhnout](https://releases.aspose.com/) z Nuget nebo můžete použít následující příkazy z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod PPS na TXT přes C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Přidejte odkaz na Aspose.Slides pro .NET a Aspose.Words pro .NET
1. Načtěte prezentaci PowerPoint PPS pomocí třídy [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Uložte dokument do [MemoryStream](https://txts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Objekt
1. Vytvořte [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) a inicializujte jej pomocí objektu MemoryStream
1. Uložte dokument pomocí [Aspose.Words.Document.Save("output.txt", SaveFormat.Txt)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Slides pro .NET a Aspose.Words pro .NET DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tato ukázka kódu ukazuje, jak převést PPS na TXT pomocí C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPS file
Aspose.Slides.Presentation pps = new Aspose.Slides.Presentation("source.pps");

var stream = new MemoryStream();

pps.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var txt = new Aspose.Words.Document(stream);
      
// Save the Word TXT document
txt.Save("output.txt", Aspose.Words.SaveFormat.Txt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online převodník PPS na TXT</h3>

<iframe title="Online nástroj txt až pps" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=txt&from=pps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod PPS na TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPS file." >}}

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
                          <span itemprop="name"><b>Jak mohu převést PPS na TXT Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikace pro převod PPS je integrována výše. Chcete-li aplikaci používat, můžete přidat svůj soubor PPS buď přetažením do určené oblasti, nebo kliknutím do oblasti importovat soubor. Jakmile je soubor přidán, klikněte na tlačítko Převést pro zahájení procesu převodu. Po dokončení převodu PPS na TXT si můžete stáhnout nově převedený soubor jediným kliknutím a bude k dispozici ve formátu TXT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod PPS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">tento online konvertor je rychlý, ale rychlost převodu PPS na TXT závisí hlavně na velikosti převáděného souboru PPS. Menší soubory PPS lze vykreslit do formátu TXT během několika sekund. Navíc, pokud jste integrovali převodní kód PPS na TXT do aplikace .NET, bude rychlost převodu záviset na tom, jak dobře jste optimalizovali aplikaci pro proces převodu.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět PPS na TXT pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Jakmile je proces převodu PPS na TXT dokončen, odkaz ke stažení převedeného souboru TXT bude okamžitě k dispozici. Všechny nahrané soubory, včetně souborů PPS, jsou po 24 hodinách vymazány ze systému a odkazy ke stažení po uplynutí této doby přestanou fungovat. Online konvertor zajišťuje bezpečnost a soukromí vašich souborů a integrovaná aplikace je k dispozici zdarma pro účely testování. To umožňuje uživatelům zkontrolovat výsledek před integrací kódu do svých projektů.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu PPS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">K online převodu souborů PPS na TXT můžete použít jakýkoli současný webový prohlížeč, jako je Google Chrome, Firefox, Opera nebo Safari. Pokud však vytváříte desktopovou aplikaci, doporučuje se Aspose.Total PPS Conversion API pro hladký a bezproblémový proces převodu.</span>
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