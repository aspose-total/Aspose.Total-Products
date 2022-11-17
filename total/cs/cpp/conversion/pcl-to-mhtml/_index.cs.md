---
title: C++ API pro export PCL do MHTML
description: Převeďte PCL na MHTML v aplikacích C++.

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: MHTML
otherformats: MARKDOWN DOTX XAMLFLOW PS FLATOPC DOTM ODT OTT WORDML RTF DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export PCL do MHTML" h2="Vykreslování PCL na MHTML v aplikacích C++ bez nutnosti jakékoli aplikace třetí strany" >}}

{{% blocks/products/pf/feature-page-summary %}}
Knihovny automatizace formátu souborů [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umožňují vývojářům C++ převést PCL na MHTML ve dvou jednoduchých krocích. Nejprve můžete použít [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API pro převod formátu souboru PCL na DOC. Za druhé, pomocí pokročilého rozhraní API pro zpracování textových dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOC do MHTML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro vykreslení PCL do MHTML" %}}
1. Otevřete soubor PCL pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte PCL na DOC pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Načtěte soubor DOC pomocí odkazu na třídu [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) rozhraní Aspose.Words API
4. Uložte dokument do formátu MHTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu PCL pomocí C++" %}}
V procesu vykreslování PCL do MHTML můžete otevřít heslem chráněný PCL a také změnit jeho heslo. Chcete-li změnit heslo souboru PCL, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
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

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy souborů MHTML přes C++" %}}
Úpravu souborů MHTML můžete také omezit pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. API vám umožňuje řídit způsob, jakým omezujete obsah pomocí parametru výčtu [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Následující příklad kódu ukazuje, jak omezit úpravy v dokumentu, aby byly možné pouze úpravy v polích formuláře.
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-markdown/" name="PCL Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-dotx/" name="PCL Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-xamlflow/" name="PCL Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-ps/" name="PCL Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-flatopc/" name="PCL Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-dotm/" name="PCL Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-odt/" name="PCL Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-ott/" name="PCL Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-wordml/" name="PCL Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-rtf/" name="PCL Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-dot/" name="PCL Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pcl-to-mhtml/" name="PCL Na MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}