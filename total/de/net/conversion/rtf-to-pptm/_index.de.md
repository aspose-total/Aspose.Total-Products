---
title: Konvertieren Sie RTF in PPTM über C# .NET 
url: /de/net/conversion/rtf-to-pptm/ 
description: Konvertieren Sie Word-Dokumente mit C# in PowerPoint-PPTM-Dateien. Konvertieren Sie mehrere Dateien innerhalb von ASP.NET oder anderen .NET-Anwendungen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie RTF in PPTM mit C#" h2="Erstellen Sie Microsoft Word RTF-zu-PowerPoint-PPTM-Konvertierungs-Apps auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" rtfsLink="https://rtfs.aspose.com/total/net" installationsRtfsLink="https://rtfs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://rtfs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie RTF in PPTM mit C#" %}}

Um den Vorgang für die Stapelkonvertierung von Word-Dokumentdateien in PowerPoint-PPTM-Präsentationen zu automatisieren, verwenden wir [Aspose.Words for .NET](https://products.aspose.com/words/net) und [Aspose.Slides für .NET](https://products.aspose.com/slides/net)-APIs. Ersteres ist eine Textverarbeitungs-API zum Verarbeiten oder Bearbeiten von Microsoft Word-Dokumenten. Letzteres ist eine API zur Manipulation von Präsentationen, mit der Sie Microsoft PowerPoint-Folien erstellen oder ändern können. Beide APIs sind Teil des Pakets [Aspose.Total for .NET](https://products.aspose.com/total/net). Sie können direkt von Nuget [herunterladen](https://downloads.aspose.com/) oder die folgenden Befehle aus der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von RTF in PPTM über C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Fügen Sie eine Referenz von Aspose.Total für .NET hinzu
1. Laden Sie die RTF-Datei mit der Klasse [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document).
1. Speichern Sie das RTF-Dokument in HTML
1. Erstellen Sie das Objekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
1. Importieren Sie HTML-Inhalte in Textrahmen einer beliebigen Folienform innerhalb der Präsentation
1. Speichern Sie das Dokument mit [Aspose.Slides.Presentation.Save("output.pptm", SaveFormat.Pptm)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Words für .NET &amp; Aspose.Slides für .NET-DLLs oder Aspose.Total für .NET-DLLs, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieses Codebeispiel zeigt, wie Sie ein RTF mit C# in PPTM konvertieren." offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word RTF file
Aspose.Words.Document rtf = new Aspose.Words.Document("sourceWordFile.rtf");

// Save RTF file to HTML 
rtf.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages RTF documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTM.

using (Presentation pptm = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPTM Presentation
	pptm.Save("filepath\\pres.pptm", Aspose.Slides.Export.SaveFormat.Pptm);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von RTF in PPTM" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-ppt/" name="RTF Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-pptx/" name="RTF Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-pps/" name="RTF Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-pot/" name="RTF Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-ppsx/" name="RTF Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-pptm/" name="RTF Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-ppsm/" name="RTF Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-potx/" name="RTF Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-potm/" name="RTF Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-pptm/" name="RTF Zu PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}