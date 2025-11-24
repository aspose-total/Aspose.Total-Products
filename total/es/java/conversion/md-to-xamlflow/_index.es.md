---
title: API de Java para exportar MD a XAMLFLOW
description: Convierta MD a XAMLFLOW usando la API de Java en las instalaciones
url_ignore: /es/java/conversion/md-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: XAML_FLOW
otherformats: PS ODT PCL DOTM DOT RTF MARKDOWN FLATOPC WORDML XAMLFLOW DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme MD a XAMLFLOW a través de Java" h2="API de Java en las instalaciones para renderizar MD a XAMLFLOW sin usar ninguna aplicación de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir MD a XAMLFLOW siguiendo dos simples pasos. Primero debe procesar el archivo MD en DOC usando [Aspose.PDF para Java](https://products.aspose.com/pdf/java/). Después de eso, al usar la poderosa API de procesamiento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), puede convertir DOC a XAMLFLOW. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir MD a XAMLFLOW" %}}
1. Abra el archivo MD usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MD a DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato XAMLFLOW usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure XAMLFLOW como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) y [Aspose.Words para Java](https://docs.aspose.com/words/java/installation/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-xaml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Mientras convierte MD a XAMLFLOW, incluso si su documento está protegido con contraseña, aún puede abrirlo usando la API de manipulación de PDF [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/). Para abrir el archivo cifrado, debe crear un objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) y abrir el MD con la contraseña del propietario.  
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
Mientras guarda su documento de entrada en formato de archivo XAMLFLOW, también puede guardar su documento en una base de datos en lugar de un sistema de archivos. Es posible que deba implementar el almacenamiento y la recuperación de objetos de documento hacia y desde una base de datos. Esto sería necesario si estuviera implementando cualquier tipo de sistema de gestión de contenido. Para guardar su XAMLFLOW en la base de datos, a menudo es necesario serializar el documento para obtener una matriz de bytes. Esto se puede hacer usando la API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Después de obtener su matriz de bytes, puede almacenarla en la base de datos usando una declaración SQL. 
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
```
{{< blocks/products/pf/agp/feature-section >}}



Convertir Markdown (MD) a XAMLFLOW permite la creación de diagramas interactivos basados en flujos y diseños de aplicaciones utilizando marcado XAML. Ideal para visualización de software, prototipado de UI y documentación de flujos de trabajo.



{{% blocks/products/pf/agp/feature-section-col title="Casos de Uso Clave" %}}



* Construir diagramas de flujo interactivos a partir de documentación en Markdown.

* Prototipar flujos de trabajo de aplicaciones WPF utilizando contenido en Markdown.

* Traducir notas de procesos técnicos en visualizaciones de XAMLFlow.

* Incrustar flujos generados en Markdown en vistas previas de aplicaciones interactivas.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de Automatización" %}}



* Tuberías automatizadas de MD a XAMLFLOW para equipos de desarrollo.

* Generación por lotes de flujos interactivos a partir de notas en Markdown.

* Actualizaciones programadas de diagramas de flujo en la documentación de software.

* Integración con CI/CD para convertir esquemas de procesos en Markdown en componentes de XAMLFLOW.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}