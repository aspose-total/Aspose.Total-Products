---
title: C++ API pro převod PCL na POTX
description: Převeďte PCL na POTX přes C++ bez použití Microsoft Word nebo Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: POTX
otherformats: PPTM POT ODP XAML PPT POTM SWF PPS PPSX POWERPOINT OTP PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslování PCL na POTX v rámci aplikací C++" h2="Převeďte PCL na POTX ve svých aplikacích C++ bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++, který chce přidat integraci funkce převodu PCL na POTX do vašich aplikací C++? Můžete to udělat ve dvou jednoduchých krocích. PCL můžete exportovat do PPTX pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Za druhé, pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) můžete převést PPTX na POTX. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro export PCL do POTX" %}}
1. Otevřete soubor PCL pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte PCL na PPTX pomocí funkce metody [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Načtěte dokument PPTX pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Uložte dokument do formátu POTX pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte „Potx“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pcl");
// save PCL as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Potx format
prs->Save(u"output.potx", Aspose::Slides::Export::SaveFormat::Potx);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu PCL pomocí C++" %}}
V procesu vykreslování PCL na POTX můžete otevřít heslem chráněný PCL a také změnit jeho heslo. Chcete-li změnit heslo souboru PCL, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte obrázky z webu do souboru POTX přes C++" %}}
Po převodu PCL na POTX můžete do výstupního dokumentu přidat také obrázky z webu. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ppotxoruje operace s obrázky v těchto oblíbených formátech: JPEG, PNG, BMP, GIF a další. Na snímek prezentace můžete přidat jeden nebo několik obrázků v počítači. Tento ukázkový kód v C++ ukazuje, jak přidat obrázek do souboru POTX
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POTX file
auto pres = System::MakeObject<Presentation>("output.potx");
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
pres->Save(u"updated.potx", SaveFormat::Potx);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další ppotxorované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-pptm/" name="PCL Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-pot/" name="PCL Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-potx/" name="PCL Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-xaml/" name="PCL Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-ppt/" name="PCL Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-potm/" name="PCL Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-swf/" name="PCL Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-pps/" name="PCL Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-ppsx/" name="PCL Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-powerpoint/" name="PCL Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-otp/" name="PCL Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-ppsm/" name="PCL Na PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}