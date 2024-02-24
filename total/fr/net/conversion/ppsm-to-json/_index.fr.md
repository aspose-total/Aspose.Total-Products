---
title: Convertir PPSM au format JSON via .NET
description: Convertir PPSM en JSON en C# sans utiliser Microsoft Excel ou Powerpoint
url_ignore: /fr/net/conversion/ppsm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir PPSM au format JSON via C#" h2="Exportez PPSM vers JSON via C# sans utiliser Microsoft<sup>&reg;</sup> Excel ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez convertir PPSM au format JSON dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez exporter PPSM vers HTML. Après cela, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir PPSM au format JSON via C#" %}}
1. Ouvrez le fichier PPSM à l'aide de la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Convertissez PPSM en HTML en utilisant la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Chargez le document HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Enregistrez le document au format JSON à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir l'PPSM protégé au format JSON via C#" %}}
À l'aide de l'API, vous pouvez également ouvrir le document protégé par mot de passe. Si votre document PPSM d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le document chiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment ouvrir un document chiffré avec un mot de passe.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PPSM en JSON dans Range via C#" %}}
Pendant que vous convertissez PPSM en JSON, vous pouvez également définir la plage de votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, obtenir CellsCollection de la feuille de calcul contenant les données, créer une plage à partir de CellsCollection en spécifiant les indices de ligne et de colonne et appeler la méthode ExportRangeToJson avec des références aux objets Range & ExportRangeToJsonOptions. Enfin, vous pouvez enregistrer les données JSON dans un fichier via la méthode File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}