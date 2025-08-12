---
title: Java-API zum Rendern von CGM in TXT
description: Exportieren Sie CGM über die Java-API in TXT, ohne Microsoft Excel oder Adobe Reader zu verwenden
url_ignore: /de/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM über Java nach TXT exportieren" h2="Konvertieren Sie die CGM-Datei in TXT, indem Sie die lokale Java-API in beliebigen Java J2SE-, J2EE-, J2ME-Anwendungen verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie die CGM-zu-TXT-Konvertierungsfunktion in Ihren Java-Anwendungen in einem zweistufigen Prozess integrieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) CGM in XLSX rendern. Im zweiten Schritt können Sie XLSX in TXT konvertieren, indem Sie die Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die CGM-Datei über Java in TXT" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie CGM in XLSX mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im TXT-Format mit [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und enthalten [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in Ihrer pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Wenn Ihr CGM-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in TXT konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes CGM über Java in TXT" %}}
Während Sie eine CGM-Datei in TXT konvertieren, können Sie Ihrem Ausgabe-TXT-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, erstellen Sie eine neue Arbeitsmappe, um die konvertierte XLSX-Datei zu öffnen. Wählen Sie das Arbeitsblatt über seinen Index aus, erstellen Sie eine Form und verwenden Sie die Funktion addTextEffect, stellen Sie Farben, Transparenz und mehr ein. Danach können Sie Ihr XLSX-Dokument als TXT mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Konvertieren von **Computer Graphics Metafile (CGM)**-Dateien in das **TXT (Plain Text)**-Format ist wertvoll, um Vektorgrafikinformationen in einer leichten, menschenlesbaren Form zu extrahieren, zu dokumentieren und zu verarbeiten. In **Java-gesteuerten Datenverarbeitungspipelines** ermöglicht diese Konvertierung die Umwandlung von CGM-Diagrammen in textbasierte Darstellungen für Logging, Metadatenspeicherung oder nachgelagerte Analysen. Durch das Erfassen der beschreibenden Elemente von CGM-Dateien in TXT können Organisationen die Integration mit anderen Systemen vereinfachen, schnelle Suche und Indizierung ermöglichen und langfristige Kompatibilität sicherstellen.



## ✅ Hauptanwendungsfälle

- **Textbasiertes Protokollieren von Diagrammen**  
  Speichern von CGM-Diagramminformationen als Klartext für Auditierung, Debugging oder Archivierungszwecke.

- **Extrahieren von Vektorgrafikbeschreibungen**  
  Konvertieren von CGM-Strukturen in TXT zum Parsen, Suchindizieren oder zur Integration mit Analysetools.

- **Dokumentation von Engineering-Metadaten**  
  Dokumentieren von CGM-bezogenen Ingenieurdaten in TXT-Dateien für schnelle Referenz und leichte Speicherung.


## ⚙️ Automatisierungsszenarien

- **Java I/O-Bibliotheken für Konvertierung**  
  Verwenden von Standard-Java-Dateiverarbeitungs-APIs zusammen mit CGM-Parsern, um Inhalte in TXT-Dateien zu extrahieren und zu schreiben.

- **Dateiüberwachungsdienste**  
  Automatisieren der CGM-in-TXT-Konvertierung durch Überwachen von Verzeichnissen mit dem Java `WatchService` auf neue Dateiereignisse.

- **Batch-Konvertierungsaufträge**  
  Verarbeiten großer Mengen von CGM-Dateien in geplanten Java-Aufträgen und exportieren textuelle Darstellungen für Archivierung oder Analyse.

- **Plain Text-Exporteure in ETL-Pipelines**  
  Integrieren von CGM-Parsing und TXT-Export in Java-basierte Extract-Transform-Load-Workflows für strukturierte Datenverarbeitung.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}