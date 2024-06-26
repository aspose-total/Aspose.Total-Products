---
title: C++ API a SVG PPSM-vé konvertálásához
description: A SVG konvertálása PPSM-vé C++ segítségével Microsoft Word vagy Adobe Acrobat Reader használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: PPSM
otherformats: PPS POTM SWF XAML OTP PPTM ODP PPSX PPT POTX POT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderje le SVG-et PPSM-re a C++ alkalmazásokon belül" h2="A SVG konvertálása PPSM-vé a C++ alkalmazásokon belül a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön egy C++ fejlesztő, aki szeretne hozzáadni a SVG–PPSM konverziós funkciót a C++ alkalmazásaihoz? Ezt két egyszerű lépésben teheti meg. A SVG-et PPTX-be exportálhatja az [Aspose.PDF for C++] használatával (https://products.aspose.com/pdf/cpp/). Másodszor, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) használatával konvertálhatja a PPTX-t PPSM-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a SVG exportálásához PPSM-be" %}}
1. Nyissa meg a SVG-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. Konvertálja a SVG-et PPTX-re a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) metódusfüggvénnyel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
4. Mentse a dokumentumot PPSM-formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfüggvénnyel, és állítsa be az `Ppsm-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class
auto doc = MakeObject<Document>(u"template.svg");
// save SVG as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsm format
prs->Save(u"output.ppsm", Aspose::Slides::Export::SaveFormat::Ppsm);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a SVG-dokumentum jelszavát a C++ segítségével" %}}
A SVG PPSM-re való renderelése során megnyithat egy jelszóval védett SVG-et, és megváltoztathatja a jelszavát. Egy SVG-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adjon hozzá képeket a webről az PPSM-fájlba a C++ segítségével" %}}
A SVG PPSM-re konvertálása után a webről képeket is hozzáadhat a kimeneti dokumentumhoz. Az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) támogatja a következő népszerű formátumú képekkel végzett műveleteket: JPEG, PNG, BMP, GIF és mások. A prezentáció egyik diájához hozzáadhat egy vagy több képet a számítógépén. Ez a mintakód a C++ nyelven megmutatja, hogyan adhat hozzá képet egy PPSM-fájlhoz
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSM file
auto pres = System::MakeObject<Presentation>("output.ppsm");
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
pres->Save(u"updated.ppsm", SaveFormat::Ppsm);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}