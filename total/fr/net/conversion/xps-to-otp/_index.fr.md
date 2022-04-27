---
title: Exporter XPS vers OTP via l'API C#
description: API .NET pour convertir XPS en OTP sans utiliser Microsoft Word
url: /fr/net/conversion/xps-to-otp/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: OTP
otherformats: XAML PPSX PPS PPT SWF PPSM POTM PPTM POWERPOINT POT OTP POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendre XPS vers OTP via .NET" h2="API .NET pour exporter XPS vers OTP sur Windows, macOS et Linux sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
À l'aide d'un ensemble d'API puissantes d'automatisation du format de fichier [Aspose.Total pour .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir XPS en OTP en deux étapes simples. En utilisant l'API de traitement PDF [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez transformer le format de fichier XPS en PPTX. Après cela, en utilisant l'API de traitement de présentation [Aspose.Slides pour .NET](https://products.aspose.com/slides/net/), vous pouvez convertir PPTX en OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir XPS en OTP" %}}
1. Ouvrez le fichier XPS à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir XPS en PPTX en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le fichier PPTX en utilisant la classe [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Enregistrez le document au format OTP à l'aide de la méthode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) et définissez `Otp` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir les métadonnées XMP du fichier XPS via .NET" %}}
Lors de la conversion de XPS en OTP, vous aurez peut-être besoin d'informations de métadonnées XMP supplémentaires pour hiérarchiser votre processus de conversion par lots. Par exemple, vous pouvez obtenir et trier vos documents de conversion en fonction de la date de création et traiter les documents en conséquence. [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/) vous permet d'accéder aux métadonnées XMP d'un fichier XPS. Pour obtenir les métadonnées d'un fichier XPS, vous pouvez créer un objet [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et ouvrir le fichier XPS d'entrée. Après cela, vous pouvez obtenir les métadonnées du fichier à l'aide de la propriété [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer un fichier OTP en lecture seule via .NET" %}}
En utilisant l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), vous pouvez encore améliorer les fonctionnalités de votre application de conversion. L'une des fonctionnalités peut être de créer votre fichier de sortie en lecture seule pour augmenter la sécurité. L'API vous permet de définir votre fichier OTP sur Lecture seule, ce qui signifie que les utilisateurs (après avoir ouvert la présentation) voient la recommandation Lecture seule. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-pot/" name="XPS Pour POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-ppsx/" name="XPS Pour PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-swf/" name="XPS Pour SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-powerpoint/" name="XPS Pour POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-otp/" name="XPS Pour OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-potm/" name="XPS Pour POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-ppt/" name="XPS Pour PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-pps/" name="XPS Pour PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-potx/" name="XPS Pour POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-xaml/" name="XPS Pour XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-ppsm/" name="XPS Pour PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-pptm/" name="XPS Pour PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}