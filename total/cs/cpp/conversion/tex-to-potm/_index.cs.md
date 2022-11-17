---
title: C++ API pro převod TEX na POTM
description: Převeďte TEX na POTM přes C++ bez použití Microsoft Word nebo Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: POTM
otherformats: PPSM PPT POT PPTM PPS SWF ODP XAML POTX PPSX OTP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslování TEX na POTM v rámci aplikací C++" h2="Převeďte TEX na POTM ve svých aplikacích C++ bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++, který chce přidat integraci funkce převodu TEX na POTM do vašich aplikací C++? Můžete to udělat ve dvou jednoduchých krocích. TEX můžete exportovat do PPTX pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Za druhé, pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) můžete převést PPTX na POTM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro export TEX do POTM" %}}
1. Otevřete soubor TEX pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte TEX na PPTX pomocí funkce metody [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Načtěte dokument PPTX pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Uložte dokument do formátu POTM pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte „Potm“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class
auto doc = MakeObject<Document>(u"template.tex");
// save TEX as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Potm format
prs->Save(u"output.potm", Aspose::Slides::Export::SaveFormat::Potm);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu TEX pomocí C++" %}}
V procesu vykreslování TEX na POTM můžete otevřít heslem chráněný TEX a také změnit jeho heslo. Chcete-li změnit heslo souboru TEX, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte obrázky z webu do souboru POTM přes C++" %}}
Po převodu TEX na POTM můžete do výstupního dokumentu přidat také obrázky z webu. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ppotmoruje operace s obrázky v těchto oblíbených formátech: JPEG, PNG, BMP, GIF a další. Na snímek prezentace můžete přidat jeden nebo několik obrázků v počítači. Tento ukázkový kód v C++ ukazuje, jak přidat obrázek do souboru POTM
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POTM file
auto pres = System::MakeObject<Presentation>("output.potm");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.potm", SaveFormat::Potm);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další ppotmorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-ppsm/" name="TEX Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-ppt/" name="TEX Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-pot/" name="TEX Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-pptm/" name="TEX Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-pps/" name="TEX Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-swf/" name="TEX Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-potm/" name="TEX Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-xaml/" name="TEX Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-potx/" name="TEX Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-ppsx/" name="TEX Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-otp/" name="TEX Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/tex-to-powerpoint/" name="TEX Na POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}