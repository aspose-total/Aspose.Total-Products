---
title: API C# pour exporter EML vers DOTX
description: Convertir EML en DOTX sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/eml-to-dotx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOTX
otherformats: EPUB DOCM TEXT MD DOC GIF DOTX DOTM JPEG ODT PDF XPS PCL DOCX PNG FLATOPC PS SVG OTT DOT TIFF EMF RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EML vers DOTX via .NET" h2="API .NET pour rendre EML en DOTX sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EML vers DOTX dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EML en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EML en DOTX" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EML via .NET" %}}
Avant de convertir EML en DOTX, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EML, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents DOTX via .NET" %}}
Lors de l'enregistrement du document de EML vers DOTX, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EML en DOTX par programmation : cas d'utilisation" %}}
La conversion de fichiers EML vers les formats DotX est nécessaire pour déverrouiller l'intégralité des capacités d'édition de documents. Cette conversion permet à vous de :

**Cas d'utilisation :**

*   **Collaboration et Travail en Équipe**: Convertir des fichiers EML afin de partager des documents avec des collègues, des partenaires ou des clients, facilitant une collaboration sans ébranchelement et un retour sur les commentaires.
*   **Enregistrement et Conservation des Courriels :** Utiliser le format DotX pour stocker et organiser du contenu de courriel dans une formate sécurisé et accessible, satisfaissant ainsi les exigences réglementaires.

*   **Édition et Révision de Documents**: Convertir des fichiers EML afin d'écrire et rédiger documents, y compris la mise en forme du texte, l'inclusion de photos et des hyperliens, ce qui facilite grandement la création d'un contenu bien pensé et professionnel.
*   **Recherche et Uso universitaire :** Utiliser DotX afin d'importer et analyser les données de courriel dans le cadre de projets de recherche, fournissant ainsi de précieuses informations sur les modèles de communication, les tendances et les thèmes.
*   **Intelligence d'affaires et Analyse des Données :** Convertir les fichiers EML afin d'extraction et de manipulation de données, permettant aux organisations de mieux comprendre le comportement des clients, la performance des ventes et les tendances du marché.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}