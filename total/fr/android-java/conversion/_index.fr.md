---
title: Conversion de documents via l'API Android 

description: Convertissez les formats Word, Excel, PowerPoint, HTML, PDF et Image à l'aide de l'API de conversion Android. Android convertit Office docx, xlsx, pptx en PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversion de documents à l'aide de l'API Android" h2="Convertissez Microsoft<sup>®</sup> Office Word, Excel, PowerPoint, PDF, Images et divers autres formats en utilisant Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) fournit la solution de conversion et de gestion de documents pour les applications Android sans dépendre d'aucun autre logiciel. Les programmeurs peuvent automatiser facilement la solution de gestion et de manipulation de documents en intégrant l'API dans de nouvelles applications développées ou dans des applications existantes. En intégrant l'API, le programmeur peut facilement ajouter des fonctionnalités pour créer, modifier ou convertir divers documents de format dans l'application. L'API PDF Converter dans Android gère les cas de conversion tels que Office DOCX, XLSX, PPTX en PDF ou vice versa. De plus, peu de cas traités par l'API sont répertoriés ci-dessous et peu de liens sont donnés pour les cas de conversion pertinents. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PDF en CSV" %}}
L'API Android totale prend en charge la conversion PDF vers Excel XLSX et CSV. C'est un processus en deux étapes. Deux API totales [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) et [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) impliqués. Le processus est que vous pouvez d'abord convertir le format PDF en Excel XLSX, puis XLSX en CSV. Plus en détail, chargez le fichier PDF via la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et rendez-le au format XLSX via [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Chargez ensuite le document XLSX rendu à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et appelez [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android - Conversion de PDF en Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversion d'Excel en Word" %}}
L'API Android gère également la conversion Excel. Le processus consiste à charger le fichier EXCEL XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et à convertir EXCEL en PDF en définissant d'abord SaveFormat sur AUTO. Chargez ensuite le fichier PDF enregistré à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et appelez [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) pour enregistrer le document au format Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Conversion d'Excel en Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir POWERPOINT en HTML et MHTML" %}}
L'API Android Total traite divers formats, y compris les fichiers PowerPoint, et peut donc convertir des présentations en HTML et MHTML. Le processus est de charger le fichier POWERPOINT PPT/PPTX à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) et d'appeler [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) pour convertir POWERPOINT en HTML. De plus, chargez maintenant le document HTML converti en utilisant la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et appelez [save](https://reference.aspose.com/cells/java/com.aspose.cells/) pour la conversion MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - Conversion de diapositives PowerPoint en HTML et MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}