---
title: API C++ pour convertir PPS en DOCM
description: Exportez PPS vers DOCM dans vos applications C++

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCM
otherformats: DOTX DOC DOCX DOTM DOT WORDML ODT WORD FLATOPC TEXT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour rendre PPS en DOCM" h2="Exportez PPS vers DOCM dans des applications C++ sans aucune dépendance Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un package complet de bibliothèques d'automatisation du format de fichier C++. En utilisant les fonctionnalités riches des API disponibles dans le package, nous pouvons facilement convertir PowerPoint PPS en Word DOCM. Pour effectuer la conversion, vous pouvez d'abord utiliser l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour convertir PPS en HTML. Après cela, en utilisant l'API de traitement de texte riche en fonctionnalités [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez convertir le HTML en DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PPS en DOCM" %}}
1. Chargez le fichier PPS à l'aide de la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Rendez PPS en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
4. Enregistrez le docmument au format DOCM en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-dotx/" name="PPS À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-docm/" name="PPS À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-docmx/" name="PPS À DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-dotm/" name="PPS À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-dot/" name="PPS À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-wordml/" name="PPS À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-odt/" name="PPS À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-word/" name="PPS À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-flatopc/" name="PPS À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-text/" name="PPS À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-rtf/" name="PPS À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pps-to-ott/" name="PPS À OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}