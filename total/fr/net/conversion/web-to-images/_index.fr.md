---
title: Convertir des pages Web HTML en images à l'aide de C#
description: Grattez les pages Web du site Web et exportez le code HTML vers des images. Développez des applications .NET pour récupérer les données du site Web en JPEG, PNG, GIF, BMP, etc. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir des pages Web en images via C#" h2="Extraire les données du site Web des pages Web HTML. Convertissez HTML en images JPG, GIF, PNG, BMP dans les applications .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Pourquoi convertir des pages Web en images ?</h2>
<p>La conversion de pages Web en images peut être utile dans diverses situations. C'est une exigence courante pour de nombreuses applications. Dans certains scénarios, il est nécessaire de capturer la totalité de la page Web sous forme d'image, y compris les parties qui ne sont pas visibles à l'écran. Cela peut être utile pour générer des aperçus de sites Web, capturer des reçus et des factures ou archiver des pages Web à des fins juridiques. Il peut être utilisé pour créer des captures d'écran de pages Web à des fins de documentation ou de test. Il peut également être utilisé pour créer des vignettes ou des aperçus de pages Web à utiliser dans les résultats de recherche ou les galeries d'images. Que vous construisiez une application de bureau ou une application Web, de nombreuses options sont disponibles pour convertir des pages Web en images à l'aide de C#.</p><br />

<p>La conversion de pages Web en images à l'aide de C# peut offrir plusieurs avantages, notamment :</p><br />
<ul>
<li>Accessibilité améliorée : Les images peuvent être plus faciles à lire et à comprendre pour les personnes ayant une déficience visuelle ou d'autres handicaps.</li>
<li>Portabilité accrue : Les images peuvent être facilement partagées ou intégrées dans d'autres documents ou applications.</li>
</ul>
<p>La conversion de pages Web en images à l'aide de C# peut également présenter certains défis, notamment :</p><br />
<ul>
<li>Prise en charge de formats limités : Certaines API ou certains outils peuvent ne pas prendre en charge tous les formats d'image ou peuvent avoir des limitations sur la taille ou la résolution des images de sortie.</li>
<li>Problèmes de compatibilité: Certaines pages Web peuvent ne pas s'afficher correctement dans tous les navigateurs ou peuvent nécessiter des paramètres ou des plug-ins spécifiques pour s'afficher correctement.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir des pages Web en images à l'aide de C# ?" %}}
Pour convertir des pages Web en images à l'aide de C#, vous pouvez utiliser une API Aspose.HTML pour .NET qui fournit cette fonctionnalité pour convertir des pages HTML en formats d'image, notamment JPEG, PNG et TIFF.</p>

1. Charger un document HTML en utilisant l'un des constructeurs disponibles dans [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Vous pouvez charger du HTML à partir d'un fichier, d'un code HTML, d'un flux ou d'une URL.
2. Créer une nouvelle instance de [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) et définissez la propriété ImageFormat sur JPEG. Par défaut, la propriété Format est définie sur PNG.
3. Utiliser le [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) de la classe Converter pour enregistrer le document HTML en tant que fichier JPEG. Vous devrez fournir HTMLDocument, ImageSaveOptions et le chemin du fichier de sortie en tant que paramètres de la méthode ConvertHTML().
4. Le fichier JPEG résultant sera enregistré dans le chemin de fichier spécifié.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences relatives à la mise au rebut Web et à la conversion d'images" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou installez directement à partir de la console du gestionnaire de packages de Visual Studio.

Deux [Aspose.Total for .NET](https://products.aspose.com/total/net/) API enfant, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) seront intégrés.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}