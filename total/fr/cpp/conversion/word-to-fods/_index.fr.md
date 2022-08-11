---
title: Convertir WORD en FODS en C++
description: API C++ pour convertir WORD en FODS sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/cpp/conversion/word-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: FODS
otherformats: EXCEL XLSM XLSX XLSB SXC TSV XLTX DIF XLTM XLS XLT XLAM ODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour convertir WORD en FODS" h2="Exportez WORD vers FODS via C++ sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez facilement inclure la fonction de conversion WORD en FODS dans vos applications C++. En utilisant l'API de manipulation et de conversion de worduments riche en fonctionnalités, puissante et facile à utiliser [Aspose.Words pour C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du WORD vers HTML. Après cela, en utilisant [Aspose.Cells pour C++](https://products.aspose.com/cells/cpp/), vous pouvez convertir HTML en FODS. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir WORD en FODS" %}}
1. Ouvrez le fichier WORD à l'aide de la référence de classe [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument)
2. Convertir WORD en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat)
3. Chargez le wordument HTML à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le wordument au format FODS à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accéder aux propriétés du wordument WORD via C++" %}}
[Aspose.Words pour C++](https://products.aspose.com/words/cpp/) vous permet également d'accéder aux propriétés du wordument du fichier WORD et vous permet de prendre une décision éclairée avant le processus de conversion. Pour accéder aux propriétés du wordument, vous pouvez utiliser [BuiltInWordumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordument_properties) pour obtenir les propriétés intégrées et [CustomWordumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordument_properties) pour obtenir des propriétés personnalisées. L'exemple de code suivant montre comment énumérer toutes les propriétés intégrées et personnalisées dans un wordument.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le fichier FODS dans le flux via C++" %}}
Après avoir converti WORD en FODS, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) vous permet d'enregistrer votre wordument pour le diffuser. Pour enregistrer des fichiers dans un flux, créez un objet MemoryStream ou FileStream et enregistrez le fichier dans cet objet de flux en appelant [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) de l'objet. Spécifiez le format de fichier souhaité à l'aide de l'énumération [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) lors de l'appel de l'énumération [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-excel/" name="WORD À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xlsm/" name="WORD À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xlsx/" name="WORD À XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xlsb/" name="WORD À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-sxc/" name="WORD À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-tsv/" name="WORD À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xltx/" name="WORD À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-dif/" name="WORD À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xltm/" name="WORD À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xls/" name="WORD À XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xlt/" name="WORD À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-xlam/" name="WORD À XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-ods/" name="WORD À ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/word-to-fods/" name="WORD À FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}