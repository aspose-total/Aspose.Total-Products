---
title: API C++ pour convertir PS en FODS
description: Convertissez PS en FODS via l'API C++ sans utiliser Microsoft Excel ou Adobe Reader
url: /fr/cpp/conversion/ps-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: FODS
otherformats: TSV XLTM XLSM MD SXC XLSB DIF XLAM XLT XLTX EXCEL ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu PS au format FODS dans les applications C++" h2="Convertissez PS en FODS dans des applications C++ natives sans nécessiter Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
La conversion de PS en FODS en C++ via les bibliothèques d'automatisation de format de fichier [Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un processus simple en deux étapes. Dans un premier temps, vous pouvez exporter PS vers XLSX en utilisant [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), puis en utilisant [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) API de programmation de feuille de calcul, vous pouvez convertir XLSX en FODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PS en FODS" %}}
1. Ouvrez le fichier PS à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convertissez PS en XLSX en utilisant la fonction membre [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Chargez le document XLSX à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le document au format FODS à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir ou définir les informations du fichier PS via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) vous permet également d'obtenir des informations sur votre document PS et vous permet de prendre des décisions éclairées avant votre processus de conversion. Afin d'obtenir des informations spécifiques sur un fichier PS, vous devez d'abord appeler la méthode [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) classe. Une fois l'objet DocumentInfo récupéré, vous pouvez obtenir les valeurs des propriétés individuelles. De plus, vous pouvez également définir les propriétés en utilisant les méthodes respectives de la classe DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le format de fichier FODS dans le flux via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permet d'enregistrer le format de fichier FODS en streaming. Pour enregistrer des fichiers dans un flux, créez un objet MemoryStream ou FileStream et enregistrez le fichier dans cet objet de flux en appelant [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) de l'objet. Spécifiez le format de fichier souhaité à l'aide de l'énumération [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) lors de l'appel de la méthode Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-fods-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-tsv/" name="PS À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xltm/" name="PS À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xlsm/" name="PS À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-md/" name="PS À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-sxc/" name="PS À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xlsb/" name="PS À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-dif/" name="PS À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xlam/" name="PS À XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xlt/" name="PS À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-xltx/" name="PS À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-excel/" name="PS À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/ps-to-ods/" name="PS À ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}