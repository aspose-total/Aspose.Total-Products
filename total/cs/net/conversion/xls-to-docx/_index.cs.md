---
title: Převeďte XLS na DOCX pomocí .NET nebo pomocí bezplatného online převodníku
description: Převeďte XLS na DOCX na platformách .NET Framework, .NET Core, Mono nebo Xamarin nebo online. Před integrací kódu rychle otestujte bezplatný online převodník  XLS na DOCX.

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Převést XLS na DOCX přes C# nebo online aplikace" h2="Export Excel&reg; XLS do DOCX na platformách .NET Framework, .NET Core, Mono nebo Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Převod XLS na DOCX na .NET" %}}
1. Otevřete soubor XLS pomocí třídy [Sešit](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Převeďte XLS na PDF a nastavte SaveFormat na Auto
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Uložte dokument do formátu DOCX pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) a nastavte Docx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Kód pro převod XLS na DOCX" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník XLS na DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xls" id="child-iframe" width="80%"></iframe>

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
                          <span itemprop="name"><b>Jak mohu převést XLS na DOCX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikace pro převod XLS je integrována výše. Chcete-li zahájit proces převodu, můžete buď přetáhnout soubor XLS, nebo kliknout do určené oblasti a importovat dokument. Dále klikněte na tlačítko "Převést" pro zahájení převodu XLS na DOCX. Po dokončení procesu si můžete snadno stáhnout převedený soubor jediným kliknutím a získat požadovaný výstup ve formátu DOCX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod XLS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Rychlost tohoto online převodníku je vysoká, ale primárně závisí na velikosti souboru XLS. Pokud máte malý soubor XLS, lze jej převést na DOCX během několika sekund. Pokud jste navíc integrovali konverzní kód do své aplikace .NET, rychlost procesu převodu závisí na tom, jak dobře jste aplikaci optimalizovali.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět XLS na DOCX pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Po dokončení procesu převodu XLS na DOCX se okamžitě vygeneruje odkaz ke stažení souborů DOCX. Upřednostňujeme bezpečnost vašich souborů, proto jsou všechny nahrané soubory po 24 hodinách smazány a odkazy ke stažení po uplynutí této doby přestanou fungovat. Můžete si být jisti, že vaše soubory jsou během procesu převodu v bezpečí, včetně souborů XLS. Výše uvedená bezplatná aplikace je určena pro testovací účely a umožňuje vám zkontrolovat výsledek před integrací kódu.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu XLS?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online převod XLS na DOCX máte možnost použít jakýkoli aktuální webový prohlížeč, jako je Google Chrome, Firefox, Opera, Safari. Pokud však vytváříte desktopovou aplikaci, můžete bez problémů integrovat Aspose.Total XLS Conversion API.</span>
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