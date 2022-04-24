---
title: Java-API zum Exportieren von EPUB nach XAMLFLOW
description: Konvertieren Sie EPUB mithilfe der lokalen Java-API in XAMLFLOW
url: /de/java/conversion/epub-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML_FLOW
otherformats: MARKDOWN DOTM PCL DOT WORDML DOTX FLATOPC XAMLFLOW ODT PS MHTML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wandeln Sie EPUB über Java in XAMLFLOW um" h2="Lokale Java-API zum Rendern von EPUB in XAMLFLOW ohne Verwendung einer Drittanbieteranwendung" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können EPUB in zwei einfachen Schritten in XAMLFLOW konvertieren. Zuerst müssen Sie die EPUB-Datei mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) in DOC rendern. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC in XAMLFLOW konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von EPUB in XAMLFLOW" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie EPUB in DOC mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document] (https://apireference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im XAMLFLOW-Format und legen Sie XAMLFLOW fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Words für Java](https://docs.aspose.com/words/java/ installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Auch wenn Ihr Dokument passwortgeschützt ist, können Sie es während der Konvertierung von EPUB in XAMLFLOW immer noch mit der PDF-Manipulations-API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) öffnen. Um die verschlüsselte Datei zu öffnen, müssen Sie ein [Dokument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)-Objekt erstellen und das EPUB mit dem Passwort des Besitzers öffnen.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie ein passwortgeschütztes EPUB-Dokument über Java" %}}
Während Sie Ihr Eingabedokument im XAMLFLOW-Dateiformat speichern, können Sie Ihr Dokument auch in einer Datenbank statt in einem Dateisystem speichern. Möglicherweise müssen Sie das Speichern und Abrufen von Document-Objekten in und aus einer Datenbank implementieren. Dies wäre erforderlich, wenn Sie ein beliebiges Content-Management-System implementieren. Um Ihr XAMLFLOW in der Datenbank zu speichern, ist es oft notwendig, das Dokument zu serialisieren, um ein Byte-Array zu erhalten. Dies kann mit der [Aspose.Words for Java](https://products.aspose.com/words/Java/)-API erfolgen. Nachdem Sie Ihr Byte-Array erhalten haben, können Sie es mit einer SQL-Anweisung in der Datenbank speichern. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-rtf/" name="EPUB Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-wordml/" name="EPUB Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-odt/" name="EPUB Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-flatopc/" name="EPUB Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-ps/" name="EPUB Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-pcl/" name="EPUB Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-mhtml/" name="EPUB Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-dotm/" name="EPUB Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-ott/" name="EPUB Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-dotx/" name="EPUB Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-xamlflow/" name="EPUB Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-markdown/" name="EPUB Zu MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}