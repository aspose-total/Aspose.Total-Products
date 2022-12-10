---
title: Convertir RTF en XLSX en C++
description: API C++ pour convertir RTF en XLSX sans utiliser Microsoft Word ou Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSX
otherformats: TSV XLTX EXCEL SXC XLS ODS CSV XLTM XLT XLSB DIF XLSM FODS XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour convertir RTF en XLSX" h2="Exportez RTF vers XLSX via C++ sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez facilement inclure la fonction de conversion RTF en XLSX dans vos applications C++. En utilisant l'API de manipulation et de conversion de rtfuments riche en fonctionnalités, puissante et facile à utiliser [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter du RTF vers HTML. Après cela, en utilisant [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), vous pouvez convertir HTML en XLSX. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir RTF en XLSX" %}}
1. Ouvrez le fichier RTF à l'aide de la référence de classe [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
2. Convertir RTF en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string_saveformat)
3. Chargez le rtfument HTML à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le rtfument au format XLSX à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accéder aux propriétés du rtfument RTF via C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vous permet également d'accéder aux propriétés du rtfument du fichier RTF et vous permet de prendre une décision éclairée avant le processus de conversion. Pour accéder aux propriétés du rtfument, vous pouvez utiliser [BuiltInRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_rtfument_properties) pour obtenir les propriétés intégrées et [CustomRtfumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_rtfument_properties) pour obtenir des propriétés personnalisées. L'exemple de code suivant montre comment énumérer toutes les propriétés intégrées et personnalisées dans un rtfument.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-rtfument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le fichier XLSX dans le flux via C++" %}}
Après avoir converti RTF en XLSX, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) vous permet d'enregistrer votre rtfument pour le diffuser. Pour enregistrer des fichiers dans un flux, créez un objet MemoryStream ou FileStream et enregistrez le fichier dans cet objet de flux en appelant [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) de l'objet. Spécifiez le format de fichier souhaité à l'aide de l'énumération [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) lors de l'appel de l'énumération [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-tsv/" name="RTF À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xltx/" name="RTF À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-excel/" name="RTF À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-sxc/" name="RTF À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xls/" name="RTF À XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-ods/" name="RTF À ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xlsx/" name="RTF À XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xltm/" name="RTF À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xlt/" name="RTF À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xlsb/" name="RTF À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-dif/" name="RTF À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xlsm/" name="RTF À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-fods/" name="RTF À FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/rtf-to-xlam/" name="RTF À XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}