---
title: Odeberte DOCX Annotation Online nebo Spravujte anotace pomocí C++
description: odstranit komentáře ze souboru DOCX prostřednictvím online aplikace zdarma. C++ API kód pro správu komentářů souborů DOCX.

family: total
platformtag: cpp
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Vymazat komentáře z DOCX Document Online nebo Spravovat přes C++" h2="Vyvíjejte výkonnou aplikaci pro anotaci dokumentů DOCX na bázi C++. Uvedený kód pro správu komentářů k souboru DOCX prostřednictvím C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Odebrat DOCX Anotace online" %}}

1. Importujte soubor DOCX a odstraňte komentáře jeho nahráním
1. Udělejte to kliknutím do oblasti přetažení pomocí aplikace pro poznámky
1. V závislosti na velikosti souboru DOCX a rychlosti internetu počkejte několik sekund
1. Kliknutím na tlačítko 'Odebrat' komentáře vymažete
1. Stáhněte soubor okamžitě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Odstraňte komentáře dokumentu DOCX pomocí C++" %}}

1. Přidejte odkaz na knihovnu do projektu C++
1. Načtěte soubor DOCX
1. Získejte všechny uzly pomocí GetChildNodes s parametrem NodeType::Comment
1. Volejte NodeCollection.Clear na kolekci komentářů

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód C++: Odstraňte komentáře ze souboru DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Přidávejte komentáře přes C++" %}}

1. Vytvořte objekt třídy Document a DocumentBuilder
1. Nebo Vložte dokument
1. Pro přidání komentáře použijte třídu Comment
1. Použijte metodu AppendChild s parametrem obj komentáře
1. Použijte příslušnou metodu jako get_Paragraphs()->Add
1. Nebo druhým způsobem je použití tříd CommentRangeStart a CommentRangeEnd
1. Chcete-li soubor uložit s přidanými komentáři, zavolejte metodu uložení

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Extrahujte všechny komentáře" %}}

1. Načíst dokument přes objekt třídy Document
1. Získejte všechny GetChildNodes v NodeCollection
1. Projděte každou kolekci a shromážděte o nich informace

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód C++: Přidejte komentář k souboru DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Extrahujte všechny komentáře" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Vyvíjejte aplikaci pro anotaci dokumentů DOCX prostřednictvím C++</h2>

Potřebujete vyvinout anotační aplikaci nebo nástroj DOCX pro poskytování zpětné vazby, návrhy nebo spolupráci s ostatními na dokumentu?S [Aspose.Words for C++](https://products.aspose.com/words/cpp/), podřízeným API [Aspose.Total for C++](https://products.aspose.com/total/cs/cpp/), může každý vývojář C++ integrovat výše uvedený kód API do své aplikace pro anotaci dokumentů.Výkonná knihovna C++ umožňuje programování libovolného řešení anotací dokumentů.Navíc může podporovat mnoho populárních formátů včetně formátu DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Knihovna C++ pro anotaci souborů DOCX" %}}

Existují tři možnosti instalace Aspose.Words pro C++ do vašeho vývojářského prostředí.Vyberte si prosím ten, který odpovídá vašim potřebám, a postupujte podle pokynů krok za krokem:<br /><br />

- Install a [Balíček NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Dokumentace](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Nainstalujte knihovnu pomocí [Konzole správce balíčků](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) v rámci Visual Studio IDE
- Nainstalujte knihovnu ručně pomocí [Instalační služba Windows Installer](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}
Tuto knihovnu C++ můžete použít k vývoji softwaru v operačních systémech Microsoft Windows, Linux a macOS:<br /><br />

- Pro Linux jsou vyžadovány GCC >= 6.3.0 a Clang >= 3.9.1
- Pro macOS jsou vyžadovány Xcode >= 12.5.1, Clang a libc++

<br /><br />
Pokud vyvíjíte software pro Linux nebo macOS, zkontrolujte informace o dalších závislostech knihoven (fontconfig a mesa-glu open-source balíčky) v [Produktová dokumentace](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Nejčastější dotazy" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Nejčastější dotazy</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mohu ve své aplikaci použít výše uvedený kód C++?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ano, můžete si stáhnout tento kód a použít jej pro účely vývoje aplikace pro anotaci dokumentů na bázi C++.Tento kód může sloužit jako cenný zdroj pro vylepšení funkčnosti a schopností vašich projektů v oblasti zpracování a manipulace s dokumenty.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Funguje tato online aplikace pro anotaci dokumentů pouze ve Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Máte možnost zahájit anotaci dokumentu pro odstranění komentářů na jakémkoli zařízení, bez ohledu na operační systém, na kterém běží, ať už je to Windows, Linux, Mac OS nebo Android. Vše, co k tomu potřebujete, je moderní webový prohlížeč a aktivní připojení k internetu.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné používat online aplikaci k anotaci dokumentu DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Výstupní soubory generované prostřednictvím naší služby budou bezpečně a automaticky odstraněny z našich serverů během 24 hodin.V důsledku toho po uplynutí této doby přestanou být odkazy na zobrazení spojené s těmito soubory funkční.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč by měl používat aplikaci?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online anotaci dokumentů DOCX můžete použít jakýkoli moderní webový prohlížeč, jako je Google Chrome, Firefox, Opera nebo Safari.Pokud však vyvíjíte desktopovou aplikaci, doporučujeme pro efektivní správu použít rozhraní API pro zpracování dokumentů Aspose.Total.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}