---
title: API de Java para exportar CGM a DOCM
description: Convierta CGM a DOCM usando la API de Java en las instalaciones
url: /es/java/conversion/cgm-to-docm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOCM
otherformats: RTF WORDML ODT FLATOPC PS PCL MHTML DOTM OTT DOTX XAMLFLOW MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme CGM a DOCM a través de Java" h2="API de Java en las instalaciones para renderizar CGM a DOCM sin usar ninguna aplicación de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir CGM a DOCM siguiendo dos simples pasos. Primero debe procesar el archivo CGM en DOC usando [Aspose.PDF para Java] (https://products.aspose.com/pdf/java/). Después de eso, al usar la poderosa API de procesamiento de documentos [Aspose.Words for Java] (https://products.aspose.com/words/java/), puede convertir DOC a DOCM. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir CGM a DOCM" %}}
1. Abra el archivo CGM usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta CGM a DOC usando [guardar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el archivo DOC usando la clase [Documento](https://apireference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato DOCM usando el método [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure DOCM como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Words para Java](https://docs.aspose.com/words/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Mientras convierte CGM a DOCM, incluso si su documento está protegido con contraseña, aún puede abrirlo usando la API de manipulación de PDF [Aspose.PDF para Java] (https://docs.aspose.com/pdf/java/installation/). Para abrir el archivo cifrado, debe crear un objeto [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) y abrir el CGM con la contraseña del propietario.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento CGM protegido con contraseña a través de Java" %}}
Mientras guarda su documento de entrada en formato de archivo DOCM, también puede guardar su documento en una base de datos en lugar de un sistema de archivos. Es posible que deba implementar el almacenamiento y la recuperación de objetos de documento hacia y desde una base de datos. Esto sería necesario si estuviera implementando cualquier tipo de sistema de gestión de contenido. Para guardar su DOCM en la base de datos, a menudo es necesario serializar el documento para obtener una matriz de bytes. Esto se puede hacer usando la API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Después de obtener su matriz de bytes, puede almacenarla en la base de datos usando una declaración SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-rtf/" name="CGM Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-wordml/" name="CGM Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-odt/" name="CGM Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-flatopc/" name="CGM Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-ps/" name="CGM Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-pcl/" name="CGM Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-mhtml/" name="CGM Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-dotm/" name="CGM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-ott/" name="CGM Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-dotx/" name="CGM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-xamlflow/" name="CGM Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/cgm-to-markdown/" name="CGM Para MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}