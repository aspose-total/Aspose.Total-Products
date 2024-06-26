---
title: Convertir le format JSON en POT via .NET
description: Analyser JSON en POT en C# sans utiliser Microsoft PowerPoint
url_ignore: /fr/net/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POTM PPT PPTM PPSM POT PPSX POWERPOINT OTP PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en POT via C#" h2="API C# pour analyser JSON vers POT sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir JSON en POT dans n'importe quelle application .NET, C#, ASP.NET et VB.NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez analyser JSON en PPTX. Après cela, en utilisant [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en POT. Les deux API relèvent du package [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en POT via C#" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) et lisez les données JSON valides du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) et [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) en tant que PPTX
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format POT en utilisant la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en POT via C#" %}}
Lors de l'analyse de JSON vers POT, vous pouvez également définir des options de mise en page pour votre format JSON à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Il vous permet de traiter le tableau comme un tableau, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le format JSON en POT avec filigrane" %}}
À l'aide de l'API, vous pouvez également convertir JSON en POT avec filigrane. Afin d'ajouter un filigrane à votre document POT, vous pouvez d'abord analyser JSON en PPTX et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PPTX nouvellement créé à l'aide de la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), sélectionnez la présentation principale, ajoutez le type de forme à l'aide de AddAutoShape et ajoutez du texte en filigrane à l'aide de AddTextFrame. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur POT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}