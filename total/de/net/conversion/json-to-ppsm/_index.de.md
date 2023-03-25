---
title: Konvertieren Sie das JSON-Format über .NET in PPSM
description: Analysieren Sie JSON in PPSM in C#, ohne Microsoft PowerPoint zu verwenden
url_ignore: /de/net/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POTM PPS PPSM POWERPOINT POT OTP PPT POTX PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie das JSON-Format über C# in PPSM" h2="C#-API zum Analysieren von JSON in PPSM ohne Verwendung von Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können JSON in jeder .NET-, C#-, ASP.NET- und VB.NET-Anwendung in zwei einfachen Schritten in PPSM konvertieren. Erstens können Sie mit [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) JSON in PPTX parsen. Danach können Sie mit [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in PPSM konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie das JSON-Format über C# in PPSM" %}}
1. Erstellen Sie ein neues [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)-Objekt und lesen Sie gültige JSON-Daten aus der Datei
2. Importieren Sie die JSON-Datei in das Arbeitsblatt mit der Klasse [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) und [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) als PPTX
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im PPSM-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Legen Sie das Layout fest und konvertieren Sie das JSON-Format über C# in PPSM" %}}
Beim Analysieren von JSON zu PPSM können Sie auch Layoutoptionen für Ihr JSON-Format mit [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) festlegen. Sie können ein Array als Tabelle verarbeiten, Nullen ignorieren, den Array-Titel ignorieren, den Objekttitel ignorieren, eine Zeichenfolge in eine Zahl oder ein Datum konvertieren, das Datums- und Zahlenformat festlegen und den Titelstil festlegen. Alle diese Optionen ermöglichen es Ihnen, Ihre Daten nach Ihren Bedürfnissen zu präsentieren. Das folgende Code-Snippet zeigt Ihnen, wie Sie die Layout-Optionen festlegen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie das JSON-Format in PPSM mit Wasserzeichen" %}}
Mit der API können Sie auch JSON in PPSM mit Wasserzeichen konvertieren. Um Ihrem PPSM-Dokument ein Wasserzeichen hinzuzufügen, können Sie zuerst JSON in PPTX parsen und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie die neu erstellte PPTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), wählen Sie die Master-Präsentation aus und fügen Sie den Formtyp hinzu AddAutoShape, und fügen Sie Wasserzeichentext mit AddTextFrame hinzu. Nachdem Sie das Wasserzeichen hinzugefügt haben, können Sie das Dokument im PPSM speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}