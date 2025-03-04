---
title: API C# pour exporter CGM vers DOTM
description: Convertir CGM en DOTM sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/cgm-to-dotm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTM
otherformats: DOTX ODT DOTM PS MARKDOWN XAMLFLOW WORDML PCL FLATOPC RTF MHTML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre CGM en DOTM via .NET" h2="API .NET pour exporter CGM vers DOTM sous Windows, macOS et Linux sans utiliser Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) est une API puissante pour ajouter des fonctionnalités de manipulation et de conversion de documents dans votre application .NET. En utilisant l'API de traitement PDF avancée [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez convertir le format de fichier CGM en DOC. Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer DOC en DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir CGM en DOTM" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir CGM en Doc en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier Doc en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Enregistrez le document au format DOTM à l'aide de la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Dotm comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Décrypter le fichier CGM en utilisant le mot de passe du propriétaire via .NET" %}}
Avant de convertir CGM en DOTM, si vous souhaitez décrypter votre document, vous pouvez le faire en utilisant l'API. Pour déchiffrer le fichier PDF, vous devez d'abord créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le CGM à l'aide du mot de passe du propriétaire. Après cela, vous devez appeler la méthode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) de l'objet Document. Enfin, enregistrez le fichier mis à jour à l'aide de la méthode Save de l'objet Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier DOTM en lecture seule via .NET" %}}
Afin de protéger votre DOTM contre la modification et d'empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document, vous pouvez également définir la protection du document à l'aide de l'API. Vous pouvez limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être fait à l'aide de l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Il vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en DOTM par programmation : cas d'utilisation" %}}
La conversion des fichiers CGM (Metafile de Graphiques informatiques) en formats DOTM (Modèles de template Microsoft Office) est nécessaire pour débloquer pleinement vos capacités de visualisation et d'analyse de données. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Développement de modèles** : Convertir des fichiers CGM en création de modèles personnalisés pour les applications Office Microsoft, telles que Excel, Word ou PowerPoint.
*   **Modélisation du processus d'affaires** : Utiliser DOTM pour visualiser les processus d'affaires, créer des flux de travail et modeler les structures organisationnelles.
*   **Présentations basées sur les données** : Convertir des fichiers CGM en création de présentations interactives avec des graphiques dynamiques et des animations, engageant votre audience et transmettant efficacement des informations complexes.
*   **Collaboration de recherche scientifique** : Utiliser DOTM pour partager les résultats de la recherche, collaborer sur des projets et visualiser les données scientifiques, accélérant ainsi le processus de découverte.
*   **Rapports d'intelligence d'affaires** : Convertir des fichiers CGM en création de panneaux interactifs, des rapports et des visualisations pour les parties prenantes, permettant une meilleure prise de décision et des stratégies commerciales éclairées.

En convertissant vos fichiers CGM en formats DOTM, vous pouvez débloquer pleinement les capacités Microsoft Office et prendre avantage de puissantes capacités de visualisation et d'analyse de données.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}