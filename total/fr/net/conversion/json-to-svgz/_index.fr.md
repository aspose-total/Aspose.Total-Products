---
title: Convertir le format JSON en SVGZ via .NET
description: Analyser JSON en SVGZ en C# sans utiliser de dépendances tierces
url_ignore: /fr/net/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE WMF DXF TGA SVGZ PSD WMZ DICOM JPEG2000 EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en SVGZ via C#" h2="API C# pour analyser JSON en SVGZ sans utiliser de dépendances tierces" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez analyser JSON en SVGZ dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. pas. Tout d'abord, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez exporter JSON vers JPEG. Après cela, en utilisant [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), vous pouvez convertir JPEG en SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en SVGZ via C#" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) et lisez les données JSON à partir du fichier
2. Convertissez JSON en JPEG à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Chargez le document JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Enregistrez le document au format SVGZ en utilisant la méthode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en SVGZ via C#" %}}
Lors de l'analyse de JSON vers SVGZ, vous pouvez également définir des options de mise en page pour votre JSON à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le format JSON en SVGZ avec filigrane" %}}
À l'aide de l'API, vous pouvez également convertir JSON en SVGZ avec filigrane dans votre document SVGZ. Pour ajouter un filigrane, vous pouvez d'abord rendre votre document JSON au format JPEG et y ajouter un filigrane. Pour illustrer l'opération, vous pouvez charger votre image JPEG convertie, ajouter des transformations à l'aide d'un objet de la classe Matrix et dessiner une chaîne comme filigrane sur la surface de l'image à l'aide de [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Après y avoir ajouté le filigrane, vous pouvez enregistrer le JPEG au format SVGZ. Vous trouverez ci-dessous un exemple de code qui montre comment ajouter un filigrane diagonal à votre document. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}