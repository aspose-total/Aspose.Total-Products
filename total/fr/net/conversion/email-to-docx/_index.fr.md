---
title: API C# pour exporter EMAIL vers DOCX
description: Convertir EMAIL en DOCX sans utiliser Microsoft Word ou Outlook sur .NET
url_ignore: /fr/net/conversion/email-to-docx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: MD GIF FLATOPC TEXT TIFF PNG DOTX PDF EMF DOC DOT WORDML DOCM XPS PS EPUB RTF OTT ODT DOTM JPEG PCL SVG DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EMAIL vers DOCX via .NET" h2="API .NET pour rendre EMAIL en DOCX sous Windows, macOS et Linux sans utiliser Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si vous êtes un développeur .NET cherchant à ajouter des fonctionnalités de conversion EMAIL vers DOCX dans vos applications, les API de manipulation de format de fichier [Aspose.Total for .NET](https://products.aspose.com/total/net/) sont la solution. avant. En utilisant [Aspose.Email for .NET](https://products.aspose.com/email/net/), vous pouvez convertir le format de fichier EMAIL en HTML. Après cela, en utilisant [Aspose.Words for .NET](https://products.aspose.com/words/net/), vous pouvez restituer HTML en DOCX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# pour convertir EMAIL en DOCX" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant la méthode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Enregistrez le document au format DOCX en utilisant la méthode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) et définissez Docx comme SaveFormat
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
Avant de convertir EMAIL en DOCX, si vous voulez vous assurer que vous convertissez le bon e-mail, vous pouvez charger le document EMAIL, l'analyser et jeter un œil à la propriété souhaitée. En utilisant la classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/), vous pouvez obtenir des informations sur l'expéditeur et les destinataires. Par exemple, vous pouvez rechercher un e-mail d'expéditeur spécifique pour la conversion à l'aide de la propriété [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de documents DOCX via .NET" %}}
Lors de l'enregistrement du document de EMAIL vers DOCX, vous devrez peut-être protéger votre document de sortie. Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. Cela peut être utile pour empêcher d'autres personnes de modifier des informations sensibles et confidentielles dans votre document. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) vous permet de contrôler la manière dont vous restreignez le contenu à l'aide de [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) paramètre d'énumération. Vous pouvez définir votre document en lecture seule en utilisant les lignes de code suivantes. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier EMAIL en DOCX par programmation : cas d'utilisation" %}}
La conversion d'e-mails en fichiers de document Word (.docx) est nécessaire pour déclencher pleinement les capacités de votre capacité à communiquer.

Cette conversion vous permet:

**Utilisations:**

*   **Analyse des correspondances commerciales** : Convertir les e-mails pour analyser les modèles de communication, suivre les réponses et identifier les domaines d'amélioration en matière de service client.
*   **Planification et organisation de réunions** : Utiliser les documents Word pour créer des agendas de réunion, des minutes et des items de tâches, simplifiant le processus de planification et assurant des résultats clairs.
*   **Création de contenu et diffusion** : Convertir les e-mails en rapports formels ou articles, les publiant sur les sites web des sociétés ou dans les newsletters pour démontrer les compétences et renforcer la reconnaissance de marque.
*   **Recherche et collecte de données** : Utiliser les documents Word pour organiser les notes de recherche, les réponses aux sondages et les transcrits d'entretiens, facilitant l'analyse des données et les insights.
*   **Conformité et conservation des dossiers** : Convertir les e-mails en archives officielles, garantissant la conformité avec les exigences réglementaires et conservant des archives de société précises.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}