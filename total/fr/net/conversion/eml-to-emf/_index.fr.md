---
title: API C# pour exporter EML vers EMF
description: Convertir EML en EMF sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/eml-to-emf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EMF
otherformats: DOC PS DOTX MD PNG XPS GIF DOTM DOT SVG JPEG EPUB OTT TIFF WORDML FLATOPC DOCM PDF EMF TEXT RTF PCL ODT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EML vers EMF via .NET" h2="API .NET pour rendre EML en EMF sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EML vers EMF dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EML en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EML en EMF" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format EMF en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Emf comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EML via .NET" %}}
Avant de convertir EML en EMF, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EML, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents EMF via .NET" %}}
Lors de l'enregistrement du document de EML vers EMF, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EML en EMF par programmation : cas d'utilisation" %}}
Les fichiers d'envoi électronique (EML) sont utilisés pour stocker les messages e-mais, ce qui les rend idéaux pour créer des documents statiques et des enregistrements de communication. Cependant, lorsqu'on travaille avec des données dynamiques, des formats d'image comme EMF deviennent essentiels pour préserver la fidélité visuelle et l'exactitude.

La conversion des fichiers EML vers les formats EMF est nécessaire pour débloquer les capacités de visualisation et d'analyse complètes de vos documents. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Enregistrement et conformité réglementaire** : Convertir les fichiers EML pour créer des enregistrements recherchables et éditables des communications e-mais, garantissant la conformité aux exigences réglementaires.
*   **Détection digitale et enquête** : Utiliser EMF pour analyser et préserver les preuves d'envoi e-mai, suivre les empreintes numériques, et reconstruire les scénarios de communication.
*   **Suivi des campagnes de marketing digitales** : Convertir les fichiers EML pour mesurer l'efficacité des campagnes de marketing électronique, optimiser les listes d'émetteurs, et améliorer les taux d'ouverture.
*   **Développement de plateformes d'apprentissage en ligne** : Créer des modules d'apprentissage interactifs en convertissant les fichiers EML en formats EMF, permettant des expériences d'apprentissage plus engageantes.
*   **Préservation des archives historiques** : Utiliser EMF pour digitaliser les enregistrements électroniques anciens, garantissant leur préservation pour les générations futures et fournissant des informations précieuses sur les modèles de communication passés.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}