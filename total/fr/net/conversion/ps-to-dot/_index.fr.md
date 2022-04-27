---
title: API C# pour exporter PS vers DOT
description: Convertir PS en DOT sans utiliser Microsoft Word
url: /fr/net/conversion/ps-to-dot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DOT
otherformats: RTF FLATOPC ODT MHTML MARKDOWN DOT WORDML XAMLFLOW PCL DOTM OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre PS en DOT via .NET" h2="API .NET pour exporter PS vers DOT sous Windows, macOS et Linux sans utiliser Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour .NET](https://products.aspose.com/total/net/) est une API puissante pour ajouter des fonctionnalités de manipulation et de conversion de documents dans votre application .NET. En utilisant l'API de traitement PDF avancée [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez convertir le format de fichier PS en DOC. Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words pour .NET](https://products.aspose.com/words/net/), vous pouvez restituer DOC en DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir PS en DOT" %}}
1. Ouvrez le fichier PS à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir PS en Doc en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier Doc en utilisant la classe [Document](https://apireference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Enregistrez le document au format DOT à l'aide de la méthode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Dot comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Décrypter le fichier PS en utilisant le mot de passe du propriétaire via .NET" %}}
Avant de convertir PS en DOT, si vous souhaitez décrypter votre document, vous pouvez le faire en utilisant l'API. Pour déchiffrer le fichier PDF, vous devez d'abord créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le PS à l'aide du mot de passe du propriétaire. Après cela, vous devez appeler la méthode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) de l'objet Document. Enfin, enregistrez le fichier mis à jour à l'aide de la méthode Save de l'objet Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier DOT en lecture seule via .NET" %}}
Afin de protéger votre DOT contre la modification et d'empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document, vous pouvez également définir la protection du document à l'aide de l'API. Vous pouvez limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être fait à l'aide de l'API [Aspose.Words pour .NET](https://products.aspose.com/words/net/). Il vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-ott/" name="PS Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-mhtml/" name="PS Pour MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-wordml/" name="PS Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-dot/" name="PS Pour DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-odt/" name="PS Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-rtf/" name="PS Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-ps/" name="PS Pour PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-flatopc/" name="PS Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-pcl/" name="PS Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-markdown/" name="PS Pour MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-xamlflow/" name="PS Pour XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ps-to-dotx/" name="PS Pour DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}