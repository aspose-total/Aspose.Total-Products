---
title: Convertir le format DOCX au format JSON via .NET
description: Convertir DOCX en JSON en C# sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOCX au format JSON via C#" h2="Analyser DOCX en JSON via C# sans utiliser Microsoft<sup>&reg;</sup> Word ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez convertir le format DOCX au format JSON dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez exporter DOCX vers HTML. Après cela, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOCX au format JSON via C#" %}}
1. Ouvrez le fichier DOCX à l'aide de la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Convertir DOCX en HTML en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Chargez le document HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Enregistrez le document au format JSON à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le DOCX protégé au format JSON via C#" %}}
À l'aide de l'API, vous pouvez également ouvrir le document protégé par mot de passe. Si votre document DOCX d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le document chiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment essayer d'ouvrir un document chiffré avec un mot de passe :  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir DOCX en JSON dans Range via C#" %}}
Pendant que vous convertissez DOCX en JSON, vous pouvez également définir la plage sur votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, obtenir CellsCollection de la feuille de calcul contenant les données, créer une plage à partir de CellsCollection en spécifiant les indices de ligne et de colonne et appeler la méthode ExportRangeToJson avec des références aux objets Range & ExportRangeToJsonOptions. Enfin, vous pouvez enregistrer les données JSON dans un fichier via la méthode File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-csv/" name="DOCX Pour CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlam/" name="DOCX Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-sxc/" name="DOCX Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-tsv/" name="DOCX Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlt/" name="DOCX Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-excel/" name="DOCX Pour EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-dif/" name="DOCX Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsm/" name="DOCX Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xltm/" name="DOCX Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsx/" name="DOCX Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsb/" name="DOCX Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-fods/" name="DOCX Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-ods/" name="DOCX Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xltx/" name="DOCX Pour XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}