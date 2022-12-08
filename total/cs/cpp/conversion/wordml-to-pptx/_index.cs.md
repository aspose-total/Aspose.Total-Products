---
title: Převést WORDML na PPTX přes C++
description: Exportujte WORDML do PPTX ve svých aplikacích C++ bez použití Microsoft Word nebo PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: PPTX
otherformats: POT PPSX POTX PPT POWERPOINT PPTM PPS PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod WORDML na PPTX" h2="Exportujte WORDML do PPTX v rámci vašich C++ aplikací bez použití Microsoft Word&reg; nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) se skládá z výkonných rozhraní API pro automatizaci souborů, která umožňují automatizovat převod WORDML na PPTX při použití dvou z těchto rozhraní API. Načtěte svůj WORDML pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) a převeďte jej do HTML, poté načtěte HTML pomocí manipulačního C++ API PowerPointu [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vytvořte novou prezentaci a uložte ji jako PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konverze WORDML na PPTX v C++" %}}
1. Otevřete soubor WORDML pomocí odkazu třídy [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
2. Převeďte WORDML do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions)
3. Inicializujte nový objekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Přidejte na snímek automatický tvar a přidejte do něj AddTextFrame
5. Načtěte obsah HTML a zapište jej do souboru prezentace
6. Uložte dokument do formátu PPTX pomocí metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Pptx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Načtěte dokument WORDML chráněný heslem přes C++" %}}
Kromě převodu dokumentů umožňuje [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API spoustu funkcí pro manipulaci s dokumenty pro vývojáře C++. V případě, že je váš formát souboru Microsoft Word WORDML chráněn heslem, můžete jej stále otevřít pomocí rozhraní API. K načtení zašifrovaného dokumentu můžete použít speciální přetížení konstruktoru, který přijímá objekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Tento objekt obsahuje vlastnost Password, která určuje řetězec hesla.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte komentáře do dokumentu PPTX prostřednictvím C++" %}}
Při ukládání WORDML jako PPTX můžete také použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) k přidání dalších funkcí do dokumentu PPTX. Do prezentace můžete například přidávat komentáře. Komentář ke snímku prezentace je spojen s konkrétním autorem. Třída Presentation obsahuje kolekci autorů v ICommentAuthorCollection, kteří jsou zpptxovědní za přidávání komentářů ke snímkům. Pro každého autora je v ICommentCollection sbírka komentářů.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další ppptxorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-pot/" name="WORDML Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-ppsx/" name="WORDML Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-potx/" name="WORDML Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-ppt/" name="WORDML Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-powerpoint/" name="WORDML Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-pptm/" name="WORDML Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-pps/" name="WORDML Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-ppsm/" name="WORDML Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-potm/" name="WORDML Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-pptx/" name="WORDML Na PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}