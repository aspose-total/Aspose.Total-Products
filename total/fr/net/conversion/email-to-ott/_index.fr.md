---
title: API C# pour exporter EMAIL vers OTT
description: Convertir EMAIL en OTT sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/email-to-ott/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: OTT
otherformats: PDF DOTX DOCM MD PCL PNG FLATOPC XPS WORDML ODT DOTM EMF TEXT SVG JPEG GIF OTT DOCX PS TIFF RTF DOT DOC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMAIL vers OTT via .NET" h2="API .NET pour rendre EMAIL en OTT sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMAIL vers OTT dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMAIL en OTT" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format OTT en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Ott comme SaveFormat
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
Avant de convertir EMAIL en OTT, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMAIL, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents OTT via .NET" %}}
Lors de l'enregistrement du document de EMAIL vers OTT, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMAIL en OTT par programmation : cas d'utilisation" %}}
Converting Email à des Contenus OTT (Over-the-Top) : Déverouiller les Énergies d'Engagement et de Flèches de Révenu

Les fichiers d'email sont utilisés pour stocker des messages personnels, ce qui en fait une idéalité pour créer les communications interactives. Cependant, lorsqu'on travaille avec le contenu dynamique, les plateformes de vidéo sur demande comme OTT deviennent essentielles pour engager les publics et générer des revenus.

La conversion des fichiers d'email vers les formats OTT est nécessaire pour déverouiller pleinement votre potentiel d'engagement et de capacités de génération de revenu. Cette conversion permet :

**Cas d'utilisation :**

*   **Récits personnalisés**: Convertir les fichiers d'email en contenus vidéos personnalisés, en utilisant les données des utilisateurs pour stimuler l'engagement et la fidélité.
*   **Publicités interactives**: Utiliser OTT pour livrer des publicités interactives, permettant aux marques de mesurer l'efficacité des publicités et d'intéragir avec les utilisateurs en temps réel.
*   **Spots publicitaires**: Convertir les fichiers d'email en séries de contenus publicitaires personnalisés, utilisant un récit dynamique et des expériences immersives pour captiver le public.
*   **Gestion relationnels clients**: Utiliser OTT pour créer des messages vidéo personnalisés pour l'accueil des clients, la maintenance et les retours, conduisant à une fidélité accrue et à une rétention plus efficace.
*   **Génération de revenus via les abonnements** : Convertir les fichiers d'email en générant des revenus grâce aux modèles d'abonnement basés sur des offres exclusives et des expériences, offrant aux utilisateurs du contenu et des expériences uniques.

En convertissant les fichiers d'email vers les formats OTT, vous pouvez déverouiller de nouvelles opportunités pour l'engagement, la croissance des revenus et le lien avec l'audience."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}