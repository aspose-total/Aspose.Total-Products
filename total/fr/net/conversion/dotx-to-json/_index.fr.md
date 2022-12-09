---
title: Convertir le format DOTX au format JSON via .NET
description: Convertir DOTX en JSON en C# sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/net/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOTX au format JSON via C#" h2="Analyser DOTX en JSON via C# sans utiliser Microsoft<sup>&reg;</sup> Word ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez convertir le format DOTX au format JSON dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez exporter DOTX vers HTML. Après cela, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOTX au format JSON via C#" %}}
1. Ouvrez le fichier DOTX à l'aide de la classe [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. Convertir DOTX en HTML en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Chargez le Document HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Enregistrez le Document au format JSON à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le DOTX protégé au format JSON via C#" %}}
À l'aide de l'API, vous pouvez également ouvrir le Document protégé par mot de passe. Si votre Document DOTX d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le Document chiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment essayer d'ouvrir un Document chiffré avec un mot de passe :  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir DOTX en JSON dans Range via C#" %}}
Pendant que vous convertissez DOTX en JSON, vous pouvez également définir la plage sur votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, obtenir CellsCollection de la feuille de calcul contenant les données, créer une plage à partir de CellsCollection en spécifiant les indices de ligne et de colonne et appeler la méthode ExportRangeToJson avec des références aux objets Range & ExportRangeToJsonOptions. Enfin, vous pouvez enregistrer les données JSON dans un fichier via la méthode File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-csv/" name="DOTX Pour CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xlam/" name="DOTX Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-sxc/" name="DOTX Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-tsv/" name="DOTX Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xlt/" name="DOTX Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-excel/" name="DOTX Pour EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-dif/" name="DOTX Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xlsm/" name="DOTX Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xltm/" name="DOTX Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xlsx/" name="DOTX Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xlsb/" name="DOTX Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-fods/" name="DOTX Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-ods/" name="DOTX Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dotx-to-xltx/" name="DOTX Pour XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}