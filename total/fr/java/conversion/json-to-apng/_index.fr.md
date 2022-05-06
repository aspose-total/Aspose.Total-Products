---
title: Convertir le format JSON en APNG via Java
description: Analyser JSON en APNG en Java sans utiliser Microsoft PowerPoint
url_ignore: /fr/java/conversion/json-to-apng/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: APNG
otherformats: JPEG2000 EMZ PSD WMF WMZ DXF IMAGE SVGZ DICOM TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en APNG via Java" h2="API Java pour analyser le format JSON en APNG dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir le format JSON en APNG dans n'importe quelle application Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en JPEG. Après cela, en utilisant [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), vous pouvez convertir JPEG en APNG.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en APNG via Java" %}}
1. Créez un nouvel objet [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) et ouvrez le fichier JSON
2. Enregistrez JSON au format JPEG en utilisant [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) méthode
3. Chargez le document JPEG en utilisant la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Enregistrez le document au format APNG en utilisant [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
De plus, l'API vous permet d'analyser JSON en APNG avec des options de mise en page spécifiées. Afin de spécifier les options de mise en page, vous pouvez utiliser la classe [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter un tableau comme un tableau, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de date et de nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en APNG via Java" %}}
À l'aide de l'API, vous pouvez également convertir JSON en APNG avec filigrane dans votre document APNG. Pour ajouter un filigrane, vous pouvez d'abord convertir JSON en JPEG et y ajouter un filigrane. Pour ajouter un filigrane, chargez un fichier image à l'aide de la classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), créez un objet de la classe [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) classe et initialisez-la avec l'objet Image, créez une nouvelle [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) et définissez la traduction et la transformation à l'angle souhaité et ajoutez un filigrane à l'aide de [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# méthode drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Après avoir ajouté le filigrane dans votre image, vous pouvez enregistrer le JPEG au format APNG. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-jpeg2000/" name="JSON Pour JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-emz/" name="JSON Pour EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-psd/" name="JSON Pour PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-wmf/" name="JSON Pour WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-wmz/" name="JSON Pour WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dxf/" name="JSON Pour DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-image/" name="JSON Pour IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-svgz/" name="JSON Pour SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dicom/" name="JSON Pour DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-tga/" name="JSON Pour TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}