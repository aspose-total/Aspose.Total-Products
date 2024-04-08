---
title: DOCM-Annotation online entfernen oder Annotationen über C++ verwalten
description: Löschen Sie Kommentare kostenlos aus DOCM-Dateien über eine Online-App. C++-API-Code zum Verwalten von Kommentaren in DOCM-Dateien.

family: total
platformtag: cpp
feature: Annotate
informat: DOCM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Kommentare aus DOCM-Dokument online löschen oder über C++ verwalten" h2="Entwickeln Sie ein leistungsstarkes C++-basiertes Dienstprogramm zur Kommentierung von DOCM-Dokumenten. Code zur Verwaltung von Kommentaren in DOCM-Dateien über C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCM-Anmerkungen online entfernen" %}}

1. Importieren Sie die DOCM-Datei, um Kommentare durch Hochladen zu löschen
1. Klicken Sie dazu per Drag & Drop der Annotation-App in den Drop-Bereich
1. Warten Sie je nach Größe der DOCM-Datei und Internetgeschwindigkeit einige Sekunden
1. Klicken Sie auf die Schaltfläche „Entfernen“, um Kommentare zu löschen
1. Laden Sie die Datei sofort herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Löschen von DOCM-Dokumentkommentaren über C++" %}}

1. Bibliotheksverweis zum C++-Projekt hinzufügen
1. DOCM-Datei laden
1. Holen Sie sich alle Knoten, indem Sie GetChildNodes mit NodeType::Comment als Parameter verwenden.
1. Rufen Sie NodeCollection.Clear für die Kommentarsammlung auf

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++-Code: Kommentare aus DOCM-Datei löschen" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Kommentare über C++ hinzufügen" %}}

1. Erstellen Sie ein Dokument und ein DocumentBuilder-Klassenobjekt
1. Oder laden Sie das Dokument
1. Verwenden Sie die Kommentarklasse zum Hinzufügen des Kommentars
1. Verwenden Sie die Methode AppendChild mit dem Kommentar obj als Parameter
1. Verwenden Sie eine entsprechende Methode wie get_Paragraphs()->Add
1. Oder andersherum: Verwenden Sie die Klassen CommentRangeStart und CommentRangeEnd
1. Rufen Sie die Save-Methode auf, um die Datei mit hinzugefügten Kommentaren zu speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Alle Kommentare extrahieren" %}}

1. Dokument über das Objekt der Dokumentklasse laden
1. Alle GetChildNodes in der NodeCollection abrufen
1. Durchlaufen Sie jede Sammlung und sammeln Sie Informationen darüber

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++-Code: Kommentar zur DOCM-Datei hinzufügen" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Alle Kommentare extrahieren" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Entwickeln Sie eine DOCM-Dokumentanmerkungsanwendung mit C++</h2>

Müssen Sie eine DOCM-Anmerkungs-App oder ein Dienstprogramm entwickeln, um Feedback zu geben, Vorschläge zu machen oder mit anderen am Dokument zusammenzuarbeiten?Da [Aspose.Words for C++](https://products.aspose.com/words/cpp/) eine untergeordnete API von [Aspose.Total for C++](https://products.aspose.com/total/de/cpp/) ist, kann jeder C++-Entwickler den obigen API-Code in seine Anwendung zur Dokumentanmerkung integrieren.Eine leistungsstarke C++-Bibliothek ermöglicht die Programmierung beliebiger Lösungen zur Dokumentannotation.Darüber hinaus unterstützt es viele gängige Formate, einschließlich des DOCM-Formats.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-Bibliothek zum Kommentieren von DOCM-Dateien" %}}

Es gibt drei Möglichkeiten, Aspose.Words für C++ in Ihrer Entwicklerumgebung zu installieren.Wählen Sie bitte eine Option aus, die Ihren Anforderungen entspricht, und folgen Sie den Schritt-für-Schritt-Anweisungen:<br /><br />

- Install a [NuGet-Paket](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Dokumentation](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Installieren Sie die Bibliothek mit [Paket-Manager-Konsole](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) in der Visual Studio IDE
- Installieren Sie die Bibliothek manuell mit [Windows Installer](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}
Sie können diese C++-Bibliothek verwenden, um Software auf den Betriebssystemen Microsoft Windows, Linux und macOS zu entwickeln:<br /><br />

- Für Linux sind GCC >= 6.3.0 und Clang >= 3.9.1 erforderlich
- Xcode >= 12.5.1, Clang und libc++ werden für macOS benötigt

<br /><br />
Wenn Sie Software für Linux oder macOS entwickeln, lesen Sie bitte die Informationen zu zusätzlichen Bibliotheksabhängigkeiten (Open-Source-Pakete „Fontconfig“ und „Mesa-Glu“) in [Produktdokumentation](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

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
              <h2>FAQs</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Kann ich den obigen C++-Code in meiner Anwendung verwenden?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ja, Sie können diesen Code gerne herunterladen und zum Entwickeln einer C++-basierten Anwendung zur Dokumentanmerkung verwenden.Dieser Code kann als wertvolle Ressource dienen, um die Funktionalität und Fähigkeiten Ihrer Projekte im Bereich der Backend-Dokumentenverarbeitung und -bearbeitung zu verbessern.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Funktioniert diese Online-App zum Kommentieren von Dokumenten nur unter Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sie haben die Flexibilität, die Dokumentanmerkung zum Entfernen von Kommentaren auf jedem Gerät zu initiieren, unabhängig vom Betriebssystem, auf dem es läuft, sei es Windows, Linux, Mac OS oder Android. Alles, was Sie brauchen, ist ein moderner Webbrowser und eine aktive Internetverbindung.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ist es sicher, die Online-App zum Kommentieren von DOCM-Dokumenten zu verwenden?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Natürlich! Die von unserem Service generierten Ausgabedateien werden innerhalb von 24 Stunden sicher und automatisch von unseren Servern entfernt.Dies hat zur Folge, dass die mit diesen Dateien verknüpften Anzeigelinks nach diesem Zeitraum nicht mehr funktionieren.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Welcher Browser wird für die Nutzung der App benötigt?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sie können jeden modernen Webbrowser wie Google Chrome, Firefox, Opera oder Safari für die Online-Annotation von DOCM-Dokumenten verwenden.Wenn Sie jedoch eine Desktopanwendung entwickeln, empfehlen wir zur effizienten Verwaltung die Verwendung der Aspose.Total-API zur Dokumentverarbeitung.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}