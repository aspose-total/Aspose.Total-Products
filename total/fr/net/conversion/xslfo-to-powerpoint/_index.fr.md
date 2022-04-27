---
title: Exporter XSLFO vers POWERPOINT via l'API C#
description: API .NET pour convertir XSLFO en POWERPOINT sans utiliser Microsoft Word
url: /fr/net/conversion/xslfo-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: POWERPOINT OTP POT POTX PPSM PPSX POTM PPTM PPS XAML PPT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre XSLFO vers POWERPOINT via .NET" h2="API .NET pour exporter XSLFO vers POWERPOINT sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total pour .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir XSLFO en POWERPOINT en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier XSLFO en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides pour .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir XSLFO en POWERPOINT" %}}
1. Ouvrez le fichier XSLFO à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir XSLFO en PPTX en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format POWERPOINT à l'aide de la méthode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Powerpoint` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xslfo");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier XSLFO via .NET" %}}
Lors de la conversion de XSLFO en POWERPOINT, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier XSLFO. Pour obtenir les métadonnées d'un fichier XSLFO, vous pouvez créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier XSLFO d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xslfo");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier POWERPOINT en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier POWERPOINT sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pot/" name="XSLFO Pour POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppsx/" name="XSLFO Pour PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-swf/" name="XSLFO Pour SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-powerpoint/" name="XSLFO Pour POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-otp/" name="XSLFO Pour OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-potm/" name="XSLFO Pour POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppt/" name="XSLFO Pour PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pps/" name="XSLFO Pour PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-potx/" name="XSLFO Pour POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-xaml/" name="XSLFO Pour XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppsm/" name="XSLFO Pour PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pptm/" name="XSLFO Pour PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}