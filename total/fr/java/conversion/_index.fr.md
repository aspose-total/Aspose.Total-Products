---
title: Conversion de format de fichier via Java 

description: Convertissez Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, images 3D, diagrammes, formats vidéo et différents autres formats avec seulement quelques lignes de code Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversion de format de fichier via Java" h2="Convertissez des documents Microsoft<sup>®</sup> Office, PDF, Images, HTML et plusieurs autres fichiers sans utiliser d'autre logiciel." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) accélère le développement de solutions de manipulation de documents à partir de zéro ou améliore les applications existantes pour gérer facilement la gestion des documents. L'API crée, édite et convertit non seulement des documents Microsoft Office, mais gère également les fichiers PDF, HTML, TIFF, JPG, PNG, BMP et SVG, les fichiers de courrier électronique, les formats vidéo, la 3D, la CAO et bien plus encore. Il s'agit d'une collection d'API de solutions de gestion et de manipulation de documents sans aucune dépendance logicielle dans les applications Java J2SE, J2EE, J2ME. Les programmeurs peuvent facilement créer, mettre à jour, rendre, imprimer et convertir entre les formats les plus populaires dans toutes les applications basées sur Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversion de Word en Excel" %}}
Total API prend en charge non seulement la conversion inter des formats Microsoft Word, mais également la conversion de Word en Excel, PDF, HTML, Images, EPUB, Markdown et XPS. Le processus de conversion est simple. Considérons le cas de la conversion **Word vers Excel**. Chargez le fichier Microsoft Word à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) et convertissez **WORD en HTML** à l'aide de la [méthode Save](https : //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Ouvrez ensuite le document HTML converti à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et enregistrez le document au format XLSX à l'aide de [Save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Les développeurs peuvent également convertir [Word en PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Conversion de Word en Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir des PDF en images" %}}
L'API prend en charge la conversion de PDF en images telles que JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel et d'autres formats. Pour la conversion PDF en image, considérons l'image JPG comme fichier cible. Le processus consiste à charger le fichier PDF à l'aide de la classe Document et à initialiser l'objet [classe JpegDevice](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) et à rendre le PDF au format JPEG via [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) méthode
Chargez le fichier JPEG à l'aide de la classe [Image](https://reference.aspose.com/imaging/java/aspose.imaging/image) et appelez enfin la méthode Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir des fichiers PowerPoint en fichiers Excel" %}}

Pour convertir des fichiers Microsoft PowerPoint en différents fichiers, y compris Excel Word, MHTML, les sous-API pertinentes impliquées dans l'API principale Aspose.Total pour Java. Processus de conversion de fichiers PowerPoint en document Excel, chargez le fichier PowerPoint à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) et convertissez **PowerPoint en HTML** en en utilisant la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Chargez ensuite le document HTML converti à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et enregistrez le document au format EXCEL à l'aide de [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)). Le code pour la conversion **PowerPoint vers Word** est également répertorié.

{{% blocks/products/pf/feature-page-code h3="Conversion Java PowerPoint en Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Conversion Java PowerPoint en Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}