---
title: Convertir TEX en FODS via l'API C#
description: API C# pour convertir un fichier TEX en FODS sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/net/conversion/tex-to-fods/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: FODS
otherformats: XLSM SXC TSV ODS EXCEL FODS TXT XLT XLTX MD XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# pour rendre TEX en FODS" h2="Exporter le fichier TEX au format FODS via C# sans utiliser Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir un fichier TEX en FODS dans n'importe quelle application .NET, C#, ASP.NET et VB.NET. Tout d'abord, en utilisant [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez exporter TEX vers XLSX. Après cela, en utilisant l'API de programmation de feuille de calcul [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez convertir XLSX en FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir TEX en FODS" %}}
1. Ouvrez le fichier TEX à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir TEX en XLSX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le document XLSX en utilisant la classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Enregistrez le document au format FODS à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) et définissez `Fods` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir TEX protégé en FODS via C#" %}}
Si votre document TEX est protégé par un mot de passe, vous ne pouvez pas le convertir en FODS sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Pour ouvrir le fichier chiffré, vous pouvez initialiser une nouvelle instance de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et transmettre le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir un fichier TEX en FODS avec filigrane via C#" %}}
Lors de la conversion du fichier TEX en FODS, vous pouvez également ajouter un filigrane au format de votre fichier FODS de sortie. Pour ajouter un filigrane, vous pouvez créer un nouvel objet Workbook et ouvrir le document XLSX converti, sélectionner Worksheet via son index, créer une Shape et utiliser sa fonction AddTextEffect. Après cela, vous pouvez enregistrer votre document XLSX au format FODS avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}