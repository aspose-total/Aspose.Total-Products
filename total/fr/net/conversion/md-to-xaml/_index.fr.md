---
title: Exporter MD vers XAML via l'API C#
description: API .NET pour convertir MD en XAML sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/md-to-xaml/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: XAML
otherformats: PPSX POTM OTP POT PPSM POWERPOINT PPS POTX PPT XAML PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre MD vers XAML via .NET" h2="API .NET pour exporter MD vers XAML sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir MD en XAML en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier MD en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir MD en XAML" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir MD en PPTX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format XAML à l'aide de la méthode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Xaml` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier MD via .NET" %}}
Lors de la conversion de MD en XAML, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier MD. Pour obtenir les métadonnées d'un fichier MD, vous pouvez créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier MD d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier XAML en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier XAML sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier MD en XAML par programmation : cas d'utilisation" %}}
**Convertir les fichiers Markdown en XAML : Découvrez la puissance complète de votre interface utilisateur**

Les fichiers Markdown (MD) sont devenus un outil essentiel pour les créateurs de contenu, les développeurs et les designers. Cependant, lorsqu'il s'agit de construire des interfaces d'utilisation (UI), le format XAML (Langage de marcage extensible d'application) est préféré.

Convertir les fichiers Markdown en XAML vous permet :

**Cas d'utilisation :**

*   **Conception d'interface utilisateur** : Convertissez les fichiers Markdown pour créer des composants UI visuellement attrayants et interactifs, tels que les boutons, les étiquettes et les cases à cocher.
*   **Développement d'applications mobiles** : Utilisez XAML pour concevoir et développer des applications mobiles qui s'adaptent facilement aux différentes tailles écrans et orientaisons.
*   **Développement d'applications bureautiques** : Convertissez les fichiers Markdown pour créer des applications bureautiques personnalisées avec des éléments UI, des emplacements et des animations personnalisés.
*   **Développement d'applications web** : Utilisez XAML pour construire des applications web avec des composants UI riches, tels que les tableaux de données, les cartes et les cartes.
*   **Optimisation de l'accessibilité** : Convertissez les fichiers Markdown pour garantir que votre UI est accessible aux utilisateurs handicapés en implémentant les attributs ARIA et la navigation clavier.

En convertissant les fichiers Markdown en XAML, vous pouvez découvrir pleinement la puissance de vos capacités de conception d'interface utilisateur et créer des expériences interactives et étincelantes pour vos utilisateurs."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}