---
title: Convertir TEX en IMAGE via Java
description: Exportez le fichier TEX vers IMAGE dans vos applications Java sans utiliser d'application tierce
url_ignore: /fr/java/conversion/tex-to-image/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: IMAGE
otherformats: DXF WMZ WMF TGA EMZ JPEG2000 SVGZ PSD  IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir TEX en IMAGE via Java" h2="Exportez le fichier TEX vers IMAGE dans n'importe quelle application Java J2SE, J2EE, J2ME sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir un fichier tex en image IMAGE en Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter TEX au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), vous pouvez rendre JPEG en IMAGE. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exporter TEX vers IMAGE via Java" %}}
1. Ouvrez le fichier TEX à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialisez l'objet de classe et rendez TEX au format JPEG à l'aide de [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. méthode aspose.pdf.Page-java.io.OutputStream-)
3. Chargez le fichier JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Enregistrez le document au format IMAGE en utilisant [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convertir TEX en IMAGE dans un seul fichier via Java" %}}
L'API vous permet également d'exporter le fichier TEX vers IMAGE dans un seul fichier. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document TEX dans un fichier TIFF, puis exporter le fichier TIFF vers IMAGE. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) méthode de la classe [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Enfin, vous pouvez charger le fichier TIFF à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et l'enregistrer au format IMAGE à l'aide de [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir TEX en IMAGE avec filigrane via Java" %}}
À l'aide de l'API, vous pouvez également exporter un fichier TEX vers IMAGE avec un filigrane dans votre document IMAGE. Afin d'ajouter un filigrane, vous pouvez d'abord convertir TEX en JPEG et y ajouter un filigrane. Pour ajouter un filigrane, chargez un fichier image à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), créez un objet de la classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) classe et initialisez-la avec l'objet Image, créez une nouvelle [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) et définissez la traduction et la transformation à l'angle souhaité et ajoutez un filigrane à l'aide de [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# méthode drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Après avoir ajouté le filigrane dans votre image, vous pouvez enregistrer le JPEG au format IMAGE. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter TEX en fichier IMAGE via Java" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image IMAGE de sortie selon vos besoins. La méthode Image.rotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. La bibliothèque fournit des méthodes simples pour effectuer des opérations complexes tout en encapsulant tous les détails laids. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et appeler Image. rotateFlip tout en spécifiant le [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversion de TEX en **IMAGE (formats raster génériques)** transforme les équations, tableaux et figures LaTeX en formats d'image universellement compatibles pour le web, l'impression et la documentation.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Intégration de figures générées en LaTeX dans des blogs et des sites web.

* Préparation d'images haute résolution pour des articles académiques.

* Partage de diagrammes dans des formats lisibles universellement.

* Conversion de tableaux LaTeX complexes en instantanés d'images.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Conversion en lot de TEX en images pour les bibliothèques de contenu.

* Intégration avec des flux de publication et de site web automatisés.

* Mises à jour déclenchées pour du contenu de cours ou de tutoriels basé sur des images.

* Exportation de plusieurs diagrammes LaTeX en formats d'image cohérents.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}