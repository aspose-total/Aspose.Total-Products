---
title: API C++ pour convertir PPTX en DOCX
description: Exportez PPTX vers DOCX dans vos applications C++

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOCX
otherformats: WORD DOTX DOC ODT DOCM FLATOPC OTT WORDML TEXT DOTM RTF DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour rendre PPTX en DOCX" h2="Exportez PPTX vers DOCX dans des applications C++ sans aucune dépendance Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un package complet de bibliothèques d'automatisation du format de fichier C++. En utilisant les fonctionnalités riches des API disponibles dans le package, nous pouvons facilement convertir PowerPoint PPTX en Word DOCX. Pour effectuer la conversion, vous pouvez d'abord utiliser l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour convertir PPTX en HTML. Après cela, en utilisant l'API de traitement de texte riche en fonctionnalités [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez convertir le HTML en DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PPTX en DOCX" %}}
1. Chargez le fichier PPTX à l'aide de la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Rendez PPTX en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOCX en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOCX format
docx->Save(u"output.docx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-word/" name="PPTX À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-dotx/" name="PPTX À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-docx/" name="PPTX À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-odt/" name="PPTX À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-docxm/" name="PPTX À DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-flatopc/" name="PPTX À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-ott/" name="PPTX À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-wordml/" name="PPTX À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-text/" name="PPTX À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-dotm/" name="PPTX À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-rtf/" name="PPTX À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/pptx-to-dot/" name="PPTX À DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}