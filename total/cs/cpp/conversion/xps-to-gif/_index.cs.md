---
title: C++ API pro export XPS do GIF
description: Převeďte XPS na GIF v aplikacích C++.

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: GIF
otherformats: DOCM DOT PCL MARKDOWN RTF FLATOPC DOTX MHTML OTT DOTM XAMLFLOW WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export XPS do GIF" h2="Vykreslování XPS na GIF v aplikacích C++ bez nutnosti jakékoli aplikace třetí strany" >}}

{{% blocks/products/pf/feature-page-summary %}}
Knihovny automatizace formátu souborů [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umožňují vývojářům C++ převést XPS na GIF ve dvou jednoduchých krocích. Nejprve můžete použít [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API pro převod formátu souboru XPS na DOC. Za druhé, pomocí pokročilého rozhraní API pro zpracování textových dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOC do GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro vykreslení XPS do GIF" %}}
1. Otevřete soubor XPS pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte XPS na DOC pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Načtěte soubor DOC pomocí odkazu na třídu [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) rozhraní Aspose.Words API
4. Uložte dokument do formátu GIF pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Gif
wordDoc->Save(u"output.Gif");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu XPS pomocí C++" %}}
V procesu vykreslování XPS do GIF můžete otevřít heslem chráněný XPS a také změnit jeho heslo. Chcete-li změnit heslo souboru XPS, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
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

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy souborů GIF přes C++" %}}
Úpravu souborů GIF můžete také omezit pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. API vám umožňuje řídit způsob, jakým omezujete obsah pomocí parametru výčtu [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Následující příklad kódu ukazuje, jak omezit úpravy v dokumentu, aby byly možné pouze úpravy v polích formuláře.
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-gif/" name="XPS Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-dot/" name="XPS Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-pcl/" name="XPS Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-markdown/" name="XPS Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-rtf/" name="XPS Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-flatopc/" name="XPS Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-dotx/" name="XPS Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-mhtml/" name="XPS Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-ott/" name="XPS Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-dotm/" name="XPS Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xamlflow/" name="XPS Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-wordml/" name="XPS Na WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}