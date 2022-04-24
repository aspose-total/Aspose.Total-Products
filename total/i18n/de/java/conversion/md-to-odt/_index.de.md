---
title: Java-API zum Exportieren von MD nach ODT
description: Konvertieren Sie MD mithilfe der lokalen Java-API in ODT
url: /de/java/conversion/md-to-odt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODT
otherformats: RTF MHTML DOTM WORDML DOT OTT FLATOPC PCL MARKDOWN XAMLFLOW PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wandeln Sie MD über Java in ODT um" h2="Lokale Java-API zum Rendern von MD in ODT ohne Verwendung einer Drittanbieteranwendung" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können MD in zwei einfachen Schritten in ODT konvertieren. Zuerst müssen Sie die MD-Datei mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) in DOC rendern. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC in ODT konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java-API zum Konvertieren von MD in ODT" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie MD in DOC mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie die DOC-Datei mithilfe der Klasse [Document] (https://apireference.aspose.com/words/java/com.aspose.words/Document) von Aspose.Words
4. Speichern Sie das Dokument mit der Methode [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) im ODT-Format und legen Sie ODT fest als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF für Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Words für Java](https://docs.aspose.com/words/java/ installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Auch wenn Ihr Dokument passwortgeschützt ist, können Sie es während der Konvertierung von MD in ODT immer noch mit der PDF-Manipulations-API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) öffnen. Um die verschlüsselte Datei zu öffnen, müssen Sie ein [Dokument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)-Objekt erstellen und das MD mit dem Passwort des Besitzers öffnen.  
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
Während Sie Ihr Eingabedokument im ODT-Dateiformat speichern, können Sie Ihr Dokument auch in einer Datenbank statt in einem Dateisystem speichern. Möglicherweise müssen Sie das Speichern und Abrufen von Document-Objekten in und aus einer Datenbank implementieren. Dies wäre erforderlich, wenn Sie ein beliebiges Content-Management-System implementieren. Um Ihr ODT in der Datenbank zu speichern, ist es oft notwendig, das Dokument zu serialisieren, um ein Byte-Array zu erhalten. Dies kann mit der [Aspose.Words for Java](https://products.aspose.com/words/Java/)-API erfolgen. Nachdem Sie Ihr Byte-Array erhalten haben, können Sie es mit einer SQL-Anweisung in der Datenbank speichern. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.ODT);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-rtf/" name="MD Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-wordml/" name="MD Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-odt/" name="MD Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-flatopc/" name="MD Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ps/" name="MD Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-pcl/" name="MD Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-mhtml/" name="MD Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-dotm/" name="MD Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ott/" name="MD Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-dotx/" name="MD Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-xamlflow/" name="MD Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-markdown/" name="MD Zu MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}