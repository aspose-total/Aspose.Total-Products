---
title: Exporter PS vers PPT via l'API C#
description: API .NET pour convertir PS en PPT sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/ps-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPT
otherformats: PPT POTX XAML PPS SWF POTM POWERPOINT PPSX PPTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre PS vers PPT via .NET" h2="API .NET pour exporter PS vers PPT sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir PS en PPT en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier PS en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir PS en PPT" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir PS en PPTX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format PPT à l'aide de la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Ppt` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier PS via .NET" %}}
Lors de la conversion de PS en PPT, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier PS. Pour obtenir les métadonnées d'un fichier PS, vous pouvez créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier PS d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier PPT en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier PPT sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier PS en PPT par programmation : cas d'utilisation" %}}
Les fichiers de format Portable Document (PS) sont utilisés pour stocker des informations sur la disposition, ce qui les rend idéaux pour créer des documents statiques tels que des présentations, des rapports et des brochures. Cependant, lorsque l'on travaille avec du contenu multimédia dynamique, les présentations de PowerPoint deviennent essentielles pour la visualisation et l'interaction.

La conversion des fichiers PS en formats de PowerPoint est nécessaire pour débloquer la pleine capacité de vos capacités de création de présentation. Cette conversion permet :

Utilisations :


*   **Conception et développement de presentation** : Convertir les fichiers PS pour créer des présentations interactives et engageantes, incorporant du texte, des images, des vidéos et des animations.
*   **Optimisation de la slide deck** : Utiliser PowerPoint pour améliorer les slides, ajuster les layouts et optimiser les éléments visuels pour une expérience de présentation polishie.
*   **Gestion de contenu et mise à jour** : Convertir les fichiers PS pour gérer et mettre à jour le contenu facilement sur plusieurs appareils et plateformes, assurant la cohérence et l'exactitude.
*   **Histoire interactive** : Utiliser PowerPoint pour créer des présentations immersives qui combinent du texte, des images, de l'audio et du vidéo pour transmettre des informations complexes d'une manière engageante.
*   **Collaboration et revue** : Convertir les fichiers PS pour faciliter le travail collaboratif et les commentaires en temps réel parmi les membres d'équipe ou les parties prenantes grâce à la partage et au commentaire en ligne.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}