---
title: Convertir EPUB en DXF via Java
description: Exportez le fichier EPUB vers DXF dans vos applications Java sans utiliser d'application tierce
url_ignore: /fr/java/conversion/epub-to-dxf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DXF
otherformats: EMZ JPEG2000 DXF IMAGE WMF  WMZ PSD TGA SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir EPUB en DXF via Java" h2="Exportez le fichier EPUB vers DXF dans n'importe quelle application Java J2SE, J2EE, J2ME sans utiliser Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir un fichier epub en image DXF en Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter EPUB au format JPEG. Après cela, en utilisant l'API de traitement d'image [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), vous pouvez rendre JPEG en DXF. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exporter EPUB vers DXF via Java" %}}
1. Ouvrez le fichier EPUB à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Initialisez l'objet de classe et rendez EPUB au format JPEG à l'aide de [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. méthode aspose.pdf.Page-java.io.OutputStream-)
3. Chargez le fichier JPEG en utilisant la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Enregistrez le document au format DXF en utilisant [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convertir EPUB en DXF dans un seul fichier via Java" %}}
L'API vous permet également d'exporter le fichier EPUB vers DXF dans un seul fichier. Afin de convertir toutes les pages, vous pouvez d'abord rendre votre document EPUB dans un fichier TIFF, puis exporter le fichier TIFF vers DXF. Vous pouvez ouvrir le fichier d'entrée à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et créer des objets de périphérique Resolution, TiffSettings et TIFF. Vous pouvez obtenir une seule image TIFF en utilisant [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) méthode de la classe [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Enfin, vous pouvez charger le fichier TIFF à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et l'enregistrer au format DXF à l'aide de [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir EPUB en DXF avec filigrane via Java" %}}
À l'aide de l'API, vous pouvez également exporter un fichier EPUB vers DXF avec un filigrane dans votre document DXF. Afin d'ajouter un filigrane, vous pouvez d'abord convertir EPUB en JPEG et y ajouter un filigrane. Pour ajouter un filigrane, chargez un fichier image à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), créez un objet de la classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) classe et initialisez-la avec l'objet Image, créez une nouvelle [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) et définissez la traduction et la transformation à l'angle souhaité et ajoutez un filigrane à l'aide de [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# méthode drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Après avoir ajouté le filigrane dans votre image, vous pouvez enregistrer le JPEG au format DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir et faire pivoter EPUB en fichier DXF via Java" %}}
À l'aide de l'API, vous pouvez également faire pivoter l'image DXF de sortie selon vos besoins. La méthode Image.rotateFlip peut être utilisée pour faire pivoter l'image de 90/180/270 degrés et retourner l'image horizontalement ou verticalement. La bibliothèque fournit des méthodes simples pour effectuer des opérations complexes tout en encapsulant tous les détails laids. Vous pouvez spécifier le type de rotation et de retournement à appliquer à l'image. Pour faire pivoter et retourner l'image, vous pouvez charger l'image JPEG convertie à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) et appeler Image. rotateFlip tout en spécifiant le [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) approprié. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
La conversion d'**EPUB en DXF** est importante pour générer des **fichiers d'échange de dessins compatibles avec CAO** à partir de publications numériques. Ce processus permet de réutiliser le contenu technique, d'ingénierie et architectural des livres électroniques dans des formats prêts pour la CAO, rendant les diagrammes et illustrations plus accessibles pour les flux de travail professionnels. En extrayant des visuels structurés de l'EPUB en DXF, les éditeurs, ingénieurs et architectes peuvent rationaliser la documentation de conception, améliorer l'interopérabilité et renforcer la facilité d'utilisation des ressources.

{{% blocks/products/pf/agp/feature-section-col title="Principaux cas d'utilisation" %}}
- **Manuels techniques avec des diagrammes** – Convertir des illustrations pédagogiques en fichiers CAO modifiables.
- **Contenu d'eBook d'ingénierie** – Transformer les ressources d'ingénierie numériques en dessins compatibles avec la CAO.
- **Documents de référence architecturaux** – Réutiliser les conceptions de bâtiments et les diagrammes des livres électroniques.
- **Publication de ressources liées à la CAO** – Fournir des publications techniques dans des formats prêts pour DXF.
- **Flux de travail de documentation de conception** – Normaliser et réutiliser des diagrammes au sein des équipes d'ingénierie.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}
- **Pipelines de conversion EPUB en DXF** – Automatiser les flux de travail pour générer des fichiers prêts pour la CAO à grande échelle.
- **Extraction automatisée d'illustrations techniques** – Extraire instantanément des diagrammes des livres électroniques en DXF.
- **Publication prête pour la CAO** – Fournir aux ingénieurs et architectes des formats CAO directement utilisables.
- **Documentation d'ingénierie d'entreprise** – Intégrer la conversion EPUB en DXF dans des systèmes de documentation à grande échelle.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}