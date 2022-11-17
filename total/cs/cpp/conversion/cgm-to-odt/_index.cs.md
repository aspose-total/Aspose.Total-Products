---
title: C++ API pro export CGM do ODT
description: Převeďte CGM na ODT v aplikacích C++.

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: ODT
otherformats: OTT WORDML MHTML PS RTF FLATOPC DOTM PCL XAMLFLOW MARKDOWN DOCM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export CGM do ODT" h2="Vykreslování CGM na ODT v aplikacích C++ bez nutnosti jakékoli aplikace třetí strany" >}}

{{% blocks/products/pf/feature-page-summary %}}
Knihovny automatizace formátu souborů [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umožňují vývojářům C++ převést CGM na ODT ve dvou jednoduchých krocích. Nejprve můžete použít [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API pro převod formátu souboru CGM na DOC. Za druhé, pomocí pokročilého rozhraní API pro zpracování textových dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOC do ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro vykreslení CGM do ODT" %}}
1. Otevřete soubor CGM pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte CGM na DOC pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Načtěte soubor DOC pomocí odkazu na třídu [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) rozhraní Aspose.Words API
4. Uložte dokument do formátu ODT pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.cgm");
// save CGM as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Odt
wordDoc->Save(u"output.Odt");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu CGM pomocí C++" %}}
V procesu vykreslování CGM do ODT můžete otevřít heslem chráněný CGM a také změnit jeho heslo. Chcete-li změnit heslo souboru CGM, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
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

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy souborů ODT přes C++" %}}
Úpravu souborů ODT můžete také omezit pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. API vám umožňuje řídit způsob, jakým omezujete obsah pomocí parametru výčtu [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Následující příklad kódu ukazuje, jak omezit úpravy v dokumentu, aby byly možné pouze úpravy v polích formuláře.
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-ott/" name="CGM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-wordml/" name="CGM Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-mhtml/" name="CGM Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-ps/" name="CGM Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-rtf/" name="CGM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-flatopc/" name="CGM Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-dotm/" name="CGM Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-pcl/" name="CGM Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-xamlflow/" name="CGM Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-markdown/" name="CGM Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-odt/" name="CGM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/cgm-to-dot/" name="CGM Na DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}