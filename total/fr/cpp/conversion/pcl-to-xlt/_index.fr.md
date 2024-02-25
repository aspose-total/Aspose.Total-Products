---
title: API C++ pour convertir PCL en XLT
description: Convertissez PCL en XLT via l'API C++ sans utiliser Microsoft Excel ou Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: XLT
otherformats: CSV SXC TSV MD XLSM EXCEL XLTX XLAM ODS XLSB TXT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu PCL au format XLT dans les applications C++" h2="Convertissez PCL en XLT dans des applications C++ natives sans nécessiter Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
La conversion de PCL en XLT en C++ via les bibliothèques d'automatisation de format de fichier [Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un processus simple en deux étapes. Dans un premier temps, vous pouvez exporter PCL vers XLSX en utilisant [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), puis en utilisant [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API de programmation de feuille de calcul, vous pouvez convertir XLSX en XLT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PCL en XLT" %}}
1. Ouvrez le fichier PCL à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convertissez PCL en XLSX en utilisant la fonction membre [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Chargez le document XLSX à l'aide de la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Enregistrez le document au format XLT à l'aide de la fonction membre [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir ou définir les informations du fichier PCL via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) vous permet également d'obtenir des informations sur votre document PCL et vous permet de prendre des décisions éclairées avant votre processus de conversion. Afin d'obtenir des informations spécifiques sur un fichier PCL, vous devez d'abord appeler la méthode [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) classe. Une fois l'objet DocumentInfo récupéré, vous pouvez obtenir les valeurs des propriétés individuelles. De plus, vous pouvez également définir les propriétés en utilisant les méthodes respectives de la classe DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le format de fichier XLT dans le flux via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permet d'enregistrer le format de fichier XLT en streaming. Pour enregistrer des fichiers dans un flux, créez un objet MemoryStream ou FileStream et enregistrez le fichier dans cet objet de flux en appelant [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) de l'objet. Spécifiez le format de fichier souhaité à l'aide de l'énumération [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) lors de l'appel de la méthode Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlt-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}