---
title: Convertir XPS en PSD via Java
description: Exportez le fichier XPS vers PSD dans vos applications Java sans utiliser d'application tierce
url_ignore: /fr/java/conversion/xps-to-psd/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: PSD
otherformats: IMAGE DXF TGA WMF WMZ EMZ PSD JPEG2000 SVGZ  DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir XPS en PSD via Java" h2="Exportez le fichier XPS vers PSD dans n'importe quelle application Java J2SE, J2EE, J2ME sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir un fichier xps en image PSD en Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter XPS au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), vous pouvez rendre JPEG en PSD. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exporter XPS vers PSD via Java" %}}
1. Ouvrez le fichier XPS à l'aide de la classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialisez l'objet de classe et rendez XPS au format JPEG à l'aide de [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. méthode aspose.pdf.Page-java.io.OutputStream-)
3. Chargez le fichier JPEG en utilisant la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Enregistrez le document au format PSD en utilisant [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convertir XPS en PSD dans un seul fichier via Java" %}}
L'API vous permet également d'exporter le fichier XPS vers PSD dans un seul fichier. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document XPS dans un fichier TIFF, puis exporter le fichier TIFF vers PSD. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) méthode de la classe [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Enfin, vous pouvez charger le fichier TIFF à l'aide de la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) et l'enregistrer au format PSD à l'aide de [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir XPS en PSD avec filigrane via Java" %}}
À l'aide de l'API, vous pouvez également exporter un fichier XPS vers PSD avec un filigrane dans votre document PSD. Afin d'ajouter un filigrane, vous pouvez d'abord convertir XPS en JPEG et y ajouter un filigrane. Pour ajouter un filigrane, chargez un fichier image à l'aide de la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), créez un objet de la classe [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) classe et initialisez-la avec l'objet Image, créez une nouvelle [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) et définissez la traduction et la transformation à l'angle souhaité et ajoutez un filigrane à l'aide de [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# méthode drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Après avoir ajouté le filigrane dans votre image, vous pouvez enregistrer le JPEG au format PSD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter XPS en fichier PSD via Java" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image PSD de sortie selon vos besoins. La méthode Image.rotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. La bibliothèque fournit des méthodes simples pour effectuer des opérations complexes tout en encapsulant tous les détails laids. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) et appeler Image. rotateFlip tout en spécifiant le [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-emz/" name="XPS Pour EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-tga/" name="XPS Pour TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-jpeg2000/" name="XPS Pour JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-image/" name="XPS Pour IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-psd/" name="XPS Pour PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-wmz/" name="XPS Pour WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-svgz/" name="XPS Pour SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to/" name="XPS Pour" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-wmf/" name="XPS Pour WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-dxf/" name="XPS Pour DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xps-to-dicom/" name="XPS Pour DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}