---
title: Konvertieren Sie POT in TXT über C# .NET 
url: /de/net/conversion/pot-to-txt/ 
description: Konvertieren Sie PowerPoint-POT-Dokumente mit C# in Word-Txt-Dateien. Konvertieren Sie mehrere Dateien innerhalb von ASP.NET oder anderen .NET-Anwendungen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie POT in TXT mit C#" h2="Erstellen Sie Apps zur Umwandlung von Microsoft PowerPoint POT-Präsentationen in Word TXT-Dokumente auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" txtsLink="https://txts.aspose.com/total/net" installationsTxtsLink="https://txts.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://txts.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie POT in TXT mit C#" %}}

Um den Prozess für die Stapelkonvertierung jeder PowerPoint-POT-Präsentation in Word-Dokumentdateien zu automatisieren, verwenden wir [Aspose.Slides for .NET](https://products.aspose.com/slides/net) und [Aspose.Words für .NET](https://products.aspose.com/words/net)-APIs. Ersteres ist eine API zur Manipulation von PowerPoint-Präsentationen, mit der Sie Microsoft PowerPoint-Folien erstellen oder ändern können. Letzteres ist eine Textverarbeitungs-API zum Verarbeiten oder Bearbeiten von Microsoft Word-Dokumenten. Beide APIs sind Teil des Pakets [Aspose.Total for .NET](https://products.aspose.com/total/net). Sie können direkt von Nuget [herunterladen](https://downloads.aspose.com/) oder die folgenden Befehle aus der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von POT in TXT über C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Fügen Sie den Verweis auf Aspose.Slides für .NET und Aspose.Words für .NET hinzu
1. Laden Sie die PowerPoint-POT-Präsentation mithilfe der Klasse [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
1. Speichern Sie das Dokument im Objekt [MemoryStream](https://txts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0).
1. Erstellen Sie [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) und initialisieren Sie es mit dem MemoryStream-Objekt
1. Speichern Sie das Dokument mit [Aspose.Words.Document.Save("output.txt", SaveFormat.Txt)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Slides für .NET und Aspose.Words für .NET DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieses Codebeispiel zeigt, wie Sie ein POT mit C# in TXT konvertieren." offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POT file
Aspose.Slides.Presentation pot = new Aspose.Slides.Presentation("source.pot");

var stream = new MemoryStream();

pot.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var txt = new Aspose.Words.Document(stream);
      
// Save the Word TXT document
txt.Save("output.txt", Aspose.Words.SaveFormat.Txt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von POT in TXT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-txt" name="POT Zu TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-docx" name="POT Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-rtf" name="POT Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-dot" name="POT Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-dotx" name="POT Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-dotm" name="POT Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-docm" name="POT Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-flatopc" name="POT Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-odt" name="POT Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-ott" name="POT Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-wordml" name="POT Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pot-to-txt" name="POT Zu TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}