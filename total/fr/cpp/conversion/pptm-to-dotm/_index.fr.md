---
title: API C++ pour convertir PPTM en DOTM
description: Exportez PPTM vers DOTM dans vos applications C++

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOTM
otherformats: DOC WORD DOTX TEXT DOCX ODT DOCM FLATOPC DOT WORDML RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour rendre PPTM en DOTM" h2="Exportez PPTM vers DOTM dans des applications C++ sans aucune dépendance Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un package complet de bibliothèques d'automatisation du format de fichier C++. En utilisant les fonctionnalités riches des API disponibles dans le package, nous pouvons facilement convertir PowerPoint PPTM en Word DOTM. Pour effectuer la conversion, vous pouvez d'abord utiliser l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour convertir PPTM en HTML. Après cela, en utilisant l'API de traitement de texte riche en fonctionnalités [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez convertir le HTML en DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PPTM en DOTM" %}}
1. Chargez le fichier PPTM à l'aide de la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Rendez PPTM en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la référence de classe [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
4. Enregistrez le dotmument au format DOTM en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotmument
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"htmlOutput.html");
// save dotmument in DOTM format
dotm->Save(u"output.dotm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-dotm/" name="PPTM À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-word/" name="PPTM À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-dotx/" name="PPTM À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-text/" name="PPTM À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-dotmx/" name="PPTM À DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-odt/" name="PPTM À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-dotmm/" name="PPTM À DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-flatopc/" name="PPTM À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-dot/" name="PPTM À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-wordml/" name="PPTM À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-rtf/" name="PPTM À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptm-to-ott/" name="PPTM À OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}