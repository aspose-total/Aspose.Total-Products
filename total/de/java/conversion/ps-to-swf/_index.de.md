---
title: Konvertieren Sie PS über die Java-API in SWF
description: Java-API zum Konvertieren von PS in SWF ohne Verwendung von Microsoft Word
url_ignore: /de/java/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: XAML POTX PPT PPSM SWF PPTM POWERPOINT POT PPS PPSX POTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Exportieren von PS nach SWF" h2="Exportieren Sie PS über die lokale Java-API nach SWF, ohne Microsoft<sup>&reg;</sup> PowerPoint oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie PS in jeder Java J2SE-, J2EE-, J2ME-Anwendung problemlos in SWF konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) PS nach PPTX exportieren. Danach können Sie mithilfe der [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint-Verarbeitungs-API PPTX in SWF konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von PS in SWF" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie PS in PPTX, indem Sie die Methode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im SWF-Format mit der Methode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Swf` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Slides für Java](https://docs.aspose.com/slides/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Beim Laden des PS-Dateiformats ist Ihr Dokument möglicherweise passwortgeschützt. Mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) können Sie auch verschlüsselte Dokumente öffnen. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie die verschlüsselte PS-Datei über Java" %}}
Nach der Konvertierung von PS in SWF können Sie Ihrer Präsentation auch einen vordefinierten Ansichtstyp hinzufügen. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) bietet eine Möglichkeit, den Ansichtstyp für die generierte Präsentation festzulegen, wenn sie in PowerPoint über die [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties)-Klasse. Die Eigenschaft [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) wird verwendet, um den Ansichtstyp mithilfe von [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType)-Enumerator. 
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}