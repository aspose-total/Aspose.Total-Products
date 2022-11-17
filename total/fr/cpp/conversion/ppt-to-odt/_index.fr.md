---
title: API C++ pour convertir PPT en ODT
description: Exportez PPT vers ODT dans vos applications C++

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: ODT
otherformats: FLATOPC WORDML TEXT OTT DOCM DOC DOTM DOCX RTF DOTX WORD DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour rendre PPT en ODT" h2="Exportez PPT vers ODT dans des applications C++ sans aucune dépendance Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un package complet de bibliothèques d'automatisation du format de fichier C++. En utilisant les fonctionnalités riches des API disponibles dans le package, nous pouvons facilement convertir PowerPoint PPT en Word ODT. Pour effectuer la conversion, vous pouvez d'abord utiliser l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour convertir PPT en HTML. Après cela, en utilisant l'API de traitement de texte riche en fonctionnalités [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez convertir le HTML en ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PPT en ODT" %}}
1. Chargez le fichier PPT à l'aide de la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Rendez PPT en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la référence de classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. Enregistrez le odtument au format ODT en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-flatopc/" name="PPT À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-wordml/" name="PPT À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-text/" name="PPT À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-ott/" name="PPT À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-odtm/" name="PPT À ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-odt/" name="PPT À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-dotm/" name="PPT À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-odtx/" name="PPT À ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-rtf/" name="PPT À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-dotx/" name="PPT À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-word/" name="PPT À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ppt-to-dot/" name="PPT À DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}