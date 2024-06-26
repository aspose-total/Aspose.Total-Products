---
title: Konvertieren Sie das JSON-Format über C++ in PPSM
description: Analysieren Sie JSON in PPSM in C++, ohne Microsoft PowerPoint zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POT PPS PPTM OTP POTX PPT PPSX POWERPOINT POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie das JSON-Format über C++ in PPSM" h2="C++-API zum Analysieren von JSON in PPSM ohne Verwendung von Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können JSON in jeder C++-Anwendung in zwei einfachen Schritten in PPSM konvertieren. Erstens können Sie mit [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) JSON in PPTX parsen. Danach können Sie mit [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) PPTX in PPSM konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie das JSON-Format über C++ in PPSM" %}}
1. Erstellen Sie ein neues [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)-Objekt und lesen Sie gültige JSON-Daten aus der Datei
2. Speichern Sie JSON als PPTX mit der Methode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Speichern Sie das Dokument im PPSM-Format mit der Methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Legen Sie das Layout fest und konvertieren Sie das JSON-Format über C++ in PPSM" %}}
Beim Analysieren von JSON zu PPSM können Sie auch die Größe von Zeilen und Spalten festlegen, indem Sie JSON mit der Klasse [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) laden. Wenn Sie dieselbe Zeilenhöhe für alle Zeilen im Arbeitsblatt festlegen müssen, können Sie dies tun, indem Sie [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f )-Methode der Sammlung [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Um dieselbe Spaltenbreite für alle Spalten im Arbeitsblatt festzulegen, verwenden Sie die Methode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) der ICells-Sammlung.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie das JSON-Format in PPSM mit Wasserzeichen in C++" %}}
Mit der API können Sie auch JSON in PPSM mit Wasserzeichen konvertieren. Um Ihrem PPSM-Dokument ein Wasserzeichen hinzuzufügen, können Sie zuerst JSON in PPTX parsen und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie die neu erstellte PPTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), rufen Sie die erste Folie ab, fügen Sie eine hinzu AutoShape vom Typ Rectangle, fügen Sie TextFrame zum Rectangle hinzu, erstellen Sie das Paragraph-Objekt für einen Textrahmen, erstellen Sie das Portion-Objekt für den Absatz, fügen Sie Wasserzeichen mit set_Text() hinzu und speichern Sie das Dokument im PPSM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}