---
title: API C# pour exporter EMAIL vers TEXT
description: Convertir EMAIL en TEXT sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: EPUB GIF MD RTF DOCM PCL FLATOPC JPEG PDF EMF WORDML DOTX ODT DOTM DOC DOT XPS SVG PNG DOCX OTT TIFF TEXT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMAIL vers TEXT via .NET" h2="API .NET pour rendre EMAIL en TEXT sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMAIL vers TEXT dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMAIL en TEXT" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format TEXT en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Text comme SaveFormat
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
Avant de convertir EMAIL en TEXT, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMAIL, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents TEXT via .NET" %}}
Lors de l'enregistrement du document de EMAIL vers TEXT, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMAIL en TEXT par programmation : cas d'utilisation" %}}
La conversion d'email en texte est utilisée pour extraire des informations de courriels, les rendant idéales pour créer des registres écrits et des résumés. Cependant, lorsqu'on travaille avec des chaînes de courriels longues, les outils comme les clients d'emails deviennent essentiels pour organiser et suivre les conversations.

La conversion de courriels en fichiers de texte est nécessaire pour déclencher la pleine puissance de vos capacités de conservation et de résumé. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Enregistrement d'email** : Convertir des courriels pour créer des registres écrits, des archives et des résumés à fin de référence historique.
*   **Analyse de la communication client** : Utiliser des fichiers de texte pour analyser les conversations clients d'email, suivre les problèmes et identifier les tendances dans la communication.
*   **Note de réunion et résumé** : Convertir des courriels pour créer des notes concises de réunion, de résumés et d'articles d'action pour les équipes et les parties prenantes.
*   **Suivi des campagnes de marketing** : Utiliser des fichiers de texte pour surveiller les conversations de campagne marketing, suivre les réponses et mesurer l'engagement.
*   **Enregistrement juridique** : Convertir des courriels pour créer des écrits officiels, preuves et transcrits à des fins juridiques.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}