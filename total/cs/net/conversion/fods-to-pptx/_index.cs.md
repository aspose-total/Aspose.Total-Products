---
title: Převeďte FODS na PPTX pomocí .NET nebo pomocí bezplatného online převodníku
description: Převeďte FODS na PPTX na platformách .NET Framework, .NET Core, Mono nebo Xamarin nebo online. Před integrací kódu rychle otestujte bezplatný online převodník  FODS na PPTX.

family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Převést FODS na PPTX přes C# nebo online aplikace" h2="Export Excel<sup>&reg;</sup> FODS do PPTX na platformách .NET Framework, .NET Core, Mono nebo Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Převod FODS na PPTX na .NET" %}}
1. Otevřete soubor FODS pomocí třídy [Sešit](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Převeďte FODS na PDF a nastavte SaveFormat na Auto
3. Načtěte převedený soubor PDF pomocí třídy [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Uložte dokument do formátu PPTX pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) a nastavte Pptx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Kód pro převod FODS na PPTX" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník FODS na PPTX</h3>

<iframe title="Online nástroj pptx až fods" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=fods" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
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
                          <span itemprop="name"><b>Jak mohu převést FODS na PPTX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikace pro převod FODS je integrována výše. Chcete-li zahájit proces převodu, můžete buď přetáhnout soubor FODS, nebo kliknout do určené oblasti a importovat dokument. Dále klikněte na tlačítko "Převést" pro zahájení převodu FODS na PPTX. Po dokončení procesu si můžete snadno stáhnout převedený soubor jediným kliknutím a získat požadovaný výstup ve formátu PPTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod FODS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Rychlost tohoto online převodníku je vysoká, ale primárně závisí na velikosti souboru FODS. Pokud máte malý soubor FODS, lze jej převést na PPTX během několika sekund. Pokud jste navíc integrovali konverzní kód do své aplikace .NET, rychlost procesu převodu závisí na tom, jak dobře jste aplikaci optimalizovali.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět FODS na PPTX pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Po dokončení procesu převodu FODS na PPTX se okamžitě vygeneruje odkaz ke stažení souborů PPTX. Upřednostňujeme bezpečnost vašich souborů, proto jsou všechny nahrané soubory po 24 hodinách smazány a odkazy ke stažení po uplynutí této doby přestanou fungovat. Můžete si být jisti, že vaše soubory jsou během procesu převodu v bezpečí, včetně souborů FODS. Výše uvedená bezplatná aplikace je určena pro testovací účely a umožňuje vám zkontrolovat výsledek před integrací kódu.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu FODS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online převod FODS na PPTX máte možnost použít jakýkoli aktuální webový prohlížeč, jako je Google Chrome, Firefox, Opera, Safari. Pokud však vytváříte desktopovou aplikaci, můžete bez problémů integrovat Aspose.Total FODS Conversion API.</span>
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