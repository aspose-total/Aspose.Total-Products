---
title: API C# pour exporter EMAIL vers DOTX
description: Convertir EMAIL en DOTX sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/email-to-dotx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTX
otherformats: PDF DOCX GIF DOTX PCL PNG OTT SVG DOTM EMF RTF TIFF DOCM ODT EPUB PS FLATOPC XPS MD WORDML DOC JPEG TEXT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMAIL vers DOTX via .NET" h2="API .NET pour rendre EMAIL en DOTX sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMAIL vers DOTX dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMAIL en DOTX" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format DOTX en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Dotx comme SaveFormat
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
Avant de convertir EMAIL en DOTX, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMAIL, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents DOTX via .NET" %}}
Lors de l'enregistrement du document de EMAIL vers DOTX, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMAIL en DOTX par programmation : cas d'utilisation" %}}
Conversion des emails vers les fichiers Microsoft Office Word Document (.docx) est nécessaire pour débloquer pleinement vos capacités de communication. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Documentation professionnelle** : Convertir les emails pour créer des documents formels, des rapports et des présentations pour les réunions d'affaires, les propositions ou les négociations.
*   **Contrôle et analyse de contrats** : Utiliser les fichiers Microsoft Office Word Document (.docx) pour lire, éditer et signer les contrats, les accords et autres documents juridiquement liés.
*   **Minutes de réunion et notes** : Convertir les emails pour créer des minutes précises et concises de réunions, agendas et actions d'équipe de collaboration.
*   **Écriture de recherche et rédaction d'essais** : Utiliser les fichiers Microsoft Office Word Document (.docx) pour écrire et personnaliser les documents de recherche, les essais et les articles universitaires avec facilité.
*   **Letterhead des entreprises et modèles de newsletter** : Convertir les emails pour créer des lettreshead professionnels, des newsletters et d'autres matériaux de marketing.

La conversion des emails vers les fichiers Microsoft Office Word Document (.docx) vous offre plusieurs avantages :

*   Lectibilité améliorée et mise en forme
*   Capacités d'éditation et de collaboration améliorées
*   Organisation et recherche des documents améliorées
*   Professionnalisme et crédibilité accrues dans la communication
*   Partage et diffusion facile des documents
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}