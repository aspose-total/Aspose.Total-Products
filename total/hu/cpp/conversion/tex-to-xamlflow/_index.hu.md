---
title: C++ API a TEX exportálásához XAMLFLOW-be
description: A TEX konvertálása XAMLFLOW-re a C++ alkalmazásokon belül.
url: /hu/cpp/conversion/tex-to-xamlflow/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XAMLFLOW
otherformats: PCL ODT DOTM MHTML DOT PS FLATOPC MARKDOWN OTT WORDML DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a TEX exportálásához XAMLFLOW-be" h2="TEX megjelenítése XAMLFLOW-ben C++ alkalmazásokon belül anélkül, hogy harmadik féltől származó alkalmazásra lenne szükség" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fájlformátumú automatizálási könyvtárak lehetővé teszik a C++ fejlesztőjének, hogy két egyszerű lépésben konvertálja a TEX-et XAMLFLOW-re. Először is használhatja az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API-t a TEX fájlformátum DOC formátumba konvertálásához. Másodszor, a fejlett Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával exportálhatja a DOC-t a XAMLFLOW-be. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a TEX megjelenítéséhez XAMLFLOW-be" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. A [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) tagfüggvény használatával konvertálja a TEX-et DOC-vé
3. Töltse be a DOC-fájlt az Aspose.Words API [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozásával
4. Mentse a dokumentumot XAMLFLOW formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Xamlflow
wordDoc->Save(u"output.Xamlflow");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a TEX-dokumentum jelszavát a C++ segítségével" %}}
A TEX XAMLFLOW-be való renderelése során megnyithat egy jelszóval védett TEX-et, és megváltoztathatja a jelszavát. Egy TEX-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
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

{{% blocks/products/pf/feature-page-section  h2="Korlátozza a XAMLFLOW fájlszerkesztést C++ segítségével" %}}
A XAMLFLOW-fájlok szerkesztését az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával is korlátozhatja. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Az API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) felsorolási paraméter segítségével. A következő kódpélda bemutatja, hogyan lehet korlátozni a szerkesztést egy dokumentumban, így csak az űrlapmezőkben lehet szerkeszteni.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Xamlflow");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-pcl/" name="TEX Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-odt/" name="TEX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-dotm/" name="TEX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-mhtml/" name="TEX Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-dot/" name="TEX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-ps/" name="TEX Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-flatopc/" name="TEX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-markdown/" name="TEX Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-ott/" name="TEX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-wordml/" name="TEX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-dotx/" name="TEX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/tex-to-rtf/" name="TEX Nak nek RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}