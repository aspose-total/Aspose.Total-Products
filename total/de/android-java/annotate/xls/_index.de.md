---
title: XLS-Anmerkungen online entfernen oder Anmerkungen mit mobilen Android-Apps verwalten
description: Löschen Sie Kommentare kostenlos aus einer XLS-Datei über die Online-App.Android-API-Code zum Verwalten von Kommentaren von XLS-Dateien.

family: total
platformtag: Android
feature: Annotate
informat: XLS
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Kommentare aus XLS-Dokumenten online löschen oder über Android-Apps verwalten" h2="Entwickeln Sie eine leistungsstarke, Android-basierte Dienstprogrammanwendung zur XLS-Dokumentanmerkung.Aufgelisteter Code zum Verwalten von Kommentaren der XLS-Datei." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS-Anmerkungen online entfernen" %}}

1. Importieren Sie die XLS-Datei, um Kommentare durch Hochladen zu löschen
1. Klicken Sie dazu per Drag & Drop der Annotation-App in den Drop-Bereich
1. Warten Sie je nach Größe der XLS-Datei und Internetgeschwindigkeit einige Sekunden
1. Klicken Sie auf die Schaltfläche „Entfernen“, um Kommentare zu löschen
1. Laden Sie die Datei sofort herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Entfernen Sie XLS-Dokumentkommentare über die Android App API" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Dokument über Workbook-Klassenobjekt laden
1. Wählen Sie das spezifische Arbeitsblatt aus
1. Alle Kommentare der mit [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Alle Thread-Kommentare über getThreadedComments abrufen
1. Verwenden Sie removeAt, um Kommentare bzw. Autoren zu entfernen
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare aus XLS-Dokument entfernen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Threadierte XLS-Kommentare aktualisieren" %}}

1. Dokument über Workbook-Klassenobjekt laden
1. Holen Sie sich das spezifische Arbeitsblatt
1. Holen Sie sich den Threadkommentar mit getComments().getThreadedComments(Index).get(Index)
1. Verwenden Sie die setNotes-Methode, um den Kommentar zu aktualisieren
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kommentare über die Android App API hinzufügen" %}}

1. Dokument über das Objekt der Arbeitsmappenklasse erstellen
1. Holen Sie sich das spezifische Arbeitsblatt
1. Kommentarindex über getComments().add hinzufügen
1. Verwenden Sie die Methode setNotes, um Kommentare hinzuzufügen
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Thread-Kommentar der XLS-Datei aktualisieren" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare hinzufügen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Entwickeln Sie eine Android-App zur XLS-Dokumentanmerkung</h2>

Müssen Sie eine Android-basierte XLS-Anmerkungs-App oder ein Dienstprogramm entwickeln, um Feedback zu geben, Vorschläge zu machen oder mit anderen am Dokument zusammenzuarbeiten?Mit [Aspose.Cells for Android via Java](https://products.aspose.com/cells/de/android-java/), einer untergeordneten API von [Aspose.Total for Android via Java](https://products.aspose.com/total/de/android-java/), kann jeder Android-Entwickler den obigen API-Code in seine Anwendung zur Dokumentanmerkung integrieren.Eine leistungsstarke Android-Bibliothek ermöglicht die Programmierung beliebiger Lösungen zur Dokumentanmerkung.Darüber hinaus unterstützt es viele gängige Formate, einschließlich des XLS-Formats.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Kommentieren von XLS-Dateien" %}}

- Wir hosten unsere Java-Pakete in [Maven-Repositorys](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java ist eine allgemeine JAR-Datei, die Bytecode enthält.
- Befolgen Sie die Anweisungen in [Schritt für Schritt Anweisungen](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) zur Installation von Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

- Android OS 2.0 oder höher.
- Das Java-Paket ist plattformübergreifend und läuft auf allen Betriebssystemen mit JVM-Implementierung.

<br />
Weitere Einzelheiten finden Sie in [Produktdokumentation](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}