---
title: C++ API pro převod XPS na SWF
description: Převeďte XPS na SWF přes C++ bez použití Microsoft Word nebo Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: SWF
otherformats: OTP PPS ODP PPSX POTM POWERPOINT PPT PPTM PPSM POTX POT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslování XPS na SWF v rámci aplikací C++" h2="Převeďte XPS na SWF ve svých aplikacích C++ bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++, který chce přidat integraci funkce převodu XPS na SWF do vašich aplikací C++? Můžete to udělat ve dvou jednoduchých krocích. XPS můžete exportovat do PPTX pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Za druhé, pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) můžete převést PPTX na SWF. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro export XPS do SWF" %}}
1. Otevřete soubor XPS pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte XPS na PPTX pomocí funkce metody [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Načtěte dokument PPTX pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Uložte dokument do formátu SWF pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte „Swf“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Swf format
prs->Save(u"output.swf", Aspose::Slides::Export::SaveFormat::Swf);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu XPS pomocí C++" %}}
V procesu vykreslování XPS na SWF můžete otevřít heslem chráněný XPS a také změnit jeho heslo. Chcete-li změnit heslo souboru XPS, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte obrázky z webu do souboru SWF přes C++" %}}
Po převodu XPS na SWF můžete do výstupního dokumentu přidat také obrázky z webu. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pswforuje operace s obrázky v těchto oblíbených formátech: JPEG, PNG, BMP, GIF a další. Na snímek prezentace můžete přidat jeden nebo několik obrázků v počítači. Tento ukázkový kód v C++ ukazuje, jak přidat obrázek do souboru SWF
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a SWF file
auto pres = System::MakeObject<Presentation>("output.swf");
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
pres->Save(u"updated.swf", SaveFormat::Swf);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další pswforované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-otp/" name="XPS Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-pps/" name="XPS Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-swf/" name="XPS Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-ppsx/" name="XPS Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-potm/" name="XPS Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-powerpoint/" name="XPS Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-ppt/" name="XPS Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-pptm/" name="XPS Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-ppsm/" name="XPS Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-potx/" name="XPS Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-pot/" name="XPS Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xaml/" name="XPS Na XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}