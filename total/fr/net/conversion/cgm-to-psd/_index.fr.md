---
title: Convertir CGM en PSD via l'API C#
description: Exportez CGM vers PSD dans vos applications .NET sans utiliser d'application tierce
url_ignore: /fr/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le fichier CGM en PSD via C#" h2="Exportez CGM vers PSD dans les applications .NET sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader ou toute autre application tierce" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement exporter une image CGM vers PSD dans n'importe quelle application .NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez exporter CGM au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), vous pouvez convertir JPEG en PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier CGM en PSD via .NET" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Initialisez l'objet de classe [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) et rendez CGM au format JPEG à l'aide de [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) méthode
3. Chargez le fichier JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Enregistrez le document au format PSD à l'aide de la méthode [Enregistrer](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le fichier CGM en PSD dans un seul fichier via C#" %}}
À l'aide de l'API, vous pouvez également convertir un fichier CGM en PSD en un seul fichier image. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document CGM dans un fichier TIFF, puis exporter le fichier TIFF vers PSD. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant la méthode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Enfin, vous pouvez charger le fichier TIFF en utilisant la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
et enregistrez-le au format PSD à l'aide de la méthode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter le fichier CGM en PSD via C#" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image PSD de sortie selon vos besoins. La méthode Image.RotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la méthode d'usine exposée par la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) et appeler la classe Image .RotateFlip tout en spécifiant le [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en PSD par programmation : cas d'utilisation" %}}
Les fichiers CGM (Metafile de graphiques informatiques) sont utilisés pour stocker des informations sur les graphiques vectoriels, ce qui les rend idéaux pour la création d'images statiques et d'illustrations. Cependant, lorsqu'on travaille avec des données dynamiques, les éditeurs de fichiers raster tels que Photoshop deviennent essentiels pour visualiser et éditer les images.

La conversion de fichiers CGM en formats PSD est nécessaire pour débloquer la pleine capacité de vos compétences en graphismes. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Conception de logos :** Convertir des fichiers CGM pour créer des logos vectoriels scalables pouvant être utilisés dans divers médias, notamment les cartes de visite, les affiches et les sites web.
*   **Branding et identité :** Utiliser PSD pour visualiser les lignes directrices de marque, créer une identité visuelle cohérente et maintenir la cohérence visuelle dans tous les matériaux marketing.
*   **Illustrations et artwork :** Convertir des fichiers CGM pour créer des illustrations détaillées, éditer l'artwork vectoriel et affiner les concepts de design.
*   **Design imprimé :** Utiliser PSD pour visualiser le design imprimé, optimiser les layouts et assurer une sortie d'image haute qualité pour différentes applications d'impression.
*   **Matériaux de graphisme conçus :** Convertir des fichiers CGM pour créer des matériels de graphisme éditables pouvant être réutilisés dans plusieurs projets, en économisant du temps et des efforts.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}