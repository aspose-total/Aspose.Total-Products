---
title: Konvertieren Sie POT über Java in das JSON-Format
description: Konvertieren Sie POT über Java in das JSON-Format, ohne Microsoft Excel oder PowerPoint zu verwenden
url_ignore: /de/java/conversion/pot-to-json/
family: total
platformtag: net
feature: conversion
informat: POT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie POT über Java in das JSON-Format" h2="Lokale Java-API zum Exportieren von POT in JSON ohne Verwendung von Microsoft<sup>&reg;</sup> Excel oder PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Die Konvertierung von POT in das JSON-Format über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Im ersten Schritt können Sie POT nach HTML exportieren, indem Sie [Aspose.Slides for Java](https://products.aspose.com/slides/java/) verwenden. Zweitens können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie POT über Java in das JSON-Format" %}}
1. Öffnen Sie die POT-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie POT in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im JSON-Format mit [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr eingegebenes POT-Dokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes POT über Java in das JSON-Format" %}}
Während Sie POT in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, einen zu exportierenden Datenbereich mithilfe der Cells.createRange-Methode erstellen, die JsonUtility.exportRangeToJson-Methode mit Verweisen auf Range & ExportRangeToJsonOptions aufrufen und String-JSON-Daten über in eine Datei schreiben BufferedWriter.write-Methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Die Umwandlung von POT-Dateien in JSON (JavaScript Object Notation) ermöglicht eine strukturierte Darstellung von Folieninhalten für Web-, Analyse- und Automatisierungssysteme. JSON wird häufig verwendet, um Präsentationsdaten in APIs, Dashboards und Machine-Learning-Pipelines zu integrieren.



{{% blocks/products/pf/agp/feature-section-col title="Hauptanwendungsfälle" %}}



* Export von Metadaten von PowerPoint-Vorlagen für Analyse oder Berichterstellung.

* Integration von Folieninhalten in Datenvisualisierungs-Webanwendungen.

* Generierung von lernbasierten Inhalten in JSON aus Bildungspräsentationen.

* Extrahieren von Diagramm- oder Textdaten für die Eingabe in KI-Modelle.

&nbsp; {{% /blocks/products/pf/agp/feature-section-col %}}

&nbsp; {{% blocks/products/pf/agp/feature-section-col title="Automatisierungsszenarien" %}}

* Automatisierte JSON-Umwandlung für REST-API-gesteuerte Plattformen.

* Integration mit Data Lakes und ETL-Systemen.

* Geplante Extraktion von Folieninhalten in strukturiertes JSON für Dashboards.

* KI-gesteuerte Indexierung und Markierung von Präsentationsinhalten.

&nbsp; {{% /blocks/products/pf/agp/feature-section-col %}}

&nbsp; {{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}