---
title: Exporter PS vers PPS via l'API C#
description: API .NET pour convertir PS en PPS sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/ps-to-pps/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPS
otherformats: XAML POTX PPS PPTM PPT PPSX POT OTP POTM PPSM POWERPOINT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre PS vers PPS via .NET" h2="API .NET pour exporter PS vers PPS sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir PS en PPS en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier PS en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir PS en PPS" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir PS en PPTX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format PPS à l'aide de la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Pps` comme SaveFormat
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
Lors de la conversion de PS en PPS, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier PS. Pour obtenir les métadonnées d'un fichier PS, vous pouvez créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier PS d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier PPS en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier PPS sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier PS en PPS par programmation : cas d'utilisation" %}}
Les fichiers de format Portable Document (PS) sont utilisés pour stocker des informations graphiques statiques, les rendant idéaux pour la création d'arrangements et de conceptions. Cependant, lorsqu'on travaille avec des données dynamiques, les présentations comme PowerPoint deviennent essentielles pour la visualisation et l'analyse.

La conversion des fichiers PS en formats PPS (Présentation PowerPoint) est nécessaire pour débloquer pleinement vos capacités de présentation. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Conception de Présentations :** Convertir les fichiers PS pour créer des présentations engageantes, en ajoutant des animations, des transitions et des éléments multimédia.
*   **Matériel de Formation et d'Éducation :** Utiliser PPS pour développer des séances de formation interactives, des simulations et des tutoriels pour les parties prenantes, améliorant la retenue du savoir et l'engagement.
*   **Propositions commerciales et Présentations :** Convertir les fichiers PS pour créer des propositions commerciales persuasives et des présentations qui mettent en valeur les produits, services ou idées, facilitant une meilleure communication avec les clients ou investisseurs.
*   **Matériaux de Campagne de Marche :** Utiliser PPS pour développer des matériaux de campagne comme des prospectus, des affiches et des posters, promouvant les produits ou services à travers un contenu visuellement appétissant.
*   **Visualisation de Données et Ré telling :** Convertir les fichiers PS pour créer des histoires interactives, des visualisations de données et des rapports qui aident à transmettre des informations complexes d'une manière engageante.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}