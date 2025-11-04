---
title: Online-Konvertierung von XPS in PPT oder Entwicklung einer Java-basierten Anwendung zum Konvertieren von XPS-Dateien
description: Kostenlose Online-App zum Konvertieren von XPS- in PPT-Dateien. Java-Konvertierungsbibliothekscode für XPS-Dokumente. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: PPT
otherformats: PPS POTM PPSM POT PPSX PPT POTX POWERPOINT OTP SWF PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online-Konvertierungs-App für XPS zu PPT und Java-Code zum Konvertieren von XPS-Dateien" h2="Entwickeln Sie eine leistungsstarke Java-basierte XPS-Konvertierungs- und Exportanwendung. Konvertieren Sie einzelne oder mehrere XPS-Dateien über die Java-Automatisierungs-API in PPT und andere Formate. Konvertieren Sie XPS-Dateien kostenlos online per App mit sofortigem Download." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Kostenlose Online-App zur Konvertierung von XPS in PPT" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=ppt&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie XPS- in PPT-Dateien online mithilfe der App" %}}

1. Laden Sie zum Konvertieren XPS-Dateien hoch
1. Warten Sie je nach XPS-Größe einige Sekunden oder länger
1. Behalten Sie die Upload-Statusleiste im Auge
1. Klicken Sie auf die Schaltfläche "Konvertieren"
1. XPS wird in ein PPT-Dokument umgewandelt
1. Laden Sie die konvertierte PPT-Datei herunter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie XPS in PPT über die Java Automation API" %}}


1. Öffnen Sie die XPS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie XPS in PPTX, indem Sie die Methode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im PPT-Format mit der Methode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Ppt` als SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Noch einige Fälle zum Speichern von XPS in PPT mit anderen Funktionen wie Konvertierungsanforderungen, Öffnen Sie die verschlüsselte XPS-Datei über Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Entwickeln Sie eine XPS-Dateikonvertierungsanwendung mit Java</h2>

Müssen Sie eine Java-basierte Softwareanwendung entwickeln, um XPS-Dateien einfach in PPT-Dokumente zu speichern und zu exportieren? Mit [Aspose.Total for Java](https://products.aspose.com/total/de/java/) kann jeder Java-Entwickler den oben genannten API-Code integrieren, um die Konvertierungsanwendung für verschiedene Formate zu programmieren, darunter Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, E-Mail-Dateien, Bilder (JPG, PNG, BMP, GIF) und andere Formate. Leistungsstarke Java-Bibliothek zur Dokumentkonvertierung, unterstützt viele gängige Formate, einschließlich des XPS-Formats. Beim Exportieren und Rendern von Dokumenten in andere Formate können Programmierer untergeordnete Aspose.Total for Java-APIs verwenden, darunter [Aspose.Words for Java](https://products.aspose.com/words/de/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/de/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/de/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/de/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/de/java/) und mehr.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Konvertierungsbibliothek für Java" %}}

Es gibt alternative Möglichkeiten, Aspose.Total for Java in Ihr System zu integrieren. Wählen Sie bitte eine Option aus, die Ihren Anforderungen entspricht, und folgen Sie den Schritt-für-Schritt-Anweisungen:<br /><br />

- Verwenden Sie Aspose.Total for Java direkt aus einem Maven-basierten Projekt und schließen Sie die relevante untergeordnete API in pom.xml ein.
- Alternativ kann man eine ZIP-Datei von [Downloads](https://releases.aspose.com/total/java) beziehen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Speichern von XPS in PPT App-Anforderungen" %}}

Jedes Betriebssystem, das die Java Runtime Environment (JRE) ausführen kann, kann Aspose.Total for Java ausführen. Im Folgenden sind die meisten, aber nicht alle unterstützten Betriebssysteme aufgeführt. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS und andere
- macOS: 10.9 (Mavericks) und höher
- Mobil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



Die Konvertierung von XPS in **PPT (PowerPoint 97-2003)** gewährleistet die Abwärtskompatibilität mit älteren Microsoft Office-Versionen und behält editierbare Folien, Texte und grundlegende Formatierungen bei.



{{% blocks/products/pf/agp/feature-section-col title="Hauptanwendungsfälle" %}}



* Kompatibilität mit älteren Office-Versionen für Unternehmenspräsentationen aus der Vergangenheit.

* Archivierung und Erhaltung historischer Präsentationen.

* Bildungsinhalte für Bildungseinrichtungen, die ältere Software verwenden.

* Interne Berichterstattung und Schulungspräsentationen für gemischte Umgebungen mit verschiedenen Office-Versionen.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatisierungsszenarien" %}}



* Stapelkonvertierung von XPS-Dateien in PPT für Unternehmensarchive.

* Geplante automatisierte Erstellung abwärtskompatibler Präsentationen.

* Integration in bestehende Dokumenten-Workflows.

* Effiziente Erstellung von Präsentationen über verschiedene Office-Versionen hinweg.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}