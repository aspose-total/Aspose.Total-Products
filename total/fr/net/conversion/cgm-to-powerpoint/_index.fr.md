---
title: Exporter CGM vers POWERPOINT via l'API C#
description: API .NET pour convertir CGM en POWERPOINT sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: OTP PPSM PPS XAML PPSX PPT POTX PPTM POWERPOINT POT POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre CGM vers POWERPOINT via .NET" h2="API .NET pour exporter CGM vers POWERPOINT sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir CGM en POWERPOINT en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier CGM en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir CGM en POWERPOINT" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir CGM en PPTX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format POWERPOINT à l'aide de la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Powerpoint` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier CGM via .NET" %}}
Lors de la conversion de CGM en POWERPOINT, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier CGM. Pour obtenir les métadonnées d'un fichier CGM, vous pouvez créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier CGM d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier POWERPOINT en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier POWERPOINT sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en POWERPOINT par programmation : cas d'utilisation" %}}
Les fichiers CGM (Metafile de graphiques informatiques) sont utilisés pour stocker les informations de graphismes vectoriels, ce qui en fait idéaux pour créer des graphiques statiques et des illustrations.

Cependant, lorsqu'on travaille avec des données dynamiques, des présentations comme PowerPoint deviennent essentielles pour présenter des visualisations engageantes et des histoires.

La conversion de fichiers CGM vers les formats de PowerPoint est nécessaire pour débloquer la pleine potentialité de vos capacités de presentation. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Presentations corporatives** : Convertir les fichiers CGM pour créer des présentations engageantes, présenter des données complexes et partager les résultats avec les parties prenantes.
*   **Développement de matériel de formation** : Utiliser PowerPoint pour visualiser le contenu de formation, simuler des scénarios réels et fournir des expériences d'apprentissage interactives.
*   **Création de matériaux de marketing** : Convertir les fichiers CGM pour concevoir des matériaux de marketing visuellement attractifs, tels que des brochures, des flyers et des affiches, qui captent l'attention et stimulent l'engagement.
*   **Presentations scientifiques** : Utiliser PowerPoint pour créer des présentations interactives, visualiser des données complexes et communiquer les résultats de recherche efficacement.
*   **Développement de cours en ligne immersifs** : Convertir les fichiers CGM pour créer des cours en ligne immersifs, utiliser des animations et des interactions, et améliorer l'engagement du student.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}