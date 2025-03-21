---
title: API C# pour exporter EMLX vers XPS
description: Convertir EMLX en XPS sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/emlx-to-xps/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: XPS
otherformats: TEXT OTT EMF WORDML GIF XPS TIFF DOCM DOCX DOT ODT DOTM DOTX PNG RTF FLATOPC EPUB DOC PS PCL PDF JPEG SVG MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMLX vers XPS via .NET" h2="API .NET pour rendre EMLX en XPS sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMLX vers XPS dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMLX en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMLX en XPS" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMLX en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format XPS en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Xps comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMLX via .NET" %}}
Avant de convertir EMLX en XPS, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMLX, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents XPS via .NET" %}}
Lors de l'enregistrement du document de EMLX vers XPS, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMLX en XPS par programmation : cas d'utilisation" %}}
Les fichiers EMLX (Electronic Messaging Layer with Extensions) sont utilisés pour stocker des informations de texte plat, les rendant idéaux à envoyer des courriers électroniques et échanger des messages commerciaux. Cependant, lorsque l'on travaille avec des données basées sur les images, les documents XPS (XML Paper Specification) deviennent essentiels pour imprimer et partager du contenu visuel.

La conversion de fichiers EMLX en formats XPS est nécessaire pour débloquer la pleine puissance de vos capacités de partage documentaire et d'impression. Cette conversion vous permet :

**Cas d'usage :**

*   **Partage de documents** : Convertir les fichiers EMLX pour partager des documents, rapports et présentations avec des collègues et clients, assurant une échange précis et sécurisé.
*   **Optimisation d'impression** : Utiliser XPS pour optimiser les arrangements imprimables, images et designs pour améliorer la qualité visuelle et réduire les tailles de fichiers.
*   **Édition et amélioration des images** : Convertir les fichiers EMLX pour éditer et améliorer le contenu image, y compris les graphiques, les photographies et les dessins.
*   **Intégration des signatures numériques** : Utiliser XPS pour intégrer les signatures numériques, garantissant une authentification et une vérification sécurisées de documents.
*   **Accèsibilité et inclusion** : Convertir les fichiers EMLX pour créer des documents accessibles et inclusifs, suivant les normes de l'accessibilité web pour améliorer la lecture.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}