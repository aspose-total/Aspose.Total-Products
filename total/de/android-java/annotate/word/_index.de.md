---
title: Word-Anmerkungen online entfernen oder Anmerkungen mit mobilen Android-Apps verwalten
description: Löschen Sie Kommentare kostenlos aus einer Word-Datei über die Online-App.Android-API-Code zum Verwalten von Kommentaren von Word-Dateien.

family: total
platformtag: Android
feature: Annotate
informat: Word
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Kommentare aus Word-Dokumenten online löschen oder über Android-Apps verwalten" h2="Entwickeln Sie eine leistungsstarke, Android-basierte Dienstprogrammanwendung zur Word-Dokumentanmerkung.Aufgelisteter Code zum Verwalten von Kommentaren der Word-Datei." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word-Anmerkungen online entfernen" %}}

1. Importieren Sie die Word-Datei, um Kommentare durch Hochladen zu löschen
1. Klicken Sie dazu per Drag & Drop der Annotation-App in den Drop-Bereich
1. Warten Sie je nach Größe der Word-Datei und Internetgeschwindigkeit einige Sekunden
1. Klicken Sie auf die Schaltfläche „Entfernen“, um Kommentare zu löschen
1. Laden Sie die Datei sofort herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Word-Dokumentkommentare über die Android-App entfernen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Dokument über das Objekt der Dokumentklasse laden
1. Holen Sie sich alle Kommentare von allen Knoten mithilfe von [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) und NodeType.COMMENT
1. Rufen Sie die [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)-Methode auf, um alle Kommentare zu löschen
1. Rufen Sie die Speichermethode auf, um die Datei zu speichern.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare aus Word-Datei löschen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word-Kommentarantwort entfernen und hinzufügen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Dokument über das Objekt der Dokumentklasse laden
1. Kommentare mit „getChild“ abrufen
1. Verwenden Sie [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment), um die angegebene Antwort auf diesen Kommentar zu entfernen
1. Verwenden Sie [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String), um eine Antwort auf diesen Kommentar hinzuzufügen
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kommentare über die Android-App hinzufügen" %}}

1. Bibliotheksverweis zum Android-Projekt hinzufügen
1. Objekt der Klasse „Dokument“ erstellen
1. Verwenden Sie [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/), um den Kommentar zu erstellen
1. Verwenden Sie getParagraphs().add und getFirstParagraph().getRuns().add
1. Rufen Sie die Save-Methode auf, um die Datei zu speichern with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: Entfernen und Hinzufügen einer Kommentarantwort aus einer Word-Datei" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Code: Kommentare hinzufügen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Entwickeln Sie eine Android-App zur Word-Dokumentanmerkung</h2>

Müssen Sie eine mobile App oder ein Dienstprogramm für Word-Anmerkungen entwickeln, um Feedback zu geben, Vorschläge zu machen oder gemeinsam mit anderen am Dokument zu arbeiten?Mit [Aspose.Words for Android via Java](https://products.aspose.com/words/de/android-java/), einer untergeordneten API von [Aspose.Total for Android via Java](https://products.aspose.com/total/de/android-java/), kann jeder Android-Entwickler den obigen API-Code in seine Anwendung zur Dokumentanmerkung integrieren.Eine leistungsstarke Android-Bibliothek ermöglicht die Programmierung beliebiger Lösungen zur Dokumentanmerkung.Darüber hinaus unterstützt es viele gängige Formate, einschließlich des Word-Formats.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-Bibliothek zum Kommentieren von Word-Dateien" %}}

- Wir hosten unsere Java-Pakete in [Maven-Repositorys](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java ist eine allgemeine JAR-Datei, die Bytecode enthält.
- Befolgen Sie die Anweisungen in [Schritt für Schritt Anweisungen](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) zur Installation von Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

- Java SE 7 und neuere Java-Versionen werden unterstützt.
- Separates Paket für Java SE 6, falls die Verwendung des veralteten JRE erforderlich ist.
- Das Java-Paket ist plattformübergreifend und läuft auf allen Betriebssystemen mit JVM-Implementierung.
- Zu den Betriebssystemen gehören Microsoft Windows, Linux, macOS, Android und iOS.

<br />
Weitere Einzelheiten zu optionalen Paketabhängigkeiten wie JogAmp JOGL, Harfbuzz-Schriftarten-Engine und Java Advanced Imaging JAI finden Sie in [Produktdokumentation](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}