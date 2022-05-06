---
title: Convertir le format JSON en WORD via .NET
description: Analyser JSON en WORD en C# sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOC MOBI DOT ODT WORDML DOTX FLATOPC EPUB DOCM OTT PS RTF WORD PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en WORD via C#" h2="API C# pour analyser JSON vers WORD sans utiliser Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez analyser JSON en WORD dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. pas. Tout d'abord, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez exporter JSON au format PDF. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez convertir un PDF en WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en WORD via C#" %}}
1. Créez un nouvel objet [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) et lisez les données JSON valides du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) et [Save](https://apireference.aspose.com/ cells/net/aspose.cells.workbook/save/methods/4) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format WORD en utilisant la méthode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en WORD via C#" %}}
Lors de l'analyse de JSON vers WORD, vous pouvez également définir des options de mise en page pour votre JSON à l'aide de [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le format JSON en WORD avec filigrane" %}}
À l'aide de l'API, vous pouvez également convertir JSON en WORD avec filigrane. Afin d'ajouter un filigrane à votre document WORD, vous pouvez d'abord analyser le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://apireference.aspose.com/words/net/aspose.words/document), créez une instance de TextWatermarkOptions et définissez ses propriétés , Appelez la méthode Watermark.SetText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-ott/" name="JSON Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-flatopc/" name="JSON Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-ps/" name="JSON Pour PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dotx/" name="JSON Pour DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-rtf/" name="JSON Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-wordml/" name="JSON Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-odt/" name="JSON Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-word/" name="JSON Pour WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-epub/" name="JSON Pour EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-doc/" name="JSON Pour DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dot/" name="JSON Pour DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-pcl/" name="JSON Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-mobi/" name="JSON Pour MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-docm/" name="JSON Pour DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}