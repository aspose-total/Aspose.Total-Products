---
title: API C# pour exporter CGM vers OTT
description: Convertir CGM en OTT sans utiliser Microsoft Word
url_ignore: /fr/net/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: OTT XAMLFLOW FLATOPC DOTX MHTML ODT DOTM PS WORDML RTF MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre CGM en OTT via .NET" h2="API .NET pour exporter CGM vers OTT sous Windows, macOS et Linux sans utiliser Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) est une API puissante pour ajouter des fonctionnalités de manipulation et de conversion de documents dans votre application .NET. En utilisant l'API de traitement PDF avancée [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez convertir le format de fichier CGM en DOC. Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer DOC en OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir CGM en OTT" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir CGM en Doc en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier Doc en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Enregistrez le document au format OTT à l'aide de la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Ott comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Décrypter le fichier CGM en utilisant le mot de passe du propriétaire via .NET" %}}
Avant de convertir CGM en OTT, si vous souhaitez décrypter votre document, vous pouvez le faire en utilisant l'API. Pour déchiffrer le fichier PDF, vous devez d'abord créer un objet [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le CGM à l'aide du mot de passe du propriétaire. Après cela, vous devez appeler la méthode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) de l'objet Document. Enfin, enregistrez le fichier mis à jour à l'aide de la méthode Save de l'objet Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier OTT en lecture seule via .NET" %}}
Afin de protéger votre OTT contre la modification et d'empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document, vous pouvez également définir la protection du document à l'aide de l'API. Vous pouvez limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être fait à l'aide de l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Il vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en OTT par programmation : cas d'utilisation" %}}
La conversion des fichiers CGM (Metafile de Graphe Computer) vers les formats OTT (OpenType Text) est nécessaire pour déverrouiller pleinement vos capacités de visualisation et d'analyse de données texte basées. Cette conversion vous permet:

**Utilisations:**

*   **Conception de typographie**: Convertir des fichiers CGM pour créer des logotypes scalables, garantissant une typographie nette et claire sur divers médias.
*   **Analyse de typographie**: Utiliser les formats OTT pour analyser les caractéristiques de la typographie, suivre les modèles d'utilisation et identifier les tendances en matière de typographie.
*   **Développement d'une identité de marque et d'entreprise**: Convertir des fichiers CGM pour concevoir une identité cohérente de marque, comprenant des logos, des typographies et des couleurs.
*   **Conception imprimée et édition**: Convertir des fichiers CGM pour créer des matériaux impressionnés professionnels, tels que les brochures, les affiches et les pôsters.
*   **Rapports et dashboard interactifs**: Convertir des fichiers CGM pour créer des dashboard interactifs, des rapports et des visualisations visuelles pour les parties prenantes, permettant une meilleure prise de décision.

En convertissant les fichiers CGM en formats OTT, vous pouvez déverrouiller pleinement vos capacités de visualisation et d'analyse de données texte basées.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}