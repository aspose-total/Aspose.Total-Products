---
title: Conversión de XPS a MHTML en línea o desarrollo de una aplicación basada en Java para convertir archivos XPS
description: Aplicación gratuita en línea para convertir archivos XPS a MHTML. Código de biblioteca de conversión Java para documentos XPS. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: MHTML
otherformats: XAMLFLOW OTT MHTML DOT MARKDOWN PCL PS RTF ODT FLATOPC DOTX DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicación de conversión de XPS a MHTML en línea y código Java para convertir archivos XPS" h2="Desarrollar una potente aplicación de conversión y exportación XPS basada en Java. Convierta archivos XPS individuales o múltiples a MHTML y otros formatos a través de la API de automatización de Java. Convierta libremente archivos XPS en línea a través de la aplicación con descarga instantánea." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicación gratuita de conversión de XPS a MHTML en línea" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=mhtml&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierte archivos XPS a MHTML en línea usando la aplicación" %}}

1. Subir archivos XPS para convertir
1. Espere unos segundos o más según el tamaño de XPS
1. Esté atento a la barra de estado de carga
1. Haga clic en el botón "Convertir"
1. XPS se convertirá en un documento MHTML
1. Descargue el archivo MHTML convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir XPS a MHTML mediante la API de automatización de Java" %}}


1. Abra el archivo XPS usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta XPS a DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato MHTML usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure MHTML como Guardar formato



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Algunos casos más para guardar XPS en MHTML con otras funciones como Requisitos de conversión, Abrir documento XPS protegido con contraseña a través de Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Desarrollar una aplicación de conversión de archivos XPS utilizando Java</h2>

¿Necesita desarrollar una aplicación de software basada en Java para guardar y exportar fácilmente archivos XPS a documentos MHTML? Con [Aspose.Total for Java](https://products.aspose.com/total/es/java/), cualquier desarrollador Java puede integrar el código API anterior para programar la aplicación de conversión en una variedad de formatos, incluidos Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, archivos de correo electrónico, imágenes (JPG, PNG, BMP, GIF) y otros formatos. Potente biblioteca Java para conversión de documentos, admite muchos formatos populares, incluido el formato XPS. Al exportar y renderizar documentos a otros formatos, los programadores pueden utilizar las API secundarias Aspose.Total for Java, incluidas [Aspose.Words for Java](https://products.aspose.com/words/es/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/es/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/es/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/es/java/) y más.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca de conversión XPS para Java" %}}

Existen opciones alternativas para integrar Aspose.Total for Java en su sistema. Elija uno que se asemeje a sus necesidades y siga las instrucciones paso a paso:<br /><br />

- Utilice Aspose.Total for Java directamente desde un proyecto basado en Maven e incluya la API secundaria relevante en pom.xml.
- Alternativamente, se puede obtener un archivo ZIP de [Descargas](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de la aplicación para guardar XPS en MHTML" %}}

Cualquier sistema operativo que pueda ejecutar Java Runtime Environment (JRE) puede ejecutar Aspose.Total for Java. A continuación se enumeran la mayoría de los sistemas operativos compatibles, pero no todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS y otros
- macOS: 10.9 (Mavericks) y posteriores
- Móvil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



Convertir XPS a **MHTML (MIME HTML)** permite empaquetar todo el documento, incluidas imágenes, texto y estilos, en un solo archivo listo para la web, ideal para archivar o compartir.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Archivar documentos XPS en un formato compatible con la web.

* Compartir informes completos por correo electrónico sin adjuntos externos.

* Publicar contenido XPS en portales web internos.

* Documentación basada en la web para uso corporativo o académico.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión automatizada por lotes de XPS a MHTML para archivos empresariales.

* Generación programada de versiones de documentos listas para la web.

* Integración con sistemas de intranet para distribución interna.

* Flujo de trabajo simplificado para archivar digitalmente informes y manuales.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}