---
title: API C# pour exporter EML vers PCL
description: Convertir EML en PCL sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/eml-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PCL
otherformats: MD DOCX RTF WORDML ODT PCL SVG DOT DOC XPS DOTM JPEG OTT PDF EPUB PS TIFF GIF TEXT PNG DOTX DOCM FLATOPC EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EML vers PCL via .NET" h2="API .NET pour rendre EML en PCL sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EML vers PCL dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EML en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EML en PCL" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format PCL en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Pcl comme SaveFormat
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

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyser le fichier EML via .NET" %}}
Avant de convertir EML en PCL, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EML, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents PCL via .NET" %}}
Lors de l'enregistrement du document de EML vers PCL, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EML en PCL par programmation : cas d'utilisation" %}}
Les fichiers EML (Électronique Mail) sont utilisés pour stocker des messages texte basés, les rendant idéaux pour la communication personnelle et la collaboration. Cependant, lorsque l'on travaille avec des données de graphiques vectoriels, les fichiers PCL (Langage de Contrôle d'Imprimante) deviennent essentiels pour une impression précise et une sortie.

La conversion des fichiers EML en formats PCL est nécessaire pour débloquer le plein potentiel de vos capacités d'impression. Cette conversion vous permet :

Utilisateurs :

*   **Imprimer un logo personnalisé** : Convertir des fichiers EML pour créer des logos, des graphiques et des images personnalisées à utiliser personnellement ou professionnellement.
*   **Documents techniques et documentation** : Utiliser PCL pour imprimer les dessins techniques, les plans, et les documents avec précision et détail.
*   **Design graphique et artwork** : Convertir des fichiers EML pour créer des conceptions complexes, des illustrations et de l'artwork d'impression ou de visualisation numérique.
*   **Impression de codes-barres et étiquettes** : Utiliser PCL pour imprimer des codes-barres, des étiquettes et des etiquettes avec précision et rapidité, idéales pour la gestion de stock et le suivi de la chaîne d'approvisionnement.
*   **Corrigé et édition de texte** : Convertir des fichiers EML pour reviser et éditer les documents texte avec un contrôle précis sur les styles de police, les tailles et les formatters.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}