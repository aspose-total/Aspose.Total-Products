---
title: Převést DOC na PPTM přes C++ nebo pomocí bezplatného online převodníku
description: Exportujte DOC do PPTM ve svých aplikacích C++ bez použití Microsoft Word nebo PowerPoint nebo online. Před integrací kódu rychle otestujte bezplatný online převodník  DOC na PPTM.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPTM
otherformats: POT PPSX PPT POTX ODP POTM PPS PPSM POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod DOC na PPTM nebo online aplikace" h2="Exportujte DOC do PPTM v rámci vašich C++ aplikací bez použití Microsoft Word&reg; nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) se skládá z výkonných rozhraní API pro automatizaci souborů, která umožňují automatizovat převod DOC na PPTM při použití dvou z těchto rozhraní API. Načtěte svůj DOC pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) a převeďte jej do HTML, poté načtěte HTML pomocí manipulačního C++ API PowerPointu [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vytvořte novou prezentaci a uložte ji jako PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konverze DOC na PPTM v C++" %}}
1. Otevřete soubor DOC pomocí odkazu třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Převeďte DOC do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Inicializujte nový objekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Přidejte na snímek automatický tvar a přidejte do něj AddTextFrame
5. Načtěte obsah HTML a zapište jej do souboru prezentace
6. Uložte dokument do formátu PPTM pomocí metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Pptm jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník DOC na PPTM</h3>

<iframe title="Online nástroj pptm až doc" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptm&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Načtěte dokument DOC chráněný heslem přes C++" %}}
Kromě převodu dokumentů umožňuje [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API spoustu funkcí pro manipulaci s dokumenty pro vývojáře C++. V případě, že je váš formát souboru Microsoft Word DOC chráněn heslem, můžete jej stále otevřít pomocí rozhraní API. K načtení zašifrovaného dokumentu můžete použít speciální přetížení konstruktoru, který přijímá objekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Tento objekt obsahuje vlastnost Password, která určuje řetězec hesla.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte komentáře do dokumentu PPTM prostřednictvím C++" %}}
Při ukládání DOC jako PPTM můžete také použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) k přidání dalších funkcí do dokumentu PPTM. Do prezentace můžete například přidávat komentáře. Komentář ke snímku prezentace je spojen s konkrétním autorem. Třída Presentation obsahuje kolekci autorů v ICommentAuthorCollection, kteří jsou zpptmovědní za přidávání komentářů ke snímkům. Pro každého autora je v ICommentCollection sbírka komentářů.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
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
                          <span itemprop="name"><b>Jak mohu převést DOC na PPTM Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Online aplikaci pro převod DOC najdete výše. Chcete-li zahájit proces převodu, můžete přidat soubor DOC buď přetažením, nebo kliknutím do bílé oblasti pro import dokumentu. Po přidání souboru můžete jednoduše kliknout na tlačítko "Převést". Po dokončení převodu DOC na PPTM si můžete stáhnout převedený soubor jediným kliknutím.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak dlouho trvá převod DOC?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Rychlost tohoto online převodníku závisí do značné míry na velikosti převáděného souboru DOC. Malé soubory DOC lze převést na PPTM během několika sekund. Pokud používáte převodní kód v rámci aplikace C++, bude rychlost převodu záviset na tom, jak dobře jste aplikaci optimalizovali.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Je bezpečné převádět DOC na PPTM pomocí bezplatného převodníku Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Samozřejmě! Poté, co je váš soubor DOC převeden na PPTM pomocí našeho online převodníku, bude okamžitě k dispozici odkaz ke stažení souboru PPTM. Bezpečnost a soukromí vašich nahraných souborů bereme vážně a mažeme je 24 hodin po dokončení procesu převodu. Ujišťujeme vás, že k vašim souborům nebude mít nikdo přístup. Náš proces převodu, včetně převodu DOC, je zcela bezpečný. Poskytujeme bezplatnou aplikaci pro testovací účely, abyste si mohli ověřit výsledky před integrací kódu.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jaký prohlížeč mám použít k převodu DOC?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pro online převod DOC můžete použít jakýkoli moderní prohlížeč, jako je Google Chrome, Firefox, Opera nebo Safari. Pokud však vyvíjíte desktopovou aplikaci, doporučujeme Aspose.Total DOC Conversion API pro hladký výkon.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}