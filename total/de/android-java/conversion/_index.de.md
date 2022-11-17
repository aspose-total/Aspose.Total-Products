---
title: Dokumentenkonvertierung über Android API 

description: Konvertieren Sie Word-, Excel-, PowerPoint-, HTML-, PDF- und Bildformate mit der Android-Konvertierungs-API. Android konvertiert Office docx, xlsx, pptx in PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentenkonvertierung mit Android API" h2="Konvertieren Sie Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Bilder und verschiedene andere Formate mit Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) bietet die Dokumentkonvertierungs- und -verwaltungslösung für Android-Anwendungen, ohne auf andere Software angewiesen zu sein. Programmierer können die Dokumentenverwaltungs- und Bearbeitungslösung einfach automatisieren, indem sie die API in neu entwickelte Anwendungen oder in bestehende Anwendungen integrieren. Durch die Integration der API kann der Programmierer einfach Funktionen hinzufügen, um Dokumente in verschiedenen Formaten innerhalb der Anwendung zu erstellen, zu bearbeiten oder zu konvertieren. Die PDF Converter API in Android verarbeitet Konvertierungsfälle wie Office DOCX, XLSX, PPTX in PDF oder umgekehrt. Darüber hinaus sind unten einige Fälle aufgeführt, die von der API behandelt werden, sowie einige Links für die relevanten Konvertierungsfälle. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PDF in CSV" %}}
Total Android API unterstützt die Konvertierung von PDF in Excel XLSX und CSV. Es ist ein zweistufiger Prozess. Insgesamt zwei APIs [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) und [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) beteiligt. Der Prozess ist, dass Sie zuerst PDF in das Excel XLSX-Format und dann XLSX in CSV umwandeln können. Genauer gesagt, laden Sie die PDF-Datei über die Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) und rendern Sie sie über [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-)-Methode. Laden Sie als Nächstes das gerenderte XLSX-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) und rufen Sie [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) Methode.

{{% blocks/products/pf/feature-page-code h3="Android - PDF-zu-Excel-Konvertierung" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertierung von Excel in Word" %}}
Die Android-API übernimmt auch die Excel-Konvertierung. Der Prozess ist, Laden Sie die EXCEL XLSX-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) und konvertieren Sie EXCEL in PDF, indem Sie zuerst SaveFormat auf AUTO setzen. Laden Sie als Nächstes die gespeicherte PDF-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) und rufen Sie [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode, um das Dokument im Word DOC/DOCX-Format zu speichern.

{{% blocks/products/pf/feature-page-code h3="Android - Konvertierung von Excel in Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie POWERPOINT in HTML und MHTML" %}}
Die Android Total API verarbeitet verschiedene Formate, einschließlich PowerPoint-Dateien, sodass Präsentationen in HTML und MHTML konvertiert werden können. Prozess ist, Laden Sie die POWERPOINT PPT/PPTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) und rufen Sie [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode zum Konvertieren von POWERPOINT in HTML. Laden Sie außerdem jetzt das konvertierte HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) und rufen Sie [save](https://reference.aspose.com/cells/java/com.aspose.cells/) Methode für die MHTML-Konvertierung. 
{{% blocks/products/pf/feature-page-code h3="Android - Konvertierung von PowerPoint-Folien in HTML und MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}