---
title: API C# pour exporter EMLX vers PCL
description: Convertir EMLX en PCL sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/emlx-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PCL
otherformats: PS EPUB PNG TEXT JPEG TIFF GIF MD FLATOPC EMF XPS ODT DOTM DOCX PCL SVG DOCM OTT WORDML DOT RTF DOTX PDF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMLX vers PCL via .NET" h2="API .NET pour rendre EMLX en PCL sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMLX vers PCL dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMLX en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMLX en PCL" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMLX en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format PCL en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Pcl comme SaveFormat
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

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EMLX via .NET" %}}
Avant de convertir EMLX en PCL, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMLX, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents PCL via .NET" %}}
Lors de l'enregistrement du document de EMLX vers PCL, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMLX en PCL par programmation : cas d'utilisation" %}}
Les fichiers de langue de mail (EMLX) sont utilisés pour stocker les informations textuelles de l'e-mail, les rendant idéaux pour la création d'e-mails simples avec des formats de mise en page de base. Cependant, lorsqu'on travaille avec des exigences de visualisation et d'analyse complexes de données, les fichiers PC/LaTeX (Liste énumérée imprimable LaTeX) deviennent essentiels pour le contrôle précis de la typographie et de l'emplacement.

La conversion des fichiers EMLX en formats PC/LaTeX est nécessaire pour débloquer le potentiel complet de visibilité et de professionnalisme de votre document. Cette conversion vous permet :

*   **Écriture technique** : Convertir les fichiers EMLX pour créer des documents techniques, manuels d'utilisation et guides d'instruction avec une typographie précise et un contrôle d'emplacement.
*   **Publication universitaire** : Utiliser PC/LaTeX pour formatter les articles de recherche, les thèses et les dissertations pour leur publication dans les revues scientifiques et les conférences réputées.
*   **Présentations techniques** : Convertir les fichiers EMLX pour créer présentations visuellement attrayantes, slideshows et conférences avec une typographie précise et un contrôle d'emplacement.
*   **Prototypage de conception** : Utiliser PC/LaTeX pour créer des prototypes interactifs de conception, mockups et preuves de concept avec une typographie précise et un contrôle d'emplacement.
*   **Communications formelles** : Convertir les fichiers EMLX pour créer des documents formels tels que les certificats, les lettres de recommandation et les rapports officiels.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}