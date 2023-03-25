---
title: Konvertieren Sie das JSON-Format über Java in OTT
description: Analysieren Sie JSON in OTT in Java, ohne Microsoft Word zu verwenden
url_ignore: /de/java/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC WORD MOBI RTF DOCM EPUB ODT OTT PS WORDML DOT PCL FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie das JSON-Format über Java in OTT" h2="Lokale Java-API zum Parsen von JSON in OTT ohne Verwendung von Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie JSON in Ihren Java-Anwendungen in zwei Schritten in OTT konvertieren. Erstens können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) JSON in PDF parsen. Im zweiten Schritt können Sie PDF in OTT konvertieren, indem Sie die Textverarbeitungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie das JSON-Format über Java in OTT" %}}
1. Erstellen Sie ein neues [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)-Objekt und lesen Sie gültige JSON-Daten aus der Datei
2. Importieren Sie die JSON-Datei in das Arbeitsblatt mit der Klasse [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) und [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) als PDF
3. Laden Sie das PDF-Dokument mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im OTT-Format mit [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Darüber hinaus können Sie mit der API Layoutoptionen für Ihr JSON festlegen, während Sie JSON mit [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) in OTT parsen. Es ermöglicht Ihnen, Array als Tabelle zu verarbeiten, Nullen zu ignorieren, Array-Titel zu ignorieren, Objekttitel zu ignorieren, Zeichenfolge in Zahl oder Datum umzuwandeln, Datums- und Zahlenformat festzulegen und Titelstil festzulegen. Alle diese Optionen ermöglichen es Ihnen, Ihre Daten nach Ihren Bedürfnissen zu präsentieren. Das folgende Code-Snippet zeigt Ihnen, wie Sie die Layout-Optionen festlegen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Legen Sie das Layout fest und konvertieren Sie das JSON-Format über Java in OTT" %}}
Mit der API können Sie auch JSON zu OTT mit Wasserzeichen parsen. Um Ihrem OTT-Dokument ein Wasserzeichen hinzuzufügen, können Sie zuerst die JSON-Datei in PDF konvertieren und ihr ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie die neu erstellte PDF-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), erstellen Sie eine Instanz von TextWatermarkOptions und setzen Sie sie seine Eigenschaften, Methode Watermark.setText aufrufen und Wasserzeichentext und Objekt von TextWatermarkOptions übergeben. Nachdem Sie das Wasserzeichen hinzugefügt haben, können Sie das Dokument in OTT speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}