---
title: PDF-Anmerkungen online entfernen oder Anmerkungen mit mobilen Android-Apps verwalten
description: Löschen Sie Kommentare kostenlos aus einer PDF-Datei über die Online-App.Android-API-Code zum Verwalten von Kommentaren von PDF-Dateien.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Kommentare aus PDF-Dokumenten online löschen oder über Android-Apps verwalten" h2="Entwickeln Sie eine leistungsstarke, Android-basierte Dienstprogrammanwendung zur PDF-Dokumentanmerkung.Aufgelisteter Code zum Verwalten von Kommentaren der PDF-Datei." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF-Anmerkungen online entfernen" %}}

1. Importieren Sie die PDF-Datei, um Kommentare durch Hochladen zu löschen
1. Klicken Sie dazu per Drag & Drop der Annotation-App in den Drop-Bereich
1. Warten Sie je nach Größe der PDF-Datei und Internetgeschwindigkeit einige Sekunden
1. Klicken Sie auf die Schaltfläche „Entfernen“, um Kommentare zu löschen
1. Laden Sie die Datei sofort herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Entfernen Sie PDF-Dokumentkommentare über die Android App API" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Dokument über das Objekt der Dokumentklasse laden
1. Wählen Sie die gewünschte Seite über getPages().get_Item(Index) aus.
1. Nutzen Sie den AnnotationSelector und erhalten Sie alle Textanmerkungen über annotationSelector.getSelected()
1. Gehen Sie jede Anmerkung durch und rufen Sie die Löschmethode auf, um sie zu entfernen.
1. Rufen Sie die Speichermethode auf, um die Datei zu speichern.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare aus PDF-Datei löschen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Anmerkung über die Android App API hinzufügen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Objekt der Klasse „Dokument“ erstellen
1. Fügen Sie die neue Seite und den Inhalt mit getPages().add() hinzu
1. Verwenden Sie getPages().get_Item(Index) der Klasse TextAnnotation
1. Setzen Sie die relevanten Anmerkungen wie Titel, Betreff, Inhalt etc.
1. Verwenden Sie getAnnotations().add, um die Anmerkungen hinzuzufügen
1. Rufen Sie die Save-Methode auf, um die Datei mit hinzugefügten Kommentaren zu speichern
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: PDF-Anmerkung hinzufügen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Entwickeln Sie eine Android-App zur PDF-Dokumentanmerkung</h2>

Müssen Sie eine mobile App oder ein Dienstprogramm für PDF-Anmerkungen entwickeln, um Feedback zu geben, Vorschläge zu machen oder mit anderen am Dokument zusammenzuarbeiten?Mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/de/android-java/), einer untergeordneten API von [Aspose.Total for Android via Java](https://products.aspose.com/total/de/android-java/), kann jeder Android-Entwickler den obigen API-Code in seine Anwendung zur Dokumentanmerkung integrieren.Eine leistungsstarke Android-Bibliothek ermöglicht die Programmierung beliebiger Lösungen zur Dokumentanmerkung.Darüber hinaus unterstützt es viele gängige Formate, einschließlich des PDF-Formats.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-Bibliothek zum Kommentieren von PDF-Dateien" %}}

- Wir hosten unsere Java-Pakete in [Maven-Repositorys](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java ist eine allgemeine JAR-Datei, die Bytecode enthält.
- Befolgen Sie die Anweisungen in [Schritt für Schritt Anweisungen](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) zur Installation von Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

- Android API 31 und 32
- Android 4.0 und höher
- Android Studio und SDK-Tools

<br />
Weitere Einzelheiten zu optionalen Paketabhängigkeiten wie JogAmp JOGL, Harfbuzz-Schriftarten-Engine und Java Advanced Imaging JAI finden Sie in [Produktdokumentation](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}