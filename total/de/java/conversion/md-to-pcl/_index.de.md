---
title: Java-API zum Exportieren von MD nach PCL
description: Konvertieren Sie MD mithilfe der lokalen Java-API in PCL
url_ignore: /de/java/conversion/md-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PCL
otherformats: PCL ODT OTT MHTML DOTM MARKDOWN RTF FLATOPC WORDML DOT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wandeln Sie MD über Java in PCL um" h2="Lokale Java-API zum Rendern von MD in PCL ohne Verwendung einer Drittanbieteranwendung" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können MD in zwei einfachen Schritten in PCL konvertieren. Zuerst müssen Sie die MD-Datei mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) in DOC rendern. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC in PCL konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von MD in PCL" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie MD in DOC mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im PCL-Format und legen Sie PCL fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Words für Java](https://docs.aspose.com/words/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Auch wenn Ihr Dokument passwortgeschützt ist, können Sie es während der Konvertierung von MD in PCL immer noch mit der PDF-Manipulations-API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) öffnen. Um die verschlüsselte Datei zu öffnen, müssen Sie ein [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)-Objekt erstellen und das MD mit dem Passwort des Besitzers öffnen.  
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
Während Sie Ihr Eingabedokument im PCL-Dateiformat speichern, können Sie Ihr Dokument auch in einer Datenbank statt in einem Dateisystem speichern. Möglicherweise müssen Sie das Speichern und Abrufen von Document-Objekten in und aus einer Datenbank implementieren. Dies wäre erforderlich, wenn Sie ein beliebiges Content-Management-System implementieren. Um Ihr PCL in der Datenbank zu speichern, ist es oft notwendig, das Dokument zu serialisieren, um ein Byte-Array zu erhalten. Dies kann mit der [Aspose.Words for Java](https://products.aspose.com/words/Java/)-API erfolgen. Nachdem Sie Ihr Byte-Array erhalten haben, können Sie es mit einer SQL-Anweisung in der Datenbank speichern. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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
## {{< blocks/products/pf/agp/feature-section >}}

Die Umwandlung von Markdown (MD) in PCL (Printer Command Language) generiert druckfertige Dateien, die mit Laser- und Tintenstrahldruckern kompatibel sind. Die PCL-Konvertierung eignet sich zur Erstellung technischer Dokumente, Berichte und Workflow-Automatisierung in unternehmensweiten Druckumgebungen.

## {{% blocks/products/pf/agp/feature-section-col title="Anwendungsfälle" %}}

* Drucken von auf Markdown basierenden Berichten auf PCL-unterstützten Druckern.
* Generierung von PCL-Ausgaben für die Stapelverteilung von Dokumenten.
* Konvertierung von Markdown-Dokumentationen in druckfertige Formate.
* Erstellung technischer Anleitungen für Büro- oder Fertigungsdruck-Workflows.

{{% /blocks/products/pf/agp/feature-section-col %}}

## {{% blocks/products/pf/agp/feature-section-col title="Automatisierungsszenarien" %}}

* Zeitgesteuerte Stapelkonvertierung von Markdown-Dateien in PCL für unternehmensweiten Druck.
* Integration mit Druckservern zur automatischen Generierung von PCL aus Markdown-Dokumentationen.
* Automatisierte Druck-Pipelines zur Konvertierung von Markdown in PCL.
* Auslöserbasierte Dokumentenerstellung für PCL-Drucker mit hohem Volumen.

{{% /blocks/products/pf/agp/feature-section-col %}}

## {{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}