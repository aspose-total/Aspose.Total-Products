---
title: Převést DOT na PPT přes C++
description: Exportujte DOT do PPT ve svých aplikacích C++ bez použití Microsoft Word nebo PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: PPT
otherformats: ODP PPSM PPTM PPSX PPS POWERPOINT POTX POT PPTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod DOT na PPT" h2="Exportujte DOT do PPT v rámci vašich C++ aplikací bez použití Microsoft Word&reg; nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) se skládá z výkonných rozhraní API pro automatizaci souborů, která umožňují automatizovat převod DOT na PPT při použití dvou z těchto rozhraní API. Načtěte svůj DOT pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) a převeďte jej do HTML, poté načtěte HTML pomocí manipulačního C++ API PowerPointu [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vytvořte novou prezentaci a uložte ji jako PPT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konverze DOT na PPT v C++" %}}
1. Otevřete soubor DOT pomocí odkazu třídy [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
2. Převeďte DOT do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_stdbasicostream_saveoptions)
3. Inicializujte nový objekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Přidejte na snímek automatický tvar a přidejte do něj AddTextFrame
5. Načtěte obsah HTML a zapište jej do souboru prezentace
6. Uložte dokument do formátu PPT pomocí metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Ppt jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOT file with an instance of Dotument
Dotument dotument = new Dotument("template.dot");
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"sourceFile.dot");
// save the dotument in HTML file format
dot->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Načtěte dokument DOT chráněný heslem přes C++" %}}
Kromě převodu dokumentů umožňuje [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API spoustu funkcí pro manipulaci s dokumenty pro vývojáře C++. V případě, že je váš formát souboru Microsoft Word DOT chráněn heslem, můžete jej stále otevřít pomocí rozhraní API. K načtení zašifrovaného dokumentu můžete použít speciální přetížení konstruktoru, který přijímá objekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Tento objekt obsahuje vlastnost Password, která určuje řetězec hesla.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotument, the password is passed to the dotument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotPassword");
// load the dotument from the local file system by filename:
SharedPtr<Dotument> dot = MakeObject<Dotument>(u"Encrypted.dot", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte komentáře do dokumentu PPT prostřednictvím C++" %}}
Při ukládání DOT jako PPT můžete také použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) k přidání dalších funkcí do dokumentu PPT. Do prezentace můžete například přidávat komentáře. Komentář ke snímku prezentace je spojen s konkrétním autorem. Třída Presentation obsahuje kolekci autorů v ICommentAuthorCollection, kteří jsou zpptovědní za přidávání komentářů ke snímkům. Pro každého autora je v ICommentCollection sbírka komentářů.
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další ppptorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-ppt/" name="DOT Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-ppsm/" name="DOT Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-pptm/" name="DOT Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-ppsx/" name="DOT Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-pps/" name="DOT Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-powerpoint/" name="DOT Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-potx/" name="DOT Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-pot/" name="DOT Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-pptx/" name="DOT Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-potm/" name="DOT Na POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}