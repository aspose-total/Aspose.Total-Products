---
title: API C# pour exporter MD vers ODT
description: Convertir MD en ODT sans utiliser Microsoft Word
url: /fr/net/conversion/md-to-odt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODT
otherformats: ODT PS XAMLFLOW DOTM MHTML DOT OTT DOTX WORDML MARKDOWN PCL RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre MD en ODT via .NET" h2="API .NET pour exporter MD vers ODT sous Windows, macOS et Linux sans utiliser Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour .NET](https://products.aspose.com/total/net/) est une API puissante pour ajouter des fonctionnalités de manipulation et de conversion de documents dans votre application .NET. En utilisant l'API de traitement PDF avancée [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez convertir le format de fichier MD en DOC. Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words pour .NET](https://products.aspose.com/words/net/), vous pouvez restituer DOC en ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir MD en ODT" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir MD en Doc en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier Doc en utilisant la classe [Document](https://apireference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Enregistrez le document au format ODT à l'aide de la méthode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Odt comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.odt", SaveFormat.Odt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Décrypter le fichier MD en utilisant le mot de passe du propriétaire via .NET" %}}
Avant de convertir MD en ODT, si vous souhaitez décrypter votre document, vous pouvez le faire en utilisant l'API. Pour déchiffrer le fichier PDF, vous devez d'abord créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le MD à l'aide du mot de passe du propriétaire. Après cela, vous devez appeler la méthode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) de l'objet Document. Enfin, enregistrez le fichier mis à jour à l'aide de la méthode Save de l'objet Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier ODT en lecture seule via .NET" %}}
Afin de protéger votre ODT contre la modification et d'empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document, vous pouvez également définir la protection du document à l'aide de l'API. Vous pouvez limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être fait à l'aide de l'API [Aspose.Words pour .NET](https://products.aspose.com/words/net/). Il vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-ott/" name="MD Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-mhtml/" name="MD Pour MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-wordml/" name="MD Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-dot/" name="MD Pour DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-odt/" name="MD Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-rtf/" name="MD Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-ps/" name="MD Pour PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-flatopc/" name="MD Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-pcl/" name="MD Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-markdown/" name="MD Pour MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xamlflow/" name="MD Pour XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-dotx/" name="MD Pour DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}