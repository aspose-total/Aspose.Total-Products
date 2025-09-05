---
title: Konvertieren Sie TXT in POT über C# .NET oder mit dem kostenlosen Online Converter
description: Konvertieren Sie Word-Dokumente mit C# in PowerPoint-POT-Dateien. Konvertieren Sie mehrere Dateien innerhalb von ASP.NET oder anderen .NET-Anwendungen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie TXT in POT mit C# oder online" h2="Erstellen Sie Microsoft Word TXT-zu-PowerPoint-POT-Konvertierungs-Apps auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="So konvertieren Sie TXT in POT mit C#" %}}

Um den Vorgang für die Stapelkonvertierung von Word-Dokumentdateien in PowerPoint-POT-Präsentationen zu automatisieren, verwenden wir [Aspose.Words for .NET](https://products.aspose.com/words/net) und [Aspose.Slides für .NET](https://products.aspose.com/slides/net)-APIs. Ersteres ist eine Textverarbeitungs-API zum Verarbeiten oder Bearbeiten von Microsoft Word-Dokumenten. Letzteres ist eine API zur Manipulation von Präsentationen, mit der Sie Microsoft PowerPoint-Folien erstellen oder ändern können. Beide APIs sind Teil des Pakets [Aspose.Total for .NET](https://products.aspose.com/total/net). Sie können direkt von Nuget [herunterladen](https://releases.aspose.com/) oder die folgenden Befehle aus der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von TXT in POT über C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Fügen Sie eine Referenz von Aspose.Total für .NET hinzu
1. Laden Sie die TXT-Datei mit der Klasse [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document).
1. Speichern Sie das TXT-Dokument in HTML
1. Erstellen Sie das Objekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
1. Importieren Sie HTML-Inhalte in Textrahmen einer beliebigen Folienform innerhalb der Präsentation
1. Speichern Sie das Dokument mit [Aspose.Slides.Presentation.Save("output.pot", SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Words für .NET &amp; Aspose.Slides für .NET-DLLs oder Aspose.Total für .NET-DLLs, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieses Codebeispiel zeigt, wie Sie ein TXT mit C# in POT konvertieren." offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

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

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online-Konverter für TXT zu POT</h3>

<iframe title="pot bis txt Online-Tool" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=pot&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von TXT in POT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="TXT-Dateien programmgesteuert in POT umwandeln: Anwendungsfälle" %}}
Die Umwandlung von TXT-Dateien in die POT-Formate (Portabeles Objekt-Modell) ist erforderlich, um den vollen Potenzial deiner Datenvisualisierung und -analysefähigkeiten zu aktivieren. Diese Umwandlung ermöglicht dir:

**Anwendungsfälle:**

*   **Textbearbeitung und Anpassung**: Wandele TXT-Dateien in ein personalisierbares Template, wie z.B. ein Dokument, eine E-Mail oder ein Konversationspartner.
*   **Datenimport und Export**: Nutze die POT-Formate zur Importierung und Exportierung von Daten aus verschiedenen Quellen, um eine reibungslose Integration mit unterschiedlichen Anwendungen zu ermöglichen.
*   **Übersetzungs- und Localisierungsanforderungen**: Wandele TXT-Dateien in POT-Format für die Übersetzung und die Localisierung, was die Inhalte zugänglicher für ein breiteres Publikum macht.
*   **Softwareentwicklung und Testen**: Nutze die POT-Formate, um Testtemplates zu erstellen, Workflowautomatisierungen durchzuführen und die Effizienz der Softwareentwicklung zu verbessern.
*   **Inhaltsverwaltung und Zusammenarbeit**: Wandele TXT-Dateien in POT-Format für collaborative Bearbeitung, Versionierung und Inhaltsmanagement-Systeme.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Häufig gestellte Fragen</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie kann ich TXT in POT Online konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Online-App für die TXT-Konvertierung ist oben integriert. Um diese App zu verwenden, können Sie Ihre TXT-Datei hinzufügen, indem Sie sie per Drag & Drop in den dafür vorgesehenen weißen Bereich ziehen oder in den Bereich klicken, um das Dokument zu importieren. Drücken Sie als Nächstes die Schaltfläche Konvertieren, um den Konvertierungsprozess zu starten. Nachdem die TXT-zu-POT-Konvertierung abgeschlossen ist, können Sie Ihre neu konvertierte Datei mit nur einem Klick herunterladen und sie steht Ihnen in Form einer POT-Datei zur Verfügung.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie lange dauert die Konvertierung von TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Dieser Online-Konverter arbeitet schnell, hängt jedoch hauptsächlich von der Größe der zu konvertierenden TXT-Datei ab. Bei kleinen TXT-Dateien kann die Konvertierung in POT in Sekundenschnelle abgeschlossen werden. Wenn Sie den Konvertierungscode jedoch in eine .NET-Anwendung integriert haben, hängt die Konvertierungsgeschwindigkeit davon ab, wie gut Ihre Anwendung für den Konvertierungsprozess optimiert wurde.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ist es sicher, TXT mit dem kostenlosen Aspose.Total-Konverter in POT umzuwandeln?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Natürlich! Sobald die TXT-zu-POT-Konvertierung abgeschlossen ist, ist der Download-Link für die neu konvertierte POT-Datei sofort verfügbar. Es gewährleistet auch die Sicherheit des Konvertierungsprozesses, da alle hochgeladenen Dateien, einschließlich TXT-Dateien, absolut sicher sind und nach 24 Stunden aus dem System gelöscht werden. Darüber hinaus funktionieren die Download-Links nach diesem Zeitraum nicht mehr, um die Privatsphäre und den Schutz Ihrer Dateien zu gewährleisten. Die integrierte App ist kostenlos nutzbar und für Testzwecke konzipiert, damit Anwender die Ergebnisse auswerten können, bevor sie den Code in ihre Projekte integrieren.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Welchen Browser sollte ich verwenden, um TXT zu konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sie können jeden modernen Webbrowser wie Google Chrome, Firefox, Opera oder Safari für die Online-Konvertierung von TXT in POT verwenden. Wenn Sie jedoch eine Desktop-Anwendung entwickeln, wird die Aspose.Total TXT Conversion API für eine reibungslose und effiziente Verarbeitung empfohlen.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}