---
title: Konvertieren Sie Webseiten-HTML in Bilder mit C#
description: Scrapen Sie Website-Webseiten und exportieren Sie HTML in Bilder. Entwickeln Sie .NET-Anwendungen, um Website-Daten in JPEG, PNG, GIF, BMP usw. zu konvertieren. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie Webseiten über C# in Bilder" h2="Extrahieren Sie Website-Daten aus HTML-Webseiten. Konvertieren Sie HTML in JPG-, GIF-, PNG- und BMP-Bilder in .NET-Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Warum Webseiten in Bilder konvertieren?</h2>
<p>Das Konvertieren von Webseiten in Bilder kann in verschiedenen Situationen nützlich sein. Dies ist eine allgemeine Anforderung für viele Anwendungen. In manchen Szenarien ist es notwendig, die gesamte Webseite als Bild zu erfassen, einschließlich der Teile, die nicht auf dem Bildschirm sichtbar sind. Dies kann nützlich sein, um Website-Vorschauen zu erstellen, Quittungen und Rechnungen zu erfassen oder Webseiten für rechtliche Zwecke zu archivieren. Damit lassen sich Screenshots von Webseiten zu Dokumentations- oder Testzwecken erstellen. Es kann auch zum Erstellen von Miniaturansichten oder Vorschauen von Webseiten zur Verwendung in Suchergebnissen oder Bildergalerien verwendet werden. Unabhängig davon, ob Sie eine Desktop-Anwendung oder eine Webanwendung erstellen, stehen zahlreiche Optionen zum Konvertieren von Webseiten in Bilder mit C# zur Verfügung.</p><br />

<p>Das Konvertieren von Webseiten in Bilder mit C# kann mehrere Vorteile bieten, darunter:</p><br />
<ul>
<li>Verbesserte Zugänglichkeit: Bilder können für Menschen mit Sehbehinderungen oder anderen Behinderungen leichter lesbar und verständlich sein.</li>
<li>Erhöhte Portabilität: Bilder können einfach geteilt oder in andere Dokumente oder Anwendungen eingebettet werden.</li>
</ul>
<p>Das Konvertieren von Webseiten in Bilder mit C# kann ebenfalls einige Herausforderungen mit sich bringen, darunter:</p><br />
<ul>
<li>Eingeschränkte Formatunterstützung: Einige APIs oder Tools unterstützen möglicherweise nicht alle Bildformate oder haben Einschränkungen hinsichtlich der Größe oder Auflösung der Ausgabebilder.</li>
<li>Kompatibilitätsprobleme: Einige Webseiten werden möglicherweise nicht in allen Browsern korrekt dargestellt oder erfordern möglicherweise bestimmte Einstellungen oder Plugins, um ordnungsgemäß angezeigt zu werden.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Wie konvertiere ich Webseiten mit C# in Bilder?" %}}
Um Webseiten mit C# in Bilder zu konvertieren, können Sie eine Aspose.HTML für .NET-API verwenden, die diese Funktionalität zum Konvertieren von HTML-Seiten in Bildformate, einschließlich JPEG, PNG und TIFF, bereitstellt.</p>

1. Laden Sie ein HTML-Dokument mit einem der in verfügbaren Konstruktoren [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
2. Erstellen Sie eine neue Instanz von [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) und setzen Sie die ImageFormat-Eigenschaft auf JPEG. Standardmäßig ist die Format-Eigenschaft auf PNG festgelegt.
3. Nutzen Sie die [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) Methode aus der Converter-Klasse, um das HTML-Dokument als JPEG-Datei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad als Parameter für die ConvertHTML()-Methode angeben.
4. Die resultierende JPEG-Datei wird im angegebenen Dateipfad gespeichert.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Anforderungen an Web-Scraping und Bildkonvertierung" %}}
Installieren Sie über die Befehlszeile als „nuget install Aspose.Total“ oder installieren Sie direkt über die Paket-Manager-Konsole von Visual Studio.

Zwei [Aspose.Total for .NET](https://products.aspose.com/total/net/) untergeordnete API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) integriert werden.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder die DLLs in einer ZIP-Datei von herunterladen [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}