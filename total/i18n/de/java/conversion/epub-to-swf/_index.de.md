---
title: Konvertieren Sie EPUB über die Java-API in SWF
description: Java-API zum Konvertieren von EPUB in SWF ohne Verwendung von Microsoft Word
url: /de/java/conversion/epub-to-swf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: SWF
otherformats: XAML PPSX PPS PPTM POTM POTX POWERPOINT PPT PPSM SWF POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Exportieren von EPUB nach SWF" h2="Exportieren Sie EPUB über die lokale Java-API nach SWF, ohne Microsoft<sup>&reg;</sup> PowerPoint oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie EPUB in jeder Java J2SE-, J2EE-, J2ME-Anwendung problemlos in SWF konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) EPUB nach PPTX exportieren. Danach können Sie mithilfe der [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint-Verarbeitungs-API PPTX in SWF konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von EPUB in SWF" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie EPUB in PPTX, indem Sie die Methode [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im SWF-Format mit der Methode [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Swf` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Slides für Java](https://docs.aspose.com/slides/java/ installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Beim Laden des EPUB-Dateiformats ist Ihr Dokument möglicherweise passwortgeschützt. Mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) können Sie auch verschlüsselte Dokumente öffnen. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie die verschlüsselte EPUB-Datei über Java" %}}
Nach der Konvertierung von EPUB in SWF können Sie Ihrer Präsentation auch einen vordefinierten Ansichtstyp hinzufügen. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) bietet eine Möglichkeit, den Ansichtstyp für die generierte Präsentation festzulegen, wenn sie in PowerPoint über die [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties)-Klasse. Die Eigenschaft [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) wird verwendet, um den Ansichtstyp mithilfe von [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType)-Enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-pps/" name="EPUB Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-swf/" name="EPUB Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-potx/" name="EPUB Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-ppsx/" name="EPUB Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-potm/" name="EPUB Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-ppt/" name="EPUB Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-ppsm/" name="EPUB Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-xaml/" name="EPUB Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-otp/" name="EPUB Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-pptm/" name="EPUB Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-pot/" name="EPUB Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-powerpoint/" name="EPUB Zu POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}