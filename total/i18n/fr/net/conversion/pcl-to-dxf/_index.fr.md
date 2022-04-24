---
title: Convertir PCL en DXF via l'API C#
description: Exportez PCL vers DXF dans vos applications .NET sans utiliser d'application tierce
url: /fr/net/conversion/pcl-to-dxf/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: DXF
otherformats: DXF JPEG2000 WMF PSD WMZ IMAGE EMZ  SVGZ TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le fichier PCL en DXF via C#" h2="Exportez PCL vers DXF dans les applications .NET sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader ou toute autre application tierce" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour .NET](https://products.aspose.com/total/net/), vous pouvez facilement exporter une image PCL vers DXF dans n'importe quelle application .NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF pour .NET](https://products.aspose.com/pdf/net/), vous pouvez exporter PCL au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), vous pouvez convertir JPEG en DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier PCL en DXF via .NET" %}}
1. Ouvrez le fichier PCL à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Initialisez l'objet de classe [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) et rendez PCL au format JPEG à l'aide de [Process](https://apireference.aspose. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) méthode
3. Chargez le fichier JPEG en utilisant la classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Enregistrez le document au format DXF à l'aide de la méthode [Enregistrer](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le fichier PCL en DXF dans un seul fichier via C#" %}}
À l'aide de l'API, vous pouvez également convertir un fichier PCL en DXF en un seul fichier image. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document PCL dans un fichier TIFF, puis exporter le fichier TIFF vers DXF. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant la méthode [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Enfin, vous pouvez charger le fichier TIFF en utilisant la classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
et enregistrez-le au format DXF à l'aide de la méthode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter le fichier PCL en DXF via C#" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image DXF de sortie selon vos besoins. La méthode Image.RotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la méthode d'usine exposée par la classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) et appeler la classe Image .RotateFlip tout en spécifiant le [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-emz/" name="PCL Pour EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-tga/" name="PCL Pour TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-jpeg2000/" name="PCL Pour JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-image/" name="PCL Pour IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-psd/" name="PCL Pour PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-wmz/" name="PCL Pour WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-svgz/" name="PCL Pour SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to/" name="PCL Pour" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-wmf/" name="PCL Pour WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-dxf/" name="PCL Pour DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/pcl-to-dicom/" name="PCL Pour DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}