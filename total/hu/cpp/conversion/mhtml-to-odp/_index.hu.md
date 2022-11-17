---
title: C++ API a MHTML ODP-vé konvertálásához
description: A MHTML konvertálása ODP-vé C++ segítségével Microsoft Word vagy Adobe Acrobat Reader használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: ODP
otherformats: PPSM PPTM PPSX XAML POTM PPS OTP POT SWF PPT POTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderje le MHTML-et ODP-re a C++ alkalmazásokon belül" h2="A MHTML konvertálása ODP-vé a C++ alkalmazásokon belül a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön egy C++ fejlesztő, aki szeretne hozzáadni a MHTML–ODP konverziós funkciót a C++ alkalmazásaihoz? Ezt két egyszerű lépésben teheti meg. A MHTML-et PPTX-be exportálhatja az [Aspose.PDF for C++] használatával (https://products.aspose.com/pdf/cpp/). Másodszor, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) használatával konvertálhatja a PPTX-t ODP-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a MHTML exportálásához ODP-be" %}}
1. Nyissa meg a MHTML-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. Konvertálja a MHTML-et PPTX-re a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) metódusfüggvénnyel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
4. Mentse a dokumentumot ODP-formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfüggvénnyel, és állítsa be az `Odp-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MHTML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.mhtml");
// save MHTML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a MHTML-dokumentum jelszavát a C++ segítségével" %}}
A MHTML ODP-re való renderelése során megnyithat egy jelszóval védett MHTML-et, és megváltoztathatja a jelszavát. Egy MHTML-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MHTML Document
auto doc = MakeObject<Document>(L"input.mhtml", L"owner");
// change password of MHTML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adjon hozzá képeket a webről az ODP-fájlba a C++ segítségével" %}}
A MHTML ODP-re konvertálása után a webről képeket is hozzáadhat a kimeneti dokumentumhoz. Az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) támogatja a következő népszerű formátumú képekkel végzett műveleteket: JPEG, PNG, BMP, GIF és mások. A prezentáció egyik diájához hozzáadhat egy vagy több képet a számítógépén. Ez a mintakód a C++ nyelven megmutatja, hogyan adhat hozzá képet egy ODP-fájlhoz
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a ODP file
auto pres = System::MakeObject<Presentation>("output.odp");
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
pres->Save(u"updated.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-ppsm/" name="MHTML Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-pptm/" name="MHTML Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-ppsx/" name="MHTML Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xaml/" name="MHTML Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-potm/" name="MHTML Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-pps/" name="MHTML Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-otp/" name="MHTML Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-pot/" name="MHTML Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-swf/" name="MHTML Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-ppt/" name="MHTML Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-potx/" name="MHTML Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-powerpoint/" name="MHTML Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}