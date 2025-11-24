---
title: Java-API zum Exportieren von MD nach GIF
description: Konvertieren Sie MD mithilfe der lokalen Java-API in GIF
url_ignore: /de/java/conversion/md-to-gif/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: GIF
otherformats: FLATOPC OTT MHTML DOTX WORDML GIF DOT DOTM PCL ODT RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wandeln Sie MD über Java in GIF um" h2="Lokale Java-API zum Rendern von MD in GIF ohne Verwendung einer Drittanbieteranwendung" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können MD in zwei einfachen Schritten in GIF konvertieren. Zuerst müssen Sie die MD-Datei mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) in DOC rendern. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC in GIF konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von MD in GIF" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie MD in DOC mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im GIF-Format und legen Sie GIF fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Words für Java](https://docs.aspose.com/words/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Auch wenn Ihr Dokument passwortgeschützt ist, können Sie es während der Konvertierung von MD in GIF immer noch mit der PDF-Manipulations-API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) öffnen. Um die verschlüsselte Datei zu öffnen, müssen Sie ein [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)-Objekt erstellen und das MD mit dem Passwort des Besitzers öffnen.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie ein passwortgeschütztes MD-Dokument über Java" %}}
Während Sie Ihr Eingabedokument im GIF-Dateiformat speichern, können Sie Ihr Dokument auch in einer Datenbank statt in einem Dateisystem speichern. Möglicherweise müssen Sie das Speichern und Abrufen von Document-Objekten in und aus einer Datenbank implementieren. Dies wäre erforderlich, wenn Sie ein beliebiges Content-Management-System implementieren. Um Ihr GIF in der Datenbank zu speichern, ist es oft notwendig, das Dokument zu serialisieren, um ein Byte-Array zu erhalten. Dies kann mit der [Aspose.Words for Java](https://products.aspose.com/words/Java/)-API erfolgen. Nachdem Sie Ihr Byte-Array erhalten haben, können Sie es mit einer SQL-Anweisung in der Datenbank speichern. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Die Umwandlung von Markdown (MD) in GIF ermöglicht es, Textinhalte, Diagramme oder Flussdiagramme in sich wiederholende Animationen umzuwandeln. GIFs werden weitgehend unterstützt, was sie für Tutorials, Social-Media-Inhalte und leichte interaktive Visuals geeignet macht.



{{% blocks/products/pf/agp/feature-section-col title="Hauptanwendungsfälle" %}}



* Umwandlung von Markdown-Flussdiagrammen in instruktive GIFs.

* Animierte Spickzettel für Codierungs- oder Dokumentations-Workflows.

* Social-Media-freundliche Visualisierungen, die aus Markdown-Notizen abgeleitet sind.

* Sich wiederholende Illustrationen für technische Anleitungen oder Software-Demos.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatisierungsszenarien" %}}



* Automatische GIF-Erstellung aus Markdown-Dokumentationsaktualisierungen.

* Stapelverarbeitung mehrerer Markdown-Diagramme zu GIFs.

* Integration in Content-Pipelines zur Erstellung von GIFs für Online-Portale.

* Geplante Markdown-zu-GIF-Konvertierung für Marketing- oder Bildungsplattformen.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}