---
title: Konvertieren Sie ODT in PPTX über C# .NET oder mit dem kostenlosen Online Converter
description: Konvertieren Sie Word-Dokumente mit C# in PowerPoint-PPTX-Dateien. Konvertieren Sie mehrere Dateien innerhalb von ASP.NET oder anderen .NET-Anwendungen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie ODT in PPTX mit C# oder online" h2="Erstellen Sie Microsoft Word ODT-zu-PowerPoint-PPTX-Konvertierungs-Apps auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="So konvertieren Sie ODT in PPTX mit C#" %}}

Um den Vorgang für die Stapelkonvertierung von Word-Dokumentdateien in PowerPoint-PPTX-Präsentationen zu automatisieren, verwenden wir [Aspose.Words for .NET](https://products.aspose.com/words/net) und [Aspose.Slides für .NET](https://products.aspose.com/slides/net)-APIs. Ersteres ist eine Textverarbeitungs-API zum Verarbeiten oder Bearbeiten von Microsoft Word-Dokumenten. Letzteres ist eine API zur Manipulation von Präsentationen, mit der Sie Microsoft PowerPoint-Folien erstellen oder ändern können. Beide APIs sind Teil des Pakets [Aspose.Total for .NET](https://products.aspose.com/total/net). Sie können direkt von Nuget [herunterladen](https://releases.aspose.com/) oder die folgenden Befehle aus der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von ODT in PPTX über C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Fügen Sie eine Referenz von Aspose.Total für .NET hinzu
1. Laden Sie die ODT-Datei mit der Klasse [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document).
1. Speichern Sie das ODT-Dokument in HTML
1. Erstellen Sie das Objekt [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
1. Importieren Sie HTML-Inhalte in Textrahmen einer beliebigen Folienform innerhalb der Präsentation
1. Speichern Sie das Dokument mit [Aspose.Slides.Presentation.Save("output.pptx", SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Words für .NET &amp; Aspose.Slides für .NET-DLLs oder Aspose.Total für .NET-DLLs, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieses Codebeispiel zeigt, wie Sie ein ODT mit C# in PPTX konvertieren." offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

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

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online-Konverter für ODT zu PPTX</h3>

<iframe title="pptx bis odt Online-Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von ODT in PPTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="ODT-Dateien programmgesteuert in PPTX umwandeln: Anwendungsfälle" %}}
ODT-Dateien werden weit verbreitet für die Erstellung, Bearbeitung und Teilen von Textdokumenten verwendet, weshalb sie zu einem idealen Wahl für Autoren, Studierende und Fachleute gleichermaßen sind. Allerdings stellt sich die Frage, wenn es darum geht, komplexe Informationen in einer visuell ansprechenden Weise darzustellen, werden PowerPoint-Presentationen unverzichtbar.

Die Konvertierung von ODT-Dateien in PowerPoint-Format ist notwendig, um die volle Leistungsfähigkeit deiner Präsentationsfähigkeiten freizusetzen. Diese Konvertierung ermöglicht dir:

**Anwendungsszenarien:**

*   **Geschäftliche Präsentationen**: Konvertiere ODT-Dateien zur Erstellung professioneller Geschäftspresentativen, die Unternehmen-Updates, Produktpräsentationen und Marketingkampagnen vorstellen.
*   **Akademische Präsentationen**: Verwende PowerPoint, um Forschungsergebnisse, akademische Aufsätze und Bachelor-Arbeiten in einer visuell ansprechenden Weise vorzustellen, deine Zuhörer zu begeistern und komplexe Informationen effektiv zu vermitteln.
*   **Verkaufs- und Marketingmaterialien**: Konvertiere ODT-Dateien zur Erstellung interaktiver Verkaufspräsentationen, Produkt-Demos und Marketingmaterialien, um dich von der Konkurrenz abzuheben.
*   **Lernmaterialien und Workshops**: Verwende PowerPoint, um lehrreiche Unterrichtspläne, Tutorials und Workshops zu erstellen, komplexe Themen zugänglicher und unterhaltsamer für Studierende zu machen.
*   **Persönliche Projekte und Blogs**: Konvertiere ODT-Dateien zur Erstellung professionell aussehender Blog-Beiträge, persönlicher Geschichten und kreativer Schreibprojekte, deine Ideen und Erfahrungen einer breiteren Zielgruppe mitzuteilen.
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
                          <span itemprop="name"><b>Wie kann ich ODT in PPTX Online konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Online-App für die ODT-Konvertierung ist oben integriert. Um diese App zu verwenden, können Sie Ihre ODT-Datei hinzufügen, indem Sie sie per Drag & Drop in den dafür vorgesehenen weißen Bereich ziehen oder in den Bereich klicken, um das Dokument zu importieren. Drücken Sie als Nächstes die Schaltfläche Konvertieren, um den Konvertierungsprozess zu starten. Nachdem die ODT-zu-PPTX-Konvertierung abgeschlossen ist, können Sie Ihre neu konvertierte Datei mit nur einem Klick herunterladen und sie steht Ihnen in Form einer PPTX-Datei zur Verfügung.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie lange dauert die Konvertierung von ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Dieser Online-Konverter arbeitet schnell, hängt jedoch hauptsächlich von der Größe der zu konvertierenden ODT-Datei ab. Bei kleinen ODT-Dateien kann die Konvertierung in PPTX in Sekundenschnelle abgeschlossen werden. Wenn Sie den Konvertierungscode jedoch in eine .NET-Anwendung integriert haben, hängt die Konvertierungsgeschwindigkeit davon ab, wie gut Ihre Anwendung für den Konvertierungsprozess optimiert wurde.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ist es sicher, ODT mit dem kostenlosen Aspose.Total-Konverter in PPTX umzuwandeln?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Natürlich! Sobald die ODT-zu-PPTX-Konvertierung abgeschlossen ist, ist der Download-Link für die neu konvertierte PPTX-Datei sofort verfügbar. Es gewährleistet auch die Sicherheit des Konvertierungsprozesses, da alle hochgeladenen Dateien, einschließlich ODT-Dateien, absolut sicher sind und nach 24 Stunden aus dem System gelöscht werden. Darüber hinaus funktionieren die Download-Links nach diesem Zeitraum nicht mehr, um die Privatsphäre und den Schutz Ihrer Dateien zu gewährleisten. Die integrierte App ist kostenlos nutzbar und für Testzwecke konzipiert, damit Anwender die Ergebnisse auswerten können, bevor sie den Code in ihre Projekte integrieren.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Welchen Browser sollte ich verwenden, um ODT zu konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sie können jeden modernen Webbrowser wie Google Chrome, Firefox, Opera oder Safari für die Online-Konvertierung von ODT in PPTX verwenden. Wenn Sie jedoch eine Desktop-Anwendung entwickeln, wird die Aspose.Total ODT Conversion API für eine reibungslose und effiziente Verarbeitung empfohlen.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}