---
title: API de Java para exportar MD a ODT
description: Convierta MD a ODT usando la API de Java en las instalaciones
url_ignore: /es/java/conversion/md-to-odt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODT
otherformats: RTF MHTML DOTM WORDML DOT OTT FLATOPC PCL MARKDOWN XAMLFLOW PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme MD a ODT a través de Java" h2="API de Java en las instalaciones para renderizar MD a ODT sin usar ninguna aplicación de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir MD a ODT siguiendo dos simples pasos. Primero debe procesar el archivo MD en DOC usando [Aspose.PDF para Java](https://products.aspose.com/pdf/java/). Después de eso, al usar la poderosa API de procesamiento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), puede convertir DOC a ODT. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir MD a ODT" %}}
1. Abra el archivo MD usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MD a DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato ODT usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure ODT como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Words para Java](https://docs.aspose.com/words/java/installation/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Mientras convierte MD a ODT, incluso si su documento está protegido con contraseña, aún puede abrirlo usando la API de manipulación de PDF [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/). Para abrir el archivo cifrado, debe crear un objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) y abrir el MD con la contraseña del propietario.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento MD protegido con contraseña a través de Java" %}}
Mientras guarda su documento de entrada en formato de archivo ODT, también puede guardar su documento en una base de datos en lugar de un sistema de archivos. Es posible que deba implementar el almacenamiento y la recuperación de objetos de documento hacia y desde una base de datos. Esto sería necesario si estuviera implementando cualquier tipo de sistema de gestión de contenido. Para guardar su ODT en la base de datos, a menudo es necesario serializar el documento para obtener una matriz de bytes. Esto se puede hacer usando la API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Después de obtener su matriz de bytes, puede almacenarla en la base de datos usando una declaración SQL. 
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
```
{{< blocks/products/pf/agp/feature-section >}}



La conversión de MD (Markdown) a ODT (OpenDocument Text) permite flujos de trabajo de documentación amigables con el software de código abierto. Los archivos ODT son ideales para equipos que utilizan LibreOffice o OpenOffice, brindándoles una alternativa flexible y ligera a los formatos de Word propietarios, al mismo tiempo que permiten un formato rico.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Publicar documentación de código abierto en archivos ODT con formato profesional.

* Convertir guías de Markdown en documentos editables de LibreOffice.

* Crear documentos multiplataforma para organizaciones que evitan los formatos propietarios.

* Producir manuales ODT localizados obtenidos a partir de contenido MD.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión por lotes de repositorios de Markdown a ODT para distribución pública.

* Generación automatizada de documentación ODT en proyectos de código abierto.

* Flujos de trabajo ETL multiplataforma que generan ODT para gobiernos u ONGs.

* Creación de ODT basada en desencadenadores en procesos de localización y traducción.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}