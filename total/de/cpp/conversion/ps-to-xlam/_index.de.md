---
title: C++-API zum Konvertieren von PS in XLAM
description: Konvertieren Sie PS in XLAM über die C++-API, ohne Microsoft Excel oder Adobe Reader zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: XLAM
otherformats: DIF XLSB XLTX CSV EXCEL FODS SXC XLTM TXT XLT TSV XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie PS in XLAM in C++-Anwendungen" h2="Konvertieren Sie PS in XLAM in nativen C++-Anwendungen, ohne Microsoft<sup>&reg;</sup> Excel oder Adobe<sup>&reg;</sup> Acrobat Reader zu benötigen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von PS in XLAM in C++ über [Aspose.Total for C++](https://products.aspose.com/total/cpp/) Dateiformat-Automatisierungsbibliotheken ist ein einfacher zweistufiger Prozess. Im ersten Schritt können Sie PS mit [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) nach XLSX exportieren, danach mit [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) Spreadsheet Programming API können Sie XLSX in XLAM konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von PS in XLAM" %}}
1. Öffnen Sie die PS-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Konvertieren Sie PS in XLSX, indem Sie die Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) verwenden
3. Laden Sie das XLSX-Dokument mithilfe der Klassenreferenz [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
4. Speichern Sie das Dokument im XLAM-Format mit der Member-Funktion [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="PS-Dateiinformationen über C++ abrufen oder festlegen" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ermöglicht es Ihnen auch, Informationen zu Ihrem PS-Dokument zu erhalten und vor dem Konvertierungsprozess fundierte Entscheidungen zu treffen. Um dateispezifische Informationen einer PS-Datei zu erhalten, müssen Sie zuerst die Methode [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) aufrufen [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) Klasse. Nachdem das DocumentInfo-Objekt abgerufen wurde, können Sie die Werte der einzelnen Eigenschaften abrufen. Darüber hinaus können Sie die Eigenschaften auch festlegen, indem Sie die entsprechenden Methoden der DocumentInfo-Klasse verwenden.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Speichern Sie das XLAM-Dateiformat im Stream über C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) ermöglicht das Speichern des XLAM-Dateiformats zum Streamen. Um Dateien in einem Stream zu speichern, erstellen Sie ein MemoryStream- oder FileStream-Objekt und speichern Sie die Datei in diesem Stream-Objekt, indem Sie [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) aufrufen. Objekts Methode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Geben Sie das gewünschte Dateiformat mit der Enumeration [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) an, wenn Sie die Save-Methode aufrufen.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlam-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-dif/" name="PS Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xlsb/" name="PS Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xltx/" name="PS Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xlam/" name="PS Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-excel/" name="PS Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-fods/" name="PS Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-sxc/" name="PS Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xltm/" name="PS Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-txt/" name="PS Zu TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xlt/" name="PS Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-tsv/" name="PS Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ps-to-xlsm/" name="PS Zu XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}