---
title: C++ API a EPUB exportálásához ODT-be
description: A EPUB konvertálása ODT-re a C++ alkalmazásokon belül.

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: ODT
otherformats: MARKDOWN DOCM MHTML XAMLFLOW DOTM DOT FLATOPC PCL WORDML PS RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a EPUB exportálásához ODT-be" h2="EPUB megjelenítése ODT-ben C++ alkalmazásokon belül anélkül, hogy harmadik féltől származó alkalmazásra lenne szükség" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fájlformátumú automatizálási könyvtárak lehetővé teszik a C++ fejlesztőjének, hogy két egyszerű lépésben konvertálja a EPUB-et ODT-re. Először is használhatja az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API-t a EPUB fájlformátum DOC formátumba konvertálásához. Másodszor, a fejlett Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával exportálhatja a DOC-t a ODT-be. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a EPUB megjelenítéséhez ODT-be" %}}
1. Nyissa meg a EPUB-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. A [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) tagfüggvény használatával konvertálja a EPUB-et DOC-vé
3. Töltse be a DOC-fájlt az Aspose.Words API [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozásával
4. Mentse a dokumentumot ODT formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Odt
wordDoc->Save(u"output.Odt");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a EPUB-dokumentum jelszavát a C++ segítségével" %}}
A EPUB ODT-be való renderelése során megnyithat egy jelszóval védett EPUB-et, és megváltoztathatja a jelszavát. Egy EPUB-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Korlátozza a ODT fájlszerkesztést C++ segítségével" %}}
A ODT-fájlok szerkesztését az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával is korlátozhatja. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Az API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) felsorolási paraméter segítségével. A következő kódpélda bemutatja, hogyan lehet korlátozni a szerkesztést egy dokumentumban, így csak az űrlapmezőkben lehet szerkeszteni.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Odt");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}