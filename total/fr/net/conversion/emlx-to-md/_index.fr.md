---
title: API C# pour exporter EMLX vers MD
description: Convertir EMLX en MD sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/emlx-to-md/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: MD
otherformats: PDF OTT PCL JPEG RTF GIF DOC DOCX EMF EPUB TIFF DOTM TEXT DOT SVG ODT XPS PS WORDML DOTX PNG MD DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMLX vers MD via .NET" h2="API .NET pour rendre EMLX en MD sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMLX vers MD dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMLX en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMLX en MD" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMLX en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format MD en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Md comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMLX via .NET" %}}
Avant de convertir EMLX en MD, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMLX, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents MD via .NET" %}}
Lors de l'enregistrement du document de EMLX vers MD, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMLX en MD par programmation : cas d'utilisation" %}}
Les fichiers EMLX (Langage de marquage d'emails) sont utilisés pour stocker des emails à texte plat avec des informations de formatting, ce qui les rend idéales pour créer des modèles et compositions d'e-mails de base. Cependant, lorsqu'on travaille avec des données structurées et des visualisations, les fichiers Markdown deviennent essentiels pour la présentation et l'analyse des données.

La conversion des fichiers EMLX en formats Markdown est nécessaire pour débloquer pleinement vos capacités de visualisation et d'analyse de données. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Documentation de projet** : Convertir les fichiers EMLX pour créer une documentation de projet lisible, suivre les modifications et collaborer avec les membres de l'équipe.
*   **Notes de réunion et minutes** : Utiliser Markdown pour prendre des notes lors des réunions, enregistrer les minutes et partager les résultats avec les participants.
*   **Journal personnel** : Convertir les fichiers EMLX pour maintenir un journal personnel ou une diary structurée, enregistrant ses pensées, expériences et réflexions de manière organisée.
*   **Écriture d'articles académiques** : Utiliser Markdown pour créer et organiser des articles et essais académiques, améliorant la lisibilité et la collaboration.
*   **Création d'une base de connaissances** : Convertir les fichiers EMLX pour construire une base de connaissances, documentant les processus, procédures et meilleures pratiques dans un format facilement cherchant et accessible.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}