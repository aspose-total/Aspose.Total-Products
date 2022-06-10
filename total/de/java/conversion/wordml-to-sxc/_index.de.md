---
title: Java-API zum Konvertieren von WORDML in SXC
description: Konvertieren Sie WORDML über Java in SXC, ohne Microsoft Word oder Microsoft Excel zu verwenden
url_ignore: /de/java/conversion/wordml-to-sxc/
family: total
platformtag: net
feature: conversion
informat: WORDML
outformat: SXC
otherformats: SXC XLSX XLSB XLT FODS XLAM XLSM XLTM DIF XLTX TSV EXCEL XLS ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie WORDML über Java in SXC" h2="Lokale Java-API zum Konvertieren von WORDML in SXC, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von WORDML in SXC über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie WORDML in HTML exportieren. Danach können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in SXC konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von WORDML in SXC" %}}
1. Öffnen Sie die WORDML-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie WORDML in HTML mit [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im SXC-Format mit [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.Words for Java](https://wordmls.aspose.com/words/java/installation/) und [Aspose.Cells for Java](https://wordmls.aspose.com/cells/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}[UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)
Vor dem Konvertieren von WORDML in SXC können Sie nicht verwendete Informationen aus dem WORDML-Dokument über [Aspose.Words for Java](https://products.aspose.com/words/java/) entfernen. Manchmal müssen Sie nicht verwendete oder doppelte Informationen entfernen, um die Größe des Ausgabedokuments und die Verarbeitungszeit zu reduzieren. Mit der Klasse [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) können Sie Optionen für die Dokumentbereinigung angeben. Um doppelte Stile oder einfach nicht verwendete Stile oder Listen aus dem Dokument zu entfernen, können Sie die Methode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) verwenden. Sie können die [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) und [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)-Eigenschaften zum Erkennen und Entfernen von Stilen, die als „nicht verwendet“ markiert sind.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie nicht verwendete Informationen aus einem WORDML-Dokument über Java" %}}
Nach der Konvertierung von WORDML in SXC können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Ihr Dokument zum Streamen speichern. Wenn Sie Dateien in einem Stream speichern müssen, sollten Sie ein FileOutputStream-Objekt erstellen und dann [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) die Datei zu diesem Stream-Objekt durch Aufrufen der save-Methode von [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xlsm/" name="WORDML Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xlt/" name="WORDML Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-ods/" name="WORDML Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-tsv/" name="WORDML Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xls/" name="WORDML Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xlsb/" name="WORDML Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-fods/" name="WORDML Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-dif/" name="WORDML Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xltx/" name="WORDML Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xlam/" name="WORDML Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xlsx/" name="WORDML Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-xltm/" name="WORDML Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-sxc/" name="WORDML Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/wordml-to-excel/" name="WORDML Zu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}