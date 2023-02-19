---
title: Java-API zum Konvertieren von DOC in FODS
description: Konvertieren Sie DOC über Java in FODS, ohne Microsoft Word oder Microsoft Excel zu verwenden
url_ignore: /de/java/conversion/doc-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: FODS
otherformats: SXC XLT EXCEL XLTM XLSB TSV XLTX XLSM XLS XLSX DIF FODS XLAM ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOC über Java in FODS" h2="Lokale Java-API zum Konvertieren von DOC in FODS, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOC in FODS über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOC in HTML exportieren. Danach können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in FODS konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von DOC in FODS" %}}
1. Öffnen Sie die DOC-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie DOC in HTML mit [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im FODS-Format mit [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und enthalten [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) und [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für DOC zu FODS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=fods&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}[UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)
Vor dem Konvertieren von DOC in FODS können Sie nicht verwendete Informationen aus dem DOC-Dokument über [Aspose.Words for Java](https://products.aspose.com/words/java/) entfernen. Manchmal müssen Sie nicht verwendete oder doppelte Informationen entfernen, um die Größe des Ausgabedokuments und die Verarbeitungszeit zu reduzieren. Mit der Klasse [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) können Sie Optionen für die Dokumentbereinigung angeben. Um doppelte Stile oder einfach nicht verwendete Stile oder Listen aus dem Dokument zu entfernen, können Sie die Methode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) verwenden. Sie können die [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) und [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)-Eigenschaften zum Erkennen und Entfernen von Stilen, die als „nicht verwendet“ markiert sind.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie nicht verwendete Informationen aus einem DOC-Dokument über Java" %}}
Nach der Konvertierung von DOC in FODS können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Ihr Dokument zum Streamen speichern. Wenn Sie Dateien in einem Stream speichern müssen, sollten Sie ein FileOutputStream-Objekt erstellen und dann [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) die Datei zu diesem Stream-Objekt durch Aufrufen der save-Methode von [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsm/" name="DOC Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlt/" name="DOC Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-ods/" name="DOC Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-tsv/" name="DOC Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xls/" name="DOC Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsb/" name="DOC Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-fods/" name="DOC Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-dif/" name="DOC Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xltx/" name="DOC Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlam/" name="DOC Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsx/" name="DOC Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xltm/" name="DOC Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-sxc/" name="DOC Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-excel/" name="DOC Zu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}