---
title: API C# pour exporter EMAIL vers WORDML
description: Convertir EMAIL en WORDML sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORDML
otherformats: MD TIFF OTT DOCM EMF DOTM PNG SVG DOT TEXT DOTX DOCX PDF DOC WORDML GIF FLATOPC EPUB ODT JPEG XPS RTF PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMAIL vers WORDML via .NET" h2="API .NET pour rendre EMAIL en WORDML sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMAIL vers WORDML dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMAIL en WORDML" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format WORDML en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Wordml comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMAIL via .NET" %}}
Avant de convertir EMAIL en WORDML, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMAIL, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents WORDML via .NET" %}}
Lors de l'enregistrement du document de EMAIL vers WORDML, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMAIL en WORDML par programmation : cas d'utilisation" %}}
Les fichiers d'email sont utilisés pour stocker les informations de communication textuelles, ce qui en fait des outils idéaux pour envoyer des messages à les destinataires. Cependant, lors du travail avec des données de présentation, les fichiers WordML (Langage de marquage de Word) deviennent essentiels pour créer des documents et des présentations de qualité professionnelle.

La conversion des fichiers d'email en formats WordML est nécessaire pour débloquer les capacités de création de document et de présentation à leur plein potentiel. Cette conversion vous permet:

**Cas d'utilisation:**

*   **Correspondance commerciale**: Convertir les fichiers d'email pour créer des rapports formels, des propositions et des minutes de réunion commerciales.
*   **Conception de présentations**: Utiliser WordML pour concevoir des présentations engageantes, ajouter des éléments multimédias et inclure des fonctionnalités interactives.
*   **Modèles de document réutilisables**: Convertir les fichiers d'email pour créer des modèles de documents réutilisables fréquemment utilisés, tels que les contrats et les politiques.
*   **Collaboration de recherche**: Utiliser WordML pour partager les résultats de recherches, collaborer avec des collègues et suivre le progrès.
*   **Création du contenu marketing**: Convertir les fichiers d'email pour créer des matériaux publicitaires, des publications sur les réseaux sociaux et des articles de blog.

En convertissant vos emails en format WordML, vous pouvez débloquer de nouvelles possibilités pour la création de document, la conception de présentation et la collaboration.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}