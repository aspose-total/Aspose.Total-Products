---
title: Convertir CGM en DXF via l'API C#
description: Exportez CGM vers DXF dans vos applications .NET sans utiliser d'application tierce
url_ignore: /fr/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le fichier CGM en DXF via C#" h2="Exportez CGM vers DXF dans les applications .NET sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader ou toute autre application tierce" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement exporter une image CGM vers DXF dans n'importe quelle application .NET en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez exporter CGM au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), vous pouvez convertir JPEG en DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier CGM en DXF via .NET" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Initialisez l'objet de classe [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) et rendez CGM au format JPEG à l'aide de [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) méthode
3. Chargez le fichier JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Enregistrez le document au format DXF à l'aide de la méthode [Enregistrer](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le fichier CGM en DXF dans un seul fichier via C#" %}}
À l'aide de l'API, vous pouvez également convertir un fichier CGM en DXF en un seul fichier image. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document CGM dans un fichier TIFF, puis exporter le fichier TIFF vers DXF. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant la méthode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Enfin, vous pouvez charger le fichier TIFF en utilisant la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
et enregistrez-le au format DXF à l'aide de la méthode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter le fichier CGM en DXF via C#" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image DXF de sortie selon vos besoins. La méthode Image.RotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la méthode d'usine exposée par la classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) et appeler la classe Image .RotateFlip tout en spécifiant le [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en DXF par programmation : cas d'utilisation" %}}
La conversion de fichiers CGM (Metafile des graphiques informatiques) en fichiers DXF (Format d'échange de dessin) est essentielle pour déclencher les capacités complètes de votre conception CAD et de vos capacités de fabrication. Cette conversion permet à vous :

**Cas d'utilisation :**

*   **Intégration du CAD :** Conversion des fichiers CGM afin de pouvoir intégrer avec les logiciels de conception assistée par ordinateur, permettant une collaboration fluide en matière de conception et l'échange de données.
*   **Optimisation du processus de fabrication:** Utiliser les fichiers DXF afin d'optimiser les processus de fabrication, réduire les coûts de production et améliorer la qualité des produits.
*   **Conception pour la fabrication (DFM)**: Conversion des fichiers CGM afin de créer des conceptions DFM, en tenant compte de facteurs tels que les propriétés des matériaux, les exigences d'outillage et les contraintes de montage.
*   **Échange de données avec les machines CNC :** Utiliser les fichiers DXF afin de communiquer les données de conception avec les machines CNC, assurant une coupe précise et une fabrication de pièces.
*   **Développement de produits et tests:** Conversion des fichiers CGM afin de créer des prototypes, tester les conceptions et valider la fonctionnalité des produits avant leur production.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}