---
title: C++ API a PDF exportálásához MHTML-be
description: A PDF konvertálása MHTML-re a C++ alkalmazásokon belül.

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: MHTML
otherformats: ODT WORDML XAMLFLOW FLATOPC DOTM OTT DOTX MARKDOWN RTF PS DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a PDF exportálásához MHTML-be" h2="PDF megjelenítése MHTML-ben C++ alkalmazásokon belül anélkül, hogy harmadik féltől származó alkalmazásra lenne szükség" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fájlformátumú automatizálási könyvtárak lehetővé teszik a C++ fejlesztőjének, hogy két egyszerű lépésben konvertálja a PDF-et MHTML-re. Először is használhatja az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API-t a PDF fájlformátum DOC formátumba konvertálásához. Másodszor, a fejlett Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával exportálhatja a DOC-t a MHTML-be. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a PDF megjelenítéséhez MHTML-be" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. A [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) tagfüggvény használatával konvertálja a PDF-et DOC-vé
3. Töltse be a DOC-fájlt az Aspose.Words API [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozásával
4. Mentse a dokumentumot MHTML formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Változtassa meg a PDF-dokumentum jelszavát a C++ segítségével" %}}
A PDF MHTML-be való renderelése során megnyithat egy jelszóval védett PDF-et, és megváltoztathatja a jelszavát. Egy PDF-fájl jelszavának megváltoztatásához ismernie kell a dokumentum tulajdonosi jelszavát. A jelszóval védett PDF dokumentumot betöltheti az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) segítségével a tulajdonos jelszavának megadásával, és a ChangePasswords metódus használatával módosíthatja a jelszót.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Korlátozza a MHTML fájlszerkesztést C++ segítségével" %}}
A MHTML-fájlok szerkesztését az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával is korlátozhatja. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Az API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) felsorolási paraméter segítségével. A következő kódpélda bemutatja, hogyan lehet korlátozni a szerkesztést egy dokumentumban, így csak az űrlapmezőkben lehet szerkeszteni.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}