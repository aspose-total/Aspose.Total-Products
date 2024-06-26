---
title: Konvertieren Sie das JSON-Format über C++ in EPUB
description: C++ API t0 Parsen von JSON in EPUB ohne Verwendung von Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: EPUB
otherformats: DOTX DOCM WORDML OTT WORD MOBI PCL DOT ODT FLATOPC CHM DOC PS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie das JSON-Format über C++ in EPUB" h2="Analysieren Sie JSON in EPUB innerhalb von C++-Anwendungen, ohne Microsoft<sup>&reg;</sup> Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for C++](https://products.aspose.com/total/cpp/) können Sie JSON in zwei einfachen Schritten in EPUB innerhalb Ihrer C++-Anwendungen parsen. Erstens können Sie mit [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) JSON in PDF exportieren. Danach können Sie mit [Aspose.Words for C++](https://products.aspose.com/words/cppp/) PDF in EPUB konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie das JSON-Format in C++ in EPUB" %}}
1. Erstellen Sie ein neues [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)-Objekt und lesen Sie gültige JSON-Daten aus der Datei
2. Speichern Sie JSON als PDF mit der Methode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
3. Laden Sie das PDF-Dokument mithilfe der Klasse [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) im EPUB-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Legen Sie das Layout fest und konvertieren Sie das JSON-Format in C++ in EPUB" %}}
Beim Analysieren von JSON in EPUB können Sie auch die Größe von Zeilen und Spalten festlegen, indem Sie JSON mit der Klasse [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) laden. Wenn Sie dieselbe Zeilenhöhe für alle Zeilen im Arbeitsblatt festlegen müssen, können Sie dies tun, indem Sie [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f )-Methode der Sammlung [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Um dieselbe Spaltenbreite für alle Spalten im Arbeitsblatt festzulegen, verwenden Sie die Methode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) der ICells-Sammlung.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie das JSON-Format in EPUB mit Wasserzeichen in C++" %}}
Mit der API können Sie auch JSON zu EPUB mit Wasserzeichen parsen. Um Ihrem EPUB-Dokument ein Wasserzeichen hinzuzufügen, können Sie zuerst JSON in PDF konvertieren und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie die neu erstellte PDF-Datei mit der Klasse [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), legen Sie verschiedene Eigenschaften für das Textwasserzeichen fest,
Rufen Sie die SetText-Methode auf und übergeben Sie den Wasserzeichentext und das Objekt von TextWatermarkOptions. Nachdem Sie das Wasserzeichen hinzugefügt haben, können Sie das Dokument in EPUB speichern.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}