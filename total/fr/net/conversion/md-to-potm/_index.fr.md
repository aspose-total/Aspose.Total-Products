---
title: Exporter MD vers POTM via l'API C#
description: API .NET pour convertir MD en POTM sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/md-to-potm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POTM
otherformats: POTX PPTM PPSM PPS POWERPOINT POTM PPT PPSX SWF XAML OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre MD vers POTM via .NET" h2="API .NET pour exporter MD vers POTM sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir MD en POTM en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier MD en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en POTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir MD en POTM" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir MD en PPTX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format POTM à l'aide de la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Potm` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier MD via .NET" %}}
Lors de la conversion de MD en POTM, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier MD. Pour obtenir les métadonnées d'un fichier MD, vous pouvez créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier MD d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier POTM en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier POTM sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier MD en POTM par programmation : cas d'utilisation" %}}
**Utilisations:**

*   **Analyse du calendrier de projet et des étapes à suivre** : Convertir des fichiers MD pour analyser les calendriers de projet, suivre les étapes à suivre et identifier les obstacles potentiels.
*   **Génération d'actes de réunion et de minutes** : Utiliser les fichiers POTM pour créer des notes de réunion structurées, générer des actes de réunion et faciliter la collaboration entre les membres du équipe.
*   **Développement de plans commerciaux et stratégies d'entreprise** : Convertir des fichiers MD pour créer des plans commerciaux, développer des stratégies et définir les actions à suivre pour les acteurs.

*   **Publication des articles de recherche et des rapports** : Utiliser les fichiers POTM pour formatter les articles de recherche, les rapports et les articles avec des formats d'impression professionnels et des citations.
*   **Vérification et approbation des notes de réunion** : Convertir des fichiers MD pour vérifier et approbner les notes de réunion, assurant leur exactitude et leur complet avant de les partager avec les membres de l'équipe ou les acteurs.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}