---
title: Convertir le format JSON en ODT via .NET
description: Analyser JSON en ODT en C# sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: DOTX WORD DOT RTF DOC DOCM MOBI OTT WORDML PCL ODT PS FLATOPC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en ODT via C#" h2="API C# pour analyser JSON vers ODT sans utiliser Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez analyser JSON en ODT dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. pas. Tout d'abord, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez exporter JSON au format PDF. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez convertir un PDF en ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en ODT via C#" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) et lisez les données JSON valides du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) et [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format ODT en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en ODT via C#" %}}
Lors de l'analyse de JSON vers ODT, vous pouvez également définir des options de mise en page pour votre JSON à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le format JSON en ODT avec filigrane" %}}
À l'aide de l'API, vous pouvez également convertir JSON en ODT avec filigrane. Afin d'ajouter un filigrane à votre document ODT, vous pouvez d'abord analyser le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/net/aspose.words/document), créez une instance de TextWatermarkOptions et définissez ses propriétés, Appelez la méthode Watermark.SetText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}