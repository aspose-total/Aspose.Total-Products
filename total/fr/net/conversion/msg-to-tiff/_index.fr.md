---
title: API C# pour exporter MSG vers TIFF
description: Convertir MSG en TIFF sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/msg-to-tiff/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TIFF
otherformats: OTT TIFF DOCM MD EPUB XPS GIF EMF DOTX PCL DOC PS FLATOPC PDF JPEG TEXT PNG WORDML DOT SVG DOCX DOTM RTF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter MSG vers TIFF via .NET" h2="API .NET pour rendre MSG en TIFF sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion MSG vers TIFF dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier MSG en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en TIFF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir MSG en TIFF" %}}
1. Ouvrez le fichier MSG à l'aide de la classe [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Convertissez MSG en HTML en utilisant la méthode [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format TIFF en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Tiff comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier MSG via .NET" %}}
Avant de convertir MSG en TIFF, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document MSG, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents TIFF via .NET" %}}
Lors de l'enregistrement du document de MSG vers TIFF, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier MSG en TIFF par programmation : cas d'utilisation" %}}
Les fichiers de format de message (MSG) sont utilisés pour stocker des messages au texte plat, les rendant idéaux pour la création de communications basées sur le texte simples. Cependant, lorsqu'on travaille avec des données d'image, le format TIFF (Format de fichier d'image étiqueté) devient essentiel pour une stockage et une manipulation d'images de haute qualité.

La conversion de fichiers MSG en formats TIFF est nécessaire pour débloquer la pleine puissance de vos contenus visuels et de vos capacités d'analyse. Cette conversion vous permet :

Utilisations : 

*   **Buts archivistes** : Convertir les fichiers MSG pour préserver des messages historiques, assurant leur exactitude et leur intégrité au fil du temps.
*   **Édition et amélioration de l'image** : Utiliser TIFF pour éditer et améliorer les données d'images, effectuer des tâches de traitement d'images avancées, et créer des visuels professionnels de haute qualité.
*   **Scanning et gestion des documents papier** : Convertir les fichiers MSG pour numériser et gérer les documents papier, réduire les besoins de stockage et améliorer l'accès.
*   **Analyse d'images médicales** : Utiliser TIFF pour analyser les images médicales, telles que les radiographies et les MRIs, pour un diagnostic et une planification de traitement.
*   **Découverte électronique et conformité réglementaire** : Convertir les fichiers MSG pour créer des enregistrements numériques tampons, garantissant la conformité avec les exigences réglementaires et facilitant les audits.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}