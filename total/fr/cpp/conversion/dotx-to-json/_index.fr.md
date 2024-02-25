---
title: Convertir le format DOTX au format JSON en C++
description: Exporter DOTX vers JSON en C++ sans utiliser Microsoft Excel ou Word

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir DOTX au format JSON via C++" h2="Exportez DOTX vers JSON via C++ sans utiliser Microsoft<sup>&reg;</sup> Word ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for C++](https://products.aspose.com/total/cpp/), vous pouvez convertir le format DOTX au format JSON dans vos applications C++. Tout d'abord, en utilisant [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter DOTX vers HTML. Après cela, en utilisant [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), vous pouvez convertir le HTML au format JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOTX au format JSON via C++" %}}
1. Ouvrez le fichier DOTX à l'aide de la référence de classe [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Convertir DOTX en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string_saveformat)
3. Chargez le dotxument HTML à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le dotxument au format JSON à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le DOTX protégé au format JSON via C++" %}}
À l'aide de l'API, vous pouvez également ouvrir le dotxument protégé par mot de passe. Si votre dotxument DOTX d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. Pour ce faire, utilisez une surcharge de constructeur spéciale, qui accepte un objet LoadOptions. Cet objet contient la propriété Password, qui spécifie la chaîne de mot de passe.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}