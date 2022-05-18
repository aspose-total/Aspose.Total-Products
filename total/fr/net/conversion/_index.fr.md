---
title: Conversion de format de fichier via C# 
url: /fr/net/conversion/
description: Convertissez Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, des images 3D, des diagrammes, des formats vidéo et de nombreux autres fichiers populaires avec seulement quelques lignes de code C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversion de format de fichier via C# .NET" h2="Convertissez des fichiers Microsoft<sup>®</sup> Office, PDF, Images, HTML et différents autres formats sans utiliser d'autre logiciel." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Bibliothèque totale .NET](https://products.aspose.com/total/net/) accélère le développement de solutions de gestion de documents à partir de zéro ou l'amélioration d'applications existantes pour gérer facilement la manipulation de documents. L'API gère non seulement les documents Microsoft Office, mais gère également les fichiers PDF, HTML, les images TIFF, JPG, PNG, BMP et SVG, les fichiers de courrier électronique, les formats vidéo, les formats de données SIG et bien plus encore. Il s'agit d'un ensemble complet d'API de solution de gestion et de manipulation de documents sans aucune dépendance logicielle. Les programmeurs peuvent facilement créer, mettre à jour, rendre, imprimer et convertir entre les formats les plus populaires dans toutes les applications basées sur .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Word en PDF" %}}
L'API Total prend en charge non seulement l'interconversion des formats Microsoft Word, mais également la conversion de Word en PDF, HTML, Images, EPUB, Markdown et XPS. Le processus de conversion est simple. Chargez le document via la classe Document et appelez simplement la méthode Save avec le format cible. C'est si simple. Les développeurs peuvent vérifier le [résultat de la conversion](https://products.aspose.com/words/net/conversion/word-to-pdf/) avant l'intégration du code de **Word en PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Conversion Word en PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir des PDF en images" %}}
L'API prend en charge la conversion de PDF en images, Powerpoint, Excel et d'autres formats. Pour la conversion PDF en image, considérons l'image JPG comme fichier cible. Le processus consiste à charger le fichier PDF à l'aide de la classe Document et à initialiser l'objet [classe JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) et à rendre le PDF au format JPEG via [Processus](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) méthode
Chargez le fichier JPEG en utilisant la classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) et enfin appelez la méthode Save.

{{% blocks/products/pf/feature-page-code h3="C# - Conversion de PDF en image" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Excel en Word et PowerPoint" %}}

Pour convertir les formats Microsoft Excel en différents fichiers, y compris Word et PowerPoint, les sous-API pertinentes impliquées dans l'API principale Aspose.Total pour .NET. Processus de conversion de fichiers Excel en document Word, chargez le fichier EXCEL à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) et convertissez d'abord EXCEL en PDF et définissez SaveFormat sur Auto. Chargez ensuite le fichier PDF converti à l'aide de la classe Document et appelez la méthode Save et définissez Doc, Docx comme SaveFormat. Code également répertorié pour la conversion Microsoft **Excel vers Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Conversion de JSON en Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Conversion d'Excel en JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}