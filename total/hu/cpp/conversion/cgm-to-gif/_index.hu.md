---
title: C++ API a CGM exportálásához GIF-be
description: A CGM konvertálása GIF-re a C++ alkalmazásokon belül.

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: GIF
otherformats: DOTM ODT FLATOPC OTT MARKDOWN DOCM DOT XAMLFLOW WORDML MHTML PCL DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a CGM exportálásához GIF-be" h2="CGM megjelenítése GIF-ben C++ alkalmazásokon belül anélkül, hogy harmadik féltől származó alkalmazásra lenne szükség" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fájlformátumú automatizálási könyvtárak lehetővé teszik a C++ fejlesztőjének, hogy két egyszerű lépésben konvertálja a CGM-et GIF-re. Először is használhatja az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API-t a CGM fájlformátum DOC formátumba konvertálásához. Másodszor, a fejlett Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával exportálhatja a DOC-t a GIF-be. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a CGM megjelenítéséhez GIF-be" %}}
1. Nyissa meg a CGM-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. A [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) tagfüggvény használatával konvertálja a CGM-et DOC-vé
3. Töltse be a DOC-fájlt az Aspose.Words API [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozásával
4. Mentse a dokumentumot GIF formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.cgm");
// save CGM as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Gif
wordDoc->Save(u"output.Gif");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a CGM-dokumentum jelszavát a C++ segítségével" %}}
A CGM GIF-be való renderelése során megnyithat egy jelszóval védett CGM-et, és megváltoztathatja a jelszavát. Egy CGM-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Korlátozza a GIF fájlszerkesztést C++ segítségével" %}}
A GIF-fájlok szerkesztését az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával is korlátozhatja. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Az API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) felsorolási paraméter segítségével. A következő kódpélda bemutatja, hogyan lehet korlátozni a szerkesztést egy dokumentumban, így csak az űrlapmezőkben lehet szerkeszteni.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Gif");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-dotm/" name="CGM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-odt/" name="CGM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-flatopc/" name="CGM Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-ott/" name="CGM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-markdown/" name="CGM Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-gif/" name="CGM Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-dot/" name="CGM Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-xamlflow/" name="CGM Nak nek XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-wordml/" name="CGM Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-mhtml/" name="CGM Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-pcl/" name="CGM Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/cgm-to-dotx/" name="CGM Nak nek DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}