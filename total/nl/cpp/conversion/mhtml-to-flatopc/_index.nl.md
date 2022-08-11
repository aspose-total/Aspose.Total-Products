---
title: C++ API om MHTML naar FLATOPC te exporteren
description: Converteer MHTML naar FLATOPC binnen C++-toepassingen.
url: /nl/cpp/conversion/mhtml-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: FLATOPC
otherformats: ODT XAMLFLOW MARKDOWN DOT DOTX RTF WORDML PCL OTT DOTM DOCM PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om MHTML naar FLATOPC te exporteren" h2="Render MHTML naar FLATOPC binnen C++-applicaties zonder dat een applicatie van derden nodig is" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) automatiseringsbibliotheken voor bestandsindelingen stellen C++-ontwikkelaars in staat om MHTML in twee eenvoudige stappen naar FLATOPC te converteren. Ten eerste kunt u de API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) gebruiken om het MHTML-bestandsformaat naar DOC te converteren. Ten tweede, door gebruik te maken van de geavanceerde Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), kunt u DOC naar FLATOPC exporteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om MHTML naar FLATOPC te renderen" %}}
1. Open het MHTML-bestand met behulp van de klasseverwijzing [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converteer MHTML naar DOC met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) lidfunctie
3. Laad DOC-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klasseverwijzing van Aspose.Words API
4. Sla het document op in FLATOPC-formaat met behulp van de lidfunctie [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MHTML file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.mhtml");
// save MHTML as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Wijzig wachtwoord van MHTML-document via C++" %}}
Tijdens het omzetten van MHTML naar FLATOPC, kunt u een met een wachtwoord beveiligde MHTML openen en ook het wachtwoord wijzigen. Om het wachtwoord van een MHTML-bestand te wijzigen, moet u het eigenaarswachtwoord van dat document weten. U kunt een met een wachtwoord beveiligd PDF-document laden met [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) door het eigenaarswachtwoord op te geven en de ChangePasswords-methode te gebruiken om het wachtwoord te wijzigen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MHTML Document
auto doc = MakeObject<Document>(L"input.mhtml", L"owner");
// change password of MHTML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van FLATOPC-bestanden via C++" %}}
U kunt het bewerken van FLATOPC-bestanden ook beperken met de API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Met API kunt u bepalen hoe u de inhoud beperkt met behulp van de opsommingsparameter [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Het volgende codevoorbeeld laat zien hoe u het bewerken in een document kunt beperken, zodat alleen bewerken in formuliervelden mogelijk is.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-odt/" name="MHTML Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-xamlflow/" name="MHTML Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-markdown/" name="MHTML Tot MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-dot/" name="MHTML Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-dotx/" name="MHTML Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-rtf/" name="MHTML Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-wordml/" name="MHTML Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-pcl/" name="MHTML Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-ott/" name="MHTML Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-dotm/" name="MHTML Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-flatopc/" name="MHTML Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/mhtml-to-ps/" name="MHTML Tot PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}