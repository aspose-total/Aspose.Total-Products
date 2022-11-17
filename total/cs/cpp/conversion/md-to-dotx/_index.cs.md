---
title: C++ API pro export MD do DOTX
description: Převeďte MD na DOTX v aplikacích C++.

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOTX
otherformats: DOCM FLATOPC MHTML PS WORDML DOTM OTT XAMLFLOW ODT MARKDOWN PCL DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export MD do DOTX" h2="Vykreslování MD na DOTX v aplikacích C++ bez nutnosti jakékoli aplikace třetí strany" >}}

{{% blocks/products/pf/feature-page-summary %}}
Knihovny automatizace formátu souborů [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umožňují vývojářům C++ převést MD na DOTX ve dvou jednoduchých krocích. Nejprve můžete použít [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API pro převod formátu souboru MD na DOC. Za druhé, pomocí pokročilého rozhraní API pro zpracování textových dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOC do DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro vykreslení MD do DOTX" %}}
1. Otevřete soubor MD pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte MD na DOC pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Načtěte soubor DOC pomocí odkazu na třídu [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) rozhraní Aspose.Words API
4. Uložte dokument do formátu DOTX pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotx
wordDoc->Save(u"output.Dotx");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Změna hesla dokumentu MD pomocí C++" %}}
V procesu vykreslování MD do DOTX můžete otevřít heslem chráněný MD a také změnit jeho heslo. Chcete-li změnit heslo souboru MD, musíte znát heslo vlastníka tohoto dokumentu. Dokument PDF chráněný heslem můžete načíst pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) zadáním hesla vlastníka a pomocí metody ChangePasswords heslo změnit.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy souborů DOTX přes C++" %}}
Úpravu souborů DOTX můžete také omezit pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. API vám umožňuje řídit způsob, jakým omezujete obsah pomocí parametru výčtu [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Následující příklad kódu ukazuje, jak omezit úpravy v dokumentu, aby byly možné pouze úpravy v polích formuláře.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotx");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-dotx/" name="MD Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-flatopc/" name="MD Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-mhtml/" name="MD Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-ps/" name="MD Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-wordml/" name="MD Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-dotm/" name="MD Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-ott/" name="MD Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-xamlflow/" name="MD Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-odt/" name="MD Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-markdown/" name="MD Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-pcl/" name="MD Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/md-to-dot/" name="MD Na DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}