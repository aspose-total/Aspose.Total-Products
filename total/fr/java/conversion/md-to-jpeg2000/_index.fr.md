---
title: Convertir MD en JPEG2000 via Java
description: Exportez le fichier MD vers JPEG2000 dans vos applications Java sans utiliser d'application tierce
url_ignore: /fr/java/conversion/md-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: JPEG2000
otherformats: WMF EMZ  DXF JPEG2000 WMZ TGA IMAGE SVGZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir MD en JPEG2000 via Java" h2="Exportez le fichier MD vers JPEG2000 dans n'importe quelle application Java J2SE, J2EE, J2ME sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir un fichier md en image JPEG2000 en Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter MD au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), vous pouvez rendre JPEG en JPEG2000. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exporter MD vers JPEG2000 via Java" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialisez l'objet de classe et rendez MD au format JPEG à l'aide de [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. méthode aspose.pdf.Page-java.io.OutputStream-)
3. Chargez le fichier JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Enregistrez le document au format JPEG2000 en utilisant [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convertir MD en JPEG2000 dans un seul fichier via Java" %}}
L'API vous permet également d'exporter le fichier MD vers JPEG2000 dans un seul fichier. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document MD dans un fichier TIFF, puis exporter le fichier TIFF vers JPEG2000. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) méthode de la classe [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Enfin, vous pouvez charger le fichier TIFF à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et l'enregistrer au format JPEG2000 à l'aide de [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir MD en JPEG2000 avec filigrane via Java" %}}
À l'aide de l'API, vous pouvez également exporter un fichier MD vers JPEG2000 avec un filigrane dans votre document JPEG2000. Afin d'ajouter un filigrane, vous pouvez d'abord convertir MD en JPEG et y ajouter un filigrane. Pour ajouter un filigrane, chargez un fichier image à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), créez un objet de la classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) classe et initialisez-la avec l'objet Image, créez une nouvelle [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) et définissez la traduction et la transformation à l'angle souhaité et ajoutez un filigrane à l'aide de [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# méthode drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Après avoir ajouté le filigrane dans votre image, vous pouvez enregistrer le JPEG au format JPEG2000. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter MD en fichier JPEG2000 via Java" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image JPEG2000 de sortie selon vos besoins. La méthode Image.rotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. La bibliothèque fournit des méthodes simples pour effectuer des opérations complexes tout en encapsulant tous les détails laids. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et appeler Image. rotateFlip tout en spécifiant le [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversion de Markdown (MD) en JPEG2000 permet l'exportation d'images haute résolution et sans perte. Idéal pour les illustrations techniques, les grands diagrammes ou les besoins d'archivage où la préservation des détails est cruciale.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Conversion de graphiques Markdown en images techniques haute résolution.

* Archivage de diagrammes complexes à partir de Markdown sans perte de qualité.

* Préparation de documentation imprimable avec des visuels détaillés.

* Illustrations scientifiques générées à partir de notes Markdown.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Conversion automatisée de diagrammes Markdown en JPEG2000 pour un stockage de haute qualité.

* Traitement par lots pour les équipes de recherche ou d'ingénierie.

* Intégration avec les flux de travail de publication nécessitant des formats d'image sans perte.

* Mises à jour planifiées des visuels dérivés de Markdown dans les archives JPEG2000.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}