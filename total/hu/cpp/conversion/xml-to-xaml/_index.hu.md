---
title: C++ API a XML XAML-vé konvertálásához
description: A XML konvertálása XAML-vé C++ segítségével Microsoft Word vagy Adobe Acrobat Reader használata nélkül
url: /hu/cpp/conversion/xml-to-xaml/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: XAML
otherformats: PPS ODP POWERPOINT PPSX OTP PPT PPSM SWF POTX POT POTM PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderje le XML-et XAML-re a C++ alkalmazásokon belül" h2="A XML konvertálása XAML-vé a C++ alkalmazásokon belül a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön egy C++ fejlesztő, aki szeretne hozzáadni a XML–XAML konverziós funkciót a C++ alkalmazásaihoz? Ezt két egyszerű lépésben teheti meg. A XML-et PPTX-be exportálhatja az [Aspose.PDF for C++] használatával (https://products.aspose.com/pdf/cpp/). Másodszor, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) használatával konvertálhatja a PPTX-t XAML-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a XML exportálásához XAML-be" %}}
1. Nyissa meg a XML-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. Konvertálja a XML-et PPTX-re a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) metódusfüggvénnyel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
4. Mentse a dokumentumot XAML-formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfüggvénnyel, és állítsa be az `Xaml-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xml");
// save XML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Xaml format
prs->Save(u"output.xaml", Aspose::Slides::Export::SaveFormat::Xaml);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a XML-dokumentum jelszavát a C++ segítségével" %}}
A XML XAML-re való renderelése során megnyithat egy jelszóval védett XML-et, és megváltoztathatja a jelszavát. Egy XML-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XML Document
auto doc = MakeObject<Document>(L"input.xml", L"owner");
// change password of XML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adjon hozzá képeket a webről az XAML-fájlba a C++ segítségével" %}}
A XML XAML-re konvertálása után a webről képeket is hozzáadhat a kimeneti dokumentumhoz. Az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) támogatja a következő népszerű formátumú képekkel végzett műveleteket: JPEG, PNG, BMP, GIF és mások. A prezentáció egyik diájához hozzáadhat egy vagy több képet a számítógépén. Ez a mintakód a C++ nyelven megmutatja, hogyan adhat hozzá képet egy XAML-fájlhoz
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a XAML file
auto pres = System::MakeObject<Presentation>("output.xaml");
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
pres->Save(u"updated.xaml", SaveFormat::Xaml);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-pps/" name="XML Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-xaml/" name="XML Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-powerpoint/" name="XML Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-ppsx/" name="XML Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-otp/" name="XML Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-ppt/" name="XML Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-ppsm/" name="XML Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-swf/" name="XML Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-potx/" name="XML Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-pot/" name="XML Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-potm/" name="XML Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xml-to-pptm/" name="XML Nak nek PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}