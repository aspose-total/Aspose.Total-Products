---
title: Convertir DOTM en FODS en C++
description: API C++ pour convertir DOTM en FODS sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/cpp/conversion/dotm-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: FODS
otherformats: SXC XLSX XLS XLAM XLSB XLTX XLT ODS DIF EXCEL XLSM TSV XLTM CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour convertir DOTM en FODS" h2="Exportez DOTM vers FODS via C++ sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez facilement inclure la fonction de conversion DOTM en FODS dans vos applications C++. En utilisant l'API de manipulation et de conversion de dotmuments riche en fonctionnalités, puissante et facile à utiliser [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du DOTM vers HTML. Après cela, en utilisant [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), vous pouvez convertir HTML en FODS. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir DOTM en FODS" %}}
1. Ouvrez le fichier DOTM à l'aide de la référence de classe [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
2. Convertir DOTM en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat)
3. Chargez le dotmument HTML à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le dotmument au format FODS à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accéder aux propriétés du dotmument DOTM via C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vous permet également d'accéder aux propriétés du dotmument du fichier DOTM et vous permet de prendre une décision éclairée avant le processus de conversion. Pour accéder aux propriétés du dotmument, vous pouvez utiliser [BuiltInDotmumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotmument_properties) pour obtenir les propriétés intégrées et [CustomDotmumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotmument_properties) pour obtenir des propriétés personnalisées. L'exemple de code suivant montre comment énumérer toutes les propriétés intégrées et personnalisées dans un dotmument.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotmument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le fichier FODS dans le flux via C++" %}}
Après avoir converti DOTM en FODS, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) vous permet d'enregistrer votre dotmument pour le diffuser. Pour enregistrer des fichiers dans un flux, créez un objet MemoryStream ou FileStream et enregistrez le fichier dans cet objet de flux en appelant [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) de l'objet. Spécifiez le format de fichier souhaité à l'aide de l'énumération [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) lors de l'appel de l'énumération [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-sxc/" name="DOTM À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xlsx/" name="DOTM À XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xls/" name="DOTM À XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xlam/" name="DOTM À XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xlsb/" name="DOTM À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xltx/" name="DOTM À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xlt/" name="DOTM À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-ods/" name="DOTM À ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-dif/" name="DOTM À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-excel/" name="DOTM À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xlsm/" name="DOTM À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-tsv/" name="DOTM À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-xltm/" name="DOTM À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/dotm-to-fods/" name="DOTM À FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}