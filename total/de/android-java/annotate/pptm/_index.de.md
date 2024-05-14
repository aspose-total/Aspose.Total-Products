---
title: PPTM-Anmerkungen online entfernen oder Anmerkungen mit mobilen Android-Apps verwalten
description: Löschen Sie Kommentare kostenlos aus einer PPTM-Datei über die Online-App.Android-API-Code zum Verwalten von Kommentaren von PPTM-Dateien.

family: total
platformtag: Android
feature: Annotate
informat: PPTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Kommentare aus der PPTM-Präsentation online löschen oder über Android-Apps verwalten" h2="Entwickeln Sie eine leistungsstarke, Android-basierte Dienstprogrammanwendung zur Kommentierung von PPTM-Präsentationen.Aufgelisteter Code zum Verwalten von Kommentaren der PPTM-Datei." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTM-Anmerkungen online entfernen" %}}

1. Importieren Sie die PPTM-Datei, um Kommentare durch Hochladen zu löschen
1. Klicken Sie dazu per Drag & Drop der Annotation-App in den Drop-Bereich
1. Warten Sie je nach Größe der PPTM-Datei und Internetgeschwindigkeit einige Sekunden
1. Klicken Sie auf die Schaltfläche „Entfernen“, um Kommentare zu löschen
1. Laden Sie die Datei sofort herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PPTM-Präsentationskommentare über die Android-App entfernen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Laden Sie PPTM über das Objekt der Präsentationsklasse
1. Durchlaufen Sie jeden Autor über die Presentation.getCommentAuthors()-Sammlung
1. Rufen Sie die clear()-Methode auf, um den Kommentar zu löschen
1. Rufen Sie abschließend getCommentAuthors().clear() auf, um alle Autoren zu entfernen
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare und Autoren aus der PPTM-Präsentation löschen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="PPTM-Präsentationskommentare über die Android-App hinzufügen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Laden Sie PPTM über das Objekt der Präsentationsklasse
1. Rufen Sie Presentation.getCommentAuthors().addAuthor(String, String) auf, um die Autoren hinzuzufügen
1. Verwenden Sie ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) zum Hinzufügen von Kommentaren
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare hinzufügen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Entwickeln Sie eine Android-App zur PPTM-Dokumentanmerkung</h2>

Müssen Sie eine mobile App oder ein Dienstprogramm für PPTM-Anmerkungen entwickeln, um Feedback zu geben, Vorschläge zu machen oder gemeinsam mit anderen am Dokument zu arbeiten?Mit [Aspose.Slides for Android via Java](https://products.aspose.com/slides/de/android-java/), einer untergeordneten API von [Aspose.Total for Android via Java](https://products.aspose.com/total/de/android-java/), kann jeder Android-Entwickler den obigen API-Code in seine Anwendung zur Dokumentanmerkung integrieren.Eine leistungsstarke Android-Bibliothek ermöglicht die Programmierung beliebiger Lösungen zur Dokumentanmerkung.Darüber hinaus unterstützt es viele gängige Formate, einschließlich des PPTM-Formats.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-Bibliothek zum Kommentieren von PPTM-Dateien" %}}

- Wir hosten unsere Java-Pakete in [Maven-Repositorys](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java ist eine allgemeine JAR-Datei, die Bytecode enthält.
- Befolgen Sie die Anweisungen in [Schritt für Schritt Anweisungen](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) zur Installation von Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

- J2SE 6.0 (Java 1.6) und höher
- Das Java-Paket ist plattformübergreifend und läuft auf allen Betriebssystemen mit JVM-Implementierung.

<br />
Weitere Einzelheiten finden Sie in [Produktdokumentation](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}