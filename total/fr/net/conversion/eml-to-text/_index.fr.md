---
title: API C# pour exporter EML vers TEXT
description: Convertir EML en TEXT sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/eml-to-text/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TEXT
otherformats: PNG DOT DOTM JPEG ODT MD XPS PS WORDML DOCX FLATOPC EPUB SVG TIFF DOTX RTF OTT DOCM DOC PDF PCL GIF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EML vers TEXT via .NET" h2="API .NET pour rendre EML en TEXT sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EML vers TEXT dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EML en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EML en TEXT" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EML via .NET" %}}
Avant de convertir EML en TEXT, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EML, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents TEXT via .NET" %}}
Lors de l'enregistrement du document de EML vers TEXT, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EML en TEXT par programmation : cas d'utilisation" %}}
Les fichiers EML (Courrier Électronique) sont utilisés pour stocker les informations de communication textuelles, ce qui en fait idéaux pour créer des messages lus et courriels. Cependant, lorsqu'on travaille avec du contenu multimédia, des documents comme les PDFs deviennent essentiels pour partager et afficher.

La conversion de fichiers EML vers des formats de texte est nécessaire pour débloquer la pleine puissance de votre contenu de message et de vos capacités d'analyse. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Analyse du message** : Convertir les fichiers EML afin d'analyser les courriels, suivre le comportement des expéditeurs et identifier les modèles de communication.
*   **Automatisation des campagnes de marketing par courrier électronique** : Utiliser les formats de texte pour visualiser les données de marketing par courrier électronique, automatiser les campagnes et mesurer les taux d'ouverture.
*   **Documentation du support client** : Convertir les fichiers EML afin de créer des documents lus, des questions fréquentes et des bases de connaissance pour les clients, ce qui facilite les services de soutien.
*   **Enregistrement historique** : Utiliser les formats de texte pour stocker et récupérer des enregistrements historiques d'e-mails, ce qui garantit la conformité réglementaire et les exigences de conservation de l'enregistrement.
*   **Réutilisation du contenu** : Convertir les fichiers EML afin de créer un contenu partageable, tels que des articles blog, mises à jour sur les réseaux sociaux et des communiqués de presse, pour améliorer l'engagement et la portée.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}