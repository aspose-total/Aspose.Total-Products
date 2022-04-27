---
title: API C# pour exporter TEX vers WORDML
description: Convertir TEX en WORDML sans utiliser Microsoft Word
url: /fr/net/conversion/tex-to-wordml/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: WORDML
otherformats: OTT FLATOPC DOTM XAMLFLOW WORDML PCL MARKDOWN RTF PS DOTX DOT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre TEX en WORDML via .NET" h2="API .NET pour exporter TEX vers WORDML sous Windows, macOS et Linux sans utiliser Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour .NET](https://products.aspose.com/total/net/) est une API puissante pour ajouter des fonctionnalités de manipulation et de conversion de documents dans votre application .NET. En utilisant l'API de traitement PDF avancée [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez convertir le format de fichier TEX en DOC. Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words pour .NET](https://products.aspose.com/words/net/), vous pouvez restituer DOC en WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir TEX en WORDML" %}}
1. Ouvrez le fichier TEX à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir TEX en Doc en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier Doc en utilisant la classe [Document](https://apireference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Enregistrez le document au format WORDML à l'aide de la méthode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Wordml comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WordML
outputDocument.Save("output.wordml", SaveFormat.WordML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Décrypter le fichier TEX en utilisant le mot de passe du propriétaire via .NET" %}}
Avant de convertir TEX en WORDML, si vous souhaitez décrypter votre document, vous pouvez le faire en utilisant l'API. Pour déchiffrer le fichier PDF, vous devez d'abord créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le TEX à l'aide du mot de passe du propriétaire. Après cela, vous devez appeler la méthode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) de l'objet Document. Enfin, enregistrez le fichier mis à jour à l'aide de la méthode Save de l'objet Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier WORDML en lecture seule via .NET" %}}
Afin de protéger votre WORDML contre la modification et d'empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document, vous pouvez également définir la protection du document à l'aide de l'API. Vous pouvez limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être fait à l'aide de l'API [Aspose.Words pour .NET](https://products.aspose.com/words/net/). Il vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-ott/" name="TEX Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-mhtml/" name="TEX Pour MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-wordml/" name="TEX Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-dot/" name="TEX Pour DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-odt/" name="TEX Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-rtf/" name="TEX Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-ps/" name="TEX Pour PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-flatopc/" name="TEX Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-pcl/" name="TEX Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-markdown/" name="TEX Pour MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-xamlflow/" name="TEX Pour XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/tex-to-dotx/" name="TEX Pour DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}