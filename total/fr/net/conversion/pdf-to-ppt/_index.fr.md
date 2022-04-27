---
title: Exporter PDF vers PPT via l'API C#
description: API .NET pour convertir PDF en PPT sans utiliser Microsoft Word
url: /fr/net/conversion/pdf-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPT
otherformats: PPT XAML POWERPOINT PPSM POTX PPTM SWF POT PPS POTM OTP PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre PDF vers PPT via .NET" h2="API .NET pour exporter PDF vers PPT sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total pour .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir PDF en PPT en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier PDF en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides pour .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir PDF en PPT" %}}
1. Ouvrez le fichier PDF à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir PDF en PPTX en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format PPT à l'aide de la méthode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Ppt` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.pdf");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier PDF via .NET" %}}
Lors de la conversion de PDF en PPT, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier PDF. Pour obtenir les métadonnées d'un fichier PDF, vous pouvez créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier PDF d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.pdf");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier PPT en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier PPT sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-pot/" name="PDF Pour POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-ppsx/" name="PDF Pour PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-swf/" name="PDF Pour SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-powerpoint/" name="PDF Pour POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-otp/" name="PDF Pour OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-potm/" name="PDF Pour POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-ppt/" name="PDF Pour PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-pps/" name="PDF Pour PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-potx/" name="PDF Pour POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-xaml/" name="PDF Pour XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-ppsm/" name="PDF Pour PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pdf-to-pptm/" name="PDF Pour PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}